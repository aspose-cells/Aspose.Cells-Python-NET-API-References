---
title: طريقة set_embedded_object
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 200
url: /ar/aspose.cells.drawing/oleobject/set_embedded_object/
is_root: false
---
##  set_embedded_object(self, link_to_file, object_data, source_file_name, display_as_icon, label) {#bool-bytes-str-bool-str}
تعيين بيانات الكائن المضمنة.



```python

def set_embedded_object(self, link_to_file, object_data, source_file_name, display_as_icon, label):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| link_to_file | bool | يشير إلى ما إذا كان الكائن مرتبطًا بالملف. إذا كانت القيمة صحيحة، فسيتم تجاهل المعلمة objectData.|
| object_data | bytes | بيانات الكائن المضمنة.|
| source_file_name | str | اسم الملف.|
| display_as_icon | bool | يشير إلى ما إذا كان سيتم عرض الكائن كأيقونة.<br/> إذا كان هذا صحيحًا، فسيتم تغطية بيانات الصورة الأصلية بواسطة الرمز.|
| label | str | تسمية الأيقونة. تعمل فقط عند ضبط displayAsIcon على "صحيح".|


##  set_embedded_object(self, link_to_file, object_data, source_file_name, display_as_icon, label, update_icon) {#bool-bytes-str-bool-str-bool}
تعيين بيانات الكائن المضمنة.



```python

def set_embedded_object(self, link_to_file, object_data, source_file_name, display_as_icon, label, update_icon):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| link_to_file | bool | يشير إلى ما إذا كان الكائن مرتبطًا بالملف. إذا كانت القيمة صحيحة، فسيتم تجاهل المعلمة objectData.|
| object_data | bytes | بيانات الكائن المضمنة.|
| source_file_name | str | اسم الملف.|
| display_as_icon | bool | يشير إلى ما إذا كان سيتم عرض الكائن كأيقونة.<br/> إذا كان هذا صحيحًا، فسيتم تغطية بيانات الصورة الأصلية بواسطة الرمز.|
| label | str | تسمية الأيقونة. تعمل فقط عند ضبط displayAsIcon على "صحيح".|
| update_icon | bool |يشير إلى ما إذا كان يتم تحديث الرمز تلقائيًا.|
###  ملاحظات

نظرًا لأن Aspose يمكنه تحديث تضمين جميع أيقونات الملفات، فمن الأفضل أن تتمكن من إضافة الرمز الصحيح مع `update_icon` كـ False.


###  أنظر أيضا

* الوحدة [`aspose.cells.drawing`](../../)
* فئة [`OleObject`](/cells/python-net/ar/aspose.cells.drawing/oleobject)
