---
title: PictureCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 440
url: /tr/aspose.cells.drawing/picturecollection/
is_root: false
---
##  PictureCollection sınıfı
[`Picture`](/cells/python-net/tr/aspose.cells.drawing/picture) nesneden oluşan bir koleksiyonu kapsüller.



PictureCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [capacity](/cells/python-net/tr/aspose.cells.drawing/picturecollection/capacity) | Dizi listesinin içerebileceği eleman sayısını alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream)`](/cells/python-net/tr/aspose.cells.drawing/picturecollection/add/#int-int-int-int-io.rawiobase) | Koleksiyona bir resim ekler.|
| [`add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, file_name)`](/cells/python-net/tr/aspose.cells.drawing/picturecollection/add/#int-int-int-int-str) | Koleksiyona bir resim ekler.|
| [`add(self, upper_left_row, upper_left_column, stream)`](/cells/python-net/tr/aspose.cells.drawing/picturecollection/add/#int-int-io.rawiobase) | Koleksiyona bir resim ekler.|
| [`add(self, upper_left_row, upper_left_column, file_name)`](/cells/python-net/tr/aspose.cells.drawing/picturecollection/add/#int-int-str) | Koleksiyona bir resim ekler.|
| [`add(self, upper_left_row, upper_left_column, stream, width_scale, height_scale)`](/cells/python-net/tr/aspose.cells.drawing/picturecollection/add/#int-int-io.rawiobase-int-int) | Koleksiyona bir resim ekler.|
| [`add(self, upper_left_row, upper_left_column, file_name, width_scale, height_scale)`](/cells/python-net/tr/aspose.cells.drawing/picturecollection/add/#int-int-str-int-int) | Koleksiyona bir resim ekler.|
| [`copy_to(self, array)`](/cells/python-net/tr/aspose.cells.drawing/picturecollection/copy_to/#list) |Hedef dizi listesinin başından başlayarak tüm dizi listesini uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/tr/aspose.cells.drawing/picturecollection/copy_to/#int-list-int-int) | Hedef dizi listesinin belirtilen indeksinden başlayarak, dizi listesindeki bir dizi öğeyi uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`index_of(self, item, index)`](/cells/python-net/tr/aspose.cells.drawing/picturecollection/index_of/#aspose.cells.drawing.picture-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının, belirtilen indeksten son elemana kadar uzanan ilk oluşumunun sıfırdan başlayan indeksini döndürür.|
| [`index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells.drawing/picturecollection/index_of/#aspose.cells.drawing.picture-int-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığında belirtilen indeksten başlayıp belirtilen sayıda eleman içeren ilk oluşumun sıfırdan başlayan indeksini döndürür.|
| [`last_index_of(self, item)`](/cells/python-net/tr/aspose.cells.drawing/picturecollection/last_index_of/#aspose.cells.drawing.picture) | Belirtilen nesneyi arar ve tüm dizi listesindeki son oluşumun sıfırdan başlayan dizinini döndürür.|
| [`last_index_of(self, item, index)`](/cells/python-net/tr/aspose.cells.drawing/picturecollection/last_index_of/#aspose.cells.drawing.picture-int) |Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının ilk elemanından belirtilen dizine kadar uzanan son oluşumun sıfır tabanlı dizinini döndürür.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells.drawing/picturecollection/last_index_of/#aspose.cells.drawing.picture-int-int) | Belirtilen nesneyi arar ve dizi listesindeki belirtilen sayıda öğeyi içeren ve belirtilen dizinde sona eren öğe aralığındaki son oluşumun sıfır tabanlı dizinini döndürür.|
| [`camera(self, row, column, range)`](/cells/python-net/tr/aspose.cells.drawing/picturecollection/camera/#int-int-str) | Atış poligonunun fotoğrafını çeker.|
| [`binary_search(self, item)`](/cells/python-net/tr/aspose.cells.drawing/picturecollection/binary_search/#aspose.cells.drawing.picture) | Varsayılan karşılaştırıcıyı kullanarak sıralanmış dizi listesinin tamamında bir öğe arar ve öğenin sıfırdan başlayan dizinini döndürür.|



###  Örnek

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# get PictureCollection
pictures = workbook.worksheets[0].pictures
# do your business
# Save the excel file.
workbook.save("result.xlsx")

```

###  Ayrıca bakınız
* modül [`aspose.cells.drawing`](..)
* sınıf [`Picture`](/cells/python-net/tr/aspose.cells.drawing/picture)
