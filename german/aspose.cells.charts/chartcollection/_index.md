---
title: ChartCollection Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 60
url: /de/aspose.cells.charts/chartcollection/
is_root: false
---
##  ChartCollection Klasse
Kapselt eine Sammlung von [`Chart`](/cells/python-net/de/aspose.cells.charts/chart) Objekten.



Der Typ ChartCollection macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [capacity](/cells/python-net/de/aspose.cells.charts/chartcollection/capacity) | Ruft die Anzahl der Elemente ab, die die Array-Liste enthalten kann, oder legt diese fest.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`add(self, type, upper_left_row, upper_left_column, lower_right_row, lower_right_column)`](/cells/python-net/de/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.charttype-int-int-int-int) | Fügt der Sammlung ein Diagramm hinzu.|
| [`add(self, type, data_range, top_row, left_column, right_row, bottom_column)`](/cells/python-net/de/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.charttype-str-int-int-int-int) | Fügt der Sammlung ein Diagramm hinzu.|
| [`add(self, data, data_range, is_vertical, top_row, left_column, right_row, bottom_column)`](/cells/python-net/de/aspose.cells.charts/chartcollection/add/#bytes-str-bool-int-int-int-int) | Fügt ein Diagramm mit voreingestellter Vorlage hinzu.|
| [`add(self, type, data_range, is_vertical, top_row, left_column, right_row, bottom_column)`](/cells/python-net/de/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.charttype-str-bool-int-int-int-int) | Fügt der Sammlung ein Diagramm hinzu.|
| [`get(self, index)`](/cells/python-net/de/aspose.cells.charts/chartcollection/get/#int) | Add API for Python Via .Net.since this[int index] wird nicht unterstützt|
| [`get(self, name)`](/cells/python-net/de/aspose.cells.charts/chartcollection/get/#str) | Hinzufügen API for Python Via .Net.since this[string Chart] is unsupported|
| [`copy_to(self, array)`](/cells/python-net/de/aspose.cells.charts/chartcollection/copy_to/#list) |Kopiert die gesamte Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am Anfang der Ziel-Array-Liste.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/de/aspose.cells.charts/chartcollection/copy_to/#int-list-int-int) | Kopiert einen Bereich von Elementen aus der Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am angegebenen Index der Ziel-Array-Liste.|
| [`index_of(self, item, index)`](/cells/python-net/de/aspose.cells.charts/chartcollection/index_of/#aspose.cells.charts.chart-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der sich vom angegebenen Index bis zum letzten Element erstreckt.|
| [`index_of(self, item, index, count)`](/cells/python-net/de/aspose.cells.charts/chartcollection/index_of/#aspose.cells.charts.chart-int-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der am angegebenen Index beginnt und die angegebene Anzahl von Elementen enthält.|
| [`last_index_of(self, item)`](/cells/python-net/de/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.chart) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb der gesamten Arrayliste zurück.|
| [`last_index_of(self, item, index)`](/cells/python-net/de/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.chart-int) |Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der sich vom ersten Element bis zum angegebenen Index erstreckt.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/de/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.chart-int-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der die angegebene Anzahl von Elementen enthält und am angegebenen Index endet.|
| [`add_floating_chart(self, type, left, top, width, height)`](/cells/python-net/de/aspose.cells.charts/chartcollection/add_floating_chart/#aspose.cells.charts.charttype-int-int-int-int) | Fügt der Sammlung ein Diagramm hinzu.|
| [`binary_search(self, item)`](/cells/python-net/de/aspose.cells.charts/chartcollection/binary_search/#aspose.cells.charts.chart) | Durchsucht die gesamte sortierte Array-Liste mithilfe des Standardvergleichers nach einem Element und gibt den nullbasierten Index des Elements zurück.|



###  Beispiel

```python
from aspose.cells import Workbook

workbook = Workbook()
charts = workbook.worksheets[0].charts

```

###  Siehe auch
* Modul [`aspose.cells.charts`](..)
* Klasse [`Chart`](/cells/python-net/de/aspose.cells.charts/chart)
