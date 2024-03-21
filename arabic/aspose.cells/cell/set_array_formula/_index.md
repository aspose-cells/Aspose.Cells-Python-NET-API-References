---
title: طريقة set_array_formula
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 310
url: /ar/aspose.cells/cell/set_array_formula/
is_root: false
---
##  set_array_formula {#str-int-int}
يعين صيغة صفيف (تم إدخال صيغة الصفيف القديمة عبر CTRL + SHIFT + ENTER في مللي إكسل) إلى نطاق من الخلايا.



```python
def set_array_formula(self, array_formula, row_number, column_number):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| array_formula | str | صيغة المصفوفة.|
| row_number | int | عدد الصفوف المراد ملؤها نتيجة صيغة الصفيف.|
| column_number | int | عدد الأعمدة لملء نتيجة صيغة الصفيف.|


##  set_array_formula {#str-int-int-aspose.cells.FormulaParseOptions}
تعيين صيغة صفيف لنطاق من الخلايا.



```python
def set_array_formula(self, array_formula, row_number, column_number, options):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| array_formula | str | صيغة المصفوفة.|
| row_number | int | عدد الصفوف المراد ملؤها نتيجة صيغة الصفيف.|
| column_number | int | عدد الأعمدة لملء نتيجة صيغة الصفيف.|
| options | [`FormulaParseOptions`](/cells/python-net/ar/aspose.cells/formulaparseoptions) | خيارات لتحليل الصيغة.|


##  set_array_formula {#str-int-int-bool-bool}
تعيين صيغة صفيف لنطاق من الخلايا.



```python
def set_array_formula(self, array_formula, row_number, column_number, is_r1c1, is_local):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| array_formula | str | صيغة المصفوفة.|
| row_number | int | عدد الصفوف المراد ملؤها نتيجة صيغة الصفيف.|
| column_number | int | عدد الأعمدة لملء نتيجة صيغة الصفيف.|
| is_r1c1 | bool | ما إذا كانت الصيغة هي صيغة R1C1|
| is_local | bool | ما إذا كانت الصيغة منسقة بالإعدادات المحلية|
###  ملاحظات

ملاحظة: هذه الفئة أصبحت الآن قديمة. بدلاً من،
الرجاء استخدام Cell.SetArrayFormula(string,int,int,FormulaParseOptions).
ستتم إزالة هذه الخاصية بعد 12 شهرًا منذ ديسمبر 2019.
Aspose نعتذر عن أي إزعاج قد تعرضت له.

##  set_array_formula {#str-int-int-aspose.cells.FormulaParseOptions-list}
تعيين صيغة صفيف لنطاق من الخلايا.



```python
def set_array_formula(self, array_formula, row_number, column_number, options, values):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| array_formula | str | صيغة المصفوفة.|
| row_number | int | عدد الصفوف المراد ملؤها نتيجة صيغة الصفيف.|
| column_number | int | عدد الأعمدة لملء نتيجة صيغة الصفيف.|
| options | [`FormulaParseOptions`](/cells/python-net/ar/aspose.cells/formulaparseoptions) | خيارات لتحليل الصيغة.|
| values | list | قيم تلك الخلايا ذات صيغة الصفيف المحددة|



###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Cell`](/cells/python-net/ar/aspose.cells/cell)
