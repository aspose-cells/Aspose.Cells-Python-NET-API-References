---
title: método add_group_box
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 130
url: /es/aspose.cells.drawing/shapecollection/add_group_box/
is_root: false
---
##  add_group_box(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Agrega un GroupBox a la hoja de cálculo.


###  Devoluciones

Un objeto GroupBox.


```python

def add_group_box(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| upper_left_row | int | Índice de la fila superior izquierda.|
| top | int | Representa el desplazamiento vertical de GroupBox desde su fila izquierda, en unidades de píxeles.|
| upper_left_column | int | Índice de la columna superior izquierda.|
| left | int | Representa el desplazamiento horizontal de GroupBox desde su columna izquierda, en unidades de píxeles.|
| height | int | Representa la altura de GroupBox, en unidades de píxeles.|
| width | int | Representa el ancho de GroupBox, en unidades de píxeles.|

###  Ejemplo

```python

# add a group box
groupBox = shapes.add_group_box(1, 0, 1, 0, 100, 50)

```



###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`ShapeCollection`](/cells/python-net/es/aspose.cells.drawing/shapecollection)
