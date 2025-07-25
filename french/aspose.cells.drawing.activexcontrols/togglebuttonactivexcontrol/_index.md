---
title: ToggleButtonActiveXControl classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 110
url: /fr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/
is_root: false
---
##  ToggleButtonActiveXControl classe
Représente un contrôle ActiveX ToggleButton.



**Héritage:** [`ToggleButtonActiveXControl`](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol)



Le type ToggleButtonActiveXControl expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [workbook](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/workbook) |  |
| [type](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/type) | Obtient le type du contrôle ActiveX.|
| [width](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/width) |  |
| [height](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/height) |  |
| [mouse_icon](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/mouse_icon) |  |
| [mouse_pointer](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/mouse_pointer) |  |
| [fore_ole_color](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/fore_ole_color) |  |
| [back_ole_color](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/back_ole_color) |  |
| [is_visible](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_visible) |  |
| [shadow](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/shadow) |  |
| [linked_cell](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/linked_cell) |  |
| [list_fill_range](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/list_fill_range) |  |
| [data](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/data) |  |
| [is_enabled](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_enabled) |  |
| [is_locked](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_locked) |  |
| [is_transparent](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_transparent) |  |
| [is_auto_size](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_auto_size) |  |
| [ime_mode](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/ime_mode) |  |
| [font](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/font) |  |
| [text_align](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/text_align) |  |
| [caption](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/caption) | Obtient et définit le texte descriptif qui apparaît sur un contrôle.|
| [picture_position](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/picture_position) |Obtient et définit l'emplacement de l'image du contrôle par rapport à sa légende.|
| [special_effect](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/special_effect) | Obtient et définit l'effet spécial du contrôle.|
| [picture](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/picture) | Obtient et définit les données de l'image.|
| [accelerator](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/accelerator) | Obtient et définit la touche d'accélérateur pour le contrôle.|
| [value](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/value) | Indique si le contrôle est coché ou non.|
| [is_triple_state](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol/is_triple_state) | Indique comment le contrôle spécifié affichera les valeurs Null.|



###  Exemple

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

###  Voir également
* module [`aspose.cells.drawing.activexcontrols`](..)
* classe [`ToggleButtonActiveXControl`](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol)
