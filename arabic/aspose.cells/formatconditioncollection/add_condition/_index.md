---
title: طريقة add_condition
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 40
url: /ar/aspose.cells/formatconditioncollection/add_condition/
is_root: false
---
##  add_condition(self, type) {#aspose.cells.FormatConditionType}
أضف شرط التنسيق.


###  عائدات

فهرس كائن شرط التنسيق؛


```python

def add_condition(self, type):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| type | [`FormatConditionType`](/cells/python-net/ar/aspose.cells/formatconditiontype) | نوع شرط التنسيق.|


##  add_condition(self, type, operator_type, formula1, formula2) {#aspose.cells.FormatConditionType-aspose.cells.OperatorType-str-str}
يضيف شرط التنسيق.


###  عائدات

فهرس كائن شرط التنسيق؛


```python

def add_condition(self, type, operator_type, formula1, formula2):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| type | [`FormatConditionType`](/cells/python-net/ar/aspose.cells/formatconditiontype) | نوع شرط التنسيق.|
| operator_type | [`OperatorType`](/cells/python-net/ar/aspose.cells/operatortype) | نوع المشغل|
| formula1 | str | القيمة أو التعبير المرتبط بالتنسيق الشرطي.<br/>إذا بدأت قيمة الإدخال بـ '='، فسيتم اعتبارها صيغة.<br/>وإلا فسيتم اعتباره قيمة عادية (نص، رقم، قيمة منطقية).<br/> بالنسبة لقيمة النص التي تبدأ بـ '='، يمكن للمستخدم إدخالها كصيغة بالتنسيق: "=\"=...\"".|
| formula2 | str | القيمة أو التعبير المرتبط بالتنسيق الشرطي.<br/> تنسيق الإدخال هو نفسه الصيغة 1|



###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`FormatConditionCollection`](/cells/python-net/ar/aspose.cells/formatconditioncollection)
