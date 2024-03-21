---
title: PivotFormatCondition Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 120
url: /de/aspose.cells.pivot/pivotformatcondition/
is_root: false
---
##  PivotFormatCondition Klasse
Stellt eine PivotTable-Formatbedingung in der PivotFormatCondition-Sammlung dar.



Der Typ PivotFormatCondition macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [scope_type](/cells/python-net/de/aspose.cells.pivot/pivotformatcondition/scope_type) | Holen Sie sich den Bereichstyp für das Bedingungsformat der Pivot-Tabelle und legen Sie ihn fest.|
| [rule_type](/cells/python-net/de/aspose.cells.pivot/pivotformatcondition/rule_type) | Rufen Sie den Regeltyp für das Bedingungsformat der Pivot-Tabelle ab und legen Sie ihn fest.|
| [format_conditions](/cells/python-net/de/aspose.cells.pivot/pivotformatcondition/format_conditions) | Rufen Sie Formatbedingungen für das Bedingungsformat der Pivot-Tabelle ab.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [add_data_area_condition](/cells/python-net/de/aspose.cells.pivot/pivotformatcondition/add_data_area_condition/#str) | Fügt eine bedingte PivotTable-Formatbeschränkung in den Datenfeldern hinzu.|
| [add_data_area_condition](/cells/python-net/de/aspose.cells.pivot/pivotformatcondition/add_data_area_condition/#aspose.cells.pivot.PivotField) | Fügt eine bedingte PivotTable-Formatbeschränkung in den Datenfeldern hinzu.|
| [add_row_area_condition](/cells/python-net/de/aspose.cells.pivot/pivotformatcondition/add_row_area_condition/#str) | Fügt eine Beschränkung für das bedingte PivotTable-Format in den Zeilenfeldern hinzu.|
| [add_row_area_condition](/cells/python-net/de/aspose.cells.pivot/pivotformatcondition/add_row_area_condition/#aspose.cells.pivot.PivotField) | Fügt eine Beschränkung für das bedingte PivotTable-Format in den Zeilenfeldern hinzu.|
| [add_column_area_condition](/cells/python-net/de/aspose.cells.pivot/pivotformatcondition/add_column_area_condition/#str) | Fügt eine Beschränkung für das bedingte PivotTable-Format in den Spaltenfeldern hinzu.|
| [add_column_area_condition](/cells/python-net/de/aspose.cells.pivot/pivotformatcondition/add_column_area_condition/#aspose.cells.pivot.PivotField) | Fügt eine Beschränkung für das bedingte PivotTable-Format in den Spaltenfeldern hinzu.|
| [set_conditional_areas](/cells/python-net/de/aspose.cells.pivot/pivotformatcondition/set_conditional_areas/#) | Legt bedingte Bereiche des PivotFormatCondition-Objekts fest.|



###  Beispiel

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

###  Siehe auch
* Modul [`aspose.cells.pivot`](..)
