---
title: printing_page_type mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 250
url: /tr/aspose.cells/pptxsaveoptions/printing_page_type/
is_root: false
---
##  printing_page_type mülk

Hangi sayfaların yazdırılmayacağını belirtir.

###  Notlar

Sayfadaki içerik seyrekse, çıktı pdf dosyasında bazı sayfalar tamamen boş olacaktır.
Bu boş sayfaları istemiyorsanız bu seçeneği kullanarak bunları atlayabilirsiniz.

###  Örnek

Aşağıdaki kod, boş sayfaları veya yalnızca hücre arka planı, kenarlıklar gibi bazı stil içeriğini içeren sayfaları atlar.

```python
from aspose.cells import PdfSaveOptions, PrintingPageType, Workbook

wb = Workbook("Book1.xlsx")
pdfSaveOptions = PdfSaveOptions()
# ignore blank pages
pdfSaveOptions.printing_page_type = PrintingPageType.IGNORE_BLANK
wb.save("output_ignore_blank_page.pdf", pdfSaveOptions)
# ignore blank pages and pages which only contains some style content like cell background
pdfSaveOptions.printing_page_type = PrintingPageType.IGNORE_STYLE
wb.save("output_ignore_blank_and_style_page.pdf", pdfSaveOptions)

```
###  Tanım:
```python
@property
def printing_page_type(self):
    ...
@printing_page_type.setter
def printing_page_type(self, value):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`PptxSaveOptions`](/cells/python-net/tr/aspose.cells/pptxsaveoptions)
* sınıf [`PrintingPageType`](/cells/python-net/tr/aspose.cells/printingpagetype)
