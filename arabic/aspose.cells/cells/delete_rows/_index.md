---
title: طريقة delete_rows
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 260
url: /ar/aspose.cells/cells/delete_rows/
is_root: false
---
##  delete_rows {#int-int}
حذف عدة صفوف.



```python
def delete_rows(self, row_index, total_rows):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| row_index | int | فهرس الصف الأول المراد حذفه.|
| total_rows | int | عدد الصفوف المراد حذفها.|
###  ملاحظات

إذا كان النطاق المحذوف يحتوي على الجزء العلوي (وليس بالكامل) من الجدول (ListObject)،
لا يمكن حذف النطاق ولن يتم فعل أي شيء.
إنه يعمل بنفس الطريقة مع MS Excel.

##  delete_rows {#int-int-bool}
حذف صفوف متعددة في ورقة العمل.


###  عائدات




```python
def delete_rows(self, row_index, total_rows, update_reference):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| row_index | int | فهرس الصف الأول المراد حذفه.|
| total_rows | int | عدد الصفوف المراد حذفها.|
| update_reference | bool | يشير إلى ما إذا كانت مراجع التحديث موجودة في أوراق العمل الأخرى.|



###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Cells`](/cells/python-net/ar/aspose.cells/cells)
