---
title: طريقة add_oval
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 220
url: /ar/aspose.cells.drawing/shapecollection/add_oval/
is_root: false
---
##  add_oval(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
إضافة شكل بيضاوي إلى ورقة العمل.


###  عائدات

جسم بيضاوي الشكل.


```python

def add_oval(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| upper_left_row | int | مؤشر الصف العلوي الأيسر.|
| top | int | يمثل الإزاحة الرأسية للشكل البيضاوي من صفه الأيسر، بوحدة البكسل.|
| upper_left_column | int | فهرس العمود العلوي الأيسر.|
| left | int | يمثل الإزاحة الأفقية للشكل البيضاوي من عموده الأيسر، بوحدة البكسل.|
| height | int | يمثل ارتفاع الشكل البيضاوي بوحدة البكسل.|
| width | int | يمثل عرض الشكل البيضاوي بوحدة البكسل.|

###  مثال

```python

# add a oval
oval = shapes.add_oval(1, 0, 1, 0, 50, 50)

```



###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](../../)
* فئة [`ShapeCollection`](/cells/python-net/ar/aspose.cells.drawing/shapecollection)
