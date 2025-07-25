---
title: provider_id عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 80
url: /ar/aspose.cells.drawing/signatureline/provider_id/
is_root: false
---
##  provider_id عقار

يحصل على معرف مزود التوقيع أو يعينه.

###  ملاحظات

إنه عادةً CLSID للوظيفة الإضافية لمزود الخدمة.

###  مثال

```python
from aspose.cells.drawing import SignatureLine
from uuid import uuid4

#  Create signature line object
s2 = SignatureLine()
s2.provider_id = uuid4("xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx")

```
###  تعريف:
```python
@property
def provider_id(self):
    ...
@provider_id.setter
def provider_id(self, value):
    ...
```

###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](../../)
* فئة [`SignatureLine`](/cells/python-net/ar/aspose.cells.drawing/signatureline)
