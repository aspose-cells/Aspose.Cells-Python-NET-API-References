---
title: Metodo set_input_range
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 210
url: /it/aspose.cells.drawing/listbox/set_input_range/
is_root: false
---
##  set_input_range {#str-bool-bool}
Imposta l'intervallo utilizzato per riempire il controllo.



```python
def set_input_range(self, formula, is_r1c1, is_local):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| formula | str | L'intervallo utilizzato per riempire il controllo.|
| is_r1c1 | bool | Se la formula deve essere formattata come R1C1.|
| is_local | bool | Indica se la formula deve essere formattata in base alle impostazioni locali.|

###  Esempio

```python

# After executing the code below, a ListBox object is created in the generated file. When the selected option is clicked, the selected value is displayed in cell A12.
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

```



###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`ListBox`](/cells/python-net/it/aspose.cells.drawing/listbox)
