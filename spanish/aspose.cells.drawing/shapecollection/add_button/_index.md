---
title: método add_button
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 60
url: /es/aspose.cells.drawing/shapecollection/add_button/
is_root: false
---
##  add_button(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Agrega un botón a la hoja de cálculo.


###  Devoluciones

Un objeto de botón.


```python

def add_button(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| upper_left_row | int | Índice de la fila superior izquierda.|
| top | int | Representa el desplazamiento vertical del botón desde su fila izquierda, en unidades de píxeles.|
| upper_left_column | int | Índice de la columna superior izquierda.|
| left | int |Representa el desplazamiento horizontal del botón desde su columna izquierda, en unidades de píxeles.|
| height | int | Representa la altura del botón, en unidades de píxel.|
| width | int | Representa el ancho del botón, en unidades de píxeles.|

###  Ejemplo

```python

# add a button
button = shapes.add_button(1, 0, 1, 0, 100, 50)

```



###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`ShapeCollection`](/cells/python-net/es/aspose.cells.drawing/shapecollection)
