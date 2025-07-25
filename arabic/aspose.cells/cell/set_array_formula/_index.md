---
title: طريقة set_array_formula
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 320
url: /ar/aspose.cells/cell/set_array_formula/
is_root: false
---
##  set_array_formula(self, array_formula, row_number, column_number) {#str-int-int}
تعيين صيغة المصفوفة (صيغة المصفوفة القديمة التي تم إدخالها عبر CTRL+SHIFT+ENTER في ms excel) إلى نطاق من الخلايا.



```python

def set_array_formula(self, array_formula, row_number, column_number):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| array_formula | str | صيغة المصفوفة.|
| row_number | int | عدد الصفوف التي سيتم ملؤها نتيجة صيغة المصفوفة.|
| column_number | int | عدد الأعمدة التي سيتم ملؤها نتيجة صيغة المصفوفة.|


##  set_array_formula(self, array_formula, row_number, column_number, options) {#str-int-int-aspose.cells.FormulaParseOptions}
تعيين صيغة المصفوفة لمجموعة من الخلايا.



```python

def set_array_formula(self, array_formula, row_number, column_number, options):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| array_formula | str | صيغة المصفوفة.|
| row_number | int | عدد الصفوف التي سيتم ملؤها نتيجة صيغة المصفوفة.|
| column_number | int | عدد الأعمدة التي سيتم ملؤها نتيجة صيغة المصفوفة.|
| options | [`FormulaParseOptions`](/cells/python-net/ar/aspose.cells/formulaparseoptions) | خيارات لتحليل الصيغة.|


##  set_array_formula(self, array_formula, row_number, column_number, is_r1c1, is_local) {#str-int-int-bool-bool}
تعيين صيغة المصفوفة لمجموعة من الخلايا.



```python

def set_array_formula(self, array_formula, row_number, column_number, is_r1c1, is_local):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| array_formula | str | صيغة المصفوفة.|
| row_number | int | عدد الصفوف التي سيتم ملؤها نتيجة صيغة المصفوفة.|
| column_number | int | عدد الأعمدة التي سيتم ملؤها نتيجة صيغة المصفوفة.|
| is_r1c1 | bool | هل الصيغة هي صيغة R1C1|
| is_local | bool | ما إذا كانت الصيغة بتنسيق محلي|
###  ملاحظات

ملاحظة: هذه الفئة أصبحت قديمة الآن. بدلاً من ذلك،
من فضلك استخدم Cell.SetArrayFormula(string,int,int,FormulaParseOptions).
سيتم إزالة هذه الخاصية بعد مرور 12 شهرًا منذ ديسمبر 2019.
Aspose يعتذر عن أي إزعاج قد يكون واجهته.

##  set_array_formula(self, array_formula, row_number, column_number, options, values) {#str-int-int-aspose.cells.FormulaParseOptions-list}
تعيين صيغة المصفوفة لمجموعة من الخلايا.



```python

def set_array_formula(self, array_formula, row_number, column_number, options, values):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| array_formula | str | صيغة المصفوفة.|
| row_number | int | عدد الصفوف التي سيتم ملؤها نتيجة صيغة المصفوفة.|
| column_number | int | عدد الأعمدة التي سيتم ملؤها نتيجة صيغة المصفوفة.|
| options | [`FormulaParseOptions`](/cells/python-net/ar/aspose.cells/formulaparseoptions) | خيارات لتحليل الصيغة.|
| values | list | القيم لتلك الخلايا ذات صيغة المصفوفة المحددة|



###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Cell`](/cells/python-net/ar/aspose.cells/cell)
