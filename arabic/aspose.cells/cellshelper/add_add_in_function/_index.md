---
title: طريقة add_add_in_function
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 20
url: /ar/aspose.cells/cellshelper/add_add_in_function/
is_root: false
---
##  add_add_in_function(، دالة، الحد الأدنى لعدد المعلمات، الحد الأقصى لعدد المعلمات، نوع المعلمات، نوع قيمة الدالة){#str-int-int-list-aspose.cells.ParameterType}
إضافة وظيفة إضافية.



```python

@staticmethod
def add_add_in_function(function, min_count_of_parameters, max_count_of_parameters, paramers_type, function_value_type):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| function | str | اسم الوظيفة.|
| min_count_of_parameters | int | الحد الأدنى لعدد المعلمات التي تتطلبها هذه الوظيفة|
| max_count_of_parameters | int | الحد الأقصى لعدد المعلمات التي تسمح بها هذه الوظيفة.|
| paramers_type | list | نوع المعلمات المستثناة للوظيفة|
| function_value_type | [`ParameterType`](/cells/python-net/ar/aspose.cells/parametertype) | نوع قيمة الوظيفة.|
###  ملاحظات

ملاحظة: هذا العضو أصبح قديمًا. بدلًا من ذلك،
من فضلك استخدم طرق WorksheetCollection.RegisterAddInFunction().
 سيتم إزالة هذه الطريقة بعد مرور 12 شهرًا منذ يناير 2022.
Aspose يعتذر عن أي إزعاج قد يكون واجهته.


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`CellsHelper`](/cells/python-net/ar/aspose.cells/cellshelper)
