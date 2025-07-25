---
title: طريقة preprocess_exported_value
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 20
url: /ar/aspose.cells/exporttableoptions/preprocess_exported_value/
is_root: false
---
##  preprocess_exported_value(self, cell_row, cell_column, value) {#int-int-aspose.cells.CellValue}
قم بمعالجة قيمة الخلية الحالية التي سيتم تصديرها مسبقًا.


###  عائدات

ما إذا كان قد تم استبدال الخلية الحالية بنوع و/أو قيمة مختلفة.


```python

def preprocess_exported_value(self, cell_row, cell_column, value):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| cell_row | int | مؤشر الصف للخلية الحالية|
| cell_column | int | مؤشر عمود الخلية|
| value | [`CellValue`](/cells/python-net/ar/aspose.cells/cellvalue) | قيمة ونوع الخلية الحالية|
###  ملاحظات

يعد مؤشر الصف والعمود بمثابة مؤشر مطلق للخلية في ورقة العمل، وليس مؤشرًا في الجدول المُصدَّر.
يمكن للمستخدم التحقق من قيمة الخلية الحالية في تنفيذ التجاوز لهذه الطريقة،
إذا كانت هناك حاجة إلى استبدال الخلية الحالية بنوع وقيمة أخرى،
هنا يجب على التنفيذ تعيين النوع والقيمة المتوقعة لكائن CellValue وإرجاع true.
بشكل افتراضي، لا تفعل هذه الطريقة أي شيء وترجع القيمة false.


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`ExportTableOptions`](/cells/python-net/ar/aspose.cells/exporttableoptions)
