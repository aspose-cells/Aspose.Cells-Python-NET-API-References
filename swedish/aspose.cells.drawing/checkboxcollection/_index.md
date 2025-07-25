---
title: CheckBoxCollection klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 100
url: /sv/aspose.cells.drawing/checkboxcollection/
is_root: false
---
##  CheckBoxCollection klass
Representerar en samling av [`CheckBox`](/cells/python-net/sv/aspose.cells.drawing/checkbox) objekt i ett kalkylblad.



Typen CheckBoxCollection avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [capacity](/cells/python-net/sv/aspose.cells.drawing/checkboxcollection/capacity) | Hämtar eller anger antalet element som arraylistan kan innehålla.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`copy_to(self, array)`](/cells/python-net/sv/aspose.cells.drawing/checkboxcollection/copy_to/#list) |Kopierar hela arraylistan till en kompatibel endimensionell arraylista, med början i början av målarraylistan.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/sv/aspose.cells.drawing/checkboxcollection/copy_to/#int-list-int-int) | Kopierar ett elementområde från arraylistan till en kompatibel endimensionell arraylista, med början vid det angivna indexet för målarraylistan.|
| [`index_of(self, item, index)`](/cells/python-net/sv/aspose.cells.drawing/checkboxcollection/index_of/#aspose.cells.drawing.checkbox-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom intervallet av element i arraylistan som sträcker sig från det angivna indexet till det sista elementet.|
| [`index_of(self, item, index, count)`](/cells/python-net/sv/aspose.cells.drawing/checkboxcollection/index_of/#aspose.cells.drawing.checkbox-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom elementintervallet i arraylistan som börjar vid det angivna indexet och innehåller det angivna antalet element.|
| [`last_index_of(self, item)`](/cells/python-net/sv/aspose.cells.drawing/checkboxcollection/last_index_of/#aspose.cells.drawing.checkbox) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom hela arraylistan.|
| [`last_index_of(self, item, index)`](/cells/python-net/sv/aspose.cells.drawing/checkboxcollection/last_index_of/#aspose.cells.drawing.checkbox-int) |Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom intervallet av element i arraylistan som sträcker sig från det första elementet till det angivna indexet.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/sv/aspose.cells.drawing/checkboxcollection/last_index_of/#aspose.cells.drawing.checkbox-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom elementintervallet i arraylistan som innehåller det angivna antalet element och slutar vid det angivna indexet.|
| [`add(self, upper_left_row, upper_left_column, height, width)`](/cells/python-net/sv/aspose.cells.drawing/checkboxcollection/add/#int-int-int-int) | Lägger till en kryssruta i samlingen.|
| [`binary_search(self, item)`](/cells/python-net/sv/aspose.cells.drawing/checkboxcollection/binary_search/#aspose.cells.drawing.checkbox) | Söker igenom hela den sorterade arraylistan efter ett element med hjälp av standardjämföraren och returnerar elementets nollbaserade index.|



###  Exempel

```python
from aspose.cells import Workbook

# Create a new Workbook.
workbook = Workbook()
# Get the first worksheet in the workbook.
sheet = workbook.worksheets[0]
index = sheet.check_boxes.add(15, 15, 20, 100)
checkBox = sheet.check_boxes[index]
checkBox.text = "Check Box 1"

```

###  Se även
* modul [`aspose.cells.drawing`](..)
* klass [`CheckBox`](/cells/python-net/sv/aspose.cells.drawing/checkbox)
