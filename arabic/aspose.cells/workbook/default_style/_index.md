---
title: default_style الملكية
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 540
url: /ar/aspose.cells/workbook/default_style/
is_root: false
---
##  default_style الملكية

الحصول على أو تعيين الكائن الافتراضي [Style](/cells/python-net/ar/aspose.cells/style) للمصنف.

###  ملاحظات

تعتبر الخاصية DefaultStyle مفيدة في تنفيذ نمط للمصنف بأكمله.

###  مثال

تقوم التعليمة البرمجية التالية بإنشاء وإنشاء مصنف جديد وتعيين [Style](/cells/python-net/ar/aspose.cells/style) افتراضيًا إليه.

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
* وحدة [aspose.cells](../../)
* فئة [Style](/cells/python-net/ar/aspose.cells/style)
* فئة [Workbook](/cells/python-net/ar/aspose.cells/workbook)
