---
title: طريقة merge
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 800
url: /ar/aspose.cells/cells/merge/
is_root: false
---
##  merge(self, first_row, first_column, total_rows, total_columns) {#int-int-int-int}
دمج نطاق محدد من الخلايا في خلية واحدة.



```python

def merge(self, first_row, first_column, total_rows, total_columns):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| first_row | int | الصف الأول من هذا النطاق (يعتمد على الصفر)|
| first_column | int | العمود الأول من هذا النطاق (يعتمد على الصفر)|
| total_rows | int |عدد الصفوف (على أساس واحد)|
| total_columns | int | عدد الأعمدة (على أساس واحد)|
###  ملاحظات

قم بالإشارة إلى الخلية المدمجة من خلال عنوان الخلية العلوية اليسرى في النطاق.

##  merge(self, first_row, first_column, total_rows, total_columns, merge_conflict) {#int-int-int-int-bool}

دمج نطاق محدد من الخلايا في خلية واحدة.



```python

def merge(self, first_row, first_column, total_rows, total_columns, merge_conflict):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| first_row | int | الصف الأول من هذا النطاق (يعتمد على الصفر)|
| first_column | int | العمود الأول من هذا النطاق (يعتمد على الصفر)|
| total_rows | int |عدد الصفوف (على أساس واحد)|
| total_columns | int | عدد الأعمدة (على أساس واحد)|
| merge_conflict | bool | دمج نطاقات الدمج المتعارضة.|
###  ملاحظات

قم بالإشارة إلى الخلية المدمجة من خلال عنوان الخلية العلوية اليسرى في النطاق.
إذا كانت mergeConflict صحيحة وكان النطاق المدمج يتعارض مع الخلايا المدمجة الأخرى،
سيتم إزالة الخلايا المدمجة الأخرى تلقائيًا.

##  merge(self, first_row, first_column, total_rows, total_columns, check_conflict, merge_conflict) {#int-int-int-int-bool-bool}
دمج نطاق محدد من الخلايا في خلية واحدة.



```python

def merge(self, first_row, first_column, total_rows, total_columns, check_conflict, merge_conflict):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| first_row | int | الصف الأول من هذا النطاق (يعتمد على الصفر)|
| first_column | int | العمود الأول من هذا النطاق (يعتمد على الصفر)|
| total_rows | int |عدد الصفوف (على أساس واحد)|
| total_columns | int | عدد الأعمدة (على أساس واحد)|
| check_conflict | bool | يشير إلى ما إذا كان التحقق من تقاطع الخلايا المدمجة مع الخلايا المدمجة الأخرى|
| merge_conflict | bool | دمج نطاقات الدمج المتعارضة.|
###  ملاحظات

قم بالإشارة إلى الخلية المدمجة من خلال عنوان الخلية العلوية اليسرى في النطاق.
إذا كانت mergeConflict صحيحة وكان النطاق المدمج يتعارض مع الخلايا المدمجة الأخرى،
سيتم إزالة الخلايا المدمجة الأخرى تلقائيًا.


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Cells`](/cells/python-net/ar/aspose.cells/cells)
