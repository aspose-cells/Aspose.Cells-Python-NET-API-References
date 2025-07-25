---
title: SparklineGroupCollection klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 300
url: /sv/aspose.cells.charts/sparklinegroupcollection/
is_root: false
---
##  SparklineGroupCollection klass
Inkapslar en samling av [`SparklineGroup`](/cells/python-net/sv/aspose.cells.charts/sparklinegroup) objekt.



Typen SparklineGroupCollection avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [capacity](/cells/python-net/sv/aspose.cells.charts/sparklinegroupcollection/capacity) | Hämtar eller anger antalet element som arraylistan kan innehålla.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`add(self, type)`](/cells/python-net/sv/aspose.cells.charts/sparklinegroupcollection/add/#aspose.cells.charts.sparklinetype) | Lägger till en [`SparklineGroup`](/cells/python-net/sv/aspose.cells.charts/sparklinegroup) med en [`Sparkline`](/cells/python-net/sv/aspose.cells.charts/sparkline) i samlingen.|
| [`add(self, type, data_range, is_vertical, location_range)`](/cells/python-net/sv/aspose.cells.charts/sparklinegroupcollection/add/#aspose.cells.charts.sparklinetype-str-bool-aspose.cells.cellarea) | Lägger till en [`SparklineGroup`](/cells/python-net/sv/aspose.cells.charts/sparklinegroup) med [`Sparkline`](/cells/python-net/sv/aspose.cells.charts/sparkline) i samlingen.|
| [`copy_to(self, array)`](/cells/python-net/sv/aspose.cells.charts/sparklinegroupcollection/copy_to/#list) |Kopierar hela arraylistan till en kompatibel endimensionell arraylista, med början i början av målarraylistan.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/sv/aspose.cells.charts/sparklinegroupcollection/copy_to/#int-list-int-int) | Kopierar ett elementområde från arraylistan till en kompatibel endimensionell arraylista, med början vid det angivna indexet för målarraylistan.|
| [`index_of(self, item, index)`](/cells/python-net/sv/aspose.cells.charts/sparklinegroupcollection/index_of/#aspose.cells.charts.sparklinegroup-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom intervallet av element i arraylistan som sträcker sig från det angivna indexet till det sista elementet.|
| [`index_of(self, item, index, count)`](/cells/python-net/sv/aspose.cells.charts/sparklinegroupcollection/index_of/#aspose.cells.charts.sparklinegroup-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom elementintervallet i arraylistan som börjar vid det angivna indexet och innehåller det angivna antalet element.|
| [`last_index_of(self, item)`](/cells/python-net/sv/aspose.cells.charts/sparklinegroupcollection/last_index_of/#aspose.cells.charts.sparklinegroup) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom hela arraylistan.|
| [`last_index_of(self, item, index)`](/cells/python-net/sv/aspose.cells.charts/sparklinegroupcollection/last_index_of/#aspose.cells.charts.sparklinegroup-int) |Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom intervallet av element i arraylistan som sträcker sig från det första elementet till det angivna indexet.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/sv/aspose.cells.charts/sparklinegroupcollection/last_index_of/#aspose.cells.charts.sparklinegroup-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom elementintervallet i arraylistan som innehåller det angivna antalet element och slutar vid det angivna indexet.|
| [`clear_sparklines(self, cell_area)`](/cells/python-net/sv/aspose.cells.charts/sparklinegroupcollection/clear_sparklines/#aspose.cells.cellarea) | Rensar miniatyrdiagrammet som finns inuti ett cellområde.|
| [`clear_sparkline_groups(self, cell_area)`](/cells/python-net/sv/aspose.cells.charts/sparklinegroupcollection/clear_sparkline_groups/#aspose.cells.cellarea) | Rensar miniatyrdiagrammets grupper som överlappar ett cellområde.|
| [`binary_search(self, item)`](/cells/python-net/sv/aspose.cells.charts/sparklinegroupcollection/binary_search/#aspose.cells.charts.sparklinegroup) | Söker igenom hela den sorterade arraylistan efter ett element med hjälp av standardjämföraren och returnerar elementets nollbaserade index.|



###  Exempel

```python
from aspose.cells import CellArea, SaveFormat, Workbook
from aspose.cells.charts import SparklineType

book = Workbook()
sheet = book.worksheets[0]
sheet.cells.get("A1").put_value(5)
sheet.cells.get("B1").put_value(2)
sheet.cells.get("C1").put_value(1)
sheet.cells.get("D1").put_value(3)
#  Define the CellArea
ca = CellArea()
ca.start_column = 4
ca.end_column = 4
ca.start_row = 0
ca.end_row = 0
idx = sheet.sparkline_groups.add(SparklineType.LINE, "A1:D1", False, ca)
group = sheet.sparkline_groups[idx]
group.sparklines.add(sheet.name + "!A1:D1", 0, 4)
book.save("output.xlsx", SaveFormat.XLSX)

```

###  Se även
* modul [`aspose.cells.charts`](..)
* klass [`Sparkline`](/cells/python-net/sv/aspose.cells.charts/sparkline)
* klass [`SparklineGroup`](/cells/python-net/sv/aspose.cells.charts/sparklinegroup)
