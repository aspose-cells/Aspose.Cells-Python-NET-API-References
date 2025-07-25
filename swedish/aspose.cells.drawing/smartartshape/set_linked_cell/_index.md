---
title: set_linked_cell metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 210
url: /sv/aspose.cells.drawing/smartartshape/set_linked_cell/
is_root: false
---
##  set_linked_cell(self, formula, is_r1c1, is_local) {#str-bool-bool}
Anger intervallet som är kopplat till kontrollens värde.



```python

def set_linked_cell(self, formula, is_r1c1, is_local):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| formula | str | Intervallet som är kopplat till kontrollens värde.|
| is_r1c1 | bool | Om formeln behöver formateras som R1C1.|
| is_local | bool | Om formeln behöver formateras efter språkinställning.|

###  Exempel

```python

# After executing the code below, a ScrollBar object is created in the generated file. As you drag the slider, the value is displayed in cell A12.
# ActiveX Controls
# Aspose.Cells.Drawing.Shape scrollBar = book.Worksheets[0].Shapes.AddActiveXControl( Aspose.Cells.Drawing.ActiveXControls.ControlType.ScrollBar,2, 0, 2, 0, 30, 130);
# Form Controls
scrollBar = book.worksheets[0].shapes.add_scroll_bar(2, 0, 2, 0, 130, 30)
# Sets the range linked to the control's value.
scrollBar.set_linked_cell("$A$12", False, True)

```



###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`SmartArtShape`](/cells/python-net/sv/aspose.cells.drawing/smartartshape)
