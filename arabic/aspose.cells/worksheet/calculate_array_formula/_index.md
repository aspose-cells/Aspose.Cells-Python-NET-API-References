---
title: طريقة calculate_array_formula
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 80
url: /ar/aspose.cells/worksheet/calculate_array_formula/
is_root: false
---
##  calculate_array_formula(self, formula, opts) {#str-aspose.cells.CalculationOptions}
يحسب الصيغة كصيغة مصفوفة.



```python

def calculate_array_formula(self, formula, opts):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| formula | str | الصيغة المراد حسابها.|
| opts | [`CalculationOptions`](/cells/python-net/ar/aspose.cells/calculationoptions) | خيارات لحساب الصيغة|


##  calculate_array_formula(self, formula, opts, max_row_count, max_column_count) {#str-aspose.cells.CalculationOptions-int-int}
يحسب الصيغة كصيغة مصفوفة.


###  عائدات

نتيجة الصيغة المحسوبة.


```python

def calculate_array_formula(self, formula, opts, max_row_count, max_column_count):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| formula | str | الصيغة المراد حسابها.|
| opts | [`CalculationOptions`](/cells/python-net/ar/aspose.cells/calculationoptions) | خيارات لحساب الصيغة|
| max_row_count | int | الحد الأقصى لعدد صفوف البيانات الناتجة.<br/> إذا كان غير موجب أو أكبر من عدد الصفوف الفعلي، فسيتم استخدام عدد الصفوف الفعلي.|
| max_column_count | int | الحد الأقصى لعدد أعمدة البيانات الناتجة.<br/> إذا كان غير موجب أو أكبر من عدد الصفوف الفعلي، فسيتم استخدام عدد الأعمدة الفعلي.|
###  ملاحظات

سيتم استخدام الصيغة كصيغة مصفوفة ديناميكية لحساب البعد والنتيجة.
يتم استخدام البعد الأقصى الذي يحدده المستخدم في الحالات التي تكون فيها النتيجة المحسوبة عبارة عن مجموعة بيانات كبيرة
(على سبيل المثال، قد تتوافق النتيجة المحسوبة مع بيانات صف أو عمود كامل)
لكن المستخدم لا يحتاج إلى مجموعة كبيرة جدًا وفقًا لمتطلبات العمل أو لأسباب تتعلق بالأداء.

##  calculate_array_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, max_row_count, max_column_count, calculation_data) {#str-aspose.cells.FormulaParseOptions-aspose.cells.CalculationOptions-int-int-int-int-aspose.cells.CalculationData}
يحسب الصيغة كصيغة مصفوفة.


###  عائدات

نتيجة الصيغة المحسوبة.


```python

def calculate_array_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, max_row_count, max_column_count, calculation_data):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| formula | str | الصيغة المراد حسابها.|
| p_opts | [`FormulaParseOptions`](/cells/python-net/ar/aspose.cells/formulaparseoptions) |خيارات تحليل الصيغة|
| c_opts | [`CalculationOptions`](/cells/python-net/ar/aspose.cells/calculationoptions) | خيارات لحساب الصيغة|
| base_cell_row | int | مؤشر الصف للخلية الأساسية.|
| base_cell_column | int | مؤشر العمود للخلية الأساسية.|
| max_row_count | int | الحد الأقصى لعدد صفوف البيانات الناتجة.<br/> إذا كان غير موجب أو أكبر من عدد الصفوف الفعلي، فسيتم استخدام عدد الصفوف الفعلي.|
| max_column_count | int | الحد الأقصى لعدد أعمدة البيانات الناتجة.<br/> إذا كان غير موجب أو أكبر من عدد الصفوف الفعلي، فسيتم استخدام عدد الأعمدة الفعلي.|
| calculation_data | [`CalculationData`](/cells/python-net/ar/aspose.cells/calculationdata) | بيانات الحساب. تُستخدم للحالة<br/>يحتاج المستخدم إلى حساب بعض الصيغ الثابتة عند تنفيذ محرك حساب مخصص.<br/>بالنسبة لهذا النوع من المواقف، يحتاج المستخدم إلى تحديده باستخدام بيانات الحساب المقدمة<br/> لـ Aspose.Cells.AbstractCalculationEngine.Calculate.|
###  ملاحظات

سيتم استخدام الصيغة كصيغة مصفوفة ديناميكية لحساب البعد والنتيجة.
يتم استخدام البعد الأقصى الذي يحدده المستخدم في الحالات التي تكون فيها النتيجة المحسوبة عبارة عن مجموعة بيانات كبيرة
(على سبيل المثال، قد تتوافق النتيجة المحسوبة مع بيانات صف أو عمود كامل)
لكن المستخدم لا يحتاج إلى مجموعة كبيرة جدًا وفقًا لمتطلبات العمل أو لأسباب تتعلق بالأداء.


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Worksheet`](/cells/python-net/ar/aspose.cells/worksheet)
