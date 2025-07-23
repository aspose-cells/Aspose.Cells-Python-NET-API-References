---
title: watermark mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 510
url: /tr/aspose.cells/pdfsaveoptions/watermark/
is_root: false
---
##  watermark mülk

watermark'i çıktı olarak alır veya ayarlar.

###  Örnek

Aşağıdaki kod çıktı pdf'inde watermark değerini ayarlar.

```python
from aspose.cells import PaperSizeType, PdfSaveOptions, TextAlignmentType, Workbook
from aspose.cells.rendering import RenderingFont, RenderingWatermark
from aspose.pydrawing import Color

# prepare a workbook with 3 pages.
wb = Workbook()
wb.worksheets[0].cells.get("A1").put_value("Page1")
index = wb.worksheets.add()
wb.worksheets[index].cells.get("A1").put_value("Page2")
index = wb.worksheets.add()
wb.worksheets[index].cells.get("A1").put_value("Page3")
wb.worksheets[index].page_setup.paper_size = PaperSizeType.PAPER_A3
# create a font for watermark, and specify bold, italic, color
font = RenderingFont("Calibri", 68)
font.italic = True
font.bold = True
font.color = Color.blue
# create a watermark from text and the specified font
watermark = RenderingWatermark("Watermark", font)
# specify horizontal and vertical alignment
watermark.h_alignment = TextAlignmentType.CENTER
watermark.v_alignment = TextAlignmentType.CENTER
# specify rotation
watermark.rotation = 30.0
# specify opacity
watermark.opacity = 0.6
# specify the scale to page(e.g. 100, 50) in percent.
watermark.scale_to_page_percent = 50
# spcify watermark for rendering to pdf.
options = PdfSaveOptions()
options.watermark = watermark
wb.save("output_watermark.pdf", options)

```
###  Tanım:
```python
@property
def watermark(self):
    ...
@watermark.setter
def watermark(self, value):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`PdfSaveOptions`](/cells/python-net/tr/aspose.cells/pdfsaveoptions)
* sınıf [`RenderingWatermark`](/cells/python-net/tr/aspose.cells.rendering/renderingwatermark)
