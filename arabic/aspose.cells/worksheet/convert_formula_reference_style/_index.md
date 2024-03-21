---
title: طريقة convert_formula_reference_style
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 120
url: /ar/aspose.cells/worksheet/convert_formula_reference_style/
is_root: false
---
##  convert_formula_reference_style {#str-bool-int-int}
تحويل النمط المرجعي للصيغة.


###  عائدات

الصيغة المحولة.


```python
def convert_formula_reference_style(self, formula, to_r1c1, base_cell_row, base_cell_column):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| formula | str | الصيغة المراد تحويلها.|
| to_r1c1 | bool | النمط المرجعي المطلوب تحويل الصيغة إليه.<br/>إذا كانت الصيغة الأصلية ذات النمط المرجعي A1،<br/>ثم يجب أن تكون هذه القيمة صحيحة حتى يتم تحويل الصيغة من النمط المرجعي A1 إلى R1C1؛<br/>إذا كانت الصيغة الأصلية من النمط المرجعي R1C1،<br/> ثم يجب أن تكون هذه القيمة خاطئة حتى يتم تحويل الصيغة من النمط المرجعي R1C1 إلى النمط المرجعي A1؛|
| base_cell_row | int | فهرس صف الخلية الأساسية.|
| base_cell_column | int | فهرس العمود للخلية الأساسية.|



###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Worksheet`](/cells/python-net/ar/aspose.cells/worksheet)
