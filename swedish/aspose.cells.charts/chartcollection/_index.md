---
title: ChartCollection klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 60
url: /sv/aspose.cells.charts/chartcollection/
is_root: false
---
##  ChartCollection klass
Inkapslar en samling av [`Chart`](/cells/python-net/sv/aspose.cells.charts/chart) objekt.



Typen ChartCollection avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [capacity](/cells/python-net/sv/aspose.cells.charts/chartcollection/capacity) | Hämtar eller anger antalet element som arraylistan kan innehålla.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`add(self, type, upper_left_row, upper_left_column, lower_right_row, lower_right_column)`](/cells/python-net/sv/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.charttype-int-int-int-int) | Lägger till ett diagram i samlingen.|
| [`add(self, type, data_range, top_row, left_column, right_row, bottom_column)`](/cells/python-net/sv/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.charttype-str-int-int-int-int) | Lägger till ett diagram i samlingen.|
| [`add(self, data, data_range, is_vertical, top_row, left_column, right_row, bottom_column)`](/cells/python-net/sv/aspose.cells.charts/chartcollection/add/#bytes-str-bool-int-int-int-int) | Lägger till ett diagram med förinställd mall.|
| [`add(self, type, data_range, is_vertical, top_row, left_column, right_row, bottom_column)`](/cells/python-net/sv/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.charttype-str-bool-int-int-int-int) | Lägger till ett diagram i samlingen.|
| [`get(self, index)`](/cells/python-net/sv/aspose.cells.charts/chartcollection/get/#int) | Lägg till API for Python Via .Net. eftersom detta[int index] inte stöds.|
| [`get(self, name)`](/cells/python-net/sv/aspose.cells.charts/chartcollection/get/#str) | Lägg till API for Python Via .Net. eftersom detta [strängdiagram] inte stöds.|
| [`copy_to(self, array)`](/cells/python-net/sv/aspose.cells.charts/chartcollection/copy_to/#list) |Kopierar hela arraylistan till en kompatibel endimensionell arraylista, med början i början av målarraylistan.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/sv/aspose.cells.charts/chartcollection/copy_to/#int-list-int-int) | Kopierar ett elementområde från arraylistan till en kompatibel endimensionell arraylista, med början vid det angivna indexet för målarraylistan.|
| [`index_of(self, item, index)`](/cells/python-net/sv/aspose.cells.charts/chartcollection/index_of/#aspose.cells.charts.chart-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom intervallet av element i arraylistan som sträcker sig från det angivna indexet till det sista elementet.|
| [`index_of(self, item, index, count)`](/cells/python-net/sv/aspose.cells.charts/chartcollection/index_of/#aspose.cells.charts.chart-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom elementintervallet i arraylistan som börjar vid det angivna indexet och innehåller det angivna antalet element.|
| [`last_index_of(self, item)`](/cells/python-net/sv/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.chart) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom hela arraylistan.|
| [`last_index_of(self, item, index)`](/cells/python-net/sv/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.chart-int) |Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom intervallet av element i arraylistan som sträcker sig från det första elementet till det angivna indexet.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/sv/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.chart-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom elementintervallet i arraylistan som innehåller det angivna antalet element och slutar vid det angivna indexet.|
| [`add_floating_chart(self, type, left, top, width, height)`](/cells/python-net/sv/aspose.cells.charts/chartcollection/add_floating_chart/#aspose.cells.charts.charttype-int-int-int-int) | Lägger till ett diagram i samlingen.|
| [`binary_search(self, item)`](/cells/python-net/sv/aspose.cells.charts/chartcollection/binary_search/#aspose.cells.charts.chart) | Söker igenom hela den sorterade arraylistan efter ett element med hjälp av standardjämföraren och returnerar elementets nollbaserade index.|



###  Exempel

```python
from aspose.cells import Workbook

workbook = Workbook()
charts = workbook.worksheets[0].charts

```

###  Se även
* modul [`aspose.cells.charts`](..)
* klass [`Chart`](/cells/python-net/sv/aspose.cells.charts/chart)
