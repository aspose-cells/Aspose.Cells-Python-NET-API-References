---
title: AbstractInterruptMonitor klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 50
url: /sv/aspose.cells/abstractinterruptmonitor/
is_root: false
---
##  AbstractInterruptMonitor klass
Övervaka avbrottsförfrågningar i alla tidskrävande operationer.



Typen AbstractInterruptMonitor avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [is_interruption_requested](/cells/python-net/sv/aspose.cells/abstractinterruptmonitor/is_interruption_requested) | Indikerar om avbrott begärs för aktuell drift.<br/>Om sant kommer den aktuella driften att avbrytas.<br/>Implementeringen bör utföra snabb och effektiv kontroll här, annars kan det bli ytterligare en flaskhals för proceduren.|
| [terminate_without_exception](/cells/python-net/sv/aspose.cells/abstractinterruptmonitor/terminate_without_exception) | När proceduren avbryts, oavsett om du avbryter proceduren tyst eller gör ett undantag.<br/>Standard är falskt, det vill säga när [AbstractInterruptMonitor.is_interruption_requested](/cells/python-net/sv/aspose.cells/abstractinterruptmonitor#is_interruption_requested) är sant,<br/> ett [CellsException](/cells/python-net/sv/aspose.cells/cellsexception) med kod [ExceptionType.INTERRUPTED](/cells/python-net/sv/aspose.cells/exceptiontype#INTERRUPTED) kommer att kastas.|



###  Se även
* modul [aspose.cells](..)
* klass [CellsException](/cells/python-net/sv/aspose.cells/cellsexception)
