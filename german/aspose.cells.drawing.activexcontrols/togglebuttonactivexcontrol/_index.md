---
title: ToggleButtonActiveXControl Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 110
url: /de/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/
is_root: false
---
##  ToggleButtonActiveXControl Klasse
Stellt ein ToggleButton-ActiveX-Steuerelement dar.



**Nachlass:** [`ToggleButtonActiveXControl`](/cells/python-net/de/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol)



Der Typ ToggleButtonActiveXControl macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [workbook](/cells/python-net/de/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/workbook) |  |
| [type](/cells/python-net/de/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/type) | Ruft den Typ des ActiveX-Steuerelements ab.|
| [width](/cells/python-net/de/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/width) |  |
| [height](/cells/python-net/de/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/height) |  |
| [mouse_icon](/cells/python-net/de/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/mouse_icon) |  |
| [mouse_pointer](/cells/python-net/de/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/mouse_pointer) |  |
| [fore_ole_color](/cells/python-net/de/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/fore_ole_color) |  |
| [back_ole_color](/cells/python-net/de/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/back_ole_color) |  |
| [is_visible](/cells/python-net/de/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_visible) |  |
| [shadow](/cells/python-net/de/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/shadow) |  |
| [linked_cell](/cells/python-net/de/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/linked_cell) |  |
| [list_fill_range](/cells/python-net/de/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/list_fill_range) |  |
| [data](/cells/python-net/de/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/data) |  |
| [is_enabled](/cells/python-net/de/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_enabled) |  |
| [is_locked](/cells/python-net/de/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_locked) |  |
| [is_transparent](/cells/python-net/de/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_transparent) |  |
| [is_auto_size](/cells/python-net/de/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_auto_size) |  |
| [ime_mode](/cells/python-net/de/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/ime_mode) |  |
| [font](/cells/python-net/de/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/font) |  |
| [text_align](/cells/python-net/de/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/text_align) |  |
| [caption](/cells/python-net/de/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/caption) | Ruft den beschreibenden Text ab, der auf einem Steuerelement angezeigt wird, und legt ihn fest.|
| [picture_position](/cells/python-net/de/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/picture_position) |Ruft die Position des Steuerelementbilds relativ zu seiner Beschriftung ab und legt diese fest.|
| [special_effect](/cells/python-net/de/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/special_effect) | Ruft den Spezialeffekt des Steuerelements ab und legt ihn fest.|
| [picture](/cells/python-net/de/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/picture) | Ruft die Daten des Bildes ab und legt sie fest.|
| [accelerator](/cells/python-net/de/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/accelerator) | Ruft die Zugriffstaste für das Steuerelement ab und legt sie fest.|
| [value](/cells/python-net/de/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/value) | Gibt an, ob das Steuerelement aktiviert ist oder nicht.|
| [is_triple_state](/cells/python-net/de/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_triple_state) | Gibt an, wie das angegebene Steuerelement Nullwerte anzeigt.|



###  Beispiel

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

###  Siehe auch
* Modul [`aspose.cells.drawing.activexcontrols`](..)
* Klasse [`ToggleButtonActiveXControl`](/cells/python-net/de/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol)
