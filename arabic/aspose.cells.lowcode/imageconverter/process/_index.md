---
title: طريقة process
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 20
url: /ar/aspose.cells.lowcode/imageconverter/process/
is_root: false
---
##  process(، ملف القالب، ملف النتيجة){#str-str}
تحويل ملف القالب إلى صور.



```python

@staticmethod
def process(template_file, result_file):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| template_file | str | ملف القالب الذي سيتم تحويله إلى صور.|
| result_file | str | الملف الناتج (نمط الاسم) للصور المولدة.|
###  ملاحظات

سيتم إنشاء ملفات الإخراج من ملف النتيجة المحدد
عن طريق إضافة رقم التسلسل للورقة والجزء المقسم.
على سبيل المثال، إذا كان ملف الإخراج المحدد هو Image.png، فسيتم إنشاء الصورة المولدة
ستكون الملفات Image_0_0.png، Image_0_1.png، ...، Image_1_0.png، ...

##  process(، خيارات التحميل، خيارات الحفظ){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions}
تحويل ملف القالب إلى صور



```python

@staticmethod
def process(load_options, save_options):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/ar/aspose.cells.lowcode/lowcodeloadoptions) | خيارات الإدخال والتحميل|
| save_options | [`LowCodeSaveOptions`](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptions) | خيارات الإخراج والحفظ|
###  ملاحظات

عند التحويل إلى صورة بتنسيق يدعم صفحات متعددة (مثل tiff)،
المحدد [`LowCodeSaveOptions.output_file`](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptions#output_file)
أو سيتم استخدام [`LowCodeSaveOptions.output_stream`](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptions#output_stream) مباشرة للصورة الناتجة.


بالنسبة لأنواع أخرى من الصور، إذا كانت خيارات الحفظ قد حددت Stream كإخراج،
ثم سيتم حفظ جميع الصور الناتجة في نفس الدفق.
بخلاف ذلك، سيتم إنشاء ملفات الإخراج من ملف الإخراج المحدد
من خيارات الحفظ عن طريق إضافة رقم التسلسل للورقة والجزء المقسم.
على سبيل المثال، إذا كان ملف الإخراج المحدد هو Image.png، فسيتم إنشاء الصورة المولدة
ستكون الملفات Image_0_0.png، Image_0_1.png، ...، Image_1_0.png، ...

##  process(، خيارات التحميل، خيارات الحفظ، المزود){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-AbstractLowCodeSaveOptionsProvider}




```python

@staticmethod
def process(load_options, save_options, provider):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/ar/aspose.cells.lowcode/lowcodeloadoptions) |  |
| save_options | [`LowCodeSaveOptions`](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptions) |  |
| provider | AbstractLowCodeSaveOptionsProvider |  |



###  أنظر أيضا
* الوحدة [`aspose.cells.lowcode`](../../)
* فئة [`ImageConverter`](/cells/python-net/ar/aspose.cells.lowcode/imageconverter)
