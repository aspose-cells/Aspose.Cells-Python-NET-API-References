---
title: ContentTypePropertyCollection klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 30
url: /sv/aspose.cells.properties/contenttypepropertycollection/
is_root: false
---
##  ContentTypePropertyCollection klass
En samling av [`ContentTypeProperty`](/cells/python-net/sv/aspose.cells.properties/contenttypeproperty) objekt som representerar ytterligare information.



Typen ContentTypePropertyCollection avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [capacity](/cells/python-net/sv/aspose.cells.properties/contenttypepropertycollection/capacity) | Hämtar eller anger antalet element som arraylistan kan innehålla.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`add(self, name, value)`](/cells/python-net/sv/aspose.cells.properties/contenttypepropertycollection/add/#str-str) | Lägger till information om innehållstypsegenskaper.|
| [`add(self, name, value, type)`](/cells/python-net/sv/aspose.cells.properties/contenttypepropertycollection/add/#str-str-str) | Lägger till information om innehållstypsegenskaper.|
| [`copy_to(self, array)`](/cells/python-net/sv/aspose.cells.properties/contenttypepropertycollection/copy_to/#list) |Kopierar hela arraylistan till en kompatibel endimensionell arraylista, med början i början av målarraylistan.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/sv/aspose.cells.properties/contenttypepropertycollection/copy_to/#int-list-int-int) | Kopierar ett elementområde från arraylistan till en kompatibel endimensionell arraylista, med början vid det angivna indexet för målarraylistan.|
| [`index_of(self, item, index)`](/cells/python-net/sv/aspose.cells.properties/contenttypepropertycollection/index_of/#aspose.cells.properties.contenttypeproperty-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom intervallet av element i arraylistan som sträcker sig från det angivna indexet till det sista elementet.|
| [`index_of(self, item, index, count)`](/cells/python-net/sv/aspose.cells.properties/contenttypepropertycollection/index_of/#aspose.cells.properties.contenttypeproperty-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom elementintervallet i arraylistan som börjar vid det angivna indexet och innehåller det angivna antalet element.|
| [`last_index_of(self, item)`](/cells/python-net/sv/aspose.cells.properties/contenttypepropertycollection/last_index_of/#aspose.cells.properties.contenttypeproperty) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom hela arraylistan.|
| [`last_index_of(self, item, index)`](/cells/python-net/sv/aspose.cells.properties/contenttypepropertycollection/last_index_of/#aspose.cells.properties.contenttypeproperty-int) |Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom intervallet av element i arraylistan som sträcker sig från det första elementet till det angivna indexet.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/sv/aspose.cells.properties/contenttypepropertycollection/last_index_of/#aspose.cells.properties.contenttypeproperty-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom elementintervallet i arraylistan som innehåller det angivna antalet element och slutar vid det angivna indexet.|
| [`get(self, name)`](/cells/python-net/sv/aspose.cells.properties/contenttypepropertycollection/get/#str) | Hämtar innehållstypsegenskapen efter egenskapsnamnet.|
| [`binary_search(self, item)`](/cells/python-net/sv/aspose.cells.properties/contenttypepropertycollection/binary_search/#aspose.cells.properties.contenttypeproperty) | Söker igenom hela den sorterade arraylistan efter ett element med hjälp av standardjämföraren och returnerar elementets nollbaserade index.|



###  Exempel

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Add a new property.
workbook.content_type_properties.add("Admin", "Aspose", "text")
# Save the Excel file
workbook.save("book1.xlsm")

```

###  Se även
* modul [`aspose.cells.properties`](..)
* klass [`ContentTypeProperty`](/cells/python-net/sv/aspose.cells.properties/contenttypeproperty)
