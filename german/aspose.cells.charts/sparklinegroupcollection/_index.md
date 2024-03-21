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
Kapselt eine Sammlung von [`SparklineGroup`](/cells/python-net/de/aspose.cells.charts/sparklinegroup)-Objekten.



Der Typ SparklineGroupCollection macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [capacity](/cells/python-net/de/aspose.cells.charts/sparklinegroupcollection/capacity) | Ruft die Anzahl der Elemente ab, die die Array-Liste enthalten kann, oder legt diese fest.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [copy_to](/cells/python-net/de/aspose.cells.charts/sparklinegroupcollection/copy_to/#list) | Kopiert die gesamte Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am Anfang der Ziel-Array-Liste.|
| [copy_to](/cells/python-net/de/aspose.cells.charts/sparklinegroupcollection/copy_to/#int-list-int-int) | Kopiert einen Bereich von Elementen aus der Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am angegebenen Index der Ziel-Array-Liste.|
| [index_of](/cells/python-net/de/aspose.cells.charts/sparklinegroupcollection/index_of/#aspose.cells.charts.SparklineGroup-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der vom angegebenen Index bis zum letzten Element reicht.|
| [index_of](/cells/python-net/de/aspose.cells.charts/sparklinegroupcollection/index_of/#aspose.cells.charts.SparklineGroup-int-int) |Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der beim angegebenen Index beginnt und die angegebene Anzahl von Elementen enthält.|
| [last_index_of](/cells/python-net/de/aspose.cells.charts/sparklinegroupcollection/last_index_of/#aspose.cells.charts.SparklineGroup) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens in der gesamten Array-Liste zurück.|
| [last_index_of](/cells/python-net/de/aspose.cells.charts/sparklinegroupcollection/last_index_of/#aspose.cells.charts.SparklineGroup-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der vom ersten Element bis zum angegebenen Index reicht.|
| [last_index_of](/cells/python-net/de/aspose.cells.charts/sparklinegroupcollection/last_index_of/#aspose.cells.charts.SparklineGroup-int-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der die angegebene Anzahl von Elementen enthält und beim angegebenen Index endet.|
| [add](/cells/python-net/de/aspose.cells.charts/sparklinegroupcollection/add/#aspose.cells.charts.SparklineType-str-bool-aspose.cells.CellArea) | Fügt der Sammlung ein [`SparklineGroup`](/cells/python-net/de/aspose.cells.charts/sparklinegroup)-Element hinzu.|
| [clear_sparklines](/cells/python-net/de/aspose.cells.charts/sparklinegroupcollection/clear_sparklines/#aspose.cells.CellArea) | Löscht die Sparklines, die sich innerhalb eines Zellbereichs befinden.|
| [clear_sparkline_groups](/cells/python-net/de/aspose.cells.charts/sparklinegroupcollection/clear_sparkline_groups/#aspose.cells.CellArea) | Löscht die Sparkline-Gruppen, die einen Zellbereich überlappen.|
| [binary_search](/cells/python-net/de/aspose.cells.charts/sparklinegroupcollection/binary_search/#aspose.cells.charts.SparklineGroup) | Durchsucht die gesamte sortierte Array-Liste mithilfe des Standardvergleichs nach einem Element und gibt den nullbasierten Index des Elements zurück.|



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
idx = sheet.sparkline_group_collection.add(SparklineType.LINE, "A1:D1", False, ca)
group = sheet.sparkline_group_collection[idx]
group.sparkline_collection.add(sheet.name + "!A1:D1", 0, 4)
book.save("output.xlsx", SaveFormat.XLSX)

```

###  Siehe auch
* Modul [`aspose.cells.charts`](..)
* Klasse [`SparklineGroup`](/cells/python-net/de/aspose.cells.charts/sparklinegroup)
