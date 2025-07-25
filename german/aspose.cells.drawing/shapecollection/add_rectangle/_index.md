---
title: add_rectangle Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 260
url: /de/aspose.cells.drawing/shapecollection/add_rectangle/
is_root: false
---
##  add_rectangle(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Fügt dem Arbeitsblatt eine Rechteckform hinzu.


###  Kehrt zurück

Ein RectangleShape-Objekt.


```python

def add_rectangle(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| upper_left_row | int | Zeilenindex oben links.|
| top | int | Stellt den vertikalen Versatz der Rechteckform von ihrer linken Reihe in Pixeleinheiten dar.|
| upper_left_column | int | Index der oberen linken Spalte.|
| left | int | Stellt den horizontalen Versatz der Rechteckform von ihrer linken Spalte in Pixeleinheiten dar.|
| height | int | Stellt die Höhe der Rechteckform in Pixeln dar.|
| width | int | Stellt die Breite der Rechteckform in Pixeln dar.|

###  Beispiel

```python

#  add a rectangle
rectangleShape = shapes.add_rectangle(2, 0, 2, 0, 130, 130)

```



###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`ShapeCollection`](/cells/python-net/de/aspose.cells.drawing/shapecollection)
