---
title: HorizontalPageBreakCollection klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 790
url: /sv/aspose.cells/horizontalpagebreakcollection/
is_root: false
---
##  HorizontalPageBreakCollection klass
Kapslar in en samling av [`HorizontalPageBreak`](/cells/python-net/sv/aspose.cells/horizontalpagebreak) objekt.



Typen HorizontalPageBreakCollection avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [capacity](/cells/python-net/sv/aspose.cells/horizontalpagebreakcollection/capacity) | Hämtar eller ställer in antalet element som arraylistan kan innehålla.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [add](/cells/python-net/sv/aspose.cells/horizontalpagebreakcollection/add/#int-int-int) |Lägger till en horisontell sidbrytning i samlingen.|
| [add](/cells/python-net/sv/aspose.cells/horizontalpagebreakcollection/add/#int) |Lägger till en horisontell sidbrytning i samlingen.|
| [add](/cells/python-net/sv/aspose.cells/horizontalpagebreakcollection/add/#int-int) |Lägger till en horisontell sidbrytning i samlingen.|
| [add](/cells/python-net/sv/aspose.cells/horizontalpagebreakcollection/add/#str) |Lägger till en horisontell sidbrytning i samlingen.|
| [copy_to](/cells/python-net/sv/aspose.cells/horizontalpagebreakcollection/copy_to/#list) | Kopierar hela arraylistan till en kompatibel endimensionell arraylista, med början i början av målarraylistan.|
| [copy_to](/cells/python-net/sv/aspose.cells/horizontalpagebreakcollection/copy_to/#int-list-int-int) | Kopierar ett intervall av element från arraylistan till en kompatibel endimensionell arraylista, med början vid det angivna indexet för målarraylistan.|
| [index_of](/cells/python-net/sv/aspose.cells/horizontalpagebreakcollection/index_of/#aspose.cells.HorizontalPageBreak-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom intervallet av element i arraylistan som sträcker sig från det angivna indexet till det sista elementet.|
| [index_of](/cells/python-net/sv/aspose.cells/horizontalpagebreakcollection/index_of/#aspose.cells.HorizontalPageBreak-int-int) |Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom intervallet av element i arraylistan som börjar vid det angivna indexet och innehåller det angivna antalet element.|
| [last_index_of](/cells/python-net/sv/aspose.cells/horizontalpagebreakcollection/last_index_of/#aspose.cells.HorizontalPageBreak) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom hela arraylistan.|
| [last_index_of](/cells/python-net/sv/aspose.cells/horizontalpagebreakcollection/last_index_of/#aspose.cells.HorizontalPageBreak-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom intervallet av element i arraylistan som sträcker sig från det första elementet till det angivna indexet.|
| [last_index_of](/cells/python-net/sv/aspose.cells/horizontalpagebreakcollection/last_index_of/#aspose.cells.HorizontalPageBreak-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom intervallet av element i arraylistan som innehåller det angivna antalet element och slutar vid det angivna indexet.|
| [binary_search](/cells/python-net/sv/aspose.cells/horizontalpagebreakcollection/binary_search/#aspose.cells.HorizontalPageBreak) | Söker i hela den sorterade arraylistan efter ett element med hjälp av standardjämföraren och returnerar elementets nollbaserade index.|



###  Exempel

```python
from aspose.cells import Workbook

excel = Workbook()
# Add a pagebreak at G5
excel.worksheets[0].horizontal_page_breaks.add("G5")
excel.worksheets[0].vertical_page_breaks.add("G5")

```

###  Se även
* modul [`aspose.cells`](..)
* klass [`HorizontalPageBreak`](/cells/python-net/sv/aspose.cells/horizontalpagebreak)
