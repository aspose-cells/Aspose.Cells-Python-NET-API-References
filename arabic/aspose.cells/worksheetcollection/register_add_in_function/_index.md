---
title: طريقة register_add_in_function
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 180
url: /ar/aspose.cells/worksheetcollection/register_add_in_function/
is_root: false
---
##  register_add_in_function {#int-str}
يضيف وظيفة الوظيفة الإضافية إلى المصنف


###  عائدات

عنوان URL لملف الوظيفة الإضافية الذي يحتوي على وظائف الوظيفة الإضافية


```python
def register_add_in_function(self, id, function_name):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| id | int | معرف البيانات التي تحتوي على وظائف الوظيفة الإضافية،<br/> يمكن الحصول عليها عن طريق الاتصال الأول على الرقم [`WorksheetCollection.register_add_in_function`](/cells/python-net/ar/aspose.cells/worksheetcollection/register_add_in_function) لنفس الملف الإضافي.|
| function_name | str | اسم الوظيفة الإضافية|


##  register_add_in_function {#str-str-bool}
يضيف وظيفة الوظيفة الإضافية إلى المصنف


###  عائدات

معرف البيانات التي تحتوي على وظيفة الوظيفة الإضافية المحددة


```python
def register_add_in_function(self, add_in_file, function_name, lib):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| add_in_file | str | يحتوي الملف على وظائف الوظيفة الإضافية|
| function_name | str | اسم الوظيفة الإضافية|
| lib | bool | ما إذا كان ملف الوظيفة الإضافية المحدد موجودًا في الدليل أو الدليل الفرعي لمكتبة Workbook Add-In.<br/>تصبح هذه العلامة سارية المفعول وتُحدث فرقًا عندما يكون ملف addInFile ذو مسار نسبي:<br/> يشير "صحيح" إلى أن المسار مرتبط بمكتبة الوظائف الإضافية ويشير "خطأ" إلى أن المسار مرتبط بهذا المصنف.|



###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`WorksheetCollection`](/cells/python-net/ar/aspose.cells/worksheetcollection)
