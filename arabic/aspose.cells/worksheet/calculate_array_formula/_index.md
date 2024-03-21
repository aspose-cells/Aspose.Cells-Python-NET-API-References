---
title: طريقة calculate_array_formula
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 80
url: /ar/aspose.cells/worksheet/calculate_array_formula/
is_root: false
---
##  calculate_array_formula {#str-aspose.cells.CalculationOptions}
حساب صيغة كصيغة صفيف.



```python
def calculate_array_formula(self, formula, opts):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| formula | str | الصيغة التي سيتم حسابها.|
| opts | [`CalculationOptions`](/cells/python-net/ar/aspose.cells/calculationoptions) | خيارات لحساب الصيغة|


##  calculate_array_formula {#str-aspose.cells.CalculationOptions-int-int}
حساب صيغة كصيغة صفيف.


###  عائدات

نتيجة الصيغة المحسوبة.


```python
def calculate_array_formula(self, formula, opts, max_row_count, max_column_count):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| formula | str | الصيغة التي سيتم حسابها.|
| opts | [`CalculationOptions`](/cells/python-net/ar/aspose.cells/calculationoptions) | خيارات لحساب الصيغة|
| max_row_count | int | الحد الأقصى لعدد الصفوف من البيانات الناتجة.<br/> إذا كان غير موجب أو أكبر من عدد الصفوف الفعلي، فسيتم استخدام عدد الصفوف الفعلي.|
| max_column_count | int | الحد الأقصى لعدد الأعمدة من البيانات الناتجة.<br/> إذا كان غير موجب أو أكبر من عدد الصفوف الفعلي، فسيتم استخدام عدد الأعمدة الفعلي.|
###  ملاحظات

سيتم أخذ الصيغة كصيغة صفيف ديناميكية لحساب البعد والنتيجة.
يتم استخدام الحد الأقصى للبعد المحدد بواسطة المستخدم في الحالات التي تكون فيها النتيجة المحسوبة عبارة عن مجموعة بيانات كبيرة
(على سبيل المثال، قد تتوافق النتيجة المحسوبة مع بيانات صف أو عمود كامل)
لكن المستخدم لا يحتاج إلى مصفوفة كبيرة جدًا وفقًا لمتطلبات العمل أو لاعتبارات الأداء.

##  calculate_array_formula {#str-aspose.cells.FormulaParseOptions-aspose.cells.CalculationOptions-int-int-int-int-aspose.cells.CalculationData}
حساب صيغة كصيغة صفيف.


###  عائدات

نتيجة الصيغة المحسوبة.


```python
def calculate_array_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, max_row_count, max_column_count, calculation_data):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| formula | str | الصيغة التي سيتم حسابها.|
| p_opts | [`FormulaParseOptions`](/cells/python-net/ar/aspose.cells/formulaparseoptions) | خيارات لتحليل الصيغة|
| c_opts | [`CalculationOptions`](/cells/python-net/ar/aspose.cells/calculationoptions) | خيارات لحساب الصيغة|
| base_cell_row | int | فهرس صف الخلية الأساسية.|
| base_cell_column | int | فهرس العمود للخلية الأساسية.|
| max_row_count | int | الحد الأقصى لعدد صفوف البيانات الناتجة.<br/> إذا كان غير موجب أو أكبر من عدد الصفوف الفعلي، فسيتم استخدام عدد الصفوف الفعلي.|
| max_column_count | int | الحد الأقصى لعدد الأعمدة من البيانات الناتجة.<br/> إذا كان غير موجب أو أكبر من عدد الصفوف الفعلي، فسيتم استخدام عدد الأعمدة الفعلي.|
| calculation_data | [`CalculationData`](/cells/python-net/ar/aspose.cells/calculationdata) | بيانات الحساب. يتم استخدامه للحالة<br/>يحتاج هذا المستخدم إلى حساب بعض الصيغ الثابتة عند تنفيذ محرك الحساب المخصص.<br/>لمثل هذا النوع من الحالات، يحتاج المستخدم إلى تحديده باستخدام بيانات الحساب المقدمة<br/> ل [`AbstractCalculationEngine.calculate`](/cells/python-net/ar/aspose.cells/abstractcalculationengine/calculate).|
###  ملاحظات

سيتم أخذ الصيغة كصيغة صفيف ديناميكية لحساب البعد والنتيجة.
يتم استخدام الحد الأقصى للبعد المحدد بواسطة المستخدم في الحالات التي تكون فيها النتيجة المحسوبة عبارة عن مجموعة بيانات كبيرة
(على سبيل المثال، قد تتوافق النتيجة المحسوبة مع بيانات صف أو عمود كامل)
لكن المستخدم لا يحتاج إلى مصفوفة كبيرة جدًا وفقًا لمتطلبات العمل أو لاعتبارات الأداء.


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Worksheet`](/cells/python-net/ar/aspose.cells/worksheet)
