---
title: TextBoxCollection klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 670
url: /sv/aspose.cells.drawing/textboxcollection/
is_root: false
---
##  TextBoxCollection klass
Inkapslar en samling av [`TextBox`](/cells/python-net/sv/aspose.cells.drawing/textbox) objekt.



Typen TextBoxCollection avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [capacity](/cells/python-net/sv/aspose.cells.drawing/textboxcollection/capacity) | Hämtar eller anger antalet element som arraylistan kan innehålla.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`copy_to(self, array)`](/cells/python-net/sv/aspose.cells.drawing/textboxcollection/copy_to/#list) |Kopierar hela arraylistan till en kompatibel endimensionell arraylista, med början i början av målarraylistan.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/sv/aspose.cells.drawing/textboxcollection/copy_to/#int-list-int-int) | Kopierar ett elementområde från arraylistan till en kompatibel endimensionell arraylista, med början vid det angivna indexet för målarraylistan.|
| [`index_of(self, item, index)`](/cells/python-net/sv/aspose.cells.drawing/textboxcollection/index_of/#aspose.cells.drawing.textbox-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom intervallet av element i arraylistan som sträcker sig från det angivna indexet till det sista elementet.|
| [`index_of(self, item, index, count)`](/cells/python-net/sv/aspose.cells.drawing/textboxcollection/index_of/#aspose.cells.drawing.textbox-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom elementintervallet i arraylistan som börjar vid det angivna indexet och innehåller det angivna antalet element.|
| [`last_index_of(self, item)`](/cells/python-net/sv/aspose.cells.drawing/textboxcollection/last_index_of/#aspose.cells.drawing.textbox) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom hela arraylistan.|
| [`last_index_of(self, item, index)`](/cells/python-net/sv/aspose.cells.drawing/textboxcollection/last_index_of/#aspose.cells.drawing.textbox-int) |Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom intervallet av element i arraylistan som sträcker sig från det första elementet till det angivna indexet.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/sv/aspose.cells.drawing/textboxcollection/last_index_of/#aspose.cells.drawing.textbox-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom elementintervallet i arraylistan som innehåller det angivna antalet element och slutar vid det angivna indexet.|
| [`get(self, name)`](/cells/python-net/sv/aspose.cells.drawing/textboxcollection/get/#str) | Hämtar elementet [`TextBox`](/cells/python-net/sv/aspose.cells.drawing/textbox) med namnet.|
| [`add(self, upper_left_row, upper_left_column, height, width)`](/cells/python-net/sv/aspose.cells.drawing/textboxcollection/add/#int-int-int-int) | Lägger till en textruta i samlingen.|
| [`binary_search(self, item)`](/cells/python-net/sv/aspose.cells.drawing/textboxcollection/binary_search/#aspose.cells.drawing.textbox) | Söker igenom hela den sorterade arraylistan efter ett element med hjälp av standardjämföraren och returnerar elementets nollbaserade index.|



###  Exempel

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# get collection object
textBoxCollection = workbook.worksheets[0].text_boxes
# add a textbox
textBoxCollection.add(1, 1, 50, 100)
for tbox in textBoxCollection:
    pass

```

###  Se även
* modul [`aspose.cells.drawing`](..)
* klass [`TextBox`](/cells/python-net/sv/aspose.cells.drawing/textbox)
