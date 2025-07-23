---
title: PictureCollection Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 440
url: /de/aspose.cells.drawing/picturecollection/
is_root: false
---
##  PictureCollection Klasse
Kapselt eine Sammlung von [`Picture`](/cells/python-net/de/aspose.cells.drawing/picture) Objekten.



Der Typ PictureCollection macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [capacity](/cells/python-net/de/aspose.cells.drawing/picturecollection/capacity) | Ruft die Anzahl der Elemente ab, die die Array-Liste enthalten kann, oder legt diese fest.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream)`](/cells/python-net/de/aspose.cells.drawing/picturecollection/add/#int-int-int-int-io.rawiobase) | Fügt der Sammlung ein Bild hinzu.|
| [`add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, file_name)`](/cells/python-net/de/aspose.cells.drawing/picturecollection/add/#int-int-int-int-str) | Fügt der Sammlung ein Bild hinzu.|
| [`add(self, upper_left_row, upper_left_column, stream)`](/cells/python-net/de/aspose.cells.drawing/picturecollection/add/#int-int-io.rawiobase) | Fügt der Sammlung ein Bild hinzu.|
| [`add(self, upper_left_row, upper_left_column, file_name)`](/cells/python-net/de/aspose.cells.drawing/picturecollection/add/#int-int-str) | Fügt der Sammlung ein Bild hinzu.|
| [`add(self, upper_left_row, upper_left_column, stream, width_scale, height_scale)`](/cells/python-net/de/aspose.cells.drawing/picturecollection/add/#int-int-io.rawiobase-int-int) | Fügt der Sammlung ein Bild hinzu.|
| [`add(self, upper_left_row, upper_left_column, file_name, width_scale, height_scale)`](/cells/python-net/de/aspose.cells.drawing/picturecollection/add/#int-int-str-int-int) | Fügt der Sammlung ein Bild hinzu.|
| [`copy_to(self, array)`](/cells/python-net/de/aspose.cells.drawing/picturecollection/copy_to/#list) |Kopiert die gesamte Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am Anfang der Ziel-Array-Liste.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/de/aspose.cells.drawing/picturecollection/copy_to/#int-list-int-int) | Kopiert einen Bereich von Elementen aus der Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am angegebenen Index der Ziel-Array-Liste.|
| [`index_of(self, item, index)`](/cells/python-net/de/aspose.cells.drawing/picturecollection/index_of/#aspose.cells.drawing.picture-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der sich vom angegebenen Index bis zum letzten Element erstreckt.|
| [`index_of(self, item, index, count)`](/cells/python-net/de/aspose.cells.drawing/picturecollection/index_of/#aspose.cells.drawing.picture-int-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der am angegebenen Index beginnt und die angegebene Anzahl von Elementen enthält.|
| [`last_index_of(self, item)`](/cells/python-net/de/aspose.cells.drawing/picturecollection/last_index_of/#aspose.cells.drawing.picture) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb der gesamten Arrayliste zurück.|
| [`last_index_of(self, item, index)`](/cells/python-net/de/aspose.cells.drawing/picturecollection/last_index_of/#aspose.cells.drawing.picture-int) |Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der sich vom ersten Element bis zum angegebenen Index erstreckt.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/de/aspose.cells.drawing/picturecollection/last_index_of/#aspose.cells.drawing.picture-int-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der die angegebene Anzahl von Elementen enthält und am angegebenen Index endet.|
| [`camera(self, row, column, range)`](/cells/python-net/de/aspose.cells.drawing/picturecollection/camera/#int-int-str) | Macht ein Foto von der Reichweite.|
| [`binary_search(self, item)`](/cells/python-net/de/aspose.cells.drawing/picturecollection/binary_search/#aspose.cells.drawing.picture) | Durchsucht die gesamte sortierte Array-Liste mithilfe des Standardvergleichers nach einem Element und gibt den nullbasierten Index des Elements zurück.|



###  Beispiel

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# get PictureCollection
pictures = workbook.worksheets[0].pictures
# do your business
# Save the excel file.
workbook.save("result.xlsx")

```

###  Siehe auch
* Modul [`aspose.cells.drawing`](..)
* Klasse [`Picture`](/cells/python-net/de/aspose.cells.drawing/picture)
