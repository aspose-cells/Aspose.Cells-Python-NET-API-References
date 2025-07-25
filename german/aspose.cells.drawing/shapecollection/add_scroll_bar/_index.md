---
title: add_scroll_bar Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 270
url: /de/aspose.cells.drawing/shapecollection/add_scroll_bar/
is_root: false
---
##  add_scroll_bar(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Fügt dem Arbeitsblatt eine Bildlaufleiste hinzu.


###  Kehrt zurück

Ein ScrollBar-Objekt.


```python

def add_scroll_bar(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| upper_left_row | int | Zeilenindex oben links.|
| top | int |Stellt den vertikalen Versatz der Bildlaufleiste von ihrer linken Zeile in Pixeleinheiten dar.|
| upper_left_column | int | Index der oberen linken Spalte.|
| left | int | Stellt den horizontalen Versatz der Bildlaufleiste von ihrer linken Spalte in Pixeleinheiten dar.|
| height | int | Stellt die Höhe der Bildlaufleiste in Pixeln dar.|
| width | int | Stellt die Breite der Bildlaufleiste in Pixeln dar.|

###  Beispiel

```python

# add a scroll bar
scrollBar = shapes.add_scroll_bar(1, 0, 1, 0, 100, 20)

```



###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`ShapeCollection`](/cells/python-net/de/aspose.cells.drawing/shapecollection)
