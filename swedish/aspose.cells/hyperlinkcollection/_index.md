---
title: HyperlinkCollection klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 850
url: /sv/aspose.cells/hyperlinkcollection/
is_root: false
---
##  HyperlinkCollection klass
Kapslar in en samling av [`Hyperlink`](/cells/python-net/sv/aspose.cells/hyperlink) objekt.



Typen HyperlinkCollection avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [capacity](/cells/python-net/sv/aspose.cells/hyperlinkcollection/capacity) | Hämtar eller ställer in antalet element som arraylistan kan innehålla.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [add](/cells/python-net/sv/aspose.cells/hyperlinkcollection/add/#int-int-int-int-str) | Lägger till en hyperlänk till en angiven cell eller ett cellintervall.|
| [add](/cells/python-net/sv/aspose.cells/hyperlinkcollection/add/#str-int-int-str) | Lägger till en hyperlänk till en angiven cell eller ett cellintervall.|
| [add](/cells/python-net/sv/aspose.cells/hyperlinkcollection/add/#str-str-str-str-str) | Lägger till en hyperlänk till en angiven cell eller ett cellintervall.|
| [copy_to](/cells/python-net/sv/aspose.cells/hyperlinkcollection/copy_to/#list) | Kopierar hela arraylistan till en kompatibel endimensionell arraylista, med början i början av målarraylistan.|
| [copy_to](/cells/python-net/sv/aspose.cells/hyperlinkcollection/copy_to/#int-list-int-int) | Kopierar ett intervall av element från arraylistan till en kompatibel endimensionell arraylista, med början vid det angivna indexet för målarraylistan.|
| [index_of](/cells/python-net/sv/aspose.cells/hyperlinkcollection/index_of/#aspose.cells.Hyperlink-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom intervallet av element i arraylistan som sträcker sig från det angivna indexet till det sista elementet.|
| [index_of](/cells/python-net/sv/aspose.cells/hyperlinkcollection/index_of/#aspose.cells.Hyperlink-int-int) |Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom intervallet av element i arraylistan som börjar vid det angivna indexet och innehåller det angivna antalet element.|
| [last_index_of](/cells/python-net/sv/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.Hyperlink) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom hela arraylistan.|
| [last_index_of](/cells/python-net/sv/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.Hyperlink-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom intervallet av element i arraylistan som sträcker sig från det första elementet till det angivna indexet.|
| [last_index_of](/cells/python-net/sv/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.Hyperlink-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom intervallet av element i arraylistan som innehåller det angivna antalet element och slutar vid det angivna indexet.|
| [binary_search](/cells/python-net/sv/aspose.cells/hyperlinkcollection/binary_search/#aspose.cells.Hyperlink) | Söker i hela den sorterade arraylistan efter ett element med hjälp av standardjämföraren och returnerar elementets nollbaserade index.|



###  Exempel

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[0]
# Get Hyperlinks Collection
hyperlinks = worksheet.hyperlinks
# Adding a hyperlink to a URL at "A1" cell
hyperlinks.add("A1", 1, 1, "http://www.aspose.com")
# Saving the Excel file
workbook.save("book1.xls")

```

###  Se även
* modul [`aspose.cells`](..)
* klass [`Hyperlink`](/cells/python-net/sv/aspose.cells/hyperlink)
