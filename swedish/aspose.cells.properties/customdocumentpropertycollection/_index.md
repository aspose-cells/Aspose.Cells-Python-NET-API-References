---
title: CustomDocumentPropertyCollection klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 40
url: /sv/aspose.cells.properties/customdocumentpropertycollection/
is_root: false
---
##  CustomDocumentPropertyCollection klass
En samling anpassade dokumentegenskaper.



**Arv:** [`CustomDocumentPropertyCollection`](/cells/python-net/sv/aspose.cells.properties/customdocumentpropertycollection)



Typen CustomDocumentPropertyCollection avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [capacity](/cells/python-net/sv/aspose.cells.properties/customdocumentpropertycollection/capacity) | Hämtar eller anger antalet element som arraylistan kan innehålla.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`get(self, name)`](/cells/python-net/sv/aspose.cells.properties/customdocumentpropertycollection/get/#str) |  |
| [`get(self, index)`](/cells/python-net/sv/aspose.cells.properties/customdocumentpropertycollection/get/#int) |  |
| [`index_of(self, name)`](/cells/python-net/sv/aspose.cells.properties/customdocumentpropertycollection/index_of/#str) |  |
| [`index_of(self, item, index)`](/cells/python-net/sv/aspose.cells.properties/customdocumentpropertycollection/index_of/#aspose.cells.properties.documentproperty-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom intervallet av element i arraylistan som sträcker sig från det angivna indexet till det sista elementet.|
| [`index_of(self, item, index, count)`](/cells/python-net/sv/aspose.cells.properties/customdocumentpropertycollection/index_of/#aspose.cells.properties.documentproperty-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom elementintervallet i arraylistan som börjar vid det angivna indexet och innehåller det angivna antalet element.|
| [`copy_to(self, array)`](/cells/python-net/sv/aspose.cells.properties/customdocumentpropertycollection/copy_to/#list) |Kopierar hela arraylistan till en kompatibel endimensionell arraylista, med början i början av målarraylistan.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/sv/aspose.cells.properties/customdocumentpropertycollection/copy_to/#int-list-int-int) | Kopierar ett elementområde från arraylistan till en kompatibel endimensionell arraylista, med början vid det angivna indexet för målarraylistan.|
| [`last_index_of(self, item)`](/cells/python-net/sv/aspose.cells.properties/customdocumentpropertycollection/last_index_of/#aspose.cells.properties.documentproperty) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom hela arraylistan.|
| [`last_index_of(self, item, index)`](/cells/python-net/sv/aspose.cells.properties/customdocumentpropertycollection/last_index_of/#aspose.cells.properties.documentproperty-int) |Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom intervallet av element i arraylistan som sträcker sig från det första elementet till det angivna indexet.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/sv/aspose.cells.properties/customdocumentpropertycollection/last_index_of/#aspose.cells.properties.documentproperty-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom elementintervallet i arraylistan som innehåller det angivna antalet element och slutar vid det angivna indexet.|
| [`add(self, name, value)`](/cells/python-net/sv/aspose.cells.properties/customdocumentpropertycollection/add/#str-str) | Skapar en ny anpassad dokumentegenskap för**Egenskapstyp.String** datatyp.|
| [`add(self, name, value)`](/cells/python-net/sv/aspose.cells.properties/customdocumentpropertycollection/add/#str-int) | Skapar en ny anpassad dokumentegenskap för**PropertyType.Number** datatyp.|
| [`add(self, name, value)`](/cells/python-net/sv/aspose.cells.properties/customdocumentpropertycollection/add/#str-datetime) | Skapar en ny anpassad dokumentegenskap för**PropertyType.DateTime** datatyp.|
| [`add(self, name, value)`](/cells/python-net/sv/aspose.cells.properties/customdocumentpropertycollection/add/#str-bool) | Skapar en ny anpassad dokumentegenskap för**PropertyType.Boolean** datatyp.|
| [`add(self, name, value)`](/cells/python-net/sv/aspose.cells.properties/customdocumentpropertycollection/add/#str-float) | Skapar en ny anpassad dokumentegenskap för**PropertyType.Float** datatyp.|
| [`binary_search(self, item)`](/cells/python-net/sv/aspose.cells.properties/customdocumentpropertycollection/binary_search/#aspose.cells.properties.documentproperty) | Söker igenom hela den sorterade arraylistan efter ett element med hjälp av standardjämföraren och returnerar elementets nollbaserade index.|
| [`add_link_to_content(self, name, source)`](/cells/python-net/sv/aspose.cells.properties/customdocumentpropertycollection/add_link_to_content/#str-str) |Skapar en ny anpassad dokumentegenskap som länkar till innehåll.|
| [`update_linked_property_value(self)`](/cells/python-net/sv/aspose.cells.properties/customdocumentpropertycollection/update_linked_property_value/#) | Uppdatera egenskapsvärde för anpassat dokument som länkar till innehåll.|
| [`update_linked_range(self)`](/cells/python-net/sv/aspose.cells.properties/customdocumentpropertycollection/update_linked_range/#) | Uppdatera egenskapsvärdet för det anpassade dokumentet till det länkade området.|



###  Anmärkningar

Varje [`DocumentProperty`](/cells/python-net/sv/aspose.cells.properties/documentproperty)-objekt representerar en anpassad egenskap för ett containerdokument.

###  Exempel

```python
from aspose.cells import Workbook

# Instantiate a Workbook object
workbook = Workbook("book1.xls")
# Retrieve a list of all custom document properties of the Excel file
customProperties = workbook.worksheets.custom_document_properties

```

###  Se även
* modul [`aspose.cells.properties`](..)
* klass [`CustomDocumentPropertyCollection`](/cells/python-net/sv/aspose.cells.properties/customdocumentpropertycollection)
* klass [`DocumentProperty`](/cells/python-net/sv/aspose.cells.properties/documentproperty)
