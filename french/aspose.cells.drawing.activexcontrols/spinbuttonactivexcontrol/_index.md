---
title: SpinButtonActiveXControl classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 90
url: /fr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/
is_root: false
---
##  SpinButtonActiveXControl classe
Représente le contrôle SpinButton.



**Héritage:** [`SpinButtonActiveXControl`](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol)



Le type SpinButtonActiveXControl expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [workbook](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/workbook) |  |
| [type](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/type) | Obtient le type du contrôle ActiveX.|
| [width](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/width) |  |
| [height](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/height) |  |
| [mouse_icon](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/mouse_icon) |  |
| [mouse_pointer](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/mouse_pointer) |  |
| [fore_ole_color](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/fore_ole_color) |  |
| [back_ole_color](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/back_ole_color) |  |
| [is_visible](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_visible) |  |
| [shadow](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/shadow) |  |
| [linked_cell](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/linked_cell) |  |
| [list_fill_range](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/list_fill_range) |  |
| [data](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/data) |  |
| [is_enabled](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_enabled) |  |
| [is_locked](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_locked) |  |
| [is_transparent](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_transparent) |  |
| [is_auto_size](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/is_auto_size) |  |
| [ime_mode](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/ime_mode) |  |
| [font](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/font) |  |
| [text_align](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/text_align) |  |
| [min](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/min) | Obtient et définit la valeur minimale acceptable.|
| [max](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/max) | Obtient et définit la valeur maximale acceptable.|
| [position](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/position) | Obtient et définit la valeur.|
| [small_change](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/small_change) | Obtient et définit le montant par lequel la propriété Position change|
| [orientation](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol/orientation) | Obtient et définit si le SpinButton ou la ScrollBar est orienté verticalement ou horizontalement.|



###  Exemple

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

###  Voir également
* module [`aspose.cells.drawing.activexcontrols`](..)
* classe [`SpinButtonActiveXControl`](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/spinbuttonactivexcontrol)
