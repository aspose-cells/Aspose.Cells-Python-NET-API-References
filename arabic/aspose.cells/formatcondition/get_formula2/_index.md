---
title: طريقة get_formula2
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 30
url: /ar/aspose.cells/formatcondition/get_formula2/
is_root: false
---
##  get_formula2(is_r1c1, is_local) {#bool-bool}
الحصول على القيمة أو التعبير المرتبط بشرط التنسيق هذا.


###  عائدات

القيمة أو التعبير المرتبط بشرط التنسيق هذا.


```python
def get_formula2(self, is_r1c1, is_local):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| is_r1c1 | bool | ما إذا كانت الصيغة تحتاج إلى تنسيقها كـ R1C1.|
| is_local | bool | ما إذا كانت الصيغة تحتاج إلى التنسيق بواسطة الإعدادات المحلية.|


##  get_formula2(row, column) {#int-int}
الحصول على صيغة التنسيق الشرطي للخلية.


###  عائدات

الصيغة.


```python
def get_formula2(self, row, column):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| row | int | فهرس الصف.|
| column | int | فهرس العمود.|


##  get_formula2(is_r1c1, is_local, row, column) {#bool-bool-int-int}
الحصول على قيمة أو تعبير التنسيق الشرطي للخلية.


###  عائدات

القيمة أو التعبير المرتبط بالتنسيق الشرطي للخلية.


```python
def get_formula2(self, is_r1c1, is_local, row, column):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| is_r1c1 | bool | ما إذا كانت الصيغة تحتاج إلى تنسيقها كـ R1C1.|
| is_local | bool | ما إذا كانت الصيغة تحتاج إلى التنسيق بواسطة الإعدادات المحلية.|
| row | int | فهرس الصف.|
| column | int | فهرس العمود.|
###  ملاحظات

يجب أن يتم احتواء الخلية المحددة بواسطة هذا التنسيق الشرطي ، وإلا فسيتم إرجاع القيمة الخالية.


###  أنظر أيضا

* وحدة [aspose.cells](../../)
* فئة [FormatCondition](/cells/python-net/ar/aspose.cells/formatcondition)
