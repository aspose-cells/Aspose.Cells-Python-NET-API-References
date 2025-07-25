---
title: auto_size عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 80
url: /ar/aspose.cells/comment/auto_size/
is_root: false
---
##  auto_size عقار

يشير إلى ما إذا كان حجم التعليق يتم تعديله تلقائيًا وفقًا لمحتواه.
ملاحظة: في بعض الحالات الخاصة (مثل بيئة ماك)، قد لا يُفعّل هذا الإعداد. إذا لم يُفعّل، يُرجى استبداله بـ FitToTextSize().

###  مثال

```python

if notcomment1.auto_size:
    # The size of the comment varies with the content
    comment1.auto_size = True

```
###  تعريف:
```python
@property
def auto_size(self):
    ...
@auto_size.setter
def auto_size(self, value):
    ...
```

###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Comment`](/cells/python-net/ar/aspose.cells/comment)
