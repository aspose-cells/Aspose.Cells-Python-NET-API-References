---
title: is_locked عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 630
url: /ar/aspose.cells.drawing/commentshape/is_locked/
is_root: false
---
##  is_locked عقار

 صحيح يعني أنه لا يمكن تعديل الكائن عندما تكون الورقة محمية.
لاحظ أن هذه القيمة لها معنى فقط إذا كانت ورقة العمل أو الكائنات الموجودة في ورقة العمل محمية.

###  مثال

```python

# Sets the specified shape to unlocked state
if shape.worksheet.is_protected and shape.is_locked:
    shape.is_locked = False
# Sets the specified shape to a locked state
if shape.worksheet.is_protected and notshape.is_locked:
    shape.is_locked = True

```
###  تعريف:
```python
@property
def is_locked(self):
    ...
@is_locked.setter
def is_locked(self, value):
    ...
```

###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](../../)
* فئة [`CommentShape`](/cells/python-net/ar/aspose.cells.drawing/commentshape)
