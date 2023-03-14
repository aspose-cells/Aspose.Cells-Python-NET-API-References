---
title: InterruptMonitor clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 950
url: /es/aspose.cells/interruptmonitor/
is_root: false
---
##  InterruptMonitor clase
Representa a todos los operadores sobre la interrupción.



**Herencia:** [InterruptMonitor](/cells/python-net/aspose.cells/interruptmonitor) → 
[AbstractInterruptMonitor](/cells/python-net/es/aspose.cells/abstractinterruptmonitor)



El tipo InterruptMonitor expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [InterruptMonitor()](/cells/python-net/es/aspose.cells/interruptmonitor/__init__/#) | Construye una nueva instancia de InterruptMonitor|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [is_interruption_requested](/cells/python-net/es/aspose.cells/interruptmonitor/is_interruption_requested) | Marcar el monitor como solicitando interrupción|
| [terminate_without_exception](/cells/python-net/es/aspose.cells/interruptmonitor/terminate_without_exception) | Cuando se interrumpe el procedimiento, ya sea que finalice el procedimiento en silencio o emita una excepción.<br/>El valor predeterminado es falso, es decir, cuando [AbstractInterruptMonitor.is_interruption_requested](/cells/python-net/es/aspose.cells/abstractinterruptmonitor#is_interruption_requested) es verdadero,<br/> Se lanzará un [CellsException](/cells/python-net/es/aspose.cells/cellsexception) con el código [ExceptionType.INTERRUPTED](/cells/python-net/es/aspose.cells/exceptiontype#INTERRUPTED).|


###  Métodos
| Método| Descripción|
| :- | :- |
| [interrupt()](/cells/python-net/es/aspose.cells/interruptmonitor/interrupt/#) | Interrumpir al operador actual.|



###  Ver también
* módulo [aspose.cells](..)
* clase [AbstractInterruptMonitor](/cells/python-net/es/aspose.cells/abstractinterruptmonitor)
* clase [CellsException](/cells/python-net/es/aspose.cells/cellsexception)
* clase [InterruptMonitor](/cells/python-net/es/aspose.cells/interruptmonitor)
