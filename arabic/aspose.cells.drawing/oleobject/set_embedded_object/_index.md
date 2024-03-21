---
title: طريقة set_embedded_object
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 190
url: /ar/aspose.cells.drawing/oleobject/set_embedded_object/
is_root: false
---
##  set_embedded_object {#bool-bytes-str-bool-str}
يضبط بيانات الكائن المضمنة.



```python
def set_embedded_object(self, link_to_file, object_data, source_file_name, display_as_icon, label):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| link_to_file | bool | يشير إلى ما إذا كان الكائن يرتبط بالملف. إذا كان صحيحًا، فسيتم تجاهل المعلمة objectData.|
| object_data | bytes | بيانات الكائن المضمنة.|
| source_file_name | str | اسم الملف.|
| display_as_icon | bool | يشير إلى ما إذا كان سيتم عرض الكائن كرمز.<br/> إذا كان هذا صحيحًا، فسيتم تغطية بيانات الصورة الأصلية بالرمز.|
| label | str | تسمية الأيقونة. يعمل فقط عندما يكون DisplayAsIcon صحيحًا.|


##  set_embedded_object {#bool-bytes-str-bool-str-bool}
يضبط بيانات الكائن المضمنة.



```python
def set_embedded_object(self, link_to_file, object_data, source_file_name, display_as_icon, label, update_icon):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| link_to_file | bool | يشير إلى ما إذا كان الكائن يرتبط بالملف. إذا كان صحيحًا، فسيتم تجاهل المعلمة objectData.|
| object_data | bytes | بيانات الكائن المضمنة.|
| source_file_name | str | اسم الملف.|
| display_as_icon | bool | يشير إلى ما إذا كان سيتم عرض الكائن كرمز.<br/> إذا كان هذا صحيحًا، فسيتم تغطية بيانات الصورة الأصلية بالرمز.|
| label | str | تسمية الأيقونة. يعمل فقط عندما يكون DisplayAsIcon صحيحًا.|
| update_icon | bool |يشير إلى ما إذا كان سيتم تحديث الرمز تلقائيًا.|
###  ملاحظات

نظرًا لأن Aspose يمكنه تحديث تضمين جميع أيقونات الملفات، فمن الأفضل أن تتمكن من إضافة الرمز الصحيح مع `update_icon` كخطأ.


###  أنظر أيضا

* الوحدة [`aspose.cells.drawing`](../../)
* فئة [`OleObject`](/cells/python-net/ar/aspose.cells.drawing/oleobject)
