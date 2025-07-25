---
title: método add_arc
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 30
url: /es/aspose.cells.drawing/shapecollection/add_arc/
is_root: false
---
##  add_arc(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Agrega un ArcShape a la hoja de cálculo.


###  Devoluciones

Un objeto ArcShape.


```python

def add_arc(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| upper_left_row | int | Índice de la fila superior izquierda.|
| top | int |Representa el desplazamiento vertical de ArcShape desde su fila izquierda, en unidades de píxeles.|
| upper_left_column | int | Índice de la columna superior izquierda.|
| left | int | Representa el desplazamiento horizontal de ArcShape desde su columna izquierda, en unidades de píxeles.|
| height | int | Representa la altura de ArcShape, en unidades de píxel.|
| width | int | Representa el ancho de ArcShape, en unidades de píxeles.|

###  Ejemplo

```python

# add a arc
arcShape = shapes.add_arc(1, 0, 1, 0, 100, 50)

```



###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`ShapeCollection`](/cells/python-net/es/aspose.cells.drawing/shapecollection)
