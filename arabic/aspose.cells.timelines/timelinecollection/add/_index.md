---
title: طريقة add
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 20
url: /ar/aspose.cells.timelines/timelinecollection/add/
is_root: false
---
##  add(self, pivot, dest_cell_name, base_field_name) {#aspose.cells.pivot.PivotTable-str-str}
إضافة جدول زمني جديد باستخدام PivotTable كمصدر للبيانات


###  عائدات

فهرس الجدول الزمني الجديد add


```python

def add(self, pivot, dest_cell_name, base_field_name):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | كائن جدول محوري|
| dest_cell_name | str | اسم الخلية في الزاوية العلوية اليسرى من نطاق الجدول الزمني.|
| base_field_name | str | اسم PivotField في PivotTable.BaseFields|

###  مثال

```python

# Add a new Timeline using PivotTable as data source
sheet.timelines.add(pivot, "i15", "date")

```


##  add(self, pivot, dest_cell_name, base_field_index) {#aspose.cells.pivot.PivotTable-str-int}
إضافة جدول زمني جديد باستخدام PivotTable كمصدر للبيانات


###  عائدات

فهرس الجدول الزمني الجديد add


```python

def add(self, pivot, dest_cell_name, base_field_index):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | كائن جدول محوري|
| dest_cell_name | str | اسم الخلية في الزاوية العلوية اليسرى من نطاق الجدول الزمني.|
| base_field_index | int | فهرس PivotField في PivotTable.BaseFields|

###  مثال

```python

# Add a new Timeline using PivotTable as data source
sheet.timelines.add(pivot, "i5", 1)

```


##  add(self, pivot, dest_cell_name, base_field) {#aspose.cells.pivot.PivotTable-str-aspose.cells.pivot.PivotField}
إضافة جدول زمني جديد باستخدام PivotTable كمصدر للبيانات


###  عائدات

فهرس الجدول الزمني الجديد add


```python

def add(self, pivot, dest_cell_name, base_field):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | كائن جدول محوري|
| dest_cell_name | str | اسم الخلية في الزاوية العلوية اليسرى من نطاق الجدول الزمني.|
| base_field | aspose.cells.pivot.PivotField | حقل المحور في PivotTable.BaseFields|

###  مثال

```python

# Add a new Timeline using PivotTable as data source
sheet.timelines.add(pivot, "i10", pivot.base_fields[1])

```


##  add(self, pivot, row, column, base_field_name) {#aspose.cells.pivot.PivotTable-int-int-str}
إضافة جدول زمني جديد باستخدام PivotTable كمصدر للبيانات


###  عائدات

فهرس الجدول الزمني الجديد add


```python

def add(self, pivot, row, column, base_field_name):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | كائن جدول محوري|
| row | int |مؤشر الصف للخلية في الزاوية العلوية اليسرى من نطاق الجدول الزمني.|
| column | int | فهرس العمود للخلية في الزاوية العلوية اليسرى من نطاق الجدول الزمني.|
| base_field_name | str | اسم PivotField في PivotTable.BaseFields|

###  مثال

```python

# Add a new Timeline using PivotTable as data source
sheet.timelines.add(pivot, 10, 5, "date")

```


##  add(self, pivot, row, column, base_field_index) {#aspose.cells.pivot.PivotTable-int-int-int}
إضافة جدول زمني جديد باستخدام PivotTable كمصدر للبيانات


###  عائدات

فهرس الجدول الزمني الجديد add


```python

def add(self, pivot, row, column, base_field_index):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | كائن جدول محوري|
| row | int |مؤشر الصف للخلية في الزاوية العلوية اليسرى من نطاق الجدول الزمني.|
| column | int | فهرس العمود للخلية في الزاوية العلوية اليسرى من نطاق الجدول الزمني.|
| base_field_index | int | فهرس PivotField في PivotTable.BaseFields|

###  مثال

```python

# Add a new Timeline using PivotTable as data source
sheet.timelines.add(pivot, 15, 5, 1)

```


##  add(self, pivot, row, column, base_field) {#aspose.cells.pivot.PivotTable-int-int-aspose.cells.pivot.PivotField}
إضافة جدول زمني جديد باستخدام PivotTable كمصدر للبيانات


###  عائدات

فهرس الجدول الزمني الجديد add


```python

def add(self, pivot, row, column, base_field):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | كائن جدول محوري|
| row | int |مؤشر الصف للخلية في الزاوية العلوية اليسرى من نطاق الجدول الزمني.|
| column | int | فهرس العمود للخلية في الزاوية العلوية اليسرى من نطاق الجدول الزمني.|
| base_field | aspose.cells.pivot.PivotField | حقل المحور في PivotTable.BaseFields|

###  مثال

```python

# Add a new Timeline using PivotTable as data source
sheet.timelines.add(pivot, 20, 5, pivot.base_fields[1])

```



###  أنظر أيضا
* الوحدة [`aspose.cells.timelines`](../../)
* فئة [`TimelineCollection`](/cells/python-net/ar/aspose.cells.timelines/timelinecollection)
