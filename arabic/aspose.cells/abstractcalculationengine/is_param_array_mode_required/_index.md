---
title: is_param_array_mode_required عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 40
url: /ar/aspose.cells/abstractcalculationengine/is_param_array_mode_required/
is_root: false
---
##  is_param_array_mode_required عقار

يشير إلى ما إذا كان هذا المحرك يحتاج إلى المعلمة التي سيتم حسابها في وضع الصفيف. القيمة الافتراضية خاطئة.
إذا كان [`CalculationData.get_param_value_in_array_mode`](/cells/python-net/ar/aspose.cells/calculationdata/get_param_value_in_array_mode) مطلوبًا عند حساب العرف
الوظائف ولم يقم المستخدم بتحديث التعريف الخاص بها
(بواسطة [`Workbook.update_custom_function_definition`](/cells/python-net/ar/aspose.cells/workbook/update_custom_function_definition))،
يجب تعيين هذه الخاصية على أنها صحيحة.

###  ملاحظات

إذا كان محرك الحساب المخصص هذا يحتاج إلى حساب المعلمة في وضع الصفيف،
ستكون هناك حاجة إلى المزيد من الأكوام لتخزين الشجرة مؤقتًا للمعلمات
ويمكن استدعاء طريقة الحساب () بشكل متكرر لحساب قيمة المعلمة.
لاعتبارات الأداء، يرجى الاحتفاظ بهذه الخاصية كقيمة افتراضية (خطأ)
إذا لم يكن هناك شرط خاص.
###  تعريف:
```python
@property
def is_param_array_mode_required(self):
    ...
```

###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`AbstractCalculationEngine`](/cells/python-net/ar/aspose.cells/abstractcalculationengine)
