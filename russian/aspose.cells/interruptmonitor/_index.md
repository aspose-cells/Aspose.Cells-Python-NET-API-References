---
title: InterruptMonitor класс
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 950
url: /ru/aspose.cells/interruptmonitor/
is_root: false
---
##  InterruptMonitor класс
Представляет весь оператор о прерывании.



**Наследование:** [InterruptMonitor](/cells/python-net/aspose.cells/interruptmonitor) → 
[AbstractInterruptMonitor](/cells/python-net/ru/aspose.cells/abstractinterruptmonitor)



Тип InterruptMonitor предоставляет следующие члены:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [InterruptMonitor()](/cells/python-net/ru/aspose.cells/interruptmonitor/__init__/#) | Создает новый экземпляр InterruptMonitor|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [is_interruption_requested](/cells/python-net/ru/aspose.cells/interruptmonitor/is_interruption_requested) | Пометить монитор как требующий прерывания|
| [terminate_without_exception](/cells/python-net/ru/aspose.cells/interruptmonitor/terminate_without_exception) | Когда процедура прерывается, завершайте процедуру тихо или выбрасывайте исключение.<br/>По умолчанию false, то есть когда [AbstractInterruptMonitor.is_interruption_requested](/cells/python-net/ru/aspose.cells/abstractinterruptmonitor#is_interruption_requested) истинно,<br/> будет выброшен [CellsException](/cells/python-net/ru/aspose.cells/cellsexception) с кодом [ExceptionType.INTERRUPTED](/cells/python-net/ru/aspose.cells/exceptiontype#INTERRUPTED).|


###  Методы
| Метод| Описание|
| :- | :- |
| [interrupt()](/cells/python-net/ru/aspose.cells/interruptmonitor/interrupt/#) | Прервать текущего оператора.|



###  Смотрите также
* модуль [aspose.cells](..)
* класс [AbstractInterruptMonitor](/cells/python-net/ru/aspose.cells/abstractinterruptmonitor)
* класс [CellsException](/cells/python-net/ru/aspose.cells/cellsexception)
* класс [InterruptMonitor](/cells/python-net/ru/aspose.cells/interruptmonitor)
