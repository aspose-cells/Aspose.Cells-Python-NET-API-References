---
title: método add_radio_button
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 250
url: /es/aspose.cells.drawing/shapecollection/add_radio_button/
is_root: false
---
##  add_radio_button(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Agrega un botón de opción a la hoja de cálculo.


###  Devoluciones

Un objeto RadioButton.


```python

def add_radio_button(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| upper_left_row | int | Índice de la fila superior izquierda.|
| top | int | Representa el desplazamiento vertical de RadioButton desde su fila izquierda, en unidades de píxeles.|
| upper_left_column | int | Índice de la columna superior izquierda.|
| left | int | Representa el desplazamiento horizontal de RadioButton desde su columna izquierda, en unidades de píxeles.|
| height | int | Representa la altura del RadioButton, en unidades de píxel.|
| width | int | Representa el ancho del RadioButton, en unidades de píxeles.|

###  Ejemplo

```python

# add a radio button
radioButton = shapes.add_radio_button(1, 0, 1, 0, 100, 50)

```



###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`ShapeCollection`](/cells/python-net/es/aspose.cells.drawing/shapecollection)
