---
title: método add_copy
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 90
url: /es/aspose.cells.drawing/shapecollection/add_copy/
is_root: false
---
##  add_copy(self, source_shape, top_row, top, left_column, left) {#aspose.cells.drawing.Shape-int-int-int-int}
Agrega y copia una forma a la hoja de cálculo.


###  Devoluciones

El nuevo objeto [`Shape`](/cells/python-net/es/aspose.cells.drawing/shape).


```python

def add_copy(self, source_shape, top_row, top, left_column, left):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| source_shape | [`Shape`](/cells/python-net/es/aspose.cells.drawing/shape) | Forma de la fuente.|
| top_row | int |El índice de la fila superior.|
| top | int | Representa el desplazamiento vertical desde su fila superior, en unidades de píxeles.|
| left_column | int | El índice de la columna izquierda.|
| left | int | Representa el desplazamiento horizontal desde su columna izquierda, en unidades de píxel.|

###  Ejemplo

```python

# add a shape
rectangle = shapes.add_rectangle(2, 0, 2, 0, 130, 130)
# Adds and copies a shape.
shapes.add_copy(rectangle, 7, 0, 7, 0)

```



###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`Shape`](/cells/python-net/es/aspose.cells.drawing/shape)
* clase [`ShapeCollection`](/cells/python-net/es/aspose.cells.drawing/shapecollection)
