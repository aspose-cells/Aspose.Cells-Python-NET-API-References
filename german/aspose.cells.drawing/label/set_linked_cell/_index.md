---
title: set_linked_cell Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 210
url: /de/aspose.cells.drawing/label/set_linked_cell/
is_root: false
---
##  set_linked_cell(self, formula, is_r1c1, is_local) {#str-bool-bool}
Legt den mit dem Wert des Steuerelements verknüpften Bereich fest.



```python

def set_linked_cell(self, formula, is_r1c1, is_local):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| formula | str | Der mit dem Wert des Steuerelements verknüpfte Bereich.|
| is_r1c1 | bool | Ob die Formel als R1C1 formatiert werden muss.|
| is_local | bool | Ob die Formel nach Gebietsschema formatiert werden muss.|

###  Beispiel

```python

# After executing the code below, a ScrollBar object is created in the generated file. As you drag the slider, the value is displayed in cell A12.
# ActiveX Controls
# Aspose.Cells.Drawing.Shape scrollBar = book.Worksheets[0].Shapes.AddActiveXControl( Aspose.Cells.Drawing.ActiveXControls.ControlType.ScrollBar,2, 0, 2, 0, 30, 130);
# Form Controls
scrollBar = book.worksheets[0].shapes.add_scroll_bar(2, 0, 2, 0, 130, 30)
# Sets the range linked to the control's value.
scrollBar.set_linked_cell("$A$12", False, True)

```



###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`Label`](/cells/python-net/de/aspose.cells.drawing/label)
