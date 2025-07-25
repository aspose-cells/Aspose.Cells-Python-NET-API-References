---
title: default_style عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 580
url: /ar/aspose.cells/workbook/default_style/
is_root: false
---
##  default_style عقار

يحصل على أو يعين الكائن الافتراضي [`Style`](/cells/python-net/ar/aspose.cells/style) للمصنف.

###  ملاحظات

تعتبر خاصية DefaultStyle مفيدة لتنفيذ نمط للمصنف بأكمله.

###  مثال

يقوم الكود التالي بإنشاء مصنف جديد وتشغيله وتعيين القيمة الافتراضية [`Style`](/cells/python-net/ar/aspose.cells/style) له.

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
