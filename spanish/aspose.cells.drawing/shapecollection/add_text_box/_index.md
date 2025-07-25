---
title: método add_text_box
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 340
url: /es/aspose.cells.drawing/shapecollection/add_text_box/
is_root: false
---
##  add_text_box(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Agrega un cuadro de texto a la hoja de cálculo.


###  Devoluciones

Un objeto [`TextBox`](/cells/python-net/es/aspose.cells.drawing/textbox).


```python

def add_text_box(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| upper_left_row | int | Índice de la fila superior izquierda.|
| top | int | Representa el desplazamiento vertical del cuadro de texto desde su fila superior, en unidades de píxeles.|
| upper_left_column | int | Índice de la columna superior izquierda.|
| left | int | Representa el desplazamiento horizontal del cuadro de texto desde su columna izquierda, en unidades de píxeles.|
| height | int | Representa la altura del cuadro de texto, en unidades de píxeles.|
| width | int | Representa el ancho del cuadro de texto, en unidades de píxeles.|

###  Ejemplo

```python

# add a TextBox
textBox = shapes.add_text_box(1, 0, 1, 0, 100, 50)

```



###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`ShapeCollection`](/cells/python-net/es/aspose.cells.drawing/shapecollection)
* clase [`TextBox`](/cells/python-net/es/aspose.cells.drawing/textbox)
