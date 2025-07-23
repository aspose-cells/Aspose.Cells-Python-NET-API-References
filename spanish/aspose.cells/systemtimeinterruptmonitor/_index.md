---
title: SystemTimeInterruptMonitor clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 1390
url: /es/aspose.cells/systemtimeinterruptmonitor/
is_root: false
---
##  SystemTimeInterruptMonitor clase
Implementación simple de AbstractInterruptMonitor verificando y comparando el tiempo actual del sistema con el límite especificado por el usuario.



**Herencia:** [`SystemTimeInterruptMonitor`](/cells/python-net/es/aspose.cells/systemtimeinterruptmonitor)



El tipo SystemTimeInterruptMonitor expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [`__init__(self, terminate_without_exception)`](/cells/python-net/es/aspose.cells/systemtimeinterruptmonitor/__init__/#bool) | Construye un monitor de interrupciones.|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [is_interruption_requested](/cells/python-net/es/aspose.cells/systemtimeinterruptmonitor/is_interruption_requested) | Esta implementación solo verifica si el costo de tiempo (desde el momento en que se inicia este monitor hasta ahora) es mayor que el límite especificado por el usuario.|
| [terminate_without_exception](/cells/python-net/es/aspose.cells/systemtimeinterruptmonitor/terminate_without_exception) |Consulte TerminateWithoutException.<br/> El usuario especifica esta propiedad al construir esta instancia de monitor.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`start_monitor(self, ms_limit)`](/cells/python-net/es/aspose.cells/systemtimeinterruptmonitor/start_monitor/#int) | Inicia el monitor con el límite de tiempo especificado. El tiempo de inicio para calcular el coste del tiempo es justo cuando se llama a este método.<br/> Por lo tanto, el procedimiento a supervisar debe iniciarse justo después de esta llamada.|



###  Observaciones

Esta implementación es solo una solución simple para escenarios simples.
Necesita recuperar y verificar frecuentemente la hora del sistema, por lo que puede tener un impacto negativo en el rendimiento hasta cierto punto.

###  Ver también
* módulo [`aspose.cells`](..)
* clase [`SystemTimeInterruptMonitor`](/cells/python-net/es/aspose.cells/systemtimeinterruptmonitor)
