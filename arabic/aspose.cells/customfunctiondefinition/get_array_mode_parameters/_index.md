---
title: طريقة get_array_mode_parameters
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 20
url: /ar/aspose.cells/customfunctiondefinition/get_array_mode_parameters/
is_root: false
---
##  get_array_mode_parameters {#str}
الحصول على مؤشرات معلمات الوظيفة المخصصة المحددة التي يجب حسابها في وضع الصفيف.


###  عائدات

مؤشرات المعلمات التي يجب حسابها في وضع الصفيف لوظيفة مخصصة معينة.
الإعداد الافتراضي فارغ، ولا توجد معلمة يلزم حسابها في وضع الصفيف للوظيفة المخصصة.


```python
def get_array_mode_parameters(self, function_name):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| function_name | str | اسم الوظيفة المخصصة.|
###  ملاحظات

بالنسبة للتعبير الذي يحتاج إلى حساب، مع أخذ A:A+B:B كمثال:
بشكل عام، في وضع القيمة، سيتم حسابه بقيمة واحدة وفقًا لقاعدة الخلية الحالية.
ولكن في وضع المصفوفة، سيتم حساب كافة قيم A1+B1،A2+B2،A3+B3،... واستخدامها في الحساب.


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`CustomFunctionDefinition`](/cells/python-net/ar/aspose.cells/customfunctiondefinition)
