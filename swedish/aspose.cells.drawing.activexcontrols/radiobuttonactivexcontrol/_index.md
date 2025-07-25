---
title: RadioButtonActiveXControl klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 70
url: /sv/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/
is_root: false
---
##  RadioButtonActiveXControl klass
Representerar en RadioButton ActiveX-kontroll.



**Arv:** [`RadioButtonActiveXControl`](/cells/python-net/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol) → 
[`ToggleButtonActiveXControl`](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol)



Typen RadioButtonActiveXControl avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [workbook](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/workbook) |  |
| [type](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/type) | Hämtar typen för ActiveX-kontrollen.|
| [width](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/width) |  |
| [height](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/height) |  |
| [mouse_icon](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/mouse_icon) |  |
| [mouse_pointer](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/mouse_pointer) |  |
| [fore_ole_color](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/fore_ole_color) |  |
| [back_ole_color](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/back_ole_color) |  |
| [is_visible](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_visible) |  |
| [shadow](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/shadow) |  |
| [linked_cell](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/linked_cell) |  |
| [list_fill_range](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/list_fill_range) |  |
| [data](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/data) |  |
| [is_enabled](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_enabled) |  |
| [is_locked](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_locked) |  |
| [is_transparent](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_transparent) |  |
| [is_auto_size](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_auto_size) |  |
| [ime_mode](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/ime_mode) |  |
| [font](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/font) |  |
| [text_align](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/text_align) |  |
| [caption](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/caption) | Hämtar och anger den beskrivande texten som visas på en kontroll.|
| [picture_position](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/picture_position) |Hämtar och anger platsen för kontrollens bild i förhållande till dess bildtext.|
| [special_effect](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/special_effect) | Hämtar och ställer in kontrollens specialeffekt.|
| [picture](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/picture) | Hämtar och ställer in bildens data.|
| [accelerator](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/accelerator) | Hämtar och ställer in acceleratortangenten för kontrollen.|
| [value](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/value) | Anger om kontrollen är kontrollerad eller inte.|
| [is_triple_state](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_triple_state) | Anger hur den angivna kontrollen kommer att visa null-värden.|
| [group_name](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/group_name) | Hämtar och anger gruppens namn.|
| [alignment](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/alignment) | Hämtar och anger positionen för bildtexten i förhållande till kontrollen.|
| [is_word_wrapped](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_word_wrapped) | Anger om innehållet i kontrollen automatiskt radbryts i slutet av en rad.|



###  Exempel

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

###  Se även
* modul [`aspose.cells.drawing.activexcontrols`](..)
* klass [`RadioButtonActiveXControl`](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol)
* klass [`ToggleButtonActiveXControl`](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol)
