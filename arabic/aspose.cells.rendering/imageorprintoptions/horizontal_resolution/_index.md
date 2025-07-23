---
title: horizontal_resolution عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 150
url: /ar/aspose.cells.rendering/imageorprintoptions/horizontal_resolution/
is_root: false
---
##  horizontal_resolution عقار

يحصل على الدقة الأفقية للصور المولدة أو يضبطها، بنقاط لكل بوصة.

###  ملاحظات

القيمة الافتراضية هي 96.


الإعداد [`ImageOrPrintOptions.horizontal_resolution`](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions#horizontal_resolution) و [`ImageOrPrintOptions.vertical_resolution`](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions#vertical_resolution) 
يؤثر على عرض وارتفاع الصورة الناتجة بالبكسل.

###  مثال

 يقوم الكود التالي بتعيين الدقة إلى 192، وعرض وارتفاع الصورة المولدة هو ضعف
الذي تم ترك الدقة فيه كقيمة افتراضية 96.

```python
from aspose.cells import Workbook
from aspose.cells.drawing import ImageType
from aspose.cells.rendering import ImageOrPrintOptions, SheetRender

wb = Workbook("Book1.xlsx")
opts = ImageOrPrintOptions()
# Set output image type: png.
opts.image_type = ImageType.PNG
# Set resolution to 192.
opts.horizontal_resolution = 192
opts.vertical_resolution = 192
# Render worksheet page to image.
sr = SheetRender(wb.worksheets[0], opts)
sr.to_image(0, "Sheet_Page1.png")

```
###  تعريف:
```python
@property
def horizontal_resolution(self):
    ...
@horizontal_resolution.setter
def horizontal_resolution(self, value):
    ...
```

###  أنظر أيضا
* الوحدة [`aspose.cells.rendering`](../../)
* فئة [`ImageOrPrintOptions`](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions)
