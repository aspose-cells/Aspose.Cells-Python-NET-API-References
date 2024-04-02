---
title: GridWorkbookSettings klass
second_title: Aspose.Cells.GridJs for Python via .NET API Referenser
description:
type: docs
weight: 80
url: /sv/aspose.cellsgridjs/gridworkbooksettings/
is_root: false
---
##  GridWorkbookSettings klass

Representerar arbetsbokens inställningar.



Typen GridWorkbookSettings avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [__init__](/cells/python-net/sv/aspose.cellsgridjs/gridworkbooksettings/__init__/#) | Konstruerar en ny instans av GridWorkbookSettings|


###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [max_iteration](/cells/python-net/sv/aspose.cellsgridjs/gridworkbooksettings/max_iteration) | Returnerar eller ställer in det maximala antalet iterationer för att lösa en cirkulär referens, standardvärdet är 100.|
| [iteration](/cells/python-net/sv/aspose.cellsgridjs/gridworkbooksettings/iteration) | Anger om använd iteration för att lösa cirkulära referenser.|
| [force_full_calculate](/cells/python-net/sv/aspose.cellsgridjs/gridworkbooksettings/force_full_calculate) | Anger om fullständigt beräknas varje gång en beräkning utlöses.|
| [create_calc_chain](/cells/python-net/sv/aspose.cellsgridjs/gridworkbooksettings/create_calc_chain) |Anger om du skapar beräknade formlerkedja. Standard är falskt.|
| [re_calculate_on_open](/cells/python-net/sv/aspose.cellsgridjs/gridworkbooksettings/re_calculate_on_open) | Indikerar om alla formler ska beräknas på nytt när filen öppnas.|
| [precision_as_displayed](/cells/python-net/sv/aspose.cellsgridjs/gridworkbooksettings/precision_as_displayed) | Sant om beräkningar i den här arbetsboken kommer att göras med enbart precisionen av siffrorna när de visas|
| [date1904](/cells/python-net/sv/aspose.cellsgridjs/gridworkbooksettings/date1904) | Hämtar eller ställer in ett värde som representerar om arbetsboken använder 1904-datumsystemet.|
| [enable_macros](/cells/python-net/sv/aspose.cellsgridjs/gridworkbooksettings/enable_macros) | Aktivera makron; Nu fungerar det bara när du kopierar ett kalkylblad till ett annat kalkylblad i en arbetsbok.|
| [check_custom_number_format](/cells/python-net/sv/aspose.cellsgridjs/gridworkbooksettings/check_custom_number_format) | Anger om anpassat nummerformat kontrolleras när Style.Custom ställs in.|
| [author](/cells/python-net/sv/aspose.cellsgridjs/gridworkbooksettings/author) | Hämtar/ställer in författaren till filen.|



###  Exempel


```python
from aspose.cellsgridjs import GridJsWorkbook, GridWorkbookSettings

g = GridJsWorkbook()
gsettings = GridWorkbookSettings()
g.settings = gsettings

```

###  Se även
* modul [`aspose.cellsgridjs`](..)
