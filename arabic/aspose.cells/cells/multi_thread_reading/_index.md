---
title: multi_thread_reading عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 1190
url: /ar/aspose.cells/cells/multi_thread_reading/
is_root: false
---
##  multi_thread_reading عقار

الحصول على أو تعيين ما إذا كان نموذج بيانات الخلايا يجب أن يدعم قراءة الخيوط المتعددة.
القيمة الافتراضية لهذه الخاصية خاطئة.

###  ملاحظات

إذا كان هناك عدة سلاسل رسائل لقراءة كائنات الصف/Cell في هذه المجموعة بشكل متزامن،
يجب تعيين هذه الخاصية على أنها صحيحة، وإلا قد تظهر نتيجة غير متوقعة.
قد يؤدي دعم القراءة متعددة الخيوط إلى انخفاض أداء الوصول إلى كائنات الصف/Cell من هذه المجموعة.
يرجى ملاحظة أن بعض الميزات لا يمكن أن تدعم قراءة الخيوط المتعددة،
مثل قيم التنسيق (بواسطة [`Cell.string_value`](/cells/python-net/ar/aspose.cells/cell#string_value)، [`Cell.display_string_value`](/cells/python-net/ar/aspose.cells/cell#display_string_value)، الخ).
لذلك، حتى مع تعيين هذه الخاصية على أنها صحيحة، فإن واجهات برمجة التطبيقات هذه لا تزال قد تعطي نتائج غير متوقعة لقراءة الخيوط المتعددة.
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
