---
title: طريقة add
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 20
url: /ar/aspose.cells.pivot/pivottablecollection/add/
is_root: false
---
##  add(self, source_data, dest_cell_name, table_name) {#str-str-str}
إضافة جدول محوري جديد.


###  عائدات

تمت إضافة مؤشر ذاكرة التخزين المؤقت الجديد.


```python

def add(self, source_data, dest_cell_name, table_name):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| source_data | str | البيانات الخاصة بمخزن البيانات المؤقت الجديد لـ PivotTable.|
| dest_cell_name | str | الخلية الموجودة في الزاوية العلوية اليسرى من نطاق وجهة تقرير الجدول المحوري.|
| table_name | str | اسم تقرير PivotTable الجديد.|


##  add(self, pivot_table, dest_cell_name, table_name) {#aspose.cells.pivot.PivotTable-str-str}
إضافة جدول محوري جديد استنادًا إلى جدول محوري آخر.


###  عائدات

الفهرس الجديد المضاف إلى جدول البيانات المحوري.


```python

def add(self, pivot_table, dest_cell_name, table_name):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| pivot_table | [`PivotTable`](/cells/python-net/ar/aspose.cells.pivot/pivottable) | المصدر pivotTable.|
| dest_cell_name | str | الخلية الموجودة في الزاوية العلوية اليسرى من نطاق وجهة تقرير الجدول المحوري.|
| table_name | str | اسم تقرير PivotTable الجديد.|


##  add(self, source_data, dest_cell_name, table_name, use_same_source) {#str-str-str-bool}
إضافة جدول محوري جديد.


###  عائدات

تمت إضافة مؤشر ذاكرة التخزين المؤقت الجديد.


```python

def add(self, source_data, dest_cell_name, table_name, use_same_source):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| source_data | str | البيانات الخاصة بمخزن البيانات المؤقت الجديد لـ PivotTable.|
| dest_cell_name | str | الخلية الموجودة في الزاوية العلوية اليسرى من نطاق وجهة تقرير الجدول المحوري.|
| table_name | str | اسم تقرير PivotTable الجديد.|
| use_same_source | bool | يشير إلى ما إذا كان يتم استخدام نفس مصدر البيانات عندما استخدم جدول محوري آخر موجود مصدر البيانات هذا.<br/> إذا كانت الخاصية صحيحة، فسوف توفر الذاكرة.|


##  add(self, source_data, row, column, table_name) {#str-int-int-str}
إضافة جدول محوري جديد.


###  عائدات

تمت إضافة مؤشر ذاكرة التخزين المؤقت الجديد.


```python

def add(self, source_data, row, column, table_name):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| source_data | str | نطاق خلايا البيانات لجدول البيانات المحوري الجديد. مثال: Sheet1!A1:C8|
| row | int |فهرس الصف للخلية في الزاوية العلوية اليسرى من نطاق وجهة تقرير الجدول المحوري.|
| column | int | فهرس العمود للخلية الموجودة في الزاوية العلوية اليسرى من نطاق وجهة تقرير الجدول المحوري.|
| table_name | str | اسم تقرير PivotTable الجديد.|


##  add(self, pivot_table, row, column, table_name) {#aspose.cells.pivot.PivotTable-int-int-str}
إضافة جدول محوري جديد استنادًا إلى جدول محوري آخر.


###  عائدات

الفهرس الجديد المضاف إلى جدول البيانات المحوري.


```python

def add(self, pivot_table, row, column, table_name):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| pivot_table | [`PivotTable`](/cells/python-net/ar/aspose.cells.pivot/pivottable) | المصدر pivotTable.|
| row | int |فهرس الصف للخلية في الزاوية العلوية اليسرى من نطاق وجهة تقرير الجدول المحوري.|
| column | int | فهرس العمود للخلية الموجودة في الزاوية العلوية اليسرى من نطاق وجهة تقرير الجدول المحوري.|
| table_name | str | اسم تقرير PivotTable الجديد.|


##  add(self, source_data, row, column, table_name, use_same_source) {#str-int-int-str-bool}
إضافة جدول محوري جديد.


###  عائدات

تمت إضافة مؤشر ذاكرة التخزين المؤقت الجديد.


```python

def add(self, source_data, row, column, table_name, use_same_source):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| source_data | str | نطاق خلايا البيانات لجدول البيانات المحوري الجديد. مثال: Sheet1!A1:C8|
| row | int |فهرس الصف للخلية في الزاوية العلوية اليسرى من نطاق وجهة تقرير الجدول المحوري.|
| column | int | فهرس العمود للخلية الموجودة في الزاوية العلوية اليسرى من نطاق وجهة تقرير الجدول المحوري.|
| table_name | str | اسم تقرير PivotTable الجديد.|
| use_same_source | bool | يشير إلى ما إذا كان يتم استخدام نفس مصدر البيانات عندما استخدم جدول محوري آخر موجود مصدر البيانات هذا.<br/> إذا كانت الخاصية صحيحة، فسوف توفر الذاكرة.|


