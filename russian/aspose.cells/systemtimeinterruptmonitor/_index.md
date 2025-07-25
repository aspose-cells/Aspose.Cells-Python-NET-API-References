---
title: SystemTimeInterruptMonitor класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 1390
url: /ru/aspose.cells/systemtimeinterruptmonitor/
is_root: false
---
##  SystemTimeInterruptMonitor класс
Простая реализация AbstractInterruptMonitor путем проверки и сравнения текущего системного времени с указанным пользователем пределом.



**Наследование:** [`SystemTimeInterruptMonitor`](/cells/python-net/ru/aspose.cells/systemtimeinterruptmonitor)



Тип SystemTimeInterruptMonitor предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self, terminate_without_exception)`](/cells/python-net/ru/aspose.cells/systemtimeinterruptmonitor/__init__/#bool) | Создает один монитор прерываний.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [is_interruption_requested](/cells/python-net/ru/aspose.cells/systemtimeinterruptmonitor/is_interruption_requested) | Эта реализация просто проверяет, превышает ли временные затраты (с момента запуска этого монитора до настоящего момента) указанный пользователем предел.|
| [terminate_without_exception](/cells/python-net/ru/aspose.cells/systemtimeinterruptmonitor/terminate_without_exception) |См. TerminateWithoutException.<br/> Это свойство указывается пользователем при создании данного экземпляра монитора.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`start_monitor(self, ms_limit)`](/cells/python-net/ru/aspose.cells/systemtimeinterruptmonitor/start_monitor/#int) | Запускает монитор с заданным лимитом времени. Время начала расчёта стоимости времени совпадает с моментом вызова этого метода.<br/> поэтому процедуру, которую необходимо контролировать, следует начинать сразу после этого звонка.|



###  Примечания

Данная реализация представляет собой простое решение для простых сценариев.
Ему приходится часто извлекать и проверять системное время, что само по себе может в некоторой степени отрицательно влиять на производительность.

###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`SystemTimeInterruptMonitor`](/cells/python-net/ru/aspose.cells/systemtimeinterruptmonitor)
