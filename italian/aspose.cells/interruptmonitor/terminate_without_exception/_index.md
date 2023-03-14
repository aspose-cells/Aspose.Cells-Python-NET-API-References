---
title: terminate_without_exception proprietà
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 50
url: /it/aspose.cells/interruptmonitor/terminate_without_exception/
is_root: false
---
##  terminate_without_exception proprietà

Quando la procedura viene interrotta, se terminare la procedura in silenzio o lanciare un'eccezione.
L'impostazione predefinita è false, ovvero quando [AbstractInterruptMonitor.is_interruption_requested](/cells/python-net/it/aspose.cells/abstractinterruptmonitor#is_interruption_requested) è vero,
verrà lanciato uno [CellsException](/cells/python-net/it/aspose.cells/cellsexception) con codice [ExceptionType.INTERRUPTED](/cells/python-net/it/aspose.cells/exceptiontype#INTERRUPTED).
###  Definizione:
```python
@property
def terminate_without_exception(self):
    ...
```

###  Guarda anche
* modulo [aspose.cells](../../)
* classe [CellsException](/cells/python-net/it/aspose.cells/cellsexception)
* classe [InterruptMonitor](/cells/python-net/it/aspose.cells/interruptmonitor)
