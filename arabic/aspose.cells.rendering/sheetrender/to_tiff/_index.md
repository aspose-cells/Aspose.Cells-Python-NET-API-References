---
title: طريقة to_tiff
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 70
url: /ar/aspose.cells.rendering/sheetrender/to_tiff/
is_root: false
---
##  to_tiff {#io.RawIOBase}
قم بعرض ورقة العمل بأكملها كصورة Tiff للبث.



```python
def to_tiff(self, stream):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| stream | io.RawIOBase | دفق صورة الإخراج|


##  to_tiff {#str}
تقديم ورقة العمل بأكملها كصورة Tiff إلى ملف.



```python
def to_tiff(self, filename):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| filename | str | اسم الملف لصورة الإخراج|

###  مثال

يقوم التعليمة البرمجية التالية بإخراج كافة صفحات الورقة الأولى إلى صورة Tiff.

```python
from aspose.cells import SaveFormat, Workbook
from aspose.cells.rendering import ImageOrPrintOptions, SheetRender

# load the source file with images.
wb = Workbook("Book1.xlsx")
imgOpt = ImageOrPrintOptions()
# set output image type.
imgOpt.save_format = SaveFormat.TIFF
# render the first sheet.
sr = SheetRender(wb.worksheets[0], imgOpt)
# output all the pages of the sheet to Tiff image.
sr.to_tiff("output.tiff")

```



###  أنظر أيضا
* الوحدة [`aspose.cells.rendering`](../../)
* فئة [`SheetRender`](/cells/python-net/ar/aspose.cells.rendering/sheetrender)
