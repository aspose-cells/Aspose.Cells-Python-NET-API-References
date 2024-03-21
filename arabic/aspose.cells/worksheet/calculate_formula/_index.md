---
title: طريقة calculate_formula
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 90
url: /ar/aspose.cells/worksheet/calculate_formula/
is_root: false
---
##  calculate_formula {#str}
يحسب صيغة.


###  عائدات

نتيجة الصيغة المحسوبة.


```python
def calculate_formula(self, formula):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| formula | str | الصيغة التي سيتم حسابها.|


##  calculate_formula {#str-aspose.cells.CalculationOptions}
حساب تعبير الصيغة مباشرة.


###  عائدات

النتيجة المحسوبة للصيغة المحددة.
قد يكون الكائن الذي تم إرجاعه من الأنواع المحتملة [`Cell.value`](/cells/python-net/ar/aspose.cells/cell#value) أو المنطقة المرجعية.


```python
def calculate_formula(self, formula, opts):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| formula | str | الصيغة التي سيتم حسابها.|
| opts | [`CalculationOptions`](/cells/python-net/ar/aspose.cells/calculationoptions) | خيارات لحساب الصيغة|
###  ملاحظات

سيتم حساب الصيغة تمامًا كما تم تعيينها على الخلية A1.
وسيتم أخذ الصيغة كصيغة عادية.
إذا كنت تريد حساب الصيغة كصيغة صفيف والحصول على صفيف للنتيجة المحسوبة،
الرجاء استخدام [`Worksheet.calculate_array_formula`](/cells/python-net/ar/aspose.cells/worksheet/calculate_array_formula) بدلا من ذلك.

##  calculate_formula {#aspose.cells.CalculationOptions-bool}
حساب كافة الصيغ في ورقة العمل هذه.



```python
def calculate_formula(self, options, recursive):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| options | [`CalculationOptions`](/cells/python-net/ar/aspose.cells/calculationoptions) | خيارات للحساب|
| recursive | bool | صحيح يعني أنه إذا كانت خلايا ورقة العمل تعتمد على خلايا أوراق العمل الأخرى،<br/>سيتم حساب الخلايا التابعة في أوراق العمل الأخرى أيضًا.<br/> "خطأ" يعني أن جميع الصيغ الموجودة في ورقة العمل قد تم حسابها وأن القيم صحيحة.|


##  calculate_formula {#str-aspose.cells.FormulaParseOptions-aspose.cells.CalculationOptions-int-int-aspose.cells.CalculationData}
حساب تعبير الصيغة مباشرة.


###  عائدات

النتيجة المحسوبة للصيغة المحددة.
قد يكون الكائن الذي تم إرجاعه من الأنواع المحتملة [`Cell.value`](/cells/python-net/ar/aspose.cells/cell#value) أو المنطقة المرجعية.


```python
def calculate_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, calculation_data):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| formula | str | الصيغة التي سيتم حسابها.|
| p_opts | [`FormulaParseOptions`](/cells/python-net/ar/aspose.cells/formulaparseoptions) | خيارات لتحليل الصيغة.|
| c_opts | [`CalculationOptions`](/cells/python-net/ar/aspose.cells/calculationoptions) | خيارات لحساب الصيغة.|
| base_cell_row | int | فهرس صف الخلية الأساسية.|
| base_cell_column | int | فهرس العمود للخلية الأساسية.|
| calculation_data | [`CalculationData`](/cells/python-net/ar/aspose.cells/calculationdata) | بيانات الحساب. يتم استخدامه للحالة<br/>يحتاج هذا المستخدم إلى حساب بعض الصيغ الثابتة عند تنفيذ محرك الحساب المخصص.<br/>لمثل هذا النوع من الحالات، يحتاج المستخدم إلى تحديده باستخدام بيانات الحساب المقدمة<br/> ل [`AbstractCalculationEngine.calculate`](/cells/python-net/ar/aspose.cells/abstractcalculationengine/calculate).|
###  ملاحظات

سيتم حساب الصيغة تمامًا كما تم تعيينها على الخلية الأساسية المحددة.
وسيتم أخذ الصيغة كصيغة عادية. إذا كنت بحاجة إلى حساب الصيغة كصيغة صفيف
وللحصول على مصفوفة للنتيجة المحسوبة، يرجى استخدامها
[`Worksheet.calculate_array_formula`](/cells/python-net/ar/aspose.cells/worksheet/calculate_array_formula) بدلا من ذلك.


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Worksheet`](/cells/python-net/ar/aspose.cells/worksheet)
