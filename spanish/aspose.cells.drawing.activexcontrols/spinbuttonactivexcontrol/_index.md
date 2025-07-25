---
title: SpinButtonActiveXControl clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 90
url: /es/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/
is_root: false
---
##  SpinButtonActiveXControl clase
Representa el control SpinButton.



**Herencia:** [`SpinButtonActiveXControl`](/cells/python-net/es/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol)



El tipo SpinButtonActiveXControl expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [workbook](/cells/python-net/es/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/workbook) |  |
| [type](/cells/python-net/es/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/type) | Obtiene el tipo del control ActiveX.|
| [width](/cells/python-net/es/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/width) |  |
| [height](/cells/python-net/es/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/height) |  |
| [mouse_icon](/cells/python-net/es/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/mouse_icon) |  |
| [mouse_pointer](/cells/python-net/es/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/mouse_pointer) |  |
| [fore_ole_color](/cells/python-net/es/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/fore_ole_color) |  |
| [back_ole_color](/cells/python-net/es/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/back_ole_color) |  |
| [is_visible](/cells/python-net/es/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_visible) |  |
| [shadow](/cells/python-net/es/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/shadow) |  |
| [linked_cell](/cells/python-net/es/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/linked_cell) |  |
| [list_fill_range](/cells/python-net/es/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/list_fill_range) |  |
| [data](/cells/python-net/es/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/data) |  |
| [is_enabled](/cells/python-net/es/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_enabled) |  |
| [is_locked](/cells/python-net/es/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_locked) |  |
| [is_transparent](/cells/python-net/es/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_transparent) |  |
| [is_auto_size](/cells/python-net/es/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_auto_size) |  |
| [ime_mode](/cells/python-net/es/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/ime_mode) |  |
| [font](/cells/python-net/es/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/font) |  |
| [text_align](/cells/python-net/es/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/text_align) |  |
| [min](/cells/python-net/es/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/min) | Obtiene y establece el valor mínimo aceptable.|
| [max](/cells/python-net/es/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/max) | Obtiene y establece el valor máximo aceptable.|
| [position](/cells/python-net/es/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/position) | Obtiene y establece el valor.|
| [small_change](/cells/python-net/es/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/small_change) | Obtiene y establece la cantidad en la que cambia la propiedad Posición|
| [orientation](/cells/python-net/es/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/orientation) | Obtiene y establece si el SpinButton o ScrollBar está orientado vertical u horizontalmente.|



###  Ejemplo

```python
from aspose import pycore
from aspose.cells import Workbook
from aspose.cells.drawing.activexcontrols import ControlType, SpinButtonActiveXControl

# Initialize a new workbook.
book = Workbook()
# Add a ToggleButtonActiveXControl.
shape = book.worksheets[0].shapes.add_active_x_control(ControlType.SPIN_BUTTON, 1, 0, 1, 0, 100, 50)
activeXControl = pycore.cast(SpinButtonActiveXControl, shape.active_x_control)
# do your business
# Save the excel file.
book.save("exmaple.xlsx")

```

###  Ver también
* módulo [`aspose.cells.drawing.activexcontrols`](..)
* clase [`SpinButtonActiveXControl`](/cells/python-net/es/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol)
