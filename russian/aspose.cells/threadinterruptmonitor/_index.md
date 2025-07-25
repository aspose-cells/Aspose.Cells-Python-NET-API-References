---
title: ThreadInterruptMonitor класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 1410
url: /ru/aspose.cells/threadinterruptmonitor/
is_root: false
---
##  ThreadInterruptMonitor класс
Простая реализация AbstractInterruptMonitor путем запуска другого потока, требующего прерывания после указанного пользователем предела сна.



**Наследование:** [`ThreadInterruptMonitor`](/cells/python-net/ru/aspose.cells/threadinterruptmonitor)



Тип ThreadInterruptMonitor предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self, terminate_without_exception)`](/cells/python-net/ru/aspose.cells/threadinterruptmonitor/__init__/#bool) | Создает один монитор прерываний.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [is_interruption_requested](/cells/python-net/ru/aspose.cells/threadinterruptmonitor/is_interruption_requested) | Эта реализация просто проверяет, превышает ли временные затраты (с момента запуска этого монитора до настоящего момента) указанный пользователем предел.|
| [terminate_without_exception](/cells/python-net/ru/aspose.cells/threadinterruptmonitor/terminate_without_exception) |См. TerminateWithoutException.<br/> Это свойство указывается пользователем при создании данного экземпляра монитора.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`start_monitor(self, ms_limit)`](/cells/python-net/ru/aspose.cells/threadinterruptmonitor/start_monitor/#int) | Запускает монитор с заданным лимитом времени. Время начала расчёта стоимости времени совпадает с моментом вызова этого метода.<br/> поэтому процедуру, которую необходимо контролировать, следует начинать сразу после этого звонка.|
| [`finish_monitor(self)`](/cells/python-net/ru/aspose.cells/threadinterruptmonitor/finish_monitor/#) | Завершает монитор для одной процедуры.|



###  Примечания

Один экземпляр монитора можно использовать многократно, при условии последовательного мониторинга каждого процесса.
Его не следует использовать для одновременного мониторинга нескольких процедур в многопоточных процессах.

###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`ThreadInterruptMonitor`](/cells/python-net/ru/aspose.cells/threadinterruptmonitor)
