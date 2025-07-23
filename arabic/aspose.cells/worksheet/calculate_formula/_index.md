---
title: طريقة calculate_formula
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 90
url: /ar/aspose.cells/worksheet/calculate_formula/
is_root: false
---
##  calculate_formula(self, formula) {#str}
يحسب الصيغة.


###  عائدات

نتيجة الصيغة المحسوبة.


```python

def calculate_formula(self, formula):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| formula | str | الصيغة المراد حسابها.|


##  calculate_formula(self, formula, opts) {#str-aspose.cells.CalculationOptions}
يحسب تعبير الصيغة بشكل مباشر.


###  عائدات

النتيجة المحسوبة للصيغة المعطاة.
من الممكن أن يكون الكائن المرتجع من الأنواع التالية: [`Cell.value`](/cells/python-net/ar/aspose.cells/cell#value)، أو ReferredArea.


```python

def calculate_formula(self, formula, opts):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| formula | str | الصيغة المراد حسابها.|
| opts | [`CalculationOptions`](/cells/python-net/ar/aspose.cells/calculationoptions) | خيارات لحساب الصيغة|
###  ملاحظات

سيتم حساب الصيغة كما تم تعيينها للخلية A1.
وسوف تؤخذ الصيغة كالصيغة العادية.
إذا كنت تريد أن يتم حساب الصيغة كصيغة مصفوفة والحصول على مصفوفة للنتيجة المحسوبة،
من فضلك استخدم [`Worksheet.calculate_array_formula`](/cells/python-net/ar/aspose.cells/worksheet/calculate_array_formula) بدلا من ذلك.

##  calculate_formula(self, options, recursive) {#aspose.cells.CalculationOptions-bool}
يحسب جميع الصيغ في ورقة العمل هذه.



```python

def calculate_formula(self, options, recursive):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| options | [`CalculationOptions`](/cells/python-net/ar/aspose.cells/calculationoptions) | خيارات الحساب|
| recursive | bool | صحيح يعني إذا كانت خلايا ورقة العمل تعتمد على خلايا أوراق عمل أخرى،<br/>سيتم حساب الخلايا التابعة في أوراق العمل الأخرى أيضًا.<br/> تعني كلمة "خطأ" أن جميع الصيغ في ورقة العمل تم حسابها وأن القيم صحيحة.|


##  calculate_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, calculation_data) {#str-aspose.cells.FormulaParseOptions-aspose.cells.CalculationOptions-int-int-aspose.cells.CalculationData}
يحسب تعبير الصيغة بشكل مباشر.


###  عائدات

النتيجة المحسوبة للصيغة المعطاة.
من الممكن أن يكون الكائن المرتجع من الأنواع التالية: [`Cell.value`](/cells/python-net/ar/aspose.cells/cell#value)، أو ReferredArea.


```python

def calculate_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, calculation_data):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| formula | str | الصيغة المراد حسابها.|
| p_opts | [`FormulaParseOptions`](/cells/python-net/ar/aspose.cells/formulaparseoptions) | خيارات لتحليل الصيغة.|
| c_opts | [`CalculationOptions`](/cells/python-net/ar/aspose.cells/calculationoptions) | خيارات لحساب الصيغة.|
| base_cell_row | int | مؤشر الصف للخلية الأساسية.|
| base_cell_column | int | مؤشر العمود للخلية الأساسية.|
| calculation_data | [`CalculationData`](/cells/python-net/ar/aspose.cells/calculationdata) | بيانات الحساب. تُستخدم للحالة<br/>يحتاج المستخدم إلى حساب بعض الصيغ الثابتة عند تنفيذ محرك حساب مخصص.<br/>بالنسبة لهذا النوع من المواقف، يحتاج المستخدم إلى تحديده باستخدام بيانات الحساب المقدمة<br/> لـ Aspose.Cells.AbstractCalculationEngine.Calculate.|
###  ملاحظات

سيتم حساب الصيغة كما لو تم تعيينها للخلية الأساسية المحددة.
وستُؤخذ الصيغة كصيغة عادية. إذا كنت ترغب في حساب الصيغة كصيغة مصفوفة،
وللحصول على مصفوفة للنتيجة المحسوبة، يرجى استخدام
[`Worksheet.calculate_array_formula`](/cells/python-net/ar/aspose.cells/worksheet/calculate_array_formula) بدلا من ذلك.


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Worksheet`](/cells/python-net/ar/aspose.cells/worksheet)
