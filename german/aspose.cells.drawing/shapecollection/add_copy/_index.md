---
title: add_copy Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 90
url: /de/aspose.cells.drawing/shapecollection/add_copy/
is_root: false
---
##  add_copy(self, source_shape, top_row, top, left_column, left) {#aspose.cells.drawing.Shape-int-int-int-int}
Fügt dem Arbeitsblatt eine Form hinzu und kopiert sie.


###  Kehrt zurück

Das neue Objekt [`Shape`](/cells/python-net/de/aspose.cells.drawing/shape).


```python

def add_copy(self, source_shape, top_row, top, left_column, left):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| source_shape | [`Shape`](/cells/python-net/de/aspose.cells.drawing/shape) | Quellform.|
| top_row | int |Der Index der obersten Zeile.|
| top | int | Stellt den vertikalen Versatz von der obersten Zeile in Pixeleinheiten dar.|
| left_column | int | Der Index der linken Spalte.|
| left | int | Stellt den horizontalen Versatz von der linken Spalte in Pixeleinheiten dar.|

###  Beispiel

```python

# add a shape
rectangle = shapes.add_rectangle(2, 0, 2, 0, 130, 130)
# Adds and copies a shape.
shapes.add_copy(rectangle, 7, 0, 7, 0)

```



###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`Shape`](/cells/python-net/de/aspose.cells.drawing/shape)
* Klasse [`ShapeCollection`](/cells/python-net/de/aspose.cells.drawing/shapecollection)
