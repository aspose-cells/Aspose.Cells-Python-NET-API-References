---
title: método add_scroll_bar
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 270
url: /es/aspose.cells.drawing/shapecollection/add_scroll_bar/
is_root: false
---
##  add_scroll_bar(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Agrega una barra de desplazamiento a la hoja de cálculo.


###  Devoluciones

Un objeto ScrollBar.


```python

def add_scroll_bar(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| upper_left_row | int | Índice de la fila superior izquierda.|
| top | int |Representa el desplazamiento vertical de ScrollBar desde su fila izquierda, en unidades de píxeles.|
| upper_left_column | int | Índice de la columna superior izquierda.|
| left | int | Representa el desplazamiento horizontal de ScrollBar desde su columna izquierda, en unidades de píxeles.|
| height | int | Representa la altura de ScrollBar, en unidades de píxeles.|
| width | int | Representa el ancho de la barra de desplazamiento, en unidades de píxeles.|

###  Ejemplo

```python

# add a scroll bar
scrollBar = shapes.add_scroll_bar(1, 0, 1, 0, 100, 20)

```



###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`ShapeCollection`](/cells/python-net/es/aspose.cells.drawing/shapecollection)
