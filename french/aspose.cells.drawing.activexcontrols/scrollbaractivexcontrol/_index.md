---
title: ScrollBarActiveXControl classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 80
url: /fr/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/
is_root: false
---
##  ScrollBarActiveXControl classe
Représente le contrôle ScrollBar.



**Héritage:** [`ScrollBarActiveXControl`](/cells/python-net/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol) → 
[`SpinButtonActiveXControl`](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol)



Le type ScrollBarActiveXControl expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [workbook](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/workbook) |  |
| [type](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/type) | Obtient le type du contrôle ActiveX.|
| [width](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/width) |  |
| [height](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/height) |  |
| [mouse_icon](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/mouse_icon) |  |
| [mouse_pointer](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/mouse_pointer) |  |
| [fore_ole_color](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/fore_ole_color) |  |
| [back_ole_color](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/back_ole_color) |  |
| [is_visible](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_visible) |  |
| [shadow](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/shadow) |  |
| [linked_cell](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/linked_cell) |  |
| [list_fill_range](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/list_fill_range) |  |
| [data](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/data) |  |
| [is_enabled](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_enabled) |  |
| [is_locked](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_locked) |  |
| [is_transparent](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_transparent) |  |
| [is_auto_size](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/is_auto_size) |  |
| [ime_mode](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/ime_mode) |  |
| [font](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/font) |  |
| [text_align](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/text_align) |  |
| [min](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/min) | Obtient et définit la valeur minimale acceptable.|
| [max](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/max) | Obtient et définit la valeur maximale acceptable.|
| [position](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/position) | Obtient et définit la valeur.|
| [small_change](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/small_change) | Obtient et définit le montant par lequel la propriété Position change|
| [orientation](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/orientation) | Obtient et définit si le SpinButton ou la ScrollBar est orienté verticalement ou horizontalement.|
| [large_change](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol/large_change) | Obtient et définit le montant par lequel la propriété Position change|



###  Exemple

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

###  Voir également
* module [`aspose.cells.drawing.activexcontrols`](..)
* classe [`ScrollBarActiveXControl`](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/scrollbaractivexcontrol)
* classe [`SpinButtonActiveXControl`](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol)
