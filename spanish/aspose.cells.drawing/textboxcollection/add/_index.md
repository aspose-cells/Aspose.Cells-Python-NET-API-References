---
title: método add
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 20
url: /es/aspose.cells.drawing/textboxcollection/add/
is_root: false
---
##  add(self, upper_left_row, upper_left_column, height, width) {#int-int-int-int}
Agrega un cuadro de texto a la colección.


###  Devoluciones

Índice de objeto [`TextBox`](/cells/python-net/es/aspose.cells.drawing/textbox).


```python

def add(self, upper_left_row, upper_left_column, height, width):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| upper_left_row | int | Índice de la fila superior izquierda.|
| upper_left_column | int | Índice de la columna superior izquierda.|
| height | int | Altura del cuadro de texto, en unidad de píxel.|
| width | int | Ancho del cuadro de texto, en unidad de píxel.|

###  Ejemplo

```python

# add a TextBox
index2 = textBoxCollection.add(1, 1, 50, 100)

```



###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`TextBox`](/cells/python-net/es/aspose.cells.drawing/textbox)
* clase [`TextBoxCollection`](/cells/python-net/es/aspose.cells.drawing/textboxcollection)
