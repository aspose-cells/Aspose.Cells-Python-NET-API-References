---
title: RadioButtonActiveXControl classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 70
url: /it/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/
is_root: false
---
##  RadioButtonActiveXControl classe
Rappresenta un controllo ActiveX RadioButton.



**Eredità:** [`RadioButtonActiveXControl`](/cells/python-net/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol) → 
[`ToggleButtonActiveXControl`](/cells/python-net/it/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol)



Il tipo RadioButtonActiveXControl espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [workbook](/cells/python-net/it/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/workbook) |  |
| [type](/cells/python-net/it/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/type) | Ottiene il tipo di controllo ActiveX.|
| [width](/cells/python-net/it/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/width) |  |
| [height](/cells/python-net/it/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/height) |  |
| [mouse_icon](/cells/python-net/it/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/mouse_icon) |  |
| [mouse_pointer](/cells/python-net/it/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/mouse_pointer) |  |
| [fore_ole_color](/cells/python-net/it/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/fore_ole_color) |  |
| [back_ole_color](/cells/python-net/it/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/back_ole_color) |  |
| [is_visible](/cells/python-net/it/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_visible) |  |
| [shadow](/cells/python-net/it/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/shadow) |  |
| [linked_cell](/cells/python-net/it/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/linked_cell) |  |
| [list_fill_range](/cells/python-net/it/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/list_fill_range) |  |
| [data](/cells/python-net/it/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/data) |  |
| [is_enabled](/cells/python-net/it/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_enabled) |  |
| [is_locked](/cells/python-net/it/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_locked) |  |
| [is_transparent](/cells/python-net/it/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_transparent) |  |
| [is_auto_size](/cells/python-net/it/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_auto_size) |  |
| [ime_mode](/cells/python-net/it/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/ime_mode) |  |
| [font](/cells/python-net/it/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/font) |  |
| [text_align](/cells/python-net/it/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/text_align) |  |
| [caption](/cells/python-net/it/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/caption) | Ottiene e imposta il testo descrittivo che appare su un controllo.|
| [picture_position](/cells/python-net/it/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/picture_position) |Ottiene e imposta la posizione dell'immagine del controllo rispetto alla sua didascalia.|
| [special_effect](/cells/python-net/it/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/special_effect) | Ottiene e imposta l'effetto speciale del controllo.|
| [picture](/cells/python-net/it/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/picture) | Ottiene e imposta i dati dell'immagine.|
| [accelerator](/cells/python-net/it/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/accelerator) | Ottiene e imposta il tasto di scelta rapida per il controllo.|
| [value](/cells/python-net/it/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/value) | Indica se il controllo è selezionato o meno.|
| [is_triple_state](/cells/python-net/it/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_triple_state) | Indica come il controllo specificato visualizzerà i valori Null.|
| [group_name](/cells/python-net/it/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/group_name) | Ottiene e imposta il nome del gruppo.|
| [alignment](/cells/python-net/it/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/alignment) | Ottiene e imposta la posizione della didascalia rispetto al controllo.|
| [is_word_wrapped](/cells/python-net/it/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_word_wrapped) | Indica se il contenuto del controllo va automaticamente a capo alla fine di una riga.|



###  Esempio

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

###  Guarda anche
* modulo [`aspose.cells.drawing.activexcontrols`](..)
* classe [`RadioButtonActiveXControl`](/cells/python-net/it/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol)
* classe [`ToggleButtonActiveXControl`](/cells/python-net/it/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol)
