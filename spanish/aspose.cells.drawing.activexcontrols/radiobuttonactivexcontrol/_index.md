---
title: RadioButtonActiveXControl clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 70
url: /es/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/
is_root: false
---
##  RadioButtonActiveXControl clase
Representa un control ActiveX RadioButton.



**Herencia:** [`RadioButtonActiveXControl`](/cells/python-net/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol) → 
[`ToggleButtonActiveXControl`](/cells/python-net/es/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol)



El tipo RadioButtonActiveXControl expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [workbook](/cells/python-net/es/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/workbook) |  |
| [type](/cells/python-net/es/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/type) | Obtiene el tipo del control ActiveX.|
| [width](/cells/python-net/es/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/width) |  |
| [height](/cells/python-net/es/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/height) |  |
| [mouse_icon](/cells/python-net/es/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/mouse_icon) |  |
| [mouse_pointer](/cells/python-net/es/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/mouse_pointer) |  |
| [fore_ole_color](/cells/python-net/es/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/fore_ole_color) |  |
| [back_ole_color](/cells/python-net/es/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/back_ole_color) |  |
| [is_visible](/cells/python-net/es/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_visible) |  |
| [shadow](/cells/python-net/es/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/shadow) |  |
| [linked_cell](/cells/python-net/es/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/linked_cell) |  |
| [list_fill_range](/cells/python-net/es/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/list_fill_range) |  |
| [data](/cells/python-net/es/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/data) |  |
| [is_enabled](/cells/python-net/es/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_enabled) |  |
| [is_locked](/cells/python-net/es/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_locked) |  |
| [is_transparent](/cells/python-net/es/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_transparent) |  |
| [is_auto_size](/cells/python-net/es/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_auto_size) |  |
| [ime_mode](/cells/python-net/es/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/ime_mode) |  |
| [font](/cells/python-net/es/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/font) |  |
| [text_align](/cells/python-net/es/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/text_align) |  |
| [caption](/cells/python-net/es/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/caption) | Obtiene y establece el texto descriptivo que aparece en un control.|
| [picture_position](/cells/python-net/es/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/picture_position) |Obtiene y establece la ubicación de la imagen del control en relación con su título.|
| [special_effect](/cells/python-net/es/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/special_effect) | Obtiene y establece el efecto especial del control.|
| [picture](/cells/python-net/es/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/picture) | Obtiene y establece los datos de la imagen.|
| [accelerator](/cells/python-net/es/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/accelerator) | Obtiene y establece la tecla aceleradora para el control.|
| [value](/cells/python-net/es/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/value) | Indica si el control está marcado o no.|
| [is_triple_state](/cells/python-net/es/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_triple_state) | Indica cómo el control especificado mostrará los valores nulos.|
| [group_name](/cells/python-net/es/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/group_name) | Obtiene y establece el nombre del grupo.|
| [alignment](/cells/python-net/es/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/alignment) | Obtiene y establece la posición del título en relación con el control.|
| [is_word_wrapped](/cells/python-net/es/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_word_wrapped) | Indica si el contenido del control se ajusta automáticamente al final de una línea.|



###  Ejemplo

```python
from aspose import pycore
from aspose.cells import Workbook
from aspose.cells.drawing.activexcontrols import ControlType, RadioButtonActiveXControl

# Initialize a new workbook.
book = Workbook()
# Add a ToggleButtonActiveXControl.
shape = book.worksheets[0].shapes.add_active_x_control(ControlType.RADIO_BUTTON, 1, 0, 1, 0, 100, 50)
activeXControl = pycore.cast(RadioButtonActiveXControl, shape.active_x_control)
# do your business
# Save the excel file.
book.save("exmaple.xlsx")

```

###  Ver también
* módulo [`aspose.cells.drawing.activexcontrols`](..)
* clase [`RadioButtonActiveXControl`](/cells/python-net/es/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol)
* clase [`ToggleButtonActiveXControl`](/cells/python-net/es/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol)
