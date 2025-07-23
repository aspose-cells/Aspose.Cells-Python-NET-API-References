---
title: add_active_x_control metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 20
url: /sv/aspose.cells.drawing/shapecollection/add_active_x_control/
is_root: false
---
##  add_active_x_control(self, type, top_row, top, left_column, left, width, height) {#aspose.cells.drawing.activexcontrols.ControlType-int-int-int-int-int-int}
Skapar en ActiveX-kontroll.


###  Returnerar




```python

def add_active_x_control(self, type, top_row, top, left_column, left, width, height):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| type | aspose.cells.drawing.activexcontrols.ControlType | Kontrollens typ.|
| top_row | int | Index för övre vänstra raden.|
| top | int | Representerar den vertikala förskjutningen av formen från dess vänstra rad, i pixelenhet.|
| left_column | int | Index i övre vänstra kolumnen.|
| left | int | Representerar den horisontella förskjutningen av formen från dess vänstra kolumn, i pixelenhet.|
| width | int | Representerar formens bredd, i pixelenhet.|
| height | int | Representerar formens höjd, i pixelenhet.|

###  Exempel

```python
from aspose.cells.drawing.activexcontrols import ControlType

# add an ActiveX control
activeXControl = shapes.add_active_x_control(ControlType.CHECK_BOX, 1, 0, 1, 0, 100, 50)

```



###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`ShapeCollection`](/cells/python-net/sv/aspose.cells.drawing/shapecollection)
