---
title: PictureCollection klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 440
url: /sv/aspose.cells.drawing/picturecollection/
is_root: false
---
##  PictureCollection klass
Inkapslar en samling av [`Picture`](/cells/python-net/sv/aspose.cells.drawing/picture) objekt.



Typen PictureCollection avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [capacity](/cells/python-net/sv/aspose.cells.drawing/picturecollection/capacity) | Hämtar eller anger antalet element som arraylistan kan innehålla.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream)`](/cells/python-net/sv/aspose.cells.drawing/picturecollection/add/#int-int-int-int-io.rawiobase) | Lägger till en bild i samlingen.|
| [`add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, file_name)`](/cells/python-net/sv/aspose.cells.drawing/picturecollection/add/#int-int-int-int-str) | Lägger till en bild i samlingen.|
| [`add(self, upper_left_row, upper_left_column, stream)`](/cells/python-net/sv/aspose.cells.drawing/picturecollection/add/#int-int-io.rawiobase) | Lägger till en bild i samlingen.|
| [`add(self, upper_left_row, upper_left_column, file_name)`](/cells/python-net/sv/aspose.cells.drawing/picturecollection/add/#int-int-str) | Lägger till en bild i samlingen.|
| [`add(self, upper_left_row, upper_left_column, stream, width_scale, height_scale)`](/cells/python-net/sv/aspose.cells.drawing/picturecollection/add/#int-int-io.rawiobase-int-int) | Lägger till en bild i samlingen.|
| [`add(self, upper_left_row, upper_left_column, file_name, width_scale, height_scale)`](/cells/python-net/sv/aspose.cells.drawing/picturecollection/add/#int-int-str-int-int) | Lägger till en bild i samlingen.|
| [`copy_to(self, array)`](/cells/python-net/sv/aspose.cells.drawing/picturecollection/copy_to/#list) |Kopierar hela arraylistan till en kompatibel endimensionell arraylista, med början i början av målarraylistan.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/sv/aspose.cells.drawing/picturecollection/copy_to/#int-list-int-int) | Kopierar ett elementområde från arraylistan till en kompatibel endimensionell arraylista, med början vid det angivna indexet för målarraylistan.|
| [`index_of(self, item, index)`](/cells/python-net/sv/aspose.cells.drawing/picturecollection/index_of/#aspose.cells.drawing.picture-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom intervallet av element i arraylistan som sträcker sig från det angivna indexet till det sista elementet.|
| [`index_of(self, item, index, count)`](/cells/python-net/sv/aspose.cells.drawing/picturecollection/index_of/#aspose.cells.drawing.picture-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom elementintervallet i arraylistan som börjar vid det angivna indexet och innehåller det angivna antalet element.|
| [`last_index_of(self, item)`](/cells/python-net/sv/aspose.cells.drawing/picturecollection/last_index_of/#aspose.cells.drawing.picture) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom hela arraylistan.|
| [`last_index_of(self, item, index)`](/cells/python-net/sv/aspose.cells.drawing/picturecollection/last_index_of/#aspose.cells.drawing.picture-int) |Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom intervallet av element i arraylistan som sträcker sig från det första elementet till det angivna indexet.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/sv/aspose.cells.drawing/picturecollection/last_index_of/#aspose.cells.drawing.picture-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom elementintervallet i arraylistan som innehåller det angivna antalet element och slutar vid det angivna indexet.|
| [`camera(self, row, column, range)`](/cells/python-net/sv/aspose.cells.drawing/picturecollection/camera/#int-int-str) | Tar ett foto av intervallet.|
| [`binary_search(self, item)`](/cells/python-net/sv/aspose.cells.drawing/picturecollection/binary_search/#aspose.cells.drawing.picture) | Söker igenom hela den sorterade arraylistan efter ett element med hjälp av standardjämföraren och returnerar elementets nollbaserade index.|



###  Exempel

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# get PictureCollection
pictures = workbook.worksheets[0].pictures
# do your business
# Save the excel file.
workbook.save("result.xlsx")

```

###  Se även
* modul [`aspose.cells.drawing`](..)
* klass [`Picture`](/cells/python-net/sv/aspose.cells.drawing/picture)
