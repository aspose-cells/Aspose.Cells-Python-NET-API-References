---
title: page_count mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 190
url: /tr/aspose.cells/xpssaveoptions/page_count/
is_root: false
---
##  page_count mülk

Kaydedilecek sayfa sayısını alır veya ayarlar.

###  Notlar

Varsayılan, System.Int32.MaxValue'dur; bu, tüm sayfaların oluşturulacağı anlamına gelir.

###  Örnek

Aşağıdaki örnek, Microsoft Excel dosyasındaki bir sayfa aralığının (3 ve 4) PDF'e nasıl dönüştürüleceğini gösterir.

```python
from aspose.cells import PdfSaveOptions, Workbook

# Open an Excel file
wb = Workbook("Book1.xlsx")
options = PdfSaveOptions()
# Print only Page 3 and Page 4 in the output PDF
# Starting page index (0-based index)
options.page_index = 3
# Number of pages to be printed
options.page_count = 2
# Save the PDF file
wb.save("output.pdf", options)

```
###  Tanım:
```python
@property
def page_count(self):
    ...
@page_count.setter
def page_count(self, value):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`XpsSaveOptions`](/cells/python-net/tr/aspose.cells/xpssaveoptions)
