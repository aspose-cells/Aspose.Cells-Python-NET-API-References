---
title: ScrollBarActiveXControl Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 80
url: /de/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/
is_root: false
---
##  ScrollBarActiveXControl Klasse
Stellt das ScrollBar-Steuerelement dar.



**Nachlass:** [`ScrollBarActiveXControl`](/cells/python-net/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol) → 
[`SpinButtonActiveXControl`](/cells/python-net/de/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol)



Der Typ ScrollBarActiveXControl macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [workbook](/cells/python-net/de/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/workbook) |  |
| [type](/cells/python-net/de/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/type) | Ruft den Typ des ActiveX-Steuerelements ab.|
| [width](/cells/python-net/de/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/width) |  |
| [height](/cells/python-net/de/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/height) |  |
| [mouse_icon](/cells/python-net/de/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/mouse_icon) |  |
| [mouse_pointer](/cells/python-net/de/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/mouse_pointer) |  |
| [fore_ole_color](/cells/python-net/de/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/fore_ole_color) |  |
| [back_ole_color](/cells/python-net/de/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/back_ole_color) |  |
| [is_visible](/cells/python-net/de/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_visible) |  |
| [shadow](/cells/python-net/de/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/shadow) |  |
| [linked_cell](/cells/python-net/de/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/linked_cell) |  |
| [list_fill_range](/cells/python-net/de/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/list_fill_range) |  |
| [data](/cells/python-net/de/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/data) |  |
| [is_enabled](/cells/python-net/de/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_enabled) |  |
| [is_locked](/cells/python-net/de/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_locked) |  |
| [is_transparent](/cells/python-net/de/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_transparent) |  |
| [is_auto_size](/cells/python-net/de/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_auto_size) |  |
| [ime_mode](/cells/python-net/de/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/ime_mode) |  |
| [font](/cells/python-net/de/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/font) |  |
| [text_align](/cells/python-net/de/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/text_align) |  |
| [min](/cells/python-net/de/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/min) | Ruft den minimal akzeptablen Wert ab und legt ihn fest.|
| [max](/cells/python-net/de/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/max) | Ruft den maximal zulässigen Wert ab und legt ihn fest.|
| [position](/cells/python-net/de/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/position) | Ruft den Wert ab und legt ihn fest.|
| [small_change](/cells/python-net/de/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/small_change) | Ruft den Betrag ab und legt ihn fest, um den sich die Eigenschaft „Position“ ändert.|
| [orientation](/cells/python-net/de/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/orientation) | Ruft ab und legt fest, ob der SpinButton oder die ScrollBar vertikal oder horizontal ausgerichtet ist.|
| [large_change](/cells/python-net/de/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/large_change) | Ruft den Betrag ab und legt ihn fest, um den sich die Eigenschaft „Position“ ändert.|



###  Beispiel

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

###  Siehe auch
* Modul [`aspose.cells.drawing.activexcontrols`](..)
* Klasse [`ScrollBarActiveXControl`](/cells/python-net/de/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol)
* Klasse [`SpinButtonActiveXControl`](/cells/python-net/de/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol)
