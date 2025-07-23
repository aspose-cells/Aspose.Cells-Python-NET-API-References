---
title: طريقة get_linked_cell
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 120
url: /ar/aspose.cells.drawing/dialogbox/get_linked_cell/
is_root: false
---
##  get_linked_cell(self, is_r1c1, is_local) {#bool-bool}
يحصل على النطاق المرتبط بقيمة عنصر التحكم.


###  عائدات

النطاق المرتبط بقيمة عنصر التحكم.


```python

def get_linked_cell(self, is_r1c1, is_local):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| is_r1c1 | bool | ما إذا كانت الصيغة تحتاج إلى تنسيقها كـ R1C1.|
| is_local | bool | ما إذا كانت الصيغة تحتاج إلى تنسيق حسب الإعدادات المحلية.|

###  مثال

```python

# You may get results like '$A$1'
link = shape.get_linked_cell(False, False)

```



###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](../../)
* فئة [`DialogBox`](/cells/python-net/ar/aspose.cells.drawing/dialogbox)
