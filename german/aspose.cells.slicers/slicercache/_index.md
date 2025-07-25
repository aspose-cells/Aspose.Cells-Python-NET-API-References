---
title: SlicerCache Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 20
url: /de/aspose.cells.slicers/slicercache/
is_root: false
---
##  SlicerCache Klasse
Stellen Sie eine zusammenfassende Beschreibung des Slicer-Cache dar



Der Typ SlicerCache macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [cross_filter_type](/cells/python-net/de/aspose.cells.slicers/slicercache/cross_filter_type) | Gibt zurück oder legt fest, ob ein Slicer an der Kreuzfilterung mit anderen Slicern teilnimmt.<br/> die denselben Slicer-Cache verwenden, und wie die Kreuzfilterung angezeigt wird. Lesen/Schreiben|
| [list](/cells/python-net/de/aspose.cells.slicers/slicercache/list) | Gibt zurück, ob der mit dem angegebenen Slicer-Cache verknüpfte Slicer auf einer Nicht-OLAP-Datenquelle basiert. Schreibgeschützt|
| [slicer_cache_items](/cells/python-net/de/aspose.cells.slicers/slicercache/slicer_cache_items) | Gibt eine SlicerCacheItem-Sammlung zurück, die die Sammlung aller Elemente im Slicer-Cache enthält. Schreibgeschützt|
| [name](/cells/python-net/de/aspose.cells.slicers/slicercache/name) | Gibt den Namen des Slicer-Cache zurück.|
| [source_name](/cells/python-net/de/aspose.cells.slicers/slicercache/source_name) | Gibt den Namen dieses Slicer-Cache zurück.|



###  Beispiel

```python
from aspose.cells import Workbook
from aspose.cells.pivot import PivotFieldType, PivotTableStyleType
from aspose.cells.slicers import SlicerStyleType

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
pivot.refresh_data()
pivot.calculate_data()
slicers = sheet.slicers
slicerIndex = slicers.add(pivot, "E12", "fruit")
slicer = slicers[slicerIndex]
slicer.style_type = SlicerStyleType.SLICER_STYLE_LIGHT2
# Get SlicerCache object of current slicer
slicerCache = slicer.slicer_cache
# do your business
book.save("out.xlsx")

```

###  Siehe auch
* Modul [`aspose.cells.slicers`](..)
