---
title: ToggleButtonActiveXControl classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 110
url: /it/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/
is_root: false
---
##  ToggleButtonActiveXControl classe
Rappresenta un controllo ActiveX ToggleButton.



**Eredità:** [`ToggleButtonActiveXControl`](/cells/python-net/it/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol)



Il tipo ToggleButtonActiveXControl espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [workbook](/cells/python-net/it/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/workbook) |  |
| [type](/cells/python-net/it/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/type) | Ottiene il tipo di controllo ActiveX.|
| [width](/cells/python-net/it/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/width) |  |
| [height](/cells/python-net/it/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/height) |  |
| [mouse_icon](/cells/python-net/it/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/mouse_icon) |  |
| [mouse_pointer](/cells/python-net/it/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/mouse_pointer) |  |
| [fore_ole_color](/cells/python-net/it/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/fore_ole_color) |  |
| [back_ole_color](/cells/python-net/it/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/back_ole_color) |  |
| [is_visible](/cells/python-net/it/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_visible) |  |
| [shadow](/cells/python-net/it/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/shadow) |  |
| [linked_cell](/cells/python-net/it/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/linked_cell) |  |
| [list_fill_range](/cells/python-net/it/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/list_fill_range) |  |
| [data](/cells/python-net/it/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/data) |  |
| [is_enabled](/cells/python-net/it/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_enabled) |  |
| [is_locked](/cells/python-net/it/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_locked) |  |
| [is_transparent](/cells/python-net/it/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_transparent) |  |
| [is_auto_size](/cells/python-net/it/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_auto_size) |  |
| [ime_mode](/cells/python-net/it/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/ime_mode) |  |
| [font](/cells/python-net/it/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/font) |  |
| [text_align](/cells/python-net/it/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/text_align) |  |
| [caption](/cells/python-net/it/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/caption) | Ottiene e imposta il testo descrittivo che appare su un controllo.|
| [picture_position](/cells/python-net/it/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/picture_position) |Ottiene e imposta la posizione dell'immagine del controllo rispetto alla sua didascalia.|
| [special_effect](/cells/python-net/it/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/special_effect) | Ottiene e imposta l'effetto speciale del controllo.|
| [picture](/cells/python-net/it/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/picture) | Ottiene e imposta i dati dell'immagine.|
| [accelerator](/cells/python-net/it/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/accelerator) | Ottiene e imposta il tasto di scelta rapida per il controllo.|
| [value](/cells/python-net/it/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/value) | Indica se il controllo è selezionato o meno.|
| [is_triple_state](/cells/python-net/it/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_triple_state) | Indica come il controllo specificato visualizzerà i valori Null.|



###  Esempio

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

###  Guarda anche
* modulo [`aspose.cells.drawing.activexcontrols`](..)
* classe [`ToggleButtonActiveXControl`](/cells/python-net/it/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol)
