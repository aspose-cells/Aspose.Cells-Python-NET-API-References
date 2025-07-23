---
title: طريقة copy_in_range
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 410
url: /ar/aspose.cells.drawing/shapecollection/copy_in_range/
is_root: false
---
##  copy_in_range(self, source_shapes, ca, dest_row, dest_column, is_contained) {#aspose.cells.drawing.ShapeCollection-aspose.cells.CellArea-int-int-bool}
نسخ الأشكال الموجودة في النطاق إلى نطاق الوجهة.



```python

def copy_in_range(self, source_shapes, ca, dest_row, dest_column, is_contained):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| source_shapes | [`ShapeCollection`](/cells/python-net/ar/aspose.cells.drawing/shapecollection) | أشكال المصدر.|
| ca | [`CellArea`](/cells/python-net/ar/aspose.cells/cellarea) | نطاق المصدر.|
| dest_row | int | مؤشر الصف المقصد لنطاق المقصد.|
| dest_column | int | عمود الوجهة لنطاق الوجهة.|
| is_contained | bool | ما إذا كان سيتم نسخ الأشكال الموجودة في النطاق فقط.<br/> إذا كانت هذه القيمة صحيحة، فسيتم نسخ الأشكال الموجودة في النطاق فقط.<br/> بخلاف ذلك، فهو يعمل مثل MS Office.|

###  مثال

```python
from aspose.cells import CellArea

# add a shape
shapes.add_rectangle(2, 0, 2, 0, 130, 130)
area2 = CellArea()
area2.start_column = 1
area2.start_row = 1
area2.end_column = 5
area2.end_row = 11
# copy
shapes.copy_in_range(shapes, area2, 12, 1, False)

```



###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](../../)
* فئة [`ShapeCollection`](/cells/python-net/ar/aspose.cells.drawing/shapecollection)
