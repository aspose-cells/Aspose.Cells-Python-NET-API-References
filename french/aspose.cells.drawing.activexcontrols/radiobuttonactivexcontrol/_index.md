---
title: RadioButtonActiveXControl classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 70
url: /fr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/
is_root: false
---
##  RadioButtonActiveXControl classe
Représente un contrôle ActiveX RadioButton.



**Héritage:** [`RadioButtonActiveXControl`](/cells/python-net/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol) → 
[`ToggleButtonActiveXControl`](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol)



Le type RadioButtonActiveXControl expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [workbook](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/workbook) |  |
| [type](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/type) | Obtient le type du contrôle ActiveX.|
| [width](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/width) |  |
| [height](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/height) |  |
| [mouse_icon](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/mouse_icon) |  |
| [mouse_pointer](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/mouse_pointer) |  |
| [fore_ole_color](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/fore_ole_color) |  |
| [back_ole_color](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/back_ole_color) |  |
| [is_visible](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_visible) |  |
| [shadow](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/shadow) |  |
| [linked_cell](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/linked_cell) |  |
| [list_fill_range](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/list_fill_range) |  |
| [data](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/data) |  |
| [is_enabled](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_enabled) |  |
| [is_locked](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_locked) |  |
| [is_transparent](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_transparent) |  |
| [is_auto_size](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_auto_size) |  |
| [ime_mode](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/ime_mode) |  |
| [font](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/font) |  |
| [text_align](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/text_align) |  |
| [caption](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/caption) | Obtient et définit le texte descriptif qui apparaît sur un contrôle.|
| [picture_position](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/picture_position) |Obtient et définit l'emplacement de l'image du contrôle par rapport à sa légende.|
| [special_effect](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/special_effect) | Obtient et définit l'effet spécial du contrôle.|
| [picture](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/picture) | Obtient et définit les données de l'image.|
| [accelerator](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/accelerator) | Obtient et définit la touche d'accélérateur pour le contrôle.|
| [value](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/value) | Indique si le contrôle est coché ou non.|
| [is_triple_state](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_triple_state) | Indique comment le contrôle spécifié affichera les valeurs Null.|
| [group_name](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/group_name) | Obtient et définit le nom du groupe.|
| [alignment](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/alignment) | Obtient et définit la position de la légende par rapport au contrôle.|
| [is_word_wrapped](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol/is_word_wrapped) | Indique si le contenu du contrôle s'enroule automatiquement à la fin d'une ligne.|



###  Exemple

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

###  Voir également
* module [`aspose.cells.drawing.activexcontrols`](..)
* classe [`RadioButtonActiveXControl`](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/radiobuttonactivexcontrol)
* classe [`ToggleButtonActiveXControl`](/cells/python-net/fr/aspose.cells.drawing.activexcontrols/togglebuttonactivexcontrol)
