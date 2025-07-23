---
title: ScrollBarActiveXControl klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 80
url: /sv/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/
is_root: false
---
##  ScrollBarActiveXControl klass
Representerar ScrollBar-kontrollen.



**Arv:** [`ScrollBarActiveXControl`](/cells/python-net/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol) → 
[`SpinButtonActiveXControl`](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol)



Typen ScrollBarActiveXControl avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [workbook](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/workbook) |  |
| [type](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/type) | Hämtar typen för ActiveX-kontrollen.|
| [width](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/width) |  |
| [height](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/height) |  |
| [mouse_icon](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/mouse_icon) |  |
| [mouse_pointer](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/mouse_pointer) |  |
| [fore_ole_color](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/fore_ole_color) |  |
| [back_ole_color](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/back_ole_color) |  |
| [is_visible](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_visible) |  |
| [shadow](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/shadow) |  |
| [linked_cell](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/linked_cell) |  |
| [list_fill_range](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/list_fill_range) |  |
| [data](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/data) |  |
| [is_enabled](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_enabled) |  |
| [is_locked](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_locked) |  |
| [is_transparent](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_transparent) |  |
| [is_auto_size](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_auto_size) |  |
| [ime_mode](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/ime_mode) |  |
| [font](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/font) |  |
| [text_align](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/text_align) |  |
| [min](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/min) | Hämtar och ställer in det lägsta acceptabla värdet.|
| [max](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/max) | Hämtar och ställer in det maximala acceptabla värdet.|
| [position](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/position) | Hämtar och ställer in värdet.|
| [small_change](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/small_change) | Hämtar och anger hur mycket Position-egenskapen ändras|
| [orientation](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/orientation) | Hämtar och anger om SpinButton eller ScrollBar är orienterade vertikalt eller horisontellt.|
| [large_change](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/large_change) | Hämtar och anger hur mycket Position-egenskapen ändras|



###  Exempel

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

###  Se även
* modul [`aspose.cells.drawing.activexcontrols`](..)
* klass [`ScrollBarActiveXControl`](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol)
* klass [`SpinButtonActiveXControl`](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol)
