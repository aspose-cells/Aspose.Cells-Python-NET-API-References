---
title: add_shape metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 280
url: /sv/aspose.cells.drawing/shapecollection/add_shape/
is_root: false
---
##  add_shape(self, type, upper_left_row, top, upper_left_column, left, height, width) {#aspose.cells.drawing.MsoDrawingType-int-int-int-int-int-int}
Lägger till en form i kalkylbladet.


###  Returnerar

Ett formobjekt.


```python

def add_shape(self, type, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| type | [`MsoDrawingType`](/cells/python-net/sv/aspose.cells.drawing/msodrawingtype) | Mso-ritningstyp.|
| upper_left_row | int | Index för övre vänstra raden.|
| top | int | Representerar den vertikala förskjutningen av formen från dess vänstra rad, i pixelenhet.|
| upper_left_column | int | Index i övre vänstra kolumnen.|
| left | int | Representerar den horisontella förskjutningen av formen från dess vänstra kolumn, i pixelenhet.|
| height | int | Representerar formens höjd, i pixelenhet.|
| width | int | Representerar formens bredd, i pixelenhet.|
###  Anmärkningar

Typen kunde inte vara Diagram/Kommentar/Bild/OleObjekt/Polygon/DialogBox
###  Exempel


```python
from aspose.cells.drawing import MsoDrawingType

# Add a shape of the specified type
shapeByType = shapes.add_shape(MsoDrawingType.CELLS_DRAWING, 1, 0, 1, 0, 100, 50)

```



###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`ShapeCollection`](/cells/python-net/sv/aspose.cells.drawing/shapecollection)
