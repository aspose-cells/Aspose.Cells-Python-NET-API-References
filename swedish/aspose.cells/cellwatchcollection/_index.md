---
title: CellWatchCollection klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 150
url: /sv/aspose.cells/cellwatchcollection/
is_root: false
---
##  CellWatchCollection klass
Representerar samlingen av celler i detta kalkylblad som övervakas i 'övervakningsfönstret'.



Typen CellWatchCollection avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [`__init__(self)`](/cells/python-net/sv/aspose.cells/cellwatchcollection/__init__/#) | Konstruerar en ny instans av CellWatchCollection|


###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [capacity](/cells/python-net/sv/aspose.cells/cellwatchcollection/capacity) | Hämtar eller anger antalet element som arraylistan kan innehålla.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`add(self, row, column)`](/cells/python-net/sv/aspose.cells/cellwatchcollection/add/#int-int) | Lägger till [`CellWatch`](/cells/python-net/sv/aspose.cells/cellwatch) med rad och kolumn.|
| [`add(self, cell_name)`](/cells/python-net/sv/aspose.cells/cellwatchcollection/add/#str) | Lägger till [`CellWatch`](/cells/python-net/sv/aspose.cells/cellwatch) med namnet på cellen.|
| [`copy_to(self, array)`](/cells/python-net/sv/aspose.cells/cellwatchcollection/copy_to/#list) |Kopierar hela arraylistan till en kompatibel endimensionell arraylista, med början i början av målarraylistan.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/sv/aspose.cells/cellwatchcollection/copy_to/#int-list-int-int) | Kopierar ett elementområde från arraylistan till en kompatibel endimensionell arraylista, med början vid det angivna indexet för målarraylistan.|
| [`index_of(self, item, index)`](/cells/python-net/sv/aspose.cells/cellwatchcollection/index_of/#aspose.cells.cellwatch-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom intervallet av element i arraylistan som sträcker sig från det angivna indexet till det sista elementet.|
| [`index_of(self, item, index, count)`](/cells/python-net/sv/aspose.cells/cellwatchcollection/index_of/#aspose.cells.cellwatch-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom elementintervallet i arraylistan som börjar vid det angivna indexet och innehåller det angivna antalet element.|
| [`last_index_of(self, item)`](/cells/python-net/sv/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.cellwatch) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom hela arraylistan.|
| [`last_index_of(self, item, index)`](/cells/python-net/sv/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.cellwatch-int) |Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom intervallet av element i arraylistan som sträcker sig från det första elementet till det angivna indexet.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/sv/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.cellwatch-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom elementintervallet i arraylistan som innehåller det angivna antalet element och slutar vid det angivna indexet.|
| [`get(self, cell_name)`](/cells/python-net/sv/aspose.cells/cellwatchcollection/get/#str) | Hämtar och sätter [`CellWatch`](/cells/python-net/sv/aspose.cells/cellwatch) med hjälp av cellens namn.|
| [`binary_search(self, item)`](/cells/python-net/sv/aspose.cells/cellwatchcollection/binary_search/#aspose.cells.cellwatch) | Söker igenom hela den sorterade arraylistan efter ett element med hjälp av standardjämföraren och returnerar elementets nollbaserade index.|



###  Exempel

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Get the first Worksheet.
sheet = workbook.worksheets[0]
#  Add Cell Watch Item into the watch window
sheet.cell_watches.add("B2")

```

###  Se även
* modul [`aspose.cells`](..)
* klass [`CellWatch`](/cells/python-net/sv/aspose.cells/cellwatch)
