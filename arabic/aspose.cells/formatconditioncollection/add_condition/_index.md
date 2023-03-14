---
title: طريقة add_condition
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 40
url: /ar/aspose.cells/formatconditioncollection/add_condition/
is_root: false
---
##  add_condition(type) {#FormatConditionType}
أضف شرط تنسيق.


###  عائدات

فهرس كائن شرط التنسيق ؛


```python
def add_condition(self, type):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| type | [FormatConditionType](/cells/python-net/ar/aspose.cells/formatconditiontype) | نوع شرط التنسيق.|


##  add_condition(type, operator_type, formula1, formula2) {#FormatConditionType-OperatorType-str-str}
يضيف شرط تنسيق.


###  عائدات

فهرس كائن شرط التنسيق ؛


```python
def add_condition(self, type, operator_type, formula1, formula2):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| type | [FormatConditionType](/cells/python-net/ar/aspose.cells/formatconditiontype) | [FormatConditionType](/cells/python-net/ar/aspose.cells/formatconditiontype) التنسيق الشرطي.<br/> قد يكون أحد أعضاء FormatConditionType.|
| operator_type | [OperatorType](/cells/python-net/ar/aspose.cells/operatortype) | المقارنة [OperatorType](/cells/python-net/ar/aspose.cells/operatortype).<br/> يمكن أن يكون أحد أعضاء OperatorType.|
| formula1 | str | القيمة أو التعبير المرتبط بالتنسيق الشرطي.<br/>إذا بدأت قيمة الإدخال بـ '=' ، فسيتم اعتبارها معادلة.<br/>وإلا سيتم اعتباره كقيمة عادية (نص ، رقم ، منطقي).<br/> بالنسبة للقيمة النصية التي تبدأ بـ '=' ، يمكن للمستخدم إدخالها كصيغة بتنسيق: "= \" = ... \ "".|
| formula2 | str | القيمة أو التعبير المرتبط بالتنسيق الشرطي.<br/>تنسيق الإدخال هو نفسه مع الصيغة 1|



###  أنظر أيضا
* وحدة [aspose.cells](../../)
* فئة [FormatConditionCollection](/cells/python-net/ar/aspose.cells/formatconditioncollection)
* فئة [FormatConditionType](/cells/python-net/ar/aspose.cells/formatconditiontype)
* فئة [OperatorType](/cells/python-net/ar/aspose.cells/operatortype)
