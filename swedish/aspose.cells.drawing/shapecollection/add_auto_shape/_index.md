---
title: add_auto_shape metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 40
url: /sv/aspose.cells.drawing/shapecollection/add_auto_shape/
is_root: false
---
##  add_auto_shape(self, type, upper_left_row, top, upper_left_column, left, height, width) {#aspose.cells.drawing.AutoShapeType-int-int-int-int-int-int}
Lägger till en autoform i kalkylbladet.


###  Returnerar

Ett formobjekt.


```python

def add_auto_shape(self, type, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| type | [`AutoShapeType`](/cells/python-net/sv/aspose.cells.drawing/autoshapetype) | Automatisk formtyp.|
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
from aspose.cells.drawing import AutoShapeType

# Adds a AutoShape to the worksheet.
autoShape = shapes.add_auto_shape(AutoShapeType.CUBE, 1, 0, 1, 0, 100, 50)

```



###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`ShapeCollection`](/cells/python-net/sv/aspose.cells.drawing/shapecollection)
