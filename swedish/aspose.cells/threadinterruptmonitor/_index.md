---
title: ThreadInterruptMonitor klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1410
url: /sv/aspose.cells/threadinterruptmonitor/
is_root: false
---
##  ThreadInterruptMonitor klass
Enkel implementering av AbstractInterruptMonitor genom att starta en annan tråd för att kräva avbrottet efter att ha sovit en användarspecificerad gräns.



**Arv:** [`ThreadInterruptMonitor`](/cells/python-net/sv/aspose.cells/threadinterruptmonitor)



Typen ThreadInterruptMonitor avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [`__init__(self, terminate_without_exception)`](/cells/python-net/sv/aspose.cells/threadinterruptmonitor/__init__/#bool) | Konstruerar en avbrottsmonitor.|


###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [is_interruption_requested](/cells/python-net/sv/aspose.cells/threadinterruptmonitor/is_interruption_requested) | Den här implementeringen kontrollerar bara om tidskostnaden (från tidpunkten då övervakaren startas till nu) är större än den användarspecificerade gränsen.|
| [terminate_without_exception](/cells/python-net/sv/aspose.cells/threadinterruptmonitor/terminate_without_exception) |Se Avsluta utan undantag.<br/> Den här egenskapen anges av användaren när den här monitorinstansen konstrueras.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`start_monitor(self, ms_limit)`](/cells/python-net/sv/aspose.cells/threadinterruptmonitor/start_monitor/#int) | Startar monitorn med den angivna tidsgränsen. Starttiden för att beräkna tidskostnaden är just när den här metoden anropas,<br/> så den procedur som behöver övervakas bör påbörjas direkt efter detta samtal.|
| [`finish_monitor(self)`](/cells/python-net/sv/aspose.cells/threadinterruptmonitor/finish_monitor/#) | Avslutar monitorn för en procedur.|



###  Anmärkningar

En övervakningsinstans kan användas upprepade gånger, så länge du övervakar varje process i sekvens.
Den bör inte användas för att övervaka flera procedurer samtidigt i flera trådar.

###  Se även
* modul [`aspose.cells`](..)
* klass [`ThreadInterruptMonitor`](/cells/python-net/sv/aspose.cells/threadinterruptmonitor)
