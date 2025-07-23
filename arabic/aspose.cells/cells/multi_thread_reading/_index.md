---
title: multi_thread_reading عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 1220
url: /ar/aspose.cells/cells/multi_thread_reading/
is_root: false
---
##  multi_thread_reading عقار

يحصل على أو يحدد ما إذا كان نموذج بيانات الخلايا يجب أن يدعم القراءة متعددة الخيوط.
القيمة الافتراضية لهذه الخاصية هي false.

###  ملاحظات

إذا كان هناك عدة مواضيع لقراءة كائنات الصف/Cell في هذه المجموعة في نفس الوقت،
يجب تعيين هذه الخاصية على true، وإلا فقد يتم إنتاج نتيجة غير متوقعة.
قد يؤدي دعم القراءة متعددة الخيوط إلى تدهور أداء الوصول إلى كائنات Row/Cell من هذه المجموعة.
يرجى ملاحظة أن بعض الميزات لا يمكنها دعم القراءة متعددة الخيوط،
مثل تنسيق القيم (بواسطة [`Cell.string_value`](/cells/python-net/ar/aspose.cells/cell#string_value)، [`Cell.display_string_value`](/cells/python-net/ar/aspose.cells/cell#display_string_value)، وما إلى ذلك).
لذا، حتى مع تعيين هذه الخاصية على true، فما زالت واجهات برمجة التطبيقات هذه قد تعطي نتائج غير متوقعة لقراءة متعددة الخيوط.
###  تعريف:
```python
@property
def multi_thread_reading(self):
    ...
@multi_thread_reading.setter
def multi_thread_reading(self, value):
    ...
```

###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Cells`](/cells/python-net/ar/aspose.cells/cells)
