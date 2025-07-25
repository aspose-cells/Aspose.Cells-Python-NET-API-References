---
title: طريقة set_linked_cell
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 210
url: /ar/aspose.cells.drawing/oval/set_linked_cell/
is_root: false
---
##  set_linked_cell(self, formula, is_r1c1, is_local) {#str-bool-bool}
تعيين النطاق المرتبط بقيمة عنصر التحكم.



```python

def set_linked_cell(self, formula, is_r1c1, is_local):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| formula | str | النطاق المرتبط بقيمة عنصر التحكم.|
| is_r1c1 | bool | ما إذا كانت الصيغة تحتاج إلى تنسيقها كـ R1C1.|
| is_local | bool | ما إذا كانت الصيغة تحتاج إلى تنسيق حسب الإعدادات المحلية.|

###  مثال

```python

# After executing the code below, a ScrollBar object is created in the generated file. As you drag the slider, the value is displayed in cell A12.
# ActiveX Controls
# Aspose.Cells.Drawing.Shape scrollBar = book.Worksheets[0].Shapes.AddActiveXControl( Aspose.Cells.Drawing.ActiveXControls.ControlType.ScrollBar,2, 0, 2, 0, 30, 130);
# Form Controls
scrollBar = book.worksheets[0].shapes.add_scroll_bar(2, 0, 2, 0, 130, 30)
# Sets the range linked to the control's value.
scrollBar.set_linked_cell("$A$12", False, True)

```



###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](../../)
* فئة [`Oval`](/cells/python-net/ar/aspose.cells.drawing/oval)
