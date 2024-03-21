---
title: PivotTableCollection Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 190
url: /de/aspose.cells.pivot/pivottablecollection/
is_root: false
---
##  PivotTableCollection Klasse
Stellt die Sammlung aller PivotTable-Objekte im angegebenen Arbeitsblatt dar.



Der Typ PivotTableCollection macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [capacity](/cells/python-net/de/aspose.cells.pivot/pivottablecollection/capacity) | Ruft die Anzahl der Elemente ab, die die Array-Liste enthalten kann, oder legt diese fest.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [add](/cells/python-net/de/aspose.cells.pivot/pivottablecollection/add/#str-str-str) | Fügt einer PivotCaches-Sammlung einen neuen PivotTable-Cache hinzu.|
| [add](/cells/python-net/de/aspose.cells.pivot/pivottablecollection/add/#str-str-str-bool) | Fügt einer PivotCaches-Sammlung einen neuen PivotTable-Cache hinzu.|
| [add](/cells/python-net/de/aspose.cells.pivot/pivottablecollection/add/#str-int-int-str) | Fügt einer PivotCaches-Sammlung einen neuen PivotTable-Cache hinzu.|
| [add](/cells/python-net/de/aspose.cells.pivot/pivottablecollection/add/#str-int-int-str-bool) | Fügt einer PivotCaches-Sammlung einen neuen PivotTable-Cache hinzu.|
| [add](/cells/python-net/de/aspose.cells.pivot/pivottablecollection/add/#aspose.cells.pivot.PivotTable-str-str) | Fügt der Sammlung ein neues PivotTable-Objekt aus einer anderen PivotTable hinzu.|
| [add](/cells/python-net/de/aspose.cells.pivot/pivottablecollection/add/#aspose.cells.pivot.PivotTable-int-int-str) | Fügt der Sammlung ein neues PivotTable-Objekt aus einer anderen PivotTable hinzu.|
| [add](/cells/python-net/de/aspose.cells.pivot/pivottablecollection/add/#list-bool-aspose.cells.pivot.PivotPageFields-str-str) |Fügt der Sammlung ein neues PivotTable-Objekt mit mehreren Konsolidierungsbereichen als Datenquelle hinzu.|
| [add](/cells/python-net/de/aspose.cells.pivot/pivottablecollection/add/#list-bool-aspose.cells.pivot.PivotPageFields-int-int-str) |Fügt der Sammlung ein neues PivotTable-Objekt mit mehreren Konsolidierungsbereichen als Datenquelle hinzu.|
| [copy_to](/cells/python-net/de/aspose.cells.pivot/pivottablecollection/copy_to/#list) | Kopiert die gesamte Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am Anfang der Ziel-Array-Liste.|
| [copy_to](/cells/python-net/de/aspose.cells.pivot/pivottablecollection/copy_to/#int-list-int-int) | Kopiert einen Bereich von Elementen aus der Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am angegebenen Index der Ziel-Array-Liste.|
| [index_of](/cells/python-net/de/aspose.cells.pivot/pivottablecollection/index_of/#aspose.cells.pivot.PivotTable-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der vom angegebenen Index bis zum letzten Element reicht.|
| [index_of](/cells/python-net/de/aspose.cells.pivot/pivottablecollection/index_of/#aspose.cells.pivot.PivotTable-int-int) |Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der beim angegebenen Index beginnt und die angegebene Anzahl von Elementen enthält.|
| [last_index_of](/cells/python-net/de/aspose.cells.pivot/pivottablecollection/last_index_of/#aspose.cells.pivot.PivotTable) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens in der gesamten Array-Liste zurück.|
| [last_index_of](/cells/python-net/de/aspose.cells.pivot/pivottablecollection/last_index_of/#aspose.cells.pivot.PivotTable-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der vom ersten Element bis zum angegebenen Index reicht.|
| [last_index_of](/cells/python-net/de/aspose.cells.pivot/pivottablecollection/last_index_of/#aspose.cells.pivot.PivotTable-int-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der die angegebene Anzahl von Elementen enthält und beim angegebenen Index endet.|
| [remove_at](/cells/python-net/de/aspose.cells.pivot/pivottablecollection/remove_at/#int-bool) | Löscht die PivotTable am angegebenen Index|
| [binary_search](/cells/python-net/de/aspose.cells.pivot/pivottablecollection/binary_search/#aspose.cells.pivot.PivotTable) | Durchsucht die gesamte sortierte Array-Liste mithilfe des Standardvergleichs nach einem Element und gibt den nullbasierten Index des Elements zurück.|



###  Beispiel

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

###  Siehe auch
* Modul [`aspose.cells.pivot`](..)
