---
title: CommentCollection klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 270
url: /sv/aspose.cells/commentcollection/
is_root: false
---
##  CommentCollection klass
Inkapslar en samling av [`Comment`](/cells/python-net/sv/aspose.cells/comment) objekt.



Typen CommentCollection avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [capacity](/cells/python-net/sv/aspose.cells/commentcollection/capacity) | Hämtar eller anger antalet element som arraylistan kan innehålla.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`add_threaded_comment(self, row, column, text, author)`](/cells/python-net/sv/aspose.cells/commentcollection/add_threaded_comment/#int-int-str-aspose.cells.threadedcommentauthor) | Lägger till en trådad kommentar.|
| [`add_threaded_comment(self, cell_name, text, author)`](/cells/python-net/sv/aspose.cells/commentcollection/add_threaded_comment/#str-str-aspose.cells.threadedcommentauthor) | Lägger till en trådad kommentar.|
| [`get_threaded_comments(self, row, column)`](/cells/python-net/sv/aspose.cells/commentcollection/get_threaded_comments/#int-int) | Hämtar de trådade kommentarerna efter rad- och kolumnindex.|
| [`get_threaded_comments(self, cell_name)`](/cells/python-net/sv/aspose.cells/commentcollection/get_threaded_comments/#str) | Hämtar de trådade kommentarerna efter cellnamn.|
| [`add(self, row, column)`](/cells/python-net/sv/aspose.cells/commentcollection/add/#int-int) | Lägger till en kommentar i samlingen.|
| [`add(self, cell_name)`](/cells/python-net/sv/aspose.cells/commentcollection/add/#str) | Lägger till en kommentar i samlingen.|
| [`get(self, row, column)`](/cells/python-net/sv/aspose.cells/commentcollection/get/#int-int) | Lägg till API for Python Via .Net. eftersom detta[int, int] inte stöds.|
| [`get(self, index)`](/cells/python-net/sv/aspose.cells/commentcollection/get/#int) | Hämtar elementet [`Comment`](/cells/python-net/sv/aspose.cells/comment) vid det angivna indexet.|
| [`get(self, cell_name)`](/cells/python-net/sv/aspose.cells/commentcollection/get/#str) | Hämtar elementet [`Comment`](/cells/python-net/sv/aspose.cells/comment) i den angivna cellen.|
| [`remove_at(self, cell_name)`](/cells/python-net/sv/aspose.cells/commentcollection/remove_at/#str) | Tar bort kommentaren för den specifika cellen.|
| [`remove_at(self, row, column)`](/cells/python-net/sv/aspose.cells/commentcollection/remove_at/#int-int) | Tar bort kommentaren för den specifika cellen.|
| [`copy_to(self, array)`](/cells/python-net/sv/aspose.cells/commentcollection/copy_to/#list) |Kopierar hela arraylistan till en kompatibel endimensionell arraylista, med början i början av målarraylistan.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/sv/aspose.cells/commentcollection/copy_to/#int-list-int-int) | Kopierar ett elementområde från arraylistan till en kompatibel endimensionell arraylista, med början vid det angivna indexet för målarraylistan.|
| [`index_of(self, item, index)`](/cells/python-net/sv/aspose.cells/commentcollection/index_of/#aspose.cells.comment-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom intervallet av element i arraylistan som sträcker sig från det angivna indexet till det sista elementet.|
| [`index_of(self, item, index, count)`](/cells/python-net/sv/aspose.cells/commentcollection/index_of/#aspose.cells.comment-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom elementintervallet i arraylistan som börjar vid det angivna indexet och innehåller det angivna antalet element.|
| [`last_index_of(self, item)`](/cells/python-net/sv/aspose.cells/commentcollection/last_index_of/#aspose.cells.comment) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom hela arraylistan.|
| [`last_index_of(self, item, index)`](/cells/python-net/sv/aspose.cells/commentcollection/last_index_of/#aspose.cells.comment-int) |Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom intervallet av element i arraylistan som sträcker sig från det första elementet till det angivna indexet.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/sv/aspose.cells/commentcollection/last_index_of/#aspose.cells.comment-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom elementintervallet i arraylistan som innehåller det angivna antalet element och slutar vid det angivna indexet.|
| [`binary_search(self, item)`](/cells/python-net/sv/aspose.cells/commentcollection/binary_search/#aspose.cells.comment) | Söker igenom hela den sorterade arraylistan efter ett element med hjälp av standardjämföraren och returnerar elementets nollbaserade index.|



###  Exempel

```python
from aspose.cells import Workbook

workbook = Workbook()
comments = workbook.worksheets[0].comments

```

###  Se även
* modul [`aspose.cells`](..)
* klass [`Comment`](/cells/python-net/sv/aspose.cells/comment)
