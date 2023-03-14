---
title: طريقة calculate_formula
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 80
url: /ar/aspose.cells/worksheet/calculate_formula/
is_root: false
---
##  calculate_formula(formula) {#str}
تحسب صيغة.


###  عائدات

نتيجة الصيغة المحسوبة.


```python
def calculate_formula(self, formula):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| formula | str | الصيغة المطلوب حسابها.|


##  calculate_formula(formula, opts) {#str-CalculationOptions}
تحسب صيغة.


###  عائدات

نتيجة الصيغة المحسوبة.


```python
def calculate_formula(self, formula, opts):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| formula | str | الصيغة المطلوب حسابها.|
| opts | [CalculationOptions](/cells/python-net/ar/aspose.cells/calculationoptions) | خيارات لحساب الصيغة|


##  calculate_formula(options, recursive) {#CalculationOptions-bool}
تحسب جميع الصيغ في ورقة العمل هذه.



```python
def calculate_formula(self, options, recursive):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| options | [CalculationOptions](/cells/python-net/ar/aspose.cells/calculationoptions) | خيارات الحساب|
| recursive | bool | يعني صحيح إذا كانت خلايا ورقة العمل تعتمد على خلايا أوراق العمل الأخرى ،<br/>سيتم حساب الخلايا التابعة في أوراق العمل الأخرى أيضًا.<br/> خطأ يعني أن جميع الصيغ في ورقة العمل قد تم حسابها وأن القيم صحيحة.|


##  calculate_formula(recursive, ignore_error, custom_function) {#bool-bool-ICustomFunction}
تحسب جميع الصيغ في ورقة العمل هذه.



```python
def calculate_formula(self, recursive, ignore_error, custom_function):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| recursive | bool | يعني صحيح إذا كانت خلايا ورقة العمل تعتمد على خلايا أوراق العمل الأخرى ،<br/>سيتم حساب الخلايا التابعة في أوراق العمل الأخرى أيضًا.<br/> خطأ يعني أن جميع الصيغ في ورقة العمل قد تم حسابها وأن القيم صحيحة.|
| ignore_error | bool | يشير إلى إخفاء الخطأ في حساب الصيغ.<br/> قد يكون الخطأ وظيفة غير مدعومة ، أو روابط خارجية ، إلخ.|
| custom_function | [ICustomFunction](/cells/python-net/ar/aspose.cells/icustomfunction) | وظائف حساب الصيغة المخصصة لتوسيع محرك الحساب.|
###  ملاحظات

ملاحظة: هذا العضو قد عفا عليه الزمن الآن. بدلاً من،
الرجاء استخدام طريقة CalculateFormula (CalculationOptions، Bool).
 ستتم إزالة هذه الطريقة بعد 12 شهرًا منذ أغسطس 2020.
Aspose يعتذر عن أي إزعاج قد يكون سببه لك.


###  أنظر أيضا
* وحدة [aspose.cells](../../)
* فئة [Worksheet](/cells/python-net/ar/aspose.cells/worksheet)
