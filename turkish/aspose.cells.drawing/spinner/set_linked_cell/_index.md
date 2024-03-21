---
title: set_linked_cell yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 200
url: /tr/aspose.cells.drawing/spinner/set_linked_cell/
is_root: false
---
##  set_linked_cell {#str-bool-bool}
Denetimin değerine bağlı aralığı ayarlar.



```python
def set_linked_cell(self, formula, is_r1c1, is_local):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| formula | str | Denetimin değerine bağlı aralık.|
| is_r1c1 | bool | Formülün R1C1 olarak biçimlendirilmesi gerekip gerekmediği.|
| is_local | bool | Formülün yerel ayara göre biçimlendirilmesi gerekip gerekmediği.|

###  Örnek

```python

# After executing the code below, a ScrollBar object is created in the generated file. As you drag the slider, the value is displayed in cell A12.
# ActiveX Controls
# Aspose.Cells.Drawing.Shape scrollBar = book.Worksheets[0].Shapes.AddActiveXControl( Aspose.Cells.Drawing.ActiveXControls.ControlType.ScrollBar,2, 0, 2, 0, 30, 130);
# Form Controls
scrollBar = book.worksheets[0].shapes.add_scroll_bar(2, 0, 2, 0, 130, 30)
# Sets the range linked to the control's value.
scrollBar.set_linked_cell("$A$12", False, True)

```



###  Ayrıca bakınız
* modül [`aspose.cells.drawing`](../../)
* sınıf [`Spinner`](/cells/python-net/tr/aspose.cells.drawing/spinner)
