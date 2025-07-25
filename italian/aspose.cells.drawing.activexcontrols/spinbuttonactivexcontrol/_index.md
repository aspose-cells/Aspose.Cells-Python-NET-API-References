---
title: SpinButtonActiveXControl classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 90
url: /it/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/
is_root: false
---
##  SpinButtonActiveXControl classe
Rappresenta il controllo SpinButton.



**Eredità:** [`SpinButtonActiveXControl`](/cells/python-net/it/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol)



Il tipo SpinButtonActiveXControl espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [workbook](/cells/python-net/it/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/workbook) |  |
| [type](/cells/python-net/it/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/type) | Ottiene il tipo di controllo ActiveX.|
| [width](/cells/python-net/it/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/width) |  |
| [height](/cells/python-net/it/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/height) |  |
| [mouse_icon](/cells/python-net/it/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/mouse_icon) |  |
| [mouse_pointer](/cells/python-net/it/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/mouse_pointer) |  |
| [fore_ole_color](/cells/python-net/it/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/fore_ole_color) |  |
| [back_ole_color](/cells/python-net/it/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/back_ole_color) |  |
| [is_visible](/cells/python-net/it/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_visible) |  |
| [shadow](/cells/python-net/it/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/shadow) |  |
| [linked_cell](/cells/python-net/it/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/linked_cell) |  |
| [list_fill_range](/cells/python-net/it/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/list_fill_range) |  |
| [data](/cells/python-net/it/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/data) |  |
| [is_enabled](/cells/python-net/it/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_enabled) |  |
| [is_locked](/cells/python-net/it/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_locked) |  |
| [is_transparent](/cells/python-net/it/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_transparent) |  |
| [is_auto_size](/cells/python-net/it/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_auto_size) |  |
| [ime_mode](/cells/python-net/it/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/ime_mode) |  |
| [font](/cells/python-net/it/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/font) |  |
| [text_align](/cells/python-net/it/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/text_align) |  |
| [min](/cells/python-net/it/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/min) | Ottiene e imposta il valore minimo accettabile.|
| [max](/cells/python-net/it/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/max) | Ottiene e imposta il valore massimo accettabile.|
| [position](/cells/python-net/it/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/position) | Ottiene e imposta il valore.|
| [small_change](/cells/python-net/it/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/small_change) | Ottiene e imposta l'importo di cui cambia la proprietà Posizione|
| [orientation](/cells/python-net/it/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/orientation) | Ottiene e imposta se SpinButton o ScrollBar sono orientati verticalmente o orizzontalmente.|



###  Esempio

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

###  Guarda anche
* modulo [`aspose.cells.drawing.activexcontrols`](..)
* classe [`SpinButtonActiveXControl`](/cells/python-net/it/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol)