##  add(self, source_data, cell, table_name, use_same_source, is_xls_classic) {#str-str-str-bool-bool}
إضافة جدول محوري جديد.


###  عائدات

تمت إضافة مؤشر ذاكرة التخزين المؤقت الجديد.


```python

def add(self, source_data, cell, table_name, use_same_source, is_xls_classic):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| source_data | str | نطاق خلايا البيانات لجدول البيانات المحوري الجديد. مثال: Sheet1!A1:C8|
| cell | str | الخلية الموجودة في الزاوية العلوية اليسرى من نطاق وجهة تقرير الجدول المحوري.|
| table_name | str | اسم تقرير PivotTable الجديد.|
| use_same_source | bool | يشير إلى ما إذا كان يتم استخدام نفس مصدر البيانات عندما استخدم جدول محوري آخر موجود مصدر البيانات هذا.<br/> إذا كانت الخاصية صحيحة، فسوف توفر الذاكرة.|
| is_xls_classic | bool | يشير إلى ما إذا كان من الممكن إضافة جدول محوري كلاسيكي لـ Excel 97-2003.|


##  add(self, source_data, is_auto_page, page_fields, dest_cell_name, table_name) {#list-bool-aspose.cells.pivot.PivotPageFields-str-str}
إضافة كائن جدول محوري جديد إلى المجموعة التي تحتوي على نطاقات توحيد متعددة كمصدر بيانات.


###  عائدات

الفهرس الجديد المضاف إلى جدول البيانات المحوري.


```python

def add(self, source_data, is_auto_page, page_fields, dest_cell_name, table_name):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| source_data | list | نطاقات التوحيد المتعددة، مثل {"Sheet1!A1:C8","Sheet2!A1:B8"} |
| is_auto_page | bool | ما إذا كان سيتم إنشاء حقل صفحة واحدة تلقائيًا.<br/> إذا كانت القيمة صحيحة، فسيتم تجاهل معلمة الصفحة التالية:|
| page_fields | [`PivotPageFields`](/cells/python-net/ar/aspose.cells.pivot/pivotpagefields) | عناصر حقل الصفحة المحورية.|
| dest_cell_name | str | destCellName اسم تقرير PivotTable الجديد.|
| table_name | str | اسم تقرير PivotTable الجديد.|


##  add(self, source_data, row, column, table_name, use_same_source, is_xls_classic) {#str-int-int-str-bool-bool}
إضافة جدول محوري جديد.


###  عائدات

تمت إضافة مؤشر ذاكرة التخزين المؤقت الجديد.


```python

def add(self, source_data, row, column, table_name, use_same_source, is_xls_classic):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| source_data | str | نطاق خلايا البيانات لجدول البيانات المحوري الجديد. مثال: Sheet1!A1:C8|
| row | int |فهرس الصف للخلية في الزاوية العلوية اليسرى من نطاق وجهة تقرير الجدول المحوري.|
| column | int | فهرس العمود للخلية الموجودة في الزاوية العلوية اليسرى من نطاق وجهة تقرير الجدول المحوري.|
| table_name | str | اسم تقرير PivotTable الجديد.|
| use_same_source | bool | يشير إلى ما إذا كان يتم استخدام نفس مصدر البيانات عندما استخدم جدول محوري آخر موجود مصدر البيانات هذا.<br/> إذا كانت الخاصية صحيحة، فسوف توفر الذاكرة.|
| is_xls_classic | bool | يشير إلى ما إذا كان من الممكن إضافة جدول محوري كلاسيكي لـ Excel 97-2003.|


##  add(self, source_data, is_auto_page, page_fields, row, column, table_name) {#list-bool-aspose.cells.pivot.PivotPageFields-int-int-str}
إضافة كائن جدول محوري جديد إلى المجموعة التي تحتوي على نطاقات توحيد متعددة كمصدر بيانات.


###  عائدات

الفهرس الجديد المضاف إلى جدول البيانات المحوري.


```python

def add(self, source_data, is_auto_page, page_fields, row, column, table_name):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| source_data | list | نطاقات التوحيد المتعددة، مثل {"Sheet1!A1:C8","Sheet2!A1:B8"} |
| is_auto_page | bool | ما إذا كان سيتم إنشاء حقل صفحة واحدة تلقائيًا.<br/> إذا كانت القيمة صحيحة، فسيتم تجاهل المعلمة pageFields التالية|
| page_fields | [`PivotPageFields`](/cells/python-net/ar/aspose.cells.pivot/pivotpagefields) | عناصر حقل الصفحة المحورية.|
| row | int |فهرس الصف للخلية في الزاوية العلوية اليسرى من نطاق وجهة تقرير الجدول المحوري.|
| column | int | فهرس العمود للخلية الموجودة في الزاوية العلوية اليسرى من نطاق وجهة تقرير الجدول المحوري.|
| table_name | str | اسم تقرير PivotTable الجديد.|



###  أنظر أيضا
* الوحدة [`aspose.cells.pivot`](../../)
* فئة [`PivotTableCollection`](/cells/python-net/ar/aspose.cells.pivot/pivottablecollection)
