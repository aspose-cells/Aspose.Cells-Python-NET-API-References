---
title: método add_freeform
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 120
url: /es/aspose.cells.drawing/shapecollection/add_freeform/
is_root: false
---
##  add_freeform(self, upper_left_row, top, upper_left_column, left, height, width, paths) {#int-int-int-int-int-int-list}
Agrega una forma libre a la hoja de cálculo.


###  Devoluciones

Una forma libre.


```python

def add_freeform(self, upper_left_row, top, upper_left_column, left, height, width, paths):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| upper_left_row | int | Índice de la fila superior izquierda.|
| top | int | Representa el desplazamiento vertical de la forma libre desde su fila izquierda, en unidades de píxeles.|
| upper_left_column | int | Índice de la columna superior izquierda.|
| left | int | Representa el desplazamiento horizontal de la forma libre desde su columna izquierda, en unidades de píxeles.|
| height | int | Representa la altura de una forma libre, en unidades de píxeles.|
| width | int | Representa el ancho de una forma libre, en unidades de píxeles.|
| paths | list | Representa una ruta definida por el usuario|
###  Observaciones

Nota: El ancho y el alto de los parámetros pueden ser cualquier valor entero positivo, no el ancho y el alto totales de la matriz ShapePath especificada por 'paths'. La relación entre ellos es de escala-relleno; es decir, cada objeto ShapePath se escalará según el ancho y el alto. Por lo tanto, cuando hay varios objetos en 'paths', cada objeto ShapePath debe diseñarse de forma razonable para cumplir con las expectativas. Cuando solo hay un objeto ShapePath y no hay otros requisitos, pasar el ancho y el alto del objeto como valores de parámetro es una buena solución.
###  Ejemplo


```python
from aspose.cells.drawing import ShapePath

# Custom figure
shapePath = ShapePath()
shapePath.move_to(60, 45)
shapePath.arc_to(25, 25, 0, 270)
shapePath.close()
shapePath.move_to(60, 20)
shapePath.line_to(110, 70)
shapePath.line_to(125, 155.5)
shapePath.arc_to(35.5, 35.5, 0, 270)
shapePath.close()
shapePath.move_to(150, 45)
shapePath.arc_to(25, 25, 0, 270)
shapePathW = shapePath.width_pixel
shapePathH = shapePath.height_pixel
shapePath1 = ShapePath()
shapePath1.move_to(0, 0)
shapePath1.cubic_bezier_to(48.24997, 0.6844,                                 96.5, -7.148871,                                 130, 11.517795)
shapePath1.cubic_bezier_to(163.5, 30.18446,                                 182.24997, 75.351,                                 201, 120.517795)
shapePath1.move_to(150, 80)
shapePath1.arc_to(25, 25, 0, 270)
if shapePath1.width_pixel > shapePathW:
    shapePathW = shapePath1.width_pixel
if shapePath1.height_pixel > shapePathH:
    shapePathH = shapePath1.height_pixel
# Notice: shapePathH and shapePathH can be any positive integer values, here we just simply set them.
# Insert custom figure into worksheet
shapes.add_freeform(1, 0, 1, 0, shapePathH, shapePathW, [shapePath, shapePath1])

```



###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`ShapeCollection`](/cells/python-net/es/aspose.cells.drawing/shapecollection)
