---
title: PivotConditionalFormat sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 60
url: /tr/aspose.cells.pivot/pivotconditionalformat/
is_root: false
---
##  PivotConditionalFormat sınıfı
PivotFormatCondition Koleksiyonundaki bir PivotTable Biçim Koşulunu temsil eder.



PivotConditionalFormat türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [pivot_areas](/cells/python-net/tr/aspose.cells.pivot/pivotconditionalformat/pivot_areas) | Tüm pivot alanlarını alır.|
| [format_conditions](/cells/python-net/tr/aspose.cells.pivot/pivotconditionalformat/format_conditions) | Pivot tablo koşullu biçimlendirmesi için koşulları alın.|
| [scope_type](/cells/python-net/tr/aspose.cells.pivot/pivotconditionalformat/scope_type) | Pivot tablo koşullu biçimi için kapsam türünü alın ve ayarlayın.|
| [rule_type](/cells/python-net/tr/aspose.cells.pivot/pivotconditionalformat/rule_type) | Pivot tablo koşul biçimi için kural türünü alın ve ayarlayın.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`add_field_area(self, axis_type, field_name)`](/cells/python-net/tr/aspose.cells.pivot/pivotconditionalformat/add_field_area/#aspose.cells.pivot.pivotfieldtype-str) | Pivot alanına bir alan ekler.|
| [`add_field_area(self, axis_type, field)`](/cells/python-net/tr/aspose.cells.pivot/pivotconditionalformat/add_field_area/#aspose.cells.pivot.pivotfieldtype-aspose.cells.pivot.pivotfield) | Pivot alanına bir alan ekler.|
| [`get_cell_areas(self)`](/cells/python-net/tr/aspose.cells.pivot/pivotconditionalformat/get_cell_areas/#) |Bu koşullu biçimlendirmenin uygulandığı tüm hücre alanlarını alır.|
| [`add_cell_area(self, ca)`](/cells/python-net/tr/aspose.cells.pivot/pivotconditionalformat/add_cell_area/#aspose.cells.cellarea) | Pivot tablo görünümüne dayalı bir alan ekler.|
| [`apply_to(self, row, column, scope)`](/cells/python-net/tr/aspose.cells.pivot/pivotconditionalformat/apply_to/#int-int-aspose.cells.pivot.pivotconditionformatscopetype) | Aralığa koşullu biçimlendirmeyi uygular.<br/> Sadece veri bölgesi için.|



###  Örnek

```python
from aspose.cells import FormatConditionType, OperatorType, Workbook
from aspose.cells.pivot import PivotFieldType, PivotTableStyleType
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
# Add PivotFormatCondition
formatIndex = pivot.conditional_formats.add()
pfc = pivot.conditional_formats[formatIndex]
pfc.add_field_area(PivotFieldType.DATA, pivot.data_fields[0])
idx = pfc.format_conditions.add_condition(FormatConditionType.CELL_VALUE)
fc = pfc.format_conditions[idx]
fc.formula1 = "100"
fc.operator = OperatorType.GREATER_OR_EQUAL
fc.style.background_color = Color.red
pivot.refresh_data()
pivot.calculate_data()
# do your business
book.save("out.xlsx")

```

###  Ayrıca bakınız
* modül [`aspose.cells.pivot`](..)
