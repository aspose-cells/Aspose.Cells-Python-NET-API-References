---
title: طريقة get_array_mode_parameters
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 20
url: /ar/aspose.cells/customfunctiondefinition/get_array_mode_parameters/
is_root: false
---
##  get_array_mode_parameters(self, function_name) {#str}
يحصل على مؤشرات معلمات الوظيفة المخصصة المحددة التي يجب حسابها في وضع المصفوفة.


###  عائدات

مؤشرات المعلمات التي يجب حسابها في وضع المصفوفة لوظيفة مخصصة معينة.
الإعداد الافتراضي هو null، ولا يوجد معلمة تحتاج إلى حسابها في وضع المصفوفة للوظيفة المخصصة.


```python

def get_array_mode_parameters(self, function_name):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| function_name | str | اسم الوظيفة المخصصة.|
###  ملاحظات

بالنسبة للتعبير الذي يحتاج إلى حساب، خذ A:A+B:B كمثال:
بشكل عام، في وضع القيمة، سيتم حسابه إلى قيمة واحدة وفقًا لقاعدة الخلية الحالية.
ولكن في وضع المصفوفة، سيتم حساب جميع قيم A1+B1،A2+B2،A3+B3،... واستخدامها في الحساب.


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`CustomFunctionDefinition`](/cells/python-net/ar/aspose.cells/customfunctiondefinition)
