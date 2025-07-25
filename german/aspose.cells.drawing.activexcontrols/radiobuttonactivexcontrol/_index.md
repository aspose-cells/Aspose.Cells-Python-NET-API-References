---
title: RadioButtonActiveXControl Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 70
url: /de/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/
is_root: false
---
##  RadioButtonActiveXControl Klasse
Stellt ein RadioButton-ActiveX-Steuerelement dar.



**Nachlass:** [`RadioButtonActiveXControl`](/cells/python-net/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol) → 
[`ToggleButtonActiveXControl`](/cells/python-net/de/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol)



Der Typ RadioButtonActiveXControl macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [workbook](/cells/python-net/de/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/workbook) |  |
| [type](/cells/python-net/de/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/type) | Ruft den Typ des ActiveX-Steuerelements ab.|
| [width](/cells/python-net/de/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/width) |  |
| [height](/cells/python-net/de/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/height) |  |
| [mouse_icon](/cells/python-net/de/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/mouse_icon) |  |
| [mouse_pointer](/cells/python-net/de/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/mouse_pointer) |  |
| [fore_ole_color](/cells/python-net/de/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/fore_ole_color) |  |
| [back_ole_color](/cells/python-net/de/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/back_ole_color) |  |
| [is_visible](/cells/python-net/de/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_visible) |  |
| [shadow](/cells/python-net/de/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/shadow) |  |
| [linked_cell](/cells/python-net/de/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/linked_cell) |  |
| [list_fill_range](/cells/python-net/de/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/list_fill_range) |  |
| [data](/cells/python-net/de/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/data) |  |
| [is_enabled](/cells/python-net/de/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_enabled) |  |
| [is_locked](/cells/python-net/de/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_locked) |  |
| [is_transparent](/cells/python-net/de/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_transparent) |  |
| [is_auto_size](/cells/python-net/de/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_auto_size) |  |
| [ime_mode](/cells/python-net/de/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/ime_mode) |  |
| [font](/cells/python-net/de/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/font) |  |
| [text_align](/cells/python-net/de/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/text_align) |  |
| [caption](/cells/python-net/de/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/caption) | Ruft den beschreibenden Text ab, der auf einem Steuerelement angezeigt wird, und legt ihn fest.|
| [picture_position](/cells/python-net/de/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/picture_position) |Ruft die Position des Steuerelementbilds relativ zu seiner Beschriftung ab und legt diese fest.|
| [special_effect](/cells/python-net/de/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/special_effect) | Ruft den Spezialeffekt des Steuerelements ab und legt ihn fest.|
| [picture](/cells/python-net/de/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/picture) | Ruft die Daten des Bildes ab und legt sie fest.|
| [accelerator](/cells/python-net/de/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/accelerator) | Ruft die Zugriffstaste für das Steuerelement ab und legt sie fest.|
| [value](/cells/python-net/de/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/value) | Gibt an, ob das Steuerelement aktiviert ist oder nicht.|
| [is_triple_state](/cells/python-net/de/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_triple_state) | Gibt an, wie das angegebene Steuerelement Nullwerte anzeigt.|
| [group_name](/cells/python-net/de/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/group_name) | Ruft den Namen der Gruppe ab und legt ihn fest.|
| [alignment](/cells/python-net/de/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/alignment) | Ruft die Position der Beschriftung relativ zum Steuerelement ab und legt sie fest.|
| [is_word_wrapped](/cells/python-net/de/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_word_wrapped) | Gibt an, ob der Inhalt des Steuerelements am Ende einer Zeile automatisch umbrochen wird.|



###  Beispiel

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

###  Siehe auch
* Modul [`aspose.cells.drawing.activexcontrols`](..)
* Klasse [`RadioButtonActiveXControl`](/cells/python-net/de/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol)
* Klasse [`ToggleButtonActiveXControl`](/cells/python-net/de/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol)
