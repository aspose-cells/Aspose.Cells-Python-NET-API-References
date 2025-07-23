---
title: SystemTimeInterruptMonitor klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1390
url: /sv/aspose.cells/systemtimeinterruptmonitor/
is_root: false
---
##  SystemTimeInterruptMonitor klass
Enkel implementering av AbstractInterruptMonitor genom att kontrollera och jämföra aktuell systemtid med användarspecificerad gräns.



**Arv:** [`SystemTimeInterruptMonitor`](/cells/python-net/sv/aspose.cells/systemtimeinterruptmonitor)



Typen SystemTimeInterruptMonitor avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [`__init__(self, terminate_without_exception)`](/cells/python-net/sv/aspose.cells/systemtimeinterruptmonitor/__init__/#bool) | Konstruerar en avbrottsmonitor.|


###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [is_interruption_requested](/cells/python-net/sv/aspose.cells/systemtimeinterruptmonitor/is_interruption_requested) | Den här implementeringen kontrollerar bara om tidskostnaden (från tidpunkten då övervakaren startas till nu) är större än den användarspecificerade gränsen.|
| [terminate_without_exception](/cells/python-net/sv/aspose.cells/systemtimeinterruptmonitor/terminate_without_exception) |Se Avsluta utan undantag.<br/> Den här egenskapen anges av användaren när den här monitorinstansen konstrueras.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`start_monitor(self, ms_limit)`](/cells/python-net/sv/aspose.cells/systemtimeinterruptmonitor/start_monitor/#int) | Startar monitorn med den angivna tidsgränsen. Starttiden för att beräkna tidskostnaden är just när den här metoden anropas,<br/> så den procedur som behöver övervakas bör påbörjas direkt efter detta samtal.|



###  Anmärkningar

Denna implementering är bara en enkel lösning för enkla scenarier.
Den behöver ofta hämta och kontrollera systemtiden, så den kan i sig ha en negativ inverkan på prestandan i viss mån.

###  Se även
* modul [`aspose.cells`](..)
* klass [`SystemTimeInterruptMonitor`](/cells/python-net/sv/aspose.cells/systemtimeinterruptmonitor)
