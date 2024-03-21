---
title: طريقة set_formula
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 340
url: /ar/aspose.cells/cell/set_formula/
is_root: false
---
##  set_formula {#str-any}
قم بتعيين الصيغة وقيمة (النتيجة المحسوبة) للصيغة.



```python
def set_formula(self, formula, value):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| formula | str | الصيغة.|
| value | any |القيمة (النتيجة المحسوبة) للصيغة.|


##  set_formula {#str-aspose.cells.FormulaParseOptions-any}
قم بتعيين الصيغة وقيمة (النتيجة المحسوبة) للصيغة.



```python
def set_formula(self, formula, options, value):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| formula | str | الصيغة.|
| options | [`FormulaParseOptions`](/cells/python-net/ar/aspose.cells/formulaparseoptions) | خيارات لتحليل الصيغة.|
| value | any |القيمة (النتيجة المحسوبة) للصيغة.|


##  set_formula {#str-bool-bool-any}
قم بتعيين الصيغة وقيمة الصيغة.



```python
def set_formula(self, formula, is_r1c1, is_local, value):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| formula | str | الصيغة.|
| is_r1c1 | bool | ما إذا كانت الصيغة هي صيغة R1C1.|
| is_local | bool | ما إذا كانت الصيغة منسقة بالإعدادات المحلية.|
| value | any | قيمة الصيغة.|
###  ملاحظات

ملاحظة: هذه الفئة أصبحت الآن قديمة. بدلاً من،
الرجاء استخدام Cell.SetFormula(string,FormulaParseOptions,object).
ستتم إزالة هذه الخاصية بعد 12 شهرًا منذ ديسمبر 2019.
Aspose نعتذر عن أي إزعاج قد تعرضت له.


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Cell`](/cells/python-net/ar/aspose.cells/cell)
