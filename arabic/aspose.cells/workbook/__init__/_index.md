---
title: Workbook منشئ
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 10
url: /ar/aspose.cells/workbook/__init__/
is_root: false
---
##  \_\_init\_\_(الذات){#}
يقوم بتهيئة مثيل جديد للفئة [`Workbook`](/cells/python-net/ar/aspose.cells/workbook).



```python

def __init__(self):
    ...
```


###  ملاحظات

تنسيق الملف الافتراضي هو Xlsx. لإنشاء أنواع ملفات أخرى، يُرجى استخدام Workbook(FileFormatType).
###  مثال


يُظهر الكود التالي كيفية استخدام المنشئ Workbook لإنشاء مثيل جديد للفئة وتهيئته.

```python
from aspose.cells import Workbook

workbook = Workbook()

```


##  \_\_init\_\_(ذاتي، نوع تنسيق الملف){#aspose.cells.FileFormatType}
يقوم بتهيئة مثيل جديد للفئة [`Workbook`](/cells/python-net/ar/aspose.cells/workbook).



```python

def __init__(self, file_format_type):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| file_format_type | [`FileFormatType`](/cells/python-net/ar/aspose.cells/fileformattype) | تنسيق الملف الجديد.|
###  ملاحظات

نوع تنسيق الملف الافتراضي هو Excel97To2003.
###  مثال


يُظهر الكود التالي كيفية استخدام المنشئ Workbook لإنشاء مثيل جديد للفئة وتهيئته باستخدام نوع تنسيق ملف مختلف.

```python
from aspose.cells import FileFormatType, Workbook

workbook = Workbook(FileFormatType.XLSX)

```


##  \_\_init\_\_(الذات، الملف){#str}
يقوم بتهيئة مثيل جديد لفئة [`Workbook`](/cells/python-net/ar/aspose.cells/workbook) وفتح ملف.



```python

def __init__(self, file):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| file | str | اسم الملف.|


##  \_\_init\_\_(الذات، الدفق){#io.RawIOBase}
يقوم بتهيئة مثيل جديد للفئة [`Workbook`](/cells/python-net/ar/aspose.cells/workbook) وفتح مجرى.



```python

def __init__(self, stream):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| stream | io.RawIOBase | النهر.|


##  \_\_init\_\_(الذات، الملف، خيارات التحميل){#str-aspose.cells.LoadOptions}
يقوم بتهيئة مثيل جديد لفئة [`Workbook`](/cells/python-net/ar/aspose.cells/workbook) وفتح ملف.



```python

def __init__(self, file, load_options):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| file | str | اسم الملف.|
| load_options | [`LoadOptions`](/cells/python-net/ar/aspose.cells/loadoptions) | خيارات التحميل|


##  \_\_init\_\_(الذات، التدفق، خيارات التحميل){#io.RawIOBase-aspose.cells.LoadOptions}
يقوم بتهيئة مثيل جديد لفئة [`Workbook`](/cells/python-net/ar/aspose.cells/workbook) ويفتح مجرى مفتوح.



```python

def __init__(self, stream, load_options):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| stream | io.RawIOBase | النهر.|
| load_options | [`LoadOptions`](/cells/python-net/ar/aspose.cells/loadoptions) | خيارات التحميل|



###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Workbook`](/cells/python-net/ar/aspose.cells/workbook)
