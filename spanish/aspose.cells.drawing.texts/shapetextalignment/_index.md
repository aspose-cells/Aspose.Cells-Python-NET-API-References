---
title: ShapeTextAlignment clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 70
url: /es/aspose.cells.drawing.texts/shapetextalignment/
is_root: false
---
##  ShapeTextAlignment clase
Representa la configuración de la alineación del texto de la forma;



El tipo ShapeTextAlignment expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [is_text_wrapped](/cells/python-net/es/aspose.cells.drawing.texts/shapetextalignment/is_text_wrapped) | Obtiene o establece el tipo de texto ajustado de la forma que contiene texto.|
| [rotate_text_with_shape](/cells/python-net/es/aspose.cells.drawing.texts/shapetextalignment/rotate_text_with_shape) | Indica si se gira el texto con forma.|
| [text_vertical_overflow](/cells/python-net/es/aspose.cells.drawing.texts/shapetextalignment/text_vertical_overflow) | Obtiene y establece el tipo de desbordamiento vertical de texto del cuadro de texto.|
| [text_horizontal_overflow](/cells/python-net/es/aspose.cells.drawing.texts/shapetextalignment/text_horizontal_overflow) | Obtiene y establece el tipo de desbordamiento horizontal de texto del cuadro de texto.|
| [rotation_angle](/cells/python-net/es/aspose.cells.drawing.texts/shapetextalignment/rotation_angle) | Obtiene y establece la rotación de la forma.|
| [text_vertical_type](/cells/python-net/es/aspose.cells.drawing.texts/shapetextalignment/text_vertical_type) | Obtiene y establece la dirección del texto.|
| [is_locked_text](/cells/python-net/es/aspose.cells.drawing.texts/shapetextalignment/is_locked_text) | Indica si la forma está bloqueada cuando la hoja de cálculo está protegida.|
| [auto_size](/cells/python-net/es/aspose.cells.drawing.texts/shapetextalignment/auto_size) | Indica si el tamaño de la forma se ajusta automáticamente según su contenido.|
| [text_shape_type](/cells/python-net/es/aspose.cells.drawing.texts/shapetextalignment/text_shape_type) | Obtiene y establece el tipo de transformación del texto.|
| [top_margin_pt](/cells/python-net/es/aspose.cells.drawing.texts/shapetextalignment/top_margin_pt) | Devuelve el margen superior en unidades de puntos.|
| [bottom_margin_pt](/cells/python-net/es/aspose.cells.drawing.texts/shapetextalignment/bottom_margin_pt) | Devuelve el margen inferior en unidades de puntos.|
| [left_margin_pt](/cells/python-net/es/aspose.cells.drawing.texts/shapetextalignment/left_margin_pt) | Devuelve el margen izquierdo en unidad de puntos|
| [right_margin_pt](/cells/python-net/es/aspose.cells.drawing.texts/shapetextalignment/right_margin_pt) | Devuelve el margen derecho en unidad de puntos|
| [is_auto_margin](/cells/python-net/es/aspose.cells.drawing.texts/shapetextalignment/is_auto_margin) |Indica si el margen del marco de texto es automático.|
| [number_of_columns](/cells/python-net/es/aspose.cells.drawing.texts/shapetextalignment/number_of_columns) | Obtiene y establece el número de columnas de texto en el rectángulo delimitador.|



###  Ejemplo

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
shape = workbook.worksheets[0].shapes.add_rectangle(1, 0, 1, 0, 50, 100)
shapeTextAlignment = shape.text_body.text_alignment

```

###  Ver también
* módulo [`aspose.cells.drawing.texts`](..)
