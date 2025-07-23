---
title: طريقة process
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 20
url: /ar/aspose.cells.lowcode/spreadsheetlocker/process/
is_root: false
---
##  process(، خيارات التحميل، خيارات الحفظ، المزود){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-aspose.cells.lowcode.AbstractLowCodeProtectionProvider}
يقوم بقفل ملف جدول البيانات بالإعدادات المحددة.



```python

@staticmethod
def process(load_options, save_options, provider):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/ar/aspose.cells.lowcode/lowcodeloadoptions) | خيارات الإدخال والتحميل|
| save_options | [`LowCodeSaveOptions`](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptions) | خيارات الإخراج والحفظ|
| provider | [`AbstractLowCodeProtectionProvider`](/cells/python-net/ar/aspose.cells.lowcode/abstractlowcodeprotectionprovider) | التنفيذ لتوفير إعدادات الحماية|


##  process(، ملف القالب، ملف النتيجة، كلمة مرور الفتح، كلمة مرور الكتابة){#str-str-str-str}
يقوم بقفل ملف جدول البيانات بالإعدادات المحددة.



```python

@staticmethod
def process(template_file, result_file, open_password, write_password):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| template_file | str | ملف القالب المراد قفله|
| result_file | str | الملف الناتج|
| open_password | str | كلمة المرور لتشفير الملفات|
| write_password | str |كلمة المرور لحماية تعديل جدول البيانات|


##  process(، خيارات التحميل، خيارات الحفظ، كلمة مرور الفتح، كلمة مرور الكتابة){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-str-str}
يقوم بقفل ملف جدول البيانات بالإعدادات المحددة.



```python

@staticmethod
def process(load_options, save_options, open_password, write_password):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/ar/aspose.cells.lowcode/lowcodeloadoptions) | خيارات الإدخال والتحميل|
| save_options | [`LowCodeSaveOptions`](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptions) | خيارات الإخراج والحفظ|
| open_password | str | كلمة المرور لتشفير الملفات|
| write_password | str |كلمة المرور لحماية تعديل جدول البيانات|


##  process(، خيارات التحميل، خيارات الحفظ، كلمة مرور الفتح، كلمة مرور الكتابة، كلمة مرور المصنف، نوع المصنف){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-str-str-str-aspose.cells.ProtectionType}
يقوم بقفل ملف جدول البيانات بالإعدادات المحددة.



```python

@staticmethod
def process(load_options, save_options, open_password, write_password, workbook_password, workbook_type):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/ar/aspose.cells.lowcode/lowcodeloadoptions) | خيارات الإدخال والتحميل|
| save_options | [`LowCodeSaveOptions`](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptions) | خيارات الإخراج والحفظ|
| open_password | str | كلمة المرور لتشفير الملفات|
| write_password | str |كلمة المرور لحماية تعديل جدول البيانات|
| workbook_password | str | كلمة المرور لحماية المصنف|
| workbook_type | [`ProtectionType`](/cells/python-net/ar/aspose.cells/protectiontype) | نوع الحماية لحماية المصنف|



###  أنظر أيضا
* الوحدة [`aspose.cells.lowcode`](../../)
* فئة [`SpreadsheetLocker`](/cells/python-net/ar/aspose.cells.lowcode/spreadsheetlocker)
