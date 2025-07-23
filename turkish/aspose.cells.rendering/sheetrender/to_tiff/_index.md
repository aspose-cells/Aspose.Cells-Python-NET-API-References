---
title: to_tiff yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 70
url: /tr/aspose.cells.rendering/sheetrender/to_tiff/
is_root: false
---
##  to_tiff(self, stream) {#io.RawIOBase}
Tüm çalışma sayfasını Tiff Görüntüsü olarak yayına dönüştürün.



```python

def to_tiff(self, stream):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| stream | io.RawIOBase | çıktı görüntüsünün akışı|


##  to_tiff(self, filename) {#str}
Tüm çalışma sayfasını Tiff Görüntüsü olarak bir dosyaya aktarın.



```python

def to_tiff(self, filename):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| filename | str | çıktı görüntüsünün dosya adı|

###  Örnek

Aşağıdaki kod, ilk sayfanın tüm sayfalarını Tiff görüntüsüne çıktı olarak verir.

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



###  Ayrıca bakınız
* modül [`aspose.cells.rendering`](../../)
* sınıf [`SheetRender`](/cells/python-net/tr/aspose.cells.rendering/sheetrender)
