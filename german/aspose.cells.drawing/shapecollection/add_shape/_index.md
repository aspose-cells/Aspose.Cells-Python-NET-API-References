---
title: add_shape Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 280
url: /de/aspose.cells.drawing/shapecollection/add_shape/
is_root: false
---
##  add_shape(self, type, upper_left_row, top, upper_left_column, left, height, width) {#aspose.cells.drawing.MsoDrawingType-int-int-int-int-int-int}
Fügt dem Arbeitsblatt eine Form hinzu.


###  Kehrt zurück

Ein Shape-Objekt.


```python

def add_shape(self, type, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| type | [`MsoDrawingType`](/cells/python-net/de/aspose.cells.drawing/msodrawingtype) | MSO-Zeichnungstyp.|
| upper_left_row | int | Zeilenindex oben links.|
| top | int | Stellt den vertikalen Versatz der Form von ihrer linken Zeile in Pixeleinheiten dar.|
| upper_left_column | int | Index der oberen linken Spalte.|
| left | int | Stellt den horizontalen Versatz der Form von ihrer linken Spalte in Pixeleinheiten dar.|
| height | int | Stellt die Höhe der Form in Pixeleinheiten dar.|
| width | int | Stellt die Breite der Form in Pixeleinheiten dar.|
###  Bemerkungen

Der Typ kann nicht Chart/Comment/Picture/OleObject/Polygon/DialogBox sein.
###  Beispiel


```python
from aspose.cells.drawing import MsoDrawingType

# Add a shape of the specified type
shapeByType = shapes.add_shape(MsoDrawingType.CELLS_DRAWING, 1, 0, 1, 0, 100, 50)

```



###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`ShapeCollection`](/cells/python-net/de/aspose.cells.drawing/shapecollection)
