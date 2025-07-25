---
title: طريقة process
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 20
url: /ar/aspose.cells.lowcode/spreadsheetsplitter/process/
is_root: false
---
##  process(, الخيارات){#aspose.cells.lowcode.LowCodeSplitOptions}
تقسيم ملف جدول البيانات إلى أجزاء متعددة.



```python

@staticmethod
def process(options):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| options | [`LowCodeSplitOptions`](/cells/python-net/ar/aspose.cells.lowcode/lowcodesplitoptions) | خيارات تقسيم جدول البيانات|


##  process(، ملف القالب، ملف النتيجة){#str-str}
تقسيم ملف القالب المعطى إلى أجزاء متعددة.



```python

@staticmethod
def process(template_file, result_file):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| template_file | str | ملف القالب المراد تقسيمه|
| result_file | str | الملف الناتج (نمط الاسم)|
###  ملاحظات

سيتم إنشاء ملفات الإخراج من الملف الناتج المحدد بواسطة
إضافة رقم التسلسل للورقة والجزء المنقسم.
على سبيل المثال، إذا كان ملف الإخراج المحدد هو Split.xlsx، فسيتم إنشاء الملف الناتج
ستكون الملفات Split_0_0.xlsx، وSplit_0_1.xlsx، و...، وSplit_1_0.xlsx، و...


###  أنظر أيضا
* الوحدة [`aspose.cells.lowcode`](../../)
* فئة [`SpreadsheetSplitter`](/cells/python-net/ar/aspose.cells.lowcode/spreadsheetsplitter)
