---
title: CommentCollection klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 300
url: /sv/aspose.cells/commentcollection/
is_root: false
---
##  CommentCollection klass
Kapslar in en samling av [`Comment`](/cells/python-net/sv/aspose.cells/comment) objekt.



Typen CommentCollection avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [capacity](/cells/python-net/sv/aspose.cells/commentcollection/capacity) | Hämtar eller ställer in antalet element som arraylistan kan innehålla.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [add_threaded_comment](/cells/python-net/sv/aspose.cells/commentcollection/add_threaded_comment/#int-int-str-aspose.cells.ThreadedCommentAuthor) | Lägger till en trådad kommentar.|
| [add_threaded_comment](/cells/python-net/sv/aspose.cells/commentcollection/add_threaded_comment/#str-str-aspose.cells.ThreadedCommentAuthor) | Lägger till en trådad kommentar.|
| [get_threaded_comments](/cells/python-net/sv/aspose.cells/commentcollection/get_threaded_comments/#int-int) | Får de trådade kommentarerna efter rad- och kolumnindex.|
| [get_threaded_comments](/cells/python-net/sv/aspose.cells/commentcollection/get_threaded_comments/#str) |Får de trådade kommentarerna efter cellnamn.|
| [add](/cells/python-net/sv/aspose.cells/commentcollection/add/#int-int) | Lägger till en kommentar till samlingen.|
| [add](/cells/python-net/sv/aspose.cells/commentcollection/add/#str) | Lägger till en kommentar till samlingen.|
| [remove_at](/cells/python-net/sv/aspose.cells/commentcollection/remove_at/#str) | Tar bort kommentaren från den specifika cellen.|
| [remove_at](/cells/python-net/sv/aspose.cells/commentcollection/remove_at/#int-int) | Tar bort kommentaren från den specifika cellen.|
| [copy_to](/cells/python-net/sv/aspose.cells/commentcollection/copy_to/#list) | Kopierar hela arraylistan till en kompatibel endimensionell arraylista, med början i början av målarraylistan.|
| [copy_to](/cells/python-net/sv/aspose.cells/commentcollection/copy_to/#int-list-int-int) | Kopierar ett intervall av element från arraylistan till en kompatibel endimensionell arraylista, med början vid det angivna indexet för målarraylistan.|
| [index_of](/cells/python-net/sv/aspose.cells/commentcollection/index_of/#aspose.cells.Comment-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom intervallet av element i arraylistan som sträcker sig från det angivna indexet till det sista elementet.|
| [index_of](/cells/python-net/sv/aspose.cells/commentcollection/index_of/#aspose.cells.Comment-int-int) |Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom intervallet av element i arraylistan som börjar vid det angivna indexet och innehåller det angivna antalet element.|
| [last_index_of](/cells/python-net/sv/aspose.cells/commentcollection/last_index_of/#aspose.cells.Comment) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom hela arraylistan.|
| [last_index_of](/cells/python-net/sv/aspose.cells/commentcollection/last_index_of/#aspose.cells.Comment-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom intervallet av element i arraylistan som sträcker sig från det första elementet till det angivna indexet.|
| [last_index_of](/cells/python-net/sv/aspose.cells/commentcollection/last_index_of/#aspose.cells.Comment-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom intervallet av element i arraylistan som innehåller det angivna antalet element och slutar vid det angivna indexet.|
| [binary_search](/cells/python-net/sv/aspose.cells/commentcollection/binary_search/#aspose.cells.Comment) | Söker i hela den sorterade arraylistan efter ett element med hjälp av standardjämföraren och returnerar elementets nollbaserade index.|



###  Exempel

```python
from aspose.cells import Workbook

workbook = Workbook()
comments = workbook.worksheets[0].comments

```

###  Se även
* modul [`aspose.cells`](..)
* klass [`Comment`](/cells/python-net/sv/aspose.cells/comment)
