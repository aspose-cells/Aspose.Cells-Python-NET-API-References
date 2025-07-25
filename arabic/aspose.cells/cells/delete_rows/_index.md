---
title: طريقة delete_rows
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 260
url: /ar/aspose.cells/cells/delete_rows/
is_root: false
---
##  delete_rows(self, row_index, total_rows) {#int-int}
حذف صفوف متعددة.



```python

def delete_rows(self, row_index, total_rows):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| row_index | int | فهرس الصف الأول الذي سيتم حذفه.|
| total_rows | int | عدد الصفوف المراد حذفها.|
###  ملاحظات

إذا كان النطاق المحذوف يحتوي على الجزء العلوي (وليس كله) من الجدول (ListObject)،
لم يتمكن من حذف النطاق ولن يتم فعل أي شيء.
يعمل بنفس الطريقة مع MS Excel.

##  delete_rows(self, row_index, total_rows, update_reference) {#int-int-bool}
حذف صفوف متعددة في ورقة العمل.


###  عائدات




```python

def delete_rows(self, row_index, total_rows, update_reference):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| row_index | int | فهرس الصف الأول الذي سيتم حذفه.|
| total_rows | int | عدد الصفوف المراد حذفها.|
| update_reference | bool | يشير إلى ما إذا كان يتم تحديث المراجع في أوراق العمل الأخرى.|


##  delete_rows(self, row_index, total_rows, options) {#int-int-aspose.cells.DeleteOptions}
حذف صفوف متعددة في ورقة العمل.


###  عائدات




```python

def delete_rows(self, row_index, total_rows, options):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| row_index | int | فهرس الصف الأول الذي سيتم حذفه.|
| total_rows | int | عدد الصفوف المراد حذفها.|
| options | [`DeleteOptions`](/cells/python-net/ar/aspose.cells/deleteoptions) | خيارات لعملية الحذف|



###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Cells`](/cells/python-net/ar/aspose.cells/cells)
