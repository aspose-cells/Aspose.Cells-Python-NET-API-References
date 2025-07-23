---
title: SpinButtonActiveXControl Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 90
url: /de/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/
is_root: false
---
##  SpinButtonActiveXControl Klasse
Stellt das SpinButton-Steuerelement dar.



**Nachlass:** [`SpinButtonActiveXControl`](/cells/python-net/de/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol)



Der Typ SpinButtonActiveXControl macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [workbook](/cells/python-net/de/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/workbook) |  |
| [type](/cells/python-net/de/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/type) | Ruft den Typ des ActiveX-Steuerelements ab.|
| [width](/cells/python-net/de/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/width) |  |
| [height](/cells/python-net/de/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/height) |  |
| [mouse_icon](/cells/python-net/de/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/mouse_icon) |  |
| [mouse_pointer](/cells/python-net/de/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/mouse_pointer) |  |
| [fore_ole_color](/cells/python-net/de/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/fore_ole_color) |  |
| [back_ole_color](/cells/python-net/de/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/back_ole_color) |  |
| [is_visible](/cells/python-net/de/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_visible) |  |
| [shadow](/cells/python-net/de/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/shadow) |  |
| [linked_cell](/cells/python-net/de/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/linked_cell) |  |
| [list_fill_range](/cells/python-net/de/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/list_fill_range) |  |
| [data](/cells/python-net/de/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/data) |  |
| [is_enabled](/cells/python-net/de/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_enabled) |  |
| [is_locked](/cells/python-net/de/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_locked) |  |
| [is_transparent](/cells/python-net/de/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_transparent) |  |
| [is_auto_size](/cells/python-net/de/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_auto_size) |  |
| [ime_mode](/cells/python-net/de/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/ime_mode) |  |
| [font](/cells/python-net/de/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/font) |  |
| [text_align](/cells/python-net/de/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/text_align) |  |
| [min](/cells/python-net/de/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/min) | Ruft den minimal akzeptablen Wert ab und legt ihn fest.|
| [max](/cells/python-net/de/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/max) | Ruft den maximal zulässigen Wert ab und legt ihn fest.|
| [position](/cells/python-net/de/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/position) | Ruft den Wert ab und legt ihn fest.|
| [small_change](/cells/python-net/de/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/small_change) | Ruft den Betrag ab und legt ihn fest, um den sich die Eigenschaft „Position“ ändert.|
| [orientation](/cells/python-net/de/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/orientation) | Ruft ab und legt fest, ob der SpinButton oder die ScrollBar vertikal oder horizontal ausgerichtet ist.|



###  Beispiel

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

###  Siehe auch
* Modul [`aspose.cells.drawing.activexcontrols`](..)
* Klasse [`SpinButtonActiveXControl`](/cells/python-net/de/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol)
