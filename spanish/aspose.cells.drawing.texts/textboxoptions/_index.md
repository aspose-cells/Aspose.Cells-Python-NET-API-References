---
title: TextBoxOptions clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 80
url: /es/aspose.cells.drawing.texts/textboxoptions/
is_root: false
---
##  TextBoxOptions clase
Representa las opciones de texto de la forma.



El tipo TextBoxOptions expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [shape_text_vertical_alignment](/cells/python-net/es/aspose.cells.drawing.texts/textboxoptions/shape_text_vertical_alignment) | Corresponde a "Formato de forma - Opciones de texto - Cuadro de texto - Alineación vertical" en Excel.|
| [resize_to_fit_text](/cells/python-net/es/aspose.cells.drawing.texts/textboxoptions/resize_to_fit_text) | Indica si se debe cambiar el tamaño de la forma para que se ajuste al texto.|
| [shape_text_direction](/cells/python-net/es/aspose.cells.drawing.texts/textboxoptions/shape_text_direction) | Obtiene o establece la dirección de visualización del texto dentro de un cuerpo de texto determinado.<br/> Corresponde a "Formato de forma - Opciones de texto - Cuadro de texto - Dirección del texto" en Excel|
| [left_margin_pt](/cells/python-net/es/aspose.cells.drawing.texts/textboxoptions/left_margin_pt) | Obtiene y establece el margen izquierdo en unidades de puntos.|
| [right_margin_pt](/cells/python-net/es/aspose.cells.drawing.texts/textboxoptions/right_margin_pt) | Obtiene y establece el margen derecho en unidades de puntos.|
| [top_margin_pt](/cells/python-net/es/aspose.cells.drawing.texts/textboxoptions/top_margin_pt) | Obtiene y establece el margen superior en unidades de puntos.|
| [bottom_margin_pt](/cells/python-net/es/aspose.cells.drawing.texts/textboxoptions/bottom_margin_pt) | Devuelve el margen inferior en unidades de puntos.|
| [allow_text_to_overflow](/cells/python-net/es/aspose.cells.drawing.texts/textboxoptions/allow_text_to_overflow) | Si permitir que el texto se desborde de la forma.|
| [wrap_text_in_shape](/cells/python-net/es/aspose.cells.drawing.texts/textboxoptions/wrap_text_in_shape) | Especifica el ajuste del texto dentro de una forma.<br/> Falso: no se realizará ningún ajuste en el cuerpo del texto.<br/>Verdadero: el ajuste se realizará en el cuerpo del texto.|



###  Ejemplo

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
index = workbook.worksheets[0].text_boxes.add(0, 0, 350, 350)
shape = workbook.worksheets[0].text_boxes[index]
shape.text = "This is test."
# do your business
# Save the excel file.
workbook.save("exmaple.xlsx")

```

###  Ver también
* módulo [`aspose.cells.drawing.texts`](..)
