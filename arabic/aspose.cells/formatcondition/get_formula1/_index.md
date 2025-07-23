---
title: طريقة get_formula1
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 20
url: /ar/aspose.cells/formatcondition/get_formula1/
is_root: false
---
##  get_formula1(self, is_r1c1, is_local) {#bool-bool}
يحصل على القيمة أو التعبير المرتبط بشرط التنسيق هذا.


###  عائدات

القيمة أو التعبير المرتبط بشرط التنسيق هذا.


```python

def get_formula1(self, is_r1c1, is_local):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| is_r1c1 | bool | ما إذا كانت الصيغة تحتاج إلى تنسيقها كـ R1C1.|
| is_local | bool | ما إذا كانت الصيغة تحتاج إلى تنسيق حسب الإعدادات المحلية.|


##  get_formula1(self, row, column) {#int-int}
يحصل على صيغة التنسيق الشرطي للخلية.


###  عائدات

الصيغة.


```python

def get_formula1(self, row, column):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| row | int | مؤشر الصف.|
| column | int | فهرس العمود.|


##  get_formula1(self, is_r1c1, is_local, row, column) {#bool-bool-int-int}
يحصل على قيمة أو تعبير التنسيق الشرطي للخلية.


###  عائدات

القيمة أو التعبير المرتبط بالتنسيق الشرطي للخلية.


```python

def get_formula1(self, is_r1c1, is_local, row, column):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| is_r1c1 | bool | ما إذا كانت الصيغة تحتاج إلى تنسيقها كـ R1C1.|
| is_local | bool | ما إذا كانت الصيغة تحتاج إلى تنسيق حسب الإعدادات المحلية.|
| row | int | مؤشر الصف.|
| column | int | فهرس العمود.|
###  ملاحظات

يجب أن تحتوي الخلية المحددة على هذا التنسيق الشرطي، وإلا سيتم إرجاع قيمة null.


###  أنظر أيضا

* الوحدة [`aspose.cells`](../../)
* فئة [`FormatCondition`](/cells/python-net/ar/aspose.cells/formatcondition)
