---
title: SparklineGroupCollection Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 300
url: /de/aspose.cells.charts/sparklinegroupcollection/
is_root: false
---
##  SparklineGroupCollection Klasse
Kapselt eine Sammlung von [`SparklineGroup`](/cells/python-net/de/aspose.cells.charts/sparklinegroup) Objekten.



Der Typ SparklineGroupCollection macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [capacity](/cells/python-net/de/aspose.cells.charts/sparklinegroupcollection/capacity) | Ruft die Anzahl der Elemente ab, die die Array-Liste enthalten kann, oder legt diese fest.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`add(self, type)`](/cells/python-net/de/aspose.cells.charts/sparklinegroupcollection/add/#aspose.cells.charts.sparklinetype) | Fügt der Sammlung eine [`SparklineGroup`](/cells/python-net/de/aspose.cells.charts/sparklinegroup) mit einer [`Sparkline`](/cells/python-net/de/aspose.cells.charts/sparkline) hinzu.|
| [`add(self, type, data_range, is_vertical, location_range)`](/cells/python-net/de/aspose.cells.charts/sparklinegroupcollection/add/#aspose.cells.charts.sparklinetype-str-bool-aspose.cells.cellarea) | Fügt der Sammlung eine [`SparklineGroup`](/cells/python-net/de/aspose.cells.charts/sparklinegroup) mit [`Sparkline`](/cells/python-net/de/aspose.cells.charts/sparkline) hinzu.|
| [`copy_to(self, array)`](/cells/python-net/de/aspose.cells.charts/sparklinegroupcollection/copy_to/#list) |Kopiert die gesamte Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am Anfang der Ziel-Array-Liste.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/de/aspose.cells.charts/sparklinegroupcollection/copy_to/#int-list-int-int) | Kopiert einen Bereich von Elementen aus der Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am angegebenen Index der Ziel-Array-Liste.|
| [`index_of(self, item, index)`](/cells/python-net/de/aspose.cells.charts/sparklinegroupcollection/index_of/#aspose.cells.charts.sparklinegroup-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der sich vom angegebenen Index bis zum letzten Element erstreckt.|
| [`index_of(self, item, index, count)`](/cells/python-net/de/aspose.cells.charts/sparklinegroupcollection/index_of/#aspose.cells.charts.sparklinegroup-int-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der am angegebenen Index beginnt und die angegebene Anzahl von Elementen enthält.|
| [`last_index_of(self, item)`](/cells/python-net/de/aspose.cells.charts/sparklinegroupcollection/last_index_of/#aspose.cells.charts.sparklinegroup) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb der gesamten Arrayliste zurück.|
| [`last_index_of(self, item, index)`](/cells/python-net/de/aspose.cells.charts/sparklinegroupcollection/last_index_of/#aspose.cells.charts.sparklinegroup-int) |Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der sich vom ersten Element bis zum angegebenen Index erstreckt.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/de/aspose.cells.charts/sparklinegroupcollection/last_index_of/#aspose.cells.charts.sparklinegroup-int-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der die angegebene Anzahl von Elementen enthält und am angegebenen Index endet.|
| [`clear_sparklines(self, cell_area)`](/cells/python-net/de/aspose.cells.charts/sparklinegroupcollection/clear_sparklines/#aspose.cells.cellarea) | Löscht die Sparklines, die sich innerhalb eines Zellenbereichs befinden.|
| [`clear_sparkline_groups(self, cell_area)`](/cells/python-net/de/aspose.cells.charts/sparklinegroupcollection/clear_sparkline_groups/#aspose.cells.cellarea) | Löscht die Sparkline-Gruppen, die einen Zellenbereich überlappen.|
| [`binary_search(self, item)`](/cells/python-net/de/aspose.cells.charts/sparklinegroupcollection/binary_search/#aspose.cells.charts.sparklinegroup) | Durchsucht die gesamte sortierte Array-Liste mithilfe des Standardvergleichers nach einem Element und gibt den nullbasierten Index des Elements zurück.|



###  Beispiel

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

###  Siehe auch
* Modul [`aspose.cells.charts`](..)
* Klasse [`Sparkline`](/cells/python-net/de/aspose.cells.charts/sparkline)
* Klasse [`SparklineGroup`](/cells/python-net/de/aspose.cells.charts/sparklinegroup)
