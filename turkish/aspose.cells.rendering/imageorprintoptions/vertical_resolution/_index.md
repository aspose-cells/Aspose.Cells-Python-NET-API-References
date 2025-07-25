---
title: vertical_resolution mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 400
url: /tr/aspose.cells.rendering/imageorprintoptions/vertical_resolution/
is_root: false
---
##  vertical_resolution mülk

Oluşturulan görüntülerin dikey çözünürlüğünü inç başına nokta cinsinden alır veya ayarlar.

###  Notlar

Varsayılan değer 96'dır.


[`ImageOrPrintOptions.horizontal_resolution`](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions#horizontal_resolution) ve [`ImageOrPrintOptions.vertical_resolution`](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions#vertical_resolution) Ayarı 
Çıkış görüntüsünün piksel cinsinden genişliğini ve yüksekliğini etkiler.

###  Örnek

 Aşağıdaki kod çözünürlüğü 192'ye ayarlar, oluşturulan görüntünün genişliği ve yüksekliği iki katıdır
çözünürlüğü varsayılan değer olarak 96 olarak bırakılan.

```python
from aspose.cells import Workbook
from aspose.cells.drawing import ImageType
from aspose.cells.rendering import ImageOrPrintOptions

wb = Workbook("Book1.xlsx")
opts = ImageOrPrintOptions()
# Set output image type: png.
opts.image_type = ImageType.PNG
# Set resolution to 192.
opts.horizontal_resolution = 192
opts.vertical_resolution = 192
# Render Chart to image.
wb.worksheets[0].charts[0].to_image("Chart.png", opts)

```
###  Tanım:
```python
@property
def vertical_resolution(self):
    ...
@vertical_resolution.setter
def vertical_resolution(self, value):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells.rendering`](../../)
* sınıf [`ImageOrPrintOptions`](/cells/python-net/tr/aspose.cells.rendering/imageorprintoptions)
