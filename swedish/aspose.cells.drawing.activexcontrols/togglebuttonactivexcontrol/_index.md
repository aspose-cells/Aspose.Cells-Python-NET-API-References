---
title: ToggleButtonActiveXControl klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 110
url: /sv/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/
is_root: false
---
##  ToggleButtonActiveXControl klass
Representerar en ActiveX-kontroll med växelknapp.



**Arv:** [`ToggleButtonActiveXControl`](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol)



Typen ToggleButtonActiveXControl avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [workbook](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/workbook) |  |
| [type](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/type) | Hämtar typen för ActiveX-kontrollen.|
| [width](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/width) |  |
| [height](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/height) |  |
| [mouse_icon](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/mouse_icon) |  |
| [mouse_pointer](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/mouse_pointer) |  |
| [fore_ole_color](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/fore_ole_color) |  |
| [back_ole_color](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/back_ole_color) |  |
| [is_visible](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_visible) |  |
| [shadow](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/shadow) |  |
| [linked_cell](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/linked_cell) |  |
| [list_fill_range](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/list_fill_range) |  |
| [data](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/data) |  |
| [is_enabled](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_enabled) |  |
| [is_locked](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_locked) |  |
| [is_transparent](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_transparent) |  |
| [is_auto_size](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_auto_size) |  |
| [ime_mode](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/ime_mode) |  |
| [font](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/font) |  |
| [text_align](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/text_align) |  |
| [caption](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/caption) | Hämtar och anger den beskrivande texten som visas på en kontroll.|
| [picture_position](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/picture_position) |Hämtar och anger platsen för kontrollens bild i förhållande till dess bildtext.|
| [special_effect](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/special_effect) | Hämtar och ställer in kontrollens specialeffekt.|
| [picture](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/picture) | Hämtar och ställer in bildens data.|
| [accelerator](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/accelerator) | Hämtar och ställer in acceleratortangenten för kontrollen.|
| [value](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/value) | Anger om kontrollen är kontrollerad eller inte.|
| [is_triple_state](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_triple_state) | Anger hur den angivna kontrollen kommer att visa null-värden.|



###  Exempel

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

###  Se även
* modul [`aspose.cells.drawing.activexcontrols`](..)
* klass [`ToggleButtonActiveXControl`](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol)
