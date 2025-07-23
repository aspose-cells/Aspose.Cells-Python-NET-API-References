---
title: método add_oval
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 220
url: /es/aspose.cells.drawing/shapecollection/add_oval/
is_root: false
---
##  add_oval(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Agrega un óvalo a la hoja de cálculo.


###  Devoluciones

Un objeto ovalado.


```python

def add_oval(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| upper_left_row | int | Índice de la fila superior izquierda.|
| top | int | Representa el desplazamiento vertical del óvalo desde su fila izquierda, en unidades de píxeles.|
| upper_left_column | int | Índice de la columna superior izquierda.|
| left | int | Representa el desplazamiento horizontal del óvalo desde su columna izquierda, en unidades de píxeles.|
| height | int | Representa la altura del óvalo, en unidad de píxel.|
| width | int | Representa el ancho del óvalo, en unidades de píxeles.|

###  Ejemplo

```python

# add a oval
oval = shapes.add_oval(1, 0, 1, 0, 50, 50)

```



###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`ShapeCollection`](/cells/python-net/es/aspose.cells.drawing/shapecollection)
