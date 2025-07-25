---
title: ScrollBarActiveXControl clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 80
url: /es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/
is_root: false
---
##  ScrollBarActiveXControl clase
Representa el control ScrollBar.



**Herencia:** [`ScrollBarActiveXControl`](/cells/python-net/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol) → 
[`SpinButtonActiveXControl`](/cells/python-net/es/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol)



El tipo ScrollBarActiveXControl expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [workbook](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/workbook) |  |
| [type](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/type) | Obtiene el tipo del control ActiveX.|
| [width](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/width) |  |
| [height](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/height) |  |
| [mouse_icon](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/mouse_icon) |  |
| [mouse_pointer](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/mouse_pointer) |  |
| [fore_ole_color](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/fore_ole_color) |  |
| [back_ole_color](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/back_ole_color) |  |
| [is_visible](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_visible) |  |
| [shadow](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/shadow) |  |
| [linked_cell](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/linked_cell) |  |
| [list_fill_range](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/list_fill_range) |  |
| [data](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/data) |  |
| [is_enabled](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_enabled) |  |
| [is_locked](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_locked) |  |
| [is_transparent](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_transparent) |  |
| [is_auto_size](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_auto_size) |  |
| [ime_mode](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/ime_mode) |  |
| [font](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/font) |  |
| [text_align](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/text_align) |  |
| [min](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/min) | Obtiene y establece el valor mínimo aceptable.|
| [max](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/max) | Obtiene y establece el valor máximo aceptable.|
| [position](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/position) | Obtiene y establece el valor.|
| [small_change](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/small_change) | Obtiene y establece la cantidad en la que cambia la propiedad Posición|
| [orientation](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/orientation) | Obtiene y establece si el SpinButton o ScrollBar está orientado vertical u horizontalmente.|
| [large_change](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/large_change) | Obtiene y establece la cantidad en la que cambia la propiedad Posición|



###  Ejemplo

```python
from aspose import pycore
from aspose.cells import Workbook
from aspose.cells.drawing.activexcontrols import ControlType, ScrollBarActiveXControl

# Initialize a new workbook.
book = Workbook()
# Add a ToggleButtonActiveXControl.
shape = book.worksheets[0].shapes.add_active_x_control(ControlType.SCROLL_BAR, 1, 0, 1, 0, 100, 50)
activeXControl = pycore.cast(ScrollBarActiveXControl, shape.active_x_control)
# do your business
# Save the excel file.
book.save("exmaple.xlsx")

```

###  Ver también
* módulo [`aspose.cells.drawing.activexcontrols`](..)
* clase [`ScrollBarActiveXControl`](/cells/python-net/es/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol)
* clase [`SpinButtonActiveXControl`](/cells/python-net/es/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol)
