---
title: طريقة set_image_resample
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 20
url: /ar/aspose.cells/pdfsaveoptions/set_image_resample/
is_root: false
---
##  set_image_resample(self, desired_ppi, jpeg_quality) {#int-int}
 تعيين عدد البكسلات لكل بوصة (PPI) المطلوب لصور إعادة العينة وجودة jpeg.
 سيتم تحويل جميع الصور إلى JPEG بإعدادات الجودة المحددة،
وسيتم إعادة أخذ العينات من الصور التي يزيد حجمها عن PPI (بكسل لكل بوصة) المحدد.



```python

def set_image_resample(self, desired_ppi, jpeg_quality):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| desired_ppi | int | عدد البكسلات المطلوبة لكل بوصة. 220 جودة عالية. 150 جودة الشاشة. 96 جودة البريد الإلكتروني.|
| jpeg_quality | int | 0 - 100% JPEG الجودة.|

###  مثال

يقوم الكود التالي بتعيين PPI المطلوب كـ 96 وجودة jpeg كـ 80 للصور في ملف pdf الناتج.

```python
from aspose.cells import PdfSaveOptions, Workbook

# load the source file with images.
wb = Workbook("Book1.xlsx")
pdfSaveOptions = PdfSaveOptions()
# set desired PPI as 96 and jpeg quality as 80.
pdfSaveOptions.set_image_resample(96, 80)
wb.save("output.pdf", pdfSaveOptions)

```



###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`PdfSaveOptions`](/cells/python-net/ar/aspose.cells/pdfsaveoptions)
