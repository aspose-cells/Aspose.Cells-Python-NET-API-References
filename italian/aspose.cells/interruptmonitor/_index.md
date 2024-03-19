---
title: InterruptMonitor classe
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 990
url: /it/aspose.cells/interruptmonitor/
is_root: false
---
##  InterruptMonitor classe
Rappresenta tutti gli operatori relativi all'interruzione.



**Eredità:** [`InterruptMonitor`](/cells/python-net/aspose.cells/interruptmonitor) → 
[`AbstractInterruptMonitor`](/cells/python-net/it/aspose.cells/abstractinterruptmonitor)



Il tipo InterruptMonitor espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [__init__](/cells/python-net/it/aspose.cells/interruptmonitor/__init__/#) | Costruisce una nuova istanza di InterruptMonitor|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [is_interruption_requested](/cells/python-net/it/aspose.cells/interruptmonitor/is_interruption_requested) | Contrassegnare il monitor come richiedente interruzione|
| [terminate_without_exception](/cells/python-net/it/aspose.cells/interruptmonitor/terminate_without_exception) | Quando la procedura viene interrotta, terminare la procedura in silenzio o lanciare un'eccezione.<br/>L'impostazione predefinita è falsa, ovvero quando [`AbstractInterruptMonitor.is_interruption_requested`](/cells/python-net/it/aspose.cells/abstractinterruptmonitor#is_interruption_requested) è vero,<br/> verrà lanciato uno [`CellsException`](/cells/python-net/it/aspose.cells/cellsexception) con codice [`ExceptionType.INTERRUPTED`](/cells/python-net/it/aspose.cells/exceptiontype#INTERRUPTED).|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [interrupt](/cells/python-net/it/aspose.cells/interruptmonitor/interrupt/#) | Interrompe l'operatore corrente.|



###  Guarda anche
* modulo [`aspose.cells`](..)
* classe [`AbstractInterruptMonitor`](/cells/python-net/it/aspose.cells/abstractinterruptmonitor)
* classe [`CellsException`](/cells/python-net/it/aspose.cells/cellsexception)
* classe [`InterruptMonitor`](/cells/python-net/it/aspose.cells/interruptmonitor)
