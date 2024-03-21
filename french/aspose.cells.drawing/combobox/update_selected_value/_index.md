---
title: méthode update_selected_value
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 240
url: /fr/aspose.cells.drawing/combobox/update_selected_value/
is_root: false
---
##  update_selected_value {#}
Mettez à jour la valeur sélectionnée par la valeur de la cellule liée.



```python
def update_selected_value(self):
    ...
```



###  Exemple

```python
from aspose import pycore
from aspose.cells.drawing import ListBox

cell = None
for i in range(10):
    cell = book.worksheets[0].cells.get(i, 0)
    cell.value = i + 1
# Create a ListBox object
# ActiveX Controls
# Aspose.Cells.Drawing.Shape listBox = book.Worksheets[0].Shapes.AddActiveXControl( Aspose.Cells.Drawing.ActiveXControls.ControlType.ListBox,2, 0, 2, 0, 130, 130);
# Form Controls
listBox = book.worksheets[0].shapes.add_list_box(2, 0, 2, 0, 130, 130)
# Sets the range used to fill the control.
listBox.set_input_range("$A$1:$A$6", False, False)
# Sets the range linked to the control's value.
listBox.set_linked_cell("$A$12", False, True)
listbx = pycore.cast(ListBox, listBox)
# Set the value of cell A12
cell = book.worksheets[0].cells.get(11, 0)
cell.value = 3
# Update the selected value by the value of the linked cell.
listBox.update_selected_value()
# -1 default, no option selected
if listbx.is_selected(2):
    pass
# Change the value of a linked cell
cell.value = 4
# Update the selected value by the value of the linked cell.
listBox.update_selected_value()
if listbx.is_selected(3):
    pass

```



###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`ComboBox`](/cells/python-net/fr/aspose.cells.drawing/combobox)
