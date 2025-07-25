---
title: طريقة create_range
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 190
url: /ar/aspose.cells/cells/create_range/
is_root: false
---
##  create_range(self, address) {#str}
إنشاء كائن [`Range`](/cells/python-net/ar/aspose.cells/range) من عنوان النطاق.


###  عائدات

كائن [`Range`](/cells/python-net/ar/aspose.cells/range)


```python

def create_range(self, address):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| address | str | عنوان النطاق.|


##  create_range(self, upper_left_cell, lower_right_cell) {#str-str}
إنشاء كائن [`Range`](/cells/python-net/ar/aspose.cells/range) من نطاق من الخلايا.


###  عائدات

كائن [`Range`](/cells/python-net/ar/aspose.cells/range)


```python

def create_range(self, upper_left_cell, lower_right_cell):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| upper_left_cell | str | اسم الخلية العلوية اليسرى.|
| lower_right_cell | str | اسم الخلية في أسفل اليمين.|


##  create_range(self, first_index, number, is_vertical) {#int-int-bool}
إنشاء كائن [`Range`](/cells/python-net/ar/aspose.cells/range) من صفوف الخلايا أو أعمدة الخلايا.


###  عائدات

كائن [`Range`](/cells/python-net/ar/aspose.cells/range).


```python

def create_range(self, first_index, number, is_vertical):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| first_index | int | فهرس الصف الأول أو فهرس العمود الأول، على أساس الصفر.|
| number | int | العدد الإجمالي للصفوف أو الأعمدة، على أساس واحد.|
| is_vertical | bool | صحيح - نطاق مُنشأ من أعمدة الخلايا. خطأ - نطاق مُنشأ من صفوف الخلايا.|


##  create_range(self, first_row, first_column, total_rows, total_columns) {#int-int-int-int}
إنشاء كائن [`Range`](/cells/python-net/ar/aspose.cells/range) من نطاق من الخلايا.


###  عائدات

كائن [`Range`](/cells/python-net/ar/aspose.cells/range)


```python

def create_range(self, first_row, first_column, total_rows, total_columns):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| first_row | int |الصف الأول من هذا النطاق|
| first_column | int | العمود الأول من هذا النطاق|
| total_rows | int | عدد الصفوف|
| total_columns | int | عدد الأعمدة|



###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Cells`](/cells/python-net/ar/aspose.cells/cells)
* فئة [`Range`](/cells/python-net/ar/aspose.cells/range)
