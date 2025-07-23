---
title: SpinButtonActiveXControl klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 90
url: /sv/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/
is_root: false
---
##  SpinButtonActiveXControl klass
Representerar SpinButton-kontrollen.



**Arv:** [`SpinButtonActiveXControl`](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol)



Typen SpinButtonActiveXControl avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [workbook](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/workbook) |  |
| [type](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/type) | Hämtar typen för ActiveX-kontrollen.|
| [width](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/width) |  |
| [height](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/height) |  |
| [mouse_icon](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/mouse_icon) |  |
| [mouse_pointer](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/mouse_pointer) |  |
| [fore_ole_color](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/fore_ole_color) |  |
| [back_ole_color](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/back_ole_color) |  |
| [is_visible](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_visible) |  |
| [shadow](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/shadow) |  |
| [linked_cell](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/linked_cell) |  |
| [list_fill_range](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/list_fill_range) |  |
| [data](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/data) |  |
| [is_enabled](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_enabled) |  |
| [is_locked](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_locked) |  |
| [is_transparent](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_transparent) |  |
| [is_auto_size](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_auto_size) |  |
| [ime_mode](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/ime_mode) |  |
| [font](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/font) |  |
| [text_align](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/text_align) |  |
| [min](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/min) | Hämtar och ställer in det lägsta acceptabla värdet.|
| [max](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/max) | Hämtar och ställer in det maximala acceptabla värdet.|
| [position](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/position) | Hämtar och ställer in värdet.|
| [small_change](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/small_change) | Hämtar och anger hur mycket Position-egenskapen ändras|
| [orientation](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/orientation) | Hämtar och anger om SpinButton eller ScrollBar är orienterade vertikalt eller horisontellt.|



###  Exempel

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

###  Se även
* modul [`aspose.cells.drawing.activexcontrols`](..)
* klass [`SpinButtonActiveXControl`](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol)
