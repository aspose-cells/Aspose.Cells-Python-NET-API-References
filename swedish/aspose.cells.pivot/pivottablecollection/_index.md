---
title: PivotTableCollection klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 250
url: /sv/aspose.cells.pivot/pivottablecollection/
is_root: false
---
##  PivotTableCollection klass
Representerar samlingen av alla pivottabellobjekt i det angivna kalkylbladet.



Typen PivotTableCollection avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [capacity](/cells/python-net/sv/aspose.cells.pivot/pivottablecollection/capacity) | Hämtar eller anger antalet element som arraylistan kan innehålla.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`add(self, source_data, dest_cell_name, table_name)`](/cells/python-net/sv/aspose.cells.pivot/pivottablecollection/add/#str-str-str) | Lägger till en ny pivottabell.|
| [`add(self, source_data, dest_cell_name, table_name, use_same_source)`](/cells/python-net/sv/aspose.cells.pivot/pivottablecollection/add/#str-str-str-bool) | Lägger till en ny pivottabell.|
| [`add(self, source_data, row, column, table_name)`](/cells/python-net/sv/aspose.cells.pivot/pivottablecollection/add/#str-int-int-str) | Lägger till en ny pivottabell.|
| [`add(self, source_data, row, column, table_name, use_same_source)`](/cells/python-net/sv/aspose.cells.pivot/pivottablecollection/add/#str-int-int-str-bool) | Lägger till en ny pivottabell.|
| [`add(self, source_data, row, column, table_name, use_same_source, is_xls_classic)`](/cells/python-net/sv/aspose.cells.pivot/pivottablecollection/add/#str-int-int-str-bool-bool) | Lägger till en ny pivottabell.|
| [`add(self, source_data, cell, table_name, use_same_source, is_xls_classic)`](/cells/python-net/sv/aspose.cells.pivot/pivottablecollection/add/#str-str-str-bool-bool) | Lägger till en ny pivottabell.|
| [`add(self, pivot_table, dest_cell_name, table_name)`](/cells/python-net/sv/aspose.cells.pivot/pivottablecollection/add/#aspose.cells.pivot.pivottable-str-str) | Lägger till en ny pivottabell baserad på en annan pivottabell.|
| [`add(self, pivot_table, row, column, table_name)`](/cells/python-net/sv/aspose.cells.pivot/pivottablecollection/add/#aspose.cells.pivot.pivottable-int-int-str) | Lägger till en ny pivottabell baserad på en annan pivottabell.|
| [`add(self, source_data, is_auto_page, page_fields, dest_cell_name, table_name)`](/cells/python-net/sv/aspose.cells.pivot/pivottablecollection/add/#list-bool-aspose.cells.pivot.pivotpagefields-str-str) | Lägger till ett nytt pivottabellobjekt i samlingen med flera konsolideringsområden som datakälla.|
| [`add(self, source_data, is_auto_page, page_fields, row, column, table_name)`](/cells/python-net/sv/aspose.cells.pivot/pivottablecollection/add/#list-bool-aspose.cells.pivot.pivotpagefields-int-int-str) | Lägger till ett nytt pivottabellobjekt i samlingen med flera konsolideringsområden som datakälla.|
| [`copy_to(self, array)`](/cells/python-net/sv/aspose.cells.pivot/pivottablecollection/copy_to/#list) |Kopierar hela arraylistan till en kompatibel endimensionell arraylista, med början i början av målarraylistan.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/sv/aspose.cells.pivot/pivottablecollection/copy_to/#int-list-int-int) | Kopierar ett elementområde från arraylistan till en kompatibel endimensionell arraylista, med början vid det angivna indexet för målarraylistan.|
| [`index_of(self, item, index)`](/cells/python-net/sv/aspose.cells.pivot/pivottablecollection/index_of/#aspose.cells.pivot.pivottable-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom intervallet av element i arraylistan som sträcker sig från det angivna indexet till det sista elementet.|
| [`index_of(self, item, index, count)`](/cells/python-net/sv/aspose.cells.pivot/pivottablecollection/index_of/#aspose.cells.pivot.pivottable-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom elementintervallet i arraylistan som börjar vid det angivna indexet och innehåller det angivna antalet element.|
| [`last_index_of(self, item)`](/cells/python-net/sv/aspose.cells.pivot/pivottablecollection/last_index_of/#aspose.cells.pivot.pivottable) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom hela arraylistan.|
| [`last_index_of(self, item, index)`](/cells/python-net/sv/aspose.cells.pivot/pivottablecollection/last_index_of/#aspose.cells.pivot.pivottable-int) |Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom intervallet av element i arraylistan som sträcker sig från det första elementet till det angivna indexet.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/sv/aspose.cells.pivot/pivottablecollection/last_index_of/#aspose.cells.pivot.pivottable-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom elementintervallet i arraylistan som innehåller det angivna antalet element och slutar vid det angivna indexet.|
| [`get(self, name)`](/cells/python-net/sv/aspose.cells.pivot/pivottablecollection/get/#str) | Hämtar pivottabellrapporten efter pivottabellens namn.|
| [`remove_pivot_table(self, pivot_table)`](/cells/python-net/sv/aspose.cells.pivot/pivottablecollection/remove_pivot_table/#aspose.cells.pivot.pivottable) | Tar bort den angivna pivottabellen och tar bort pivottabelldata|
| [`remove_pivot_table_data(self, pivot_table, keep_data)`](/cells/python-net/sv/aspose.cells.pivot/pivottablecollection/remove_pivot_table_data/#aspose.cells.pivot.pivottable-bool) | Tar bort den angivna pivottabellen|
| [`remove_by_index(self, index)`](/cells/python-net/sv/aspose.cells.pivot/pivottablecollection/remove_by_index/#int) | Tar bort pivottabellen vid det angivna indexet och tar bort pivottabelldata|
| [`remove_at(self, index, keep_data)`](/cells/python-net/sv/aspose.cells.pivot/pivottablecollection/remove_at/#int-bool) | Tar bort pivottabellen vid det angivna indexet|
| [`binary_search(self, item)`](/cells/python-net/sv/aspose.cells.pivot/pivottablecollection/binary_search/#aspose.cells.pivot.pivottable) | Söker igenom hela den sorterade arraylistan efter ett element med hjälp av standardjämföraren och returnerar elementets nollbaserade index.|



###  Exempel

```python
from aspose.cells import FormatConditionType, OperatorType, Workbook
from aspose.cells.pivot import PivotFieldType, PivotFilterType, PivotTableStyleType
from aspose.pydrawing import Color

book = Workbook()
sheet = book.worksheets[0]
cells = sheet.cells
cells.get(0, 0).value = "fruit"
cells.get(1, 0).value = "grape"
cells.get(2, 0).value = "blueberry"
cells.get(3, 0).value = "kiwi"
cells.get(4, 0).value = "cherry"
cells.get(5, 0).value = "grape"
cells.get(6, 0).value = "blueberry"
cells.get(7, 0).value = "kiwi"
cells.get(8, 0).value = "cherry"
cells.get(0, 1).value = "year"
cells.get(1, 1).value = 2020
cells.get(2, 1).value = 2020
cells.get(3, 1).value = 2020
cells.get(4, 1).value = 2020
cells.get(5, 1).value = 2021
cells.get(6, 1).value = 2021
cells.get(7, 1).value = 2021
cells.get(8, 1).value = 2021
cells.get(0, 2).value = "amount"
cells.get(1, 2).value = 50
cells.get(2, 2).value = 60
cells.get(3, 2).value = 70
cells.get(4, 2).value = 80
cells.get(5, 2).value = 90
cells.get(6, 2).value = 100
cells.get(7, 2).value = 110
cells.get(8, 2).value = 120
pivots = sheet.pivot_tables
pivotIndex = pivots.add("=Sheet1!A1:C9", "A12", "TestPivotTable")
pivot = pivots[pivotIndex]
pivot.add_field_to_area(PivotFieldType.ROW, "fruit")
pivot.add_field_to_area(PivotFieldType.COLUMN, "year")
pivot.add_field_to_area(PivotFieldType.DATA, "amount")
pivot.pivot_table_style_type = PivotTableStyleType.PIVOT_TABLE_STYLE_MEDIUM10
# Change PivotField's attributes
rowField = pivot.row_fields[0]
rowField.display_name = "custom display name"
# Add PivotFilter
index = pivot.pivot_filters.add(0, PivotFilterType.COUNT)
filter = pivot.pivot_filters[index]
filter.auto_filter.filter_top10(0, False, False, 2)
# Add PivotFormatCondition
formatIndex = pivot.pivot_format_conditions.add()
pfc = pivot.pivot_format_conditions[formatIndex]
fcc = pfc.format_conditions
fcc.add_area(pivot.data_body_range)
idx = fcc.add_condition(FormatConditionType.CELL_VALUE)
fc = fcc[idx]
fc.formula1 = "100"
fc.operator = OperatorType.GREATER_OR_EQUAL
fc.style.background_color = Color.red
pivot.refresh_data()
pivot.calculate_data()
# do your business
book.save("out.xlsx")

```

###  Se även
* modul [`aspose.cells.pivot`](..)
