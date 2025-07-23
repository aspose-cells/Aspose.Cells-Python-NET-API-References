---
title: ThreadInterruptMonitor clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 1410
url: /es/aspose.cells/threadinterruptmonitor/
is_root: false
---
##  ThreadInterruptMonitor clase
Implementación simple de AbstractInterruptMonitor iniciando otro hilo para requerir la interrupción después de que el usuario alcance el límite especificado.



**Herencia:** [`ThreadInterruptMonitor`](/cells/python-net/es/aspose.cells/threadinterruptmonitor)



El tipo ThreadInterruptMonitor expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [`__init__(self, terminate_without_exception)`](/cells/python-net/es/aspose.cells/threadinterruptmonitor/__init__/#bool) | Construye un monitor de interrupciones.|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [is_interruption_requested](/cells/python-net/es/aspose.cells/threadinterruptmonitor/is_interruption_requested) | Esta implementación solo verifica si el costo de tiempo (desde el momento en que se inicia este monitor hasta ahora) es mayor que el límite especificado por el usuario.|
| [terminate_without_exception](/cells/python-net/es/aspose.cells/threadinterruptmonitor/terminate_without_exception) |Consulte TerminateWithoutException.<br/> El usuario especifica esta propiedad al construir esta instancia de monitor.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`start_monitor(self, ms_limit)`](/cells/python-net/es/aspose.cells/threadinterruptmonitor/start_monitor/#int) | Inicia el monitor con el límite de tiempo especificado. El tiempo de inicio para calcular el coste del tiempo es justo cuando se llama a este método.<br/> Por lo tanto, el procedimiento a supervisar debe iniciarse justo después de esta llamada.|
| [`finish_monitor(self)`](/cells/python-net/es/aspose.cells/threadinterruptmonitor/finish_monitor/#) | Finaliza el monitor para un procedimiento.|



###  Observaciones

Se puede usar una instancia de monitor repetidamente, siempre que se monitoree cada proceso en secuencia.
No debe utilizarse para supervisar varios procedimientos simultáneamente en subprocesos múltiples.

###  Ver también
* módulo [`aspose.cells`](..)
* clase [`ThreadInterruptMonitor`](/cells/python-net/es/aspose.cells/threadinterruptmonitor)
