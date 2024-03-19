---
title: InterruptMonitor класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 990
url: /ru/aspose.cells/interruptmonitor/
is_root: false
---
##  InterruptMonitor класс
Представляет всех операторов прерывания.



**Наследование:** [`InterruptMonitor`](/cells/python-net/aspose.cells/interruptmonitor) → 
[`AbstractInterruptMonitor`](/cells/python-net/ru/aspose.cells/abstractinterruptmonitor)



Тип InterruptMonitor предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [__init__](/cells/python-net/ru/aspose.cells/interruptmonitor/__init__/#) | Создает новый экземпляр InterruptMonitor.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [is_interruption_requested](/cells/python-net/ru/aspose.cells/interruptmonitor/is_interruption_requested) | Пометить монитор как запрашивающий прерывание|
| [terminate_without_exception](/cells/python-net/ru/aspose.cells/interruptmonitor/terminate_without_exception) | Когда процедура прерывается, следует ли завершить ее незаметно или выдать исключение.<br/>По умолчанию установлено значение false, то есть, когда [`AbstractInterruptMonitor.is_interruption_requested`](/cells/python-net/ru/aspose.cells/abstractinterruptmonitor#is_interruption_requested) истинно,<br/> будет выброшен [`CellsException`](/cells/python-net/ru/aspose.cells/cellsexception) с кодом [`ExceptionType.INTERRUPTED`](/cells/python-net/ru/aspose.cells/exceptiontype#INTERRUPTED).|


###  Методы
| Метод| Описание|
| :- | :- |
| [interrupt](/cells/python-net/ru/aspose.cells/interruptmonitor/interrupt/#) | Прервите текущий оператор.|



###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`AbstractInterruptMonitor`](/cells/python-net/ru/aspose.cells/abstractinterruptmonitor)
* класс [`CellsException`](/cells/python-net/ru/aspose.cells/cellsexception)
* класс [`InterruptMonitor`](/cells/python-net/ru/aspose.cells/interruptmonitor)
