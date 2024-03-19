---
title: طريقة preprocess_exported_value
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 20
url: /ar/aspose.cells/exporttableoptions/preprocess_exported_value/
is_root: false
---
##  preprocess_exported_value {#int-int-aspose.cells.CellValue}
المعالجة المسبقة لقيمة الخلية الحالية المراد تصديرها.


###  عائدات

ما إذا كان قد تم استبدال الخلية الحالية بنوع و/أو قيمة مختلفة.


```python
def preprocess_exported_value(self, cell_row, cell_column, value):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| cell_row | int | فهرس الصف للخلية الحالية|
| cell_column | int | فهرس عمود الخلية|
| value | [`CellValue`](/cells/python-net/ar/aspose.cells/cellvalue) | قيمة ونوع الخلية الحالية|
###  ملاحظات

فهرس الصف والعمود هو الفهرس المطلق للخلية في ورقة العمل، وليس الفهرس في الجدول الذي تم تصديره.
يمكن للمستخدم التحقق من قيمة الخلية الحالية في تنفيذ التجاوز لهذه الطريقة،
إذا كانت الخلية الحالية بحاجة إلى استبدالها بنوع وقيمة أخرى،
هنا يجب أن يقوم التنفيذ بتعيين النوع والقيمة المتوقعة لكائن CellValue وإرجاع صحيح.
بشكل افتراضي، لا تفعل هذه الطريقة شيئًا وترجع خطأ.


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`ExportTableOptions`](/cells/python-net/ar/aspose.cells/exporttableoptions)
