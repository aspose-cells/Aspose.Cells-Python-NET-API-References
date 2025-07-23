---
title: look_at_type عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 90
url: /ar/aspose.cells/findoptions/look_at_type/
is_root: false
---
##  look_at_type عقار

أنظر إلى النوع.

###  ملاحظات

عندما يكون [`FindOptions.regex_key`](/cells/python-net/ar/aspose.cells/findoptions#regex_key) صحيحًا وقد حدد المستخدم القاعدة الدقيقة للتعبير العادي،
من أجل مراعاة الأداء، يجب تعيين هذه الخاصية على [`LookAtType.ENTIRE_CONTENT`](/cells/python-net/ar/aspose.cells/lookattype#ENTIRE_CONTENT).
وإلا فسوف نقوم بإعادة تصميم مفتاح البحث للتأكد من إمكانية مطابقته وفقًا للنوع المحدد.
على سبيل المثال، عندما يكون النوع هو [`LookAtType.CONTAINS`](/cells/python-net/ar/aspose.cells/lookattype#CONTAINS) (هذه هي القيمة الافتراضية لهذه الخاصية)،
سوف نقوم بإضافة أحرف البدل في بداية ونهاية مفتاح البحث تلقائيًا.
في هذه الحالة، ستصبح التعبيرات العادية أكثر تعقيدًا وسيقل الأداء أيضًا.
###  تعريف:
```python
@property
def look_at_type(self):
    ...
@look_at_type.setter
def look_at_type(self, value):
    ...
```

###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`FindOptions`](/cells/python-net/ar/aspose.cells/findoptions)
* فئة [`LookAtType`](/cells/python-net/ar/aspose.cells/lookattype)
