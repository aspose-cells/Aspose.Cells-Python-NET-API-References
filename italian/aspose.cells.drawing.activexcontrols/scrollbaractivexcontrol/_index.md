---
title: ScrollBarActiveXControl classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 80
url: /it/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/
is_root: false
---
##  ScrollBarActiveXControl classe
Rappresenta il controllo ScrollBar.



**Eredità:** [`ScrollBarActiveXControl`](/cells/python-net/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol) → 
[`SpinButtonActiveXControl`](/cells/python-net/it/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol)



Il tipo ScrollBarActiveXControl espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [workbook](/cells/python-net/it/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/workbook) |  |
| [type](/cells/python-net/it/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/type) | Ottiene il tipo di controllo ActiveX.|
| [width](/cells/python-net/it/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/width) |  |
| [height](/cells/python-net/it/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/height) |  |
| [mouse_icon](/cells/python-net/it/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/mouse_icon) |  |
| [mouse_pointer](/cells/python-net/it/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/mouse_pointer) |  |
| [fore_ole_color](/cells/python-net/it/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/fore_ole_color) |  |
| [back_ole_color](/cells/python-net/it/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/back_ole_color) |  |
| [is_visible](/cells/python-net/it/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_visible) |  |
| [shadow](/cells/python-net/it/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/shadow) |  |
| [linked_cell](/cells/python-net/it/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/linked_cell) |  |
| [list_fill_range](/cells/python-net/it/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/list_fill_range) |  |
| [data](/cells/python-net/it/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/data) |  |
| [is_enabled](/cells/python-net/it/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_enabled) |  |
| [is_locked](/cells/python-net/it/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_locked) |  |
| [is_transparent](/cells/python-net/it/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_transparent) |  |
| [is_auto_size](/cells/python-net/it/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_auto_size) |  |
| [ime_mode](/cells/python-net/it/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/ime_mode) |  |
| [font](/cells/python-net/it/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/font) |  |
| [text_align](/cells/python-net/it/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/text_align) |  |
| [min](/cells/python-net/it/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/min) | Ottiene e imposta il valore minimo accettabile.|
| [max](/cells/python-net/it/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/max) | Ottiene e imposta il valore massimo accettabile.|
| [position](/cells/python-net/it/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/position) | Ottiene e imposta il valore.|
| [small_change](/cells/python-net/it/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/small_change) | Ottiene e imposta l'importo di cui cambia la proprietà Posizione|
| [orientation](/cells/python-net/it/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/orientation) | Ottiene e imposta se SpinButton o ScrollBar sono orientati verticalmente o orizzontalmente.|
| [large_change](/cells/python-net/it/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/large_change) | Ottiene e imposta l'importo di cui cambia la proprietà Posizione|



###  Esempio

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

###  Guarda anche
* modulo [`aspose.cells.drawing.activexcontrols`](..)
* classe [`ScrollBarActiveXControl`](/cells/python-net/it/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol)
* classe [`SpinButtonActiveXControl`](/cells/python-net/it/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol)
