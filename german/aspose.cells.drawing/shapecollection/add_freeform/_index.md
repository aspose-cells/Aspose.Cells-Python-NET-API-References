---
title: add_freeform Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 120
url: /de/aspose.cells.drawing/shapecollection/add_freeform/
is_root: false
---
##  add_freeform(self, upper_left_row, top, upper_left_column, left, height, width, paths) {#int-int-int-int-int-int-list}
Fügt dem Arbeitsblatt eine Freihandform hinzu.


###  Kehrt zurück

Eine Freiform.


```python

def add_freeform(self, upper_left_row, top, upper_left_column, left, height, width, paths):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| upper_left_row | int | Zeilenindex oben links.|
| top | int | Stellt den vertikalen Versatz der Freiform von ihrer linken Reihe in Pixeleinheiten dar.|
| upper_left_column | int | Index der oberen linken Spalte.|
| left | int | Stellt den horizontalen Versatz der Freiform von ihrer linken Spalte in Pixeleinheiten dar.|
| height | int | Stellt die Höhe der Freiform in Pixeleinheiten dar.|
| width | int | Stellt die Breite der Freiform in Pixeleinheiten dar.|
| paths | list | Stellt einen benutzerdefinierten Pfad dar|
###  Bemerkungen

Hinweis: Breite und Höhe in den Parametern können beliebige positive Ganzzahlen sein und dürfen nicht der Gesamtbreite und -höhe des durch „paths“ angegebenen ShapePath-Arrays entsprechen. Die Beziehung zwischen ihnen ist eine Skalierungs-Füll-Beziehung, d. h. jedes ShapePath-Objekt wird entsprechend seiner Breite und Höhe skaliert. Wenn sich in den „paths“ mehrere Objekte befinden, muss daher jedes ShapePath-Objekt angemessen gestaltet werden, um den Erwartungen zu entsprechen. Wenn nur ein ShapePath-Objekt vorhanden ist und keine weiteren Anforderungen bestehen, ist die Übergabe der Breite und Höhe des Objekts als Parameterwerte eine gute Lösung.
###  Beispiel


```python
from aspose.cells.drawing import ShapePath

# Custom figure
shapePath = ShapePath()
shapePath.move_to(60, 45)
shapePath.arc_to(25, 25, 0, 270)
shapePath.close()
shapePath.move_to(60, 20)
shapePath.line_to(110, 70)
shapePath.line_to(125, 155.5)
shapePath.arc_to(35.5, 35.5, 0, 270)
shapePath.close()
shapePath.move_to(150, 45)
shapePath.arc_to(25, 25, 0, 270)
shapePathW = shapePath.width_pixel
shapePathH = shapePath.height_pixel
shapePath1 = ShapePath()
shapePath1.move_to(0, 0)
shapePath1.cubic_bezier_to(48.24997, 0.6844,                                 96.5, -7.148871,                                 130, 11.517795)
shapePath1.cubic_bezier_to(163.5, 30.18446,                                 182.24997, 75.351,                                 201, 120.517795)
shapePath1.move_to(150, 80)
shapePath1.arc_to(25, 25, 0, 270)
if shapePath1.width_pixel > shapePathW:
    shapePathW = shapePath1.width_pixel
if shapePath1.height_pixel > shapePathH:
    shapePathH = shapePath1.height_pixel
# Notice: shapePathH and shapePathH can be any positive integer values, here we just simply set them.
# Insert custom figure into worksheet
shapes.add_freeform(1, 0, 1, 0, shapePathH, shapePathW, [shapePath, shapePath1])

```



###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`ShapeCollection`](/cells/python-net/de/aspose.cells.drawing/shapecollection)
