---
title: InterruptMonitor Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 950
url: /de/aspose.cells/interruptmonitor/
is_root: false
---
##  InterruptMonitor Klasse
Stellt alle Operatoren über den Interrupt dar.



**Nachlass:** [InterruptMonitor](/cells/python-net/aspose.cells/interruptmonitor) → 
[AbstractInterruptMonitor](/cells/python-net/de/aspose.cells/abstractinterruptmonitor)



Der Typ InterruptMonitor macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [InterruptMonitor()](/cells/python-net/de/aspose.cells/interruptmonitor/__init__/#) | Erstellt eine neue Instanz von InterruptMonitor|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [is_interruption_requested](/cells/python-net/de/aspose.cells/interruptmonitor/is_interruption_requested) | Markieren Sie den Monitor als Unterbrechung anfordernd|
| [terminate_without_exception](/cells/python-net/de/aspose.cells/interruptmonitor/terminate_without_exception) | Wenn die Prozedur unterbrochen wird, ob die Prozedur stillschweigend beendet oder eine Ausnahme ausgelöst wird.<br/>Standard ist falsch, das heißt, wenn [AbstractInterruptMonitor.is_interruption_requested](/cells/python-net/de/aspose.cells/abstractinterruptmonitor#is_interruption_requested) wahr ist,<br/> ein [CellsException](/cells/python-net/de/aspose.cells/cellsexception) mit dem Code [ExceptionType.INTERRUPTED](/cells/python-net/de/aspose.cells/exceptiontype#INTERRUPTED) wird geworfen.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [interrupt()](/cells/python-net/de/aspose.cells/interruptmonitor/interrupt/#) | Unterbrechen Sie den aktuellen Operator.|



###  Siehe auch
* Modul [aspose.cells](..)
* Klasse [AbstractInterruptMonitor](/cells/python-net/de/aspose.cells/abstractinterruptmonitor)
* Klasse [CellsException](/cells/python-net/de/aspose.cells/cellsexception)
* Klasse [InterruptMonitor](/cells/python-net/de/aspose.cells/interruptmonitor)
