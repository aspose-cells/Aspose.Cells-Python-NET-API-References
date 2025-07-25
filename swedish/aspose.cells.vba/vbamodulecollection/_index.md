---
title: VbaModuleCollection klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 20
url: /sv/aspose.cells.vba/vbamodulecollection/
is_root: false
---
##  VbaModuleCollection klass
Representerar listan över [`VbaModule`](/cells/python-net/sv/aspose.cells.vba/vbamodule)



Typen VbaModuleCollection avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [capacity](/cells/python-net/sv/aspose.cells.vba/vbamodulecollection/capacity) | Hämtar eller anger antalet element som arraylistan kan innehålla.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`add(self, sheet)`](/cells/python-net/sv/aspose.cells.vba/vbamodulecollection/add/#aspose.cells.worksheet) | Lägger till modul för ett kalkylblad.|
| [`add(self, type, name)`](/cells/python-net/sv/aspose.cells.vba/vbamodulecollection/add/#aspose.cells.vba.vbamoduletype-str) | Lägger till modul.|
| [`get(self, index)`](/cells/python-net/sv/aspose.cells.vba/vbamodulecollection/get/#int) | Hämtar [`VbaModule`](/cells/python-net/sv/aspose.cells.vba/vbamodule) i listan via indexet.|
| [`get(self, name)`](/cells/python-net/sv/aspose.cells.vba/vbamodulecollection/get/#str) | Hämtar [`VbaModule`](/cells/python-net/sv/aspose.cells.vba/vbamodule) i listan efter namnet.|
| [`copy_to(self, array)`](/cells/python-net/sv/aspose.cells.vba/vbamodulecollection/copy_to/#list) |Kopierar hela arraylistan till en kompatibel endimensionell arraylista, med början i början av målarraylistan.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/sv/aspose.cells.vba/vbamodulecollection/copy_to/#int-list-int-int) | Kopierar ett elementområde från arraylistan till en kompatibel endimensionell arraylista, med början vid det angivna indexet för målarraylistan.|
| [`index_of(self, item, index)`](/cells/python-net/sv/aspose.cells.vba/vbamodulecollection/index_of/#aspose.cells.vba.vbamodule-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom intervallet av element i arraylistan som sträcker sig från det angivna indexet till det sista elementet.|
| [`index_of(self, item, index, count)`](/cells/python-net/sv/aspose.cells.vba/vbamodulecollection/index_of/#aspose.cells.vba.vbamodule-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom elementintervallet i arraylistan som börjar vid det angivna indexet och innehåller det angivna antalet element.|
| [`last_index_of(self, item)`](/cells/python-net/sv/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.vbamodule) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom hela arraylistan.|
| [`last_index_of(self, item, index)`](/cells/python-net/sv/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.vbamodule-int) |Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom intervallet av element i arraylistan som sträcker sig från det första elementet till det angivna indexet.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/sv/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.vbamodule-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom elementintervallet i arraylistan som innehåller det angivna antalet element och slutar vid det angivna indexet.|
| [`add_designer_storage(self, name, data)`](/cells/python-net/sv/aspose.cells.vba/vbamodulecollection/add_designer_storage/#str-bytes) |  |
| [`get_designer_storage(self, name)`](/cells/python-net/sv/aspose.cells.vba/vbamodulecollection/get_designer_storage/#str) | Representerar Designerns data.|
| [`add_user_form(self, name, codes, designer_storage)`](/cells/python-net/sv/aspose.cells.vba/vbamodulecollection/add_user_form/#str-str-bytes) | Infoga användarformulär i VBA-projekt.|
| [`remove_by_worksheet(self, sheet)`](/cells/python-net/sv/aspose.cells.vba/vbamodulecollection/remove_by_worksheet/#aspose.cells.worksheet) | Tar bort modulen för ett kalkylblad.|
| [`remove_by_name(self, name)`](/cells/python-net/sv/aspose.cells.vba/vbamodulecollection/remove_by_name/#str) | Ta bort modulen efter namn|
| [`binary_search(self, item)`](/cells/python-net/sv/aspose.cells.vba/vbamodulecollection/binary_search/#aspose.cells.vba.vbamodule) | Söker igenom hela den sorterade arraylistan efter ett element med hjälp av standardjämföraren och returnerar elementets nollbaserade index.|



###  Exempel

```python
from aspose.cells import Workbook
from aspose.cells.vba import VbaModuleType

# Instantiating a Workbook object
workbook = Workbook()
#  Init VBA project.
vbaProject = workbook.vba_project
#  Add a new module.
vbaProject.modules.add(VbaModuleType.CLASS, "test")
# Saving the Excel file
workbook.save("book1.xlsm")

```

###  Se även
* modul [`aspose.cells.vba`](..)
* klass [`VbaModule`](/cells/python-net/sv/aspose.cells.vba/vbamodule)
