---
title: método add_active_x_control
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 20
url: /es/aspose.cells.drawing/shapecollection/add_active_x_control/
is_root: false
---
##  add_active_x_control(self, type, top_row, top, left_column, left, width, height) {#aspose.cells.drawing.activexcontrols.ControlType-int-int-int-int-int-int}
Crea un control Activex.


###  Devoluciones




```python

def add_active_x_control(self, type, top_row, top, left_column, left, width, height):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| type | aspose.cells.drawing.activexcontrols.ControlType | El tipo de control.|
| top_row | int | Índice de la fila superior izquierda.|
| top | int | Representa el desplazamiento vertical de la forma desde su fila izquierda, en unidades de píxeles.|
| left_column | int | Índice de la columna superior izquierda.|
| left | int | Representa el desplazamiento horizontal de la forma desde su columna izquierda, en unidades de píxeles.|
| width | int | Representa el ancho de la forma, en unidades de píxeles.|
| height | int | Representa la altura de la forma, en unidades de píxeles.|

###  Ejemplo

```python
from aspose.cells.drawing.activexcontrols import ControlType

# add an ActiveX control
activeXControl = shapes.add_active_x_control(ControlType.CHECK_BOX, 1, 0, 1, 0, 100, 50)

```



###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`ShapeCollection`](/cells/python-net/es/aspose.cells.drawing/shapecollection)
