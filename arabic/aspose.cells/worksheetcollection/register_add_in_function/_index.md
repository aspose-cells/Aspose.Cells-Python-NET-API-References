---
title: طريقة register_add_in_function
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 180
url: /ar/aspose.cells/worksheetcollection/register_add_in_function/
is_root: false
---
##  register_add_in_function(self, id, function_name) {#int-str}
إضافة وظيفة إضافية إلى المصنف


###  عائدات

عنوان URL لملف الإضافة الذي يحتوي على وظائف الإضافة


```python

def register_add_in_function(self, id, function_name):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| id | int |معرف البيانات التي تحتوي على وظائف الإضافة،<br/> يمكن الحصول عليها من خلال المكالمة الأولى على الرقم [`WorksheetCollection.register_add_in_function`](/cells/python-net/ar/aspose.cells/worksheetcollection/register_add_in_function) لنفس الملف الإضافي.|
| function_name | str | اسم وظيفة الإضافة|


##  register_add_in_function(self, add_in_file, function_name, lib) {#str-str-bool}
إضافة وظيفة إضافية إلى المصنف


###  عائدات

معرف البيانات التي تحتوي على وظيفة الإضافة المحددة


```python

def register_add_in_function(self, add_in_file, function_name, lib):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| add_in_file | str | يحتوي الملف على وظائف الإضافة|
| function_name | str | اسم وظيفة الإضافة|
| lib | bool | ما إذا كان ملف الإضافة المحدد موجودًا في الدليل أو الدليل الفرعي لمكتبة Workbook Add-In.<br/>يسري هذا العلم ويحدث فرقًا عندما يكون addInFile الخاص به على مسار نسبي:<br/> يشير true إلى أن المسار نسبي لمكتبة Add-In ويشير false إلى أن المسار نسبي لهذا المصنف.|



###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`WorksheetCollection`](/cells/python-net/ar/aspose.cells/worksheetcollection)
