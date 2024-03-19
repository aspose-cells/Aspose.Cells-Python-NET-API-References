---
title: default_style عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 550
url: /ar/aspose.cells/workbook/default_style/
is_root: false
---
##  default_style عقار

الحصول على الكائن الافتراضي [`Style`](/cells/python-net/ar/aspose.cells/style) للمصنف أو تعيينه.

###  ملاحظات

تعتبر الخاصية DefaultStyle مفيدة لتطبيق نمط للمصنف بأكمله.

###  مثال

يقوم التعليمة البرمجية التالية بإنشاء مصنف جديد وإنشاء مثيل له وتعيين الإعداد الافتراضي له [`Style`](/cells/python-net/ar/aspose.cells/style).

```python
from aspose.cells import Workbook

workbook = Workbook()
defaultStyle = workbook.default_style
defaultStyle.font.name = "Tahoma"
workbook.default_style = defaultStyle

```
###  تعريف:
```python
@property
def default_style(self):
    ...
@default_style.setter
def default_style(self, value):
    ...
```

###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Style`](/cells/python-net/ar/aspose.cells/style)
* فئة [`Workbook`](/cells/python-net/ar/aspose.cells/workbook)
