---
title: método add_shape
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 280
url: /es/aspose.cells.drawing/shapecollection/add_shape/
is_root: false
---
##  add_shape(self, type, upper_left_row, top, upper_left_column, left, height, width) {#aspose.cells.drawing.MsoDrawingType-int-int-int-int-int-int}
Agrega una forma a la hoja de cálculo.


###  Devoluciones

Un objeto de forma.


```python

def add_shape(self, type, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| type | [`MsoDrawingType`](/cells/python-net/es/aspose.cells.drawing/msodrawingtype) | Tipo de dibujo Mso.|
| upper_left_row | int | Índice de la fila superior izquierda.|
| top | int | Representa el desplazamiento vertical de la forma desde su fila izquierda, en unidades de píxeles.|
| upper_left_column | int | Índice de la columna superior izquierda.|
| left | int | Representa el desplazamiento horizontal de la forma desde su columna izquierda, en unidades de píxeles.|
| height | int | Representa la altura de la forma, en unidades de píxeles.|
| width | int | Representa el ancho de la forma, en unidades de píxeles.|
###  Observaciones

El tipo no puede ser Gráfico/Comentario/Imagen/OleObject/Polígono/Cuadro de diálogo
###  Ejemplo


```python
from aspose.cells.drawing import MsoDrawingType

# Add a shape of the specified type
shapeByType = shapes.add_shape(MsoDrawingType.CELLS_DRAWING, 1, 0, 1, 0, 100, 50)

```



###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`ShapeCollection`](/cells/python-net/es/aspose.cells.drawing/shapecollection)
