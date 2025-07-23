---
title: LoadFilter klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 940
url: /sv/aspose.cells/loadfilter/
is_root: false
---
##  LoadFilter klass
Representerar filtret som ger alternativ för att läsa in data när arbetsboken läses in från en mall.



Typen LoadFilter avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [`__init__(self)`](/cells/python-net/sv/aspose.cells/loadfilter/__init__/#) | Konstruerar ett LoadFilter med standardfilteralternativen LoadDataFilterOptions.All.|
| [`__init__(self, opts)`](/cells/python-net/sv/aspose.cells/loadfilter/__init__/#aspose.cells.loaddatafilteroptions) | Konstruerar ett LoadFilter med givna filteralternativ.|


###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [load_data_filter_options](/cells/python-net/sv/aspose.cells/loadfilter/load_data_filter_options) |Filteralternativen för att ange vilka data som ska laddas.|
| [sheets_in_loading_order](/cells/python-net/sv/aspose.cells/loadfilter/sheets_in_loading_order) | Anger vilka ark (index) som ska laddas och i vilken ordning.<br/>Standardvärdet är null, vilket anger att alla ark ska läsas in i standardordningen i mallfilen.<br/> Om det inte är null och indexet för något ark inte finns i den returnerade arrayen, kommer arket inte att läsas in.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`start_sheet(self, sheet)`](/cells/python-net/sv/aspose.cells/loadfilter/start_sheet/#aspose.cells.worksheet) | Förbereder filteralternativ innan ett givet arbetsblad laddas.<br/>Användarens implementering av LoadFilter kan ändra LoadDataFilterOptions här<br/> för att ange hur data ska laddas för det här kalkylbladet.|



###  Anmärkningar

Användaren kan ange filteralternativ eller implementera sin egen LoadFilter för att ange hur data ska laddas.

###  Se även
* modul [`aspose.cells`](..)
