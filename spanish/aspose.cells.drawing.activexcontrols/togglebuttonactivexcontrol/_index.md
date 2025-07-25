---
title: ToggleButtonActiveXControl clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 110
url: /es/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/
is_root: false
---
##  ToggleButtonActiveXControl clase
Representa un control ActiveX ToggleButton.



**Herencia:** [`ToggleButtonActiveXControl`](/cells/python-net/es/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol)



El tipo ToggleButtonActiveXControl expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [workbook](/cells/python-net/es/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/workbook) |  |
| [type](/cells/python-net/es/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/type) | Obtiene el tipo del control ActiveX.|
| [width](/cells/python-net/es/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/width) |  |
| [height](/cells/python-net/es/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/height) |  |
| [mouse_icon](/cells/python-net/es/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/mouse_icon) |  |
| [mouse_pointer](/cells/python-net/es/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/mouse_pointer) |  |
| [fore_ole_color](/cells/python-net/es/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/fore_ole_color) |  |
| [back_ole_color](/cells/python-net/es/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/back_ole_color) |  |
| [is_visible](/cells/python-net/es/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_visible) |  |
| [shadow](/cells/python-net/es/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/shadow) |  |
| [linked_cell](/cells/python-net/es/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/linked_cell) |  |
| [list_fill_range](/cells/python-net/es/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/list_fill_range) |  |
| [data](/cells/python-net/es/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/data) |  |
| [is_enabled](/cells/python-net/es/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_enabled) |  |
| [is_locked](/cells/python-net/es/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_locked) |  |
| [is_transparent](/cells/python-net/es/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_transparent) |  |
| [is_auto_size](/cells/python-net/es/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_auto_size) |  |
| [ime_mode](/cells/python-net/es/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/ime_mode) |  |
| [font](/cells/python-net/es/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/font) |  |
| [text_align](/cells/python-net/es/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/text_align) |  |
| [caption](/cells/python-net/es/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/caption) | Obtiene y establece el texto descriptivo que aparece en un control.|
| [picture_position](/cells/python-net/es/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/picture_position) |Obtiene y establece la ubicación de la imagen del control en relación con su título.|
| [special_effect](/cells/python-net/es/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/special_effect) | Obtiene y establece el efecto especial del control.|
| [picture](/cells/python-net/es/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/picture) | Obtiene y establece los datos de la imagen.|
| [accelerator](/cells/python-net/es/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/accelerator) | Obtiene y establece la tecla aceleradora para el control.|
| [value](/cells/python-net/es/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/value) | Indica si el control está marcado o no.|
| [is_triple_state](/cells/python-net/es/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_triple_state) | Indica cómo el control especificado mostrará los valores nulos.|



###  Ejemplo

```python
from aspose import pycore
from aspose.cells import Workbook
from aspose.cells.drawing.activexcontrols import ControlType, ToggleButtonActiveXControl

# Initialize a new workbook.
book = Workbook()
# Add a ToggleButtonActiveXControl.
shape = book.worksheets[0].shapes.add_active_x_control(ControlType.TOGGLE_BUTTON, 1, 0, 1, 0, 100, 50)
activeXControl = pycore.cast(ToggleButtonActiveXControl, shape.active_x_control)
# do your business
# Save the excel file.
book.save("exmaple.xlsx")

```

###  Ver también
* módulo [`aspose.cells.drawing.activexcontrols`](..)
* clase [`ToggleButtonActiveXControl`](/cells/python-net/es/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol)
