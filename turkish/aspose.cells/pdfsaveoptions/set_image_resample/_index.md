---
title: set_image_resample yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 20
url: /tr/aspose.cells/pdfsaveoptions/set_image_resample/
is_root: false
---
##  set_image_resample(self, desired_ppi, jpeg_quality) {#int-int}
 Yeniden örnekleme görüntülerinin istenilen PPI'sini (inç başına piksel) ve jpeg kalitesini ayarlar.
 Tüm görseller belirtilen kalite ayarıyla JPEG'e dönüştürülecektir.
ve belirtilen PPI'dan (inç başına piksel) daha büyük olan görüntüler yeniden örneklenecektir.



```python

def set_image_resample(self, desired_ppi, jpeg_quality):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| desired_ppi | int | İstenilen inç başına piksel sayısı. 220 yüksek kalite. 150 ekran kalitesi. 96 e-posta kalitesi.|
| jpeg_quality | int | 0 - 100% JPEG kalite.|

###  Örnek

Aşağıdaki kod çıktı pdf'deki resimler için istenilen PPI değerini 96, jpeg kalitesini ise 80 olarak ayarlar.

```python
from aspose.cells import PdfSaveOptions, Workbook

# load the source file with images.
wb = Workbook("Book1.xlsx")
pdfSaveOptions = PdfSaveOptions()
# set desired PPI as 96 and jpeg quality as 80.
pdfSaveOptions.set_image_resample(96, 80)
wb.save("output.pdf", pdfSaveOptions)

```



###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`PdfSaveOptions`](/cells/python-net/tr/aspose.cells/pdfsaveoptions)
