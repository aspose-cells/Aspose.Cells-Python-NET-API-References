---
title: método add_combo_box
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 80
url: /es/aspose.cells.drawing/shapecollection/add_combo_box/
is_root: false
---
##  add_combo_box(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Agrega un ComboBox a la hoja de cálculo.


###  Devoluciones

Un objeto ComboBox.


```python

def add_combo_box(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| upper_left_row | int | Índice de la fila superior izquierda.|
| top | int | Representa el desplazamiento vertical del ComboBox desde su fila izquierda, en unidades de píxeles.|
| upper_left_column | int | Índice de la columna superior izquierda.|
| left | int | Representa el desplazamiento horizontal del ComboBox desde su columna izquierda, en unidades de píxeles.|
| height | int | Representa la altura del ComboBox, en unidades de píxeles.|
| width | int | Representa el ancho del ComboBox, en unidades de píxeles.|

###  Ejemplo

```python

# add a combo box
comboBox = shapes.add_combo_box(1, 0, 1, 0, 100, 50)

```



###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`ShapeCollection`](/cells/python-net/es/aspose.cells.drawing/shapecollection)
