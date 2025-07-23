---
title: método add_spinner
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 320
url: /es/aspose.cells.drawing/shapecollection/add_spinner/
is_root: false
---
##  add_spinner(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Agrega un Spinner a la hoja de trabajo.


###  Devoluciones

Un objeto Spinner.


```python

def add_spinner(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| upper_left_row | int | Índice de la fila superior izquierda.|
| top | int |Representa el desplazamiento vertical de Spinner desde su fila izquierda, en unidades de píxeles.|
| upper_left_column | int | Índice de la columna superior izquierda.|
| left | int | Representa el desplazamiento horizontal de Spinner desde su columna izquierda, en unidades de píxeles.|
| height | int | Representa la altura del Spinner, en unidades de píxel.|
| width | int | Representa el ancho del Spinner, en unidades de píxeles.|

###  Ejemplo

```python

# add a spinner
spinner = shapes.add_spinner(1, 0, 1, 0, 100, 50)

```



###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`ShapeCollection`](/cells/python-net/es/aspose.cells.drawing/shapecollection)
