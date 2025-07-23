---
title: طريقة add
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 20
url: /ar/aspose.cells.slicers/slicercollection/add/
is_root: false
---
##  add(self, pivot, dest_cell_name, base_field_name) {#aspose.cells.pivot.PivotTable-str-str}
إضافة شريحة جديدة باستخدام PivotTable كمصدر بيانات


###  عائدات

مؤشر التقطيع الجديد add


```python

def add(self, pivot, dest_cell_name, base_field_name):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | كائن جدول محوري|
| dest_cell_name | str | الخلية الموجودة في الزاوية العلوية اليسرى من نطاق المقطع.|
| base_field_name | str | اسم PivotField في PivotTable.BaseFields|

###  مثال

```python

slicers.add(pivot, "E3", "fruit")

```


##  add(self, pivot, dest_cell_name, base_field_index) {#aspose.cells.pivot.PivotTable-str-int}
إضافة شريحة جديدة باستخدام PivotTable كمصدر بيانات


###  عائدات

مؤشر التقطيع الجديد add


```python

def add(self, pivot, dest_cell_name, base_field_index):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | كائن جدول محوري|
| dest_cell_name | str | الخلية الموجودة في الزاوية العلوية اليسرى من نطاق المقطع.|
| base_field_index | int | فهرس PivotField في PivotTable.BaseFields|

###  مثال

```python

slicers.add(pivot, "E20", 0)

```


##  add(self, pivot, dest_cell_name, base_field) {#aspose.cells.pivot.PivotTable-str-aspose.cells.pivot.PivotField}
إضافة شريحة جديدة باستخدام PivotTable كمصدر بيانات


###  عائدات

مؤشر التقطيع الجديد add


```python

def add(self, pivot, dest_cell_name, base_field):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | كائن جدول محوري|
| dest_cell_name | str | الخلية الموجودة في الزاوية العلوية اليسرى من نطاق المقطع.|
| base_field | aspose.cells.pivot.PivotField | حقل المحور في PivotTable.BaseFields|

###  مثال

```python

slicers.add(pivot, "I3", pivot.base_fields[0])

```


##  add(self, table, index, dest_cell_name) {#aspose.cells.tables.ListObject-int-str}
إضافة شريحة جديدة باستخدام ListObjet كمصدر بيانات


###  عائدات

مؤشر التقطيع الجديد add


```python

def add(self, table, index, dest_cell_name):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| table | aspose.cells.tables.ListObject | كائن ListObject|
| index | int | فهرس ListColumn في ListObject.ListColumns|
| dest_cell_name | str | الخلية الموجودة في الزاوية العلوية اليسرى من نطاق المقطع.|

###  مثال

```python

slicers.add(table, 1, "E38")

```


##  add(self, table, list_column, dest_cell_name) {#aspose.cells.tables.ListObject-aspose.cells.tables.ListColumn-str}
إضافة شريحة جديدة باستخدام ListObjet كمصدر بيانات


###  عائدات

مؤشر التقطيع الجديد add


```python

def add(self, table, list_column, dest_cell_name):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| table | aspose.cells.tables.ListObject | كائن ListObject|
| list_column | aspose.cells.tables.ListColumn | ListColumn في ListObject.ListColumns|
| dest_cell_name | str | الخلية الموجودة في الزاوية العلوية اليسرى من نطاق المقطع.|

###  مثال

```python

slicers.add(table, table.list_columns[1], "I38")

```


##  add(self, pivot, row, column, base_field_name) {#aspose.cells.pivot.PivotTable-int-int-str}
إضافة شريحة جديدة باستخدام PivotTable كمصدر بيانات


###  عائدات

مؤشر التقطيع الجديد add


```python

def add(self, pivot, row, column, base_field_name):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | كائن جدول محوري|
| row | int | مؤشر الصف للخلية في الزاوية العلوية اليسرى من نطاق المقطع.|
| column | int | فهرس العمود للخلية في الزاوية العلوية اليسرى من نطاق المقطع.|
| base_field_name | str | اسم PivotField في PivotTable.BaseFields|

###  مثال

```python

slicers.add(pivot, 20, 12, "fruit")

```


##  add(self, pivot, row, column, base_field_index) {#aspose.cells.pivot.PivotTable-int-int-int}
إضافة شريحة جديدة باستخدام PivotTable كمصدر بيانات


###  عائدات

مؤشر التقطيع الجديد add


```python

def add(self, pivot, row, column, base_field_index):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | كائن جدول محوري|
| row | int | مؤشر الصف للخلية في الزاوية العلوية اليسرى من نطاق المقطع.|
| column | int | فهرس العمود للخلية في الزاوية العلوية اليسرى من نطاق المقطع.|
| base_field_index | int | فهرس PivotField في PivotTable.BaseFields|

###  مثال

```python

slicers.add(pivot, 20, 8, 0)

```


##  add(self, pivot, row, column, base_field) {#aspose.cells.pivot.PivotTable-int-int-aspose.cells.pivot.PivotField}
إضافة شريحة جديدة باستخدام PivotTable كمصدر بيانات


###  عائدات

مؤشر التقطيع الجديد add


```python

def add(self, pivot, row, column, base_field):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | كائن جدول محوري|
| row | int | مؤشر الصف للخلية في الزاوية العلوية اليسرى من نطاق المقطع.|
| column | int | فهرس العمود للخلية في الزاوية العلوية اليسرى من نطاق المقطع.|
| base_field | aspose.cells.pivot.PivotField | حقل المحور في PivotTable.BaseFields|

###  مثال

```python

slicers.add(pivot, 3, 12, pivot.base_fields[0])

```


##  add(self, table, list_column, row, column) {#aspose.cells.tables.ListObject-aspose.cells.tables.ListColumn-int-int}
إضافة شريحة جديدة باستخدام ListObjet كمصدر بيانات


###  عائدات

مؤشر التقطيع الجديد add


```python

def add(self, table, list_column, row, column):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| table | aspose.cells.tables.ListObject | كائن ListObject|
| list_column | aspose.cells.tables.ListColumn | ListColumn في ListObject.ListColumns|
| row | int | مؤشر الصف للخلية في الزاوية العلوية اليسرى من نطاق المقطع.|
| column | int | فهرس العمود للخلية في الزاوية العلوية اليسرى من نطاق المقطع.|

###  مثال

```python

slicers.add(table, table.list_columns[1], 38, 12)

```



###  أنظر أيضا
* الوحدة [`aspose.cells.slicers`](../../)
* فئة [`SlicerCollection`](/cells/python-net/ar/aspose.cells.slicers/slicercollection)
