---
title: HorizontalPageBreakCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 770
url: /tr/aspose.cells/horizontalpagebreakcollection/
is_root: false
---
##  HorizontalPageBreakCollection sınıfı
[`HorizontalPageBreak`](/cells/python-net/tr/aspose.cells/horizontalpagebreak) nesneden oluşan bir koleksiyonu kapsüller.



HorizontalPageBreakCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [capacity](/cells/python-net/tr/aspose.cells/horizontalpagebreakcollection/capacity) | Dizi listesinin içerebileceği eleman sayısını alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`add(self, row, start_column, end_column)`](/cells/python-net/tr/aspose.cells/horizontalpagebreakcollection/add/#int-int-int) | Koleksiyona yatay sayfa sonu ekler.|
| [`add(self, row)`](/cells/python-net/tr/aspose.cells/horizontalpagebreakcollection/add/#int) | Koleksiyona yatay sayfa sonu ekler.|
| [`add(self, row, column)`](/cells/python-net/tr/aspose.cells/horizontalpagebreakcollection/add/#int-int) | Koleksiyona yatay sayfa sonu ekler.|
| [`add(self, cell_name)`](/cells/python-net/tr/aspose.cells/horizontalpagebreakcollection/add/#str) | Koleksiyona yatay sayfa sonu ekler.|
| [`copy_to(self, array)`](/cells/python-net/tr/aspose.cells/horizontalpagebreakcollection/copy_to/#list) |Hedef dizi listesinin başından başlayarak tüm dizi listesini uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/tr/aspose.cells/horizontalpagebreakcollection/copy_to/#int-list-int-int) | Hedef dizi listesinin belirtilen indeksinden başlayarak, dizi listesindeki bir dizi öğeyi uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`index_of(self, item, index)`](/cells/python-net/tr/aspose.cells/horizontalpagebreakcollection/index_of/#aspose.cells.horizontalpagebreak-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının, belirtilen indeksten son elemana kadar uzanan ilk oluşumunun sıfırdan başlayan indeksini döndürür.|
| [`index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells/horizontalpagebreakcollection/index_of/#aspose.cells.horizontalpagebreak-int-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığında belirtilen indeksten başlayıp belirtilen sayıda eleman içeren ilk oluşumun sıfırdan başlayan indeksini döndürür.|
| [`last_index_of(self, item)`](/cells/python-net/tr/aspose.cells/horizontalpagebreakcollection/last_index_of/#aspose.cells.horizontalpagebreak) | Belirtilen nesneyi arar ve tüm dizi listesindeki son oluşumun sıfırdan başlayan dizinini döndürür.|
| [`last_index_of(self, item, index)`](/cells/python-net/tr/aspose.cells/horizontalpagebreakcollection/last_index_of/#aspose.cells.horizontalpagebreak-int) |Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının ilk elemanından belirtilen dizine kadar uzanan son oluşumun sıfır tabanlı dizinini döndürür.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells/horizontalpagebreakcollection/last_index_of/#aspose.cells.horizontalpagebreak-int-int) | Belirtilen nesneyi arar ve dizi listesindeki belirtilen sayıda öğeyi içeren ve belirtilen dizinde sona eren öğe aralığındaki son oluşumun sıfır tabanlı dizinini döndürür.|
| [`get(self, cell_name)`](/cells/python-net/tr/aspose.cells/horizontalpagebreakcollection/get/#str) | Belirtilen hücre adına sahip [`HorizontalPageBreak`](/cells/python-net/tr/aspose.cells/horizontalpagebreak) öğesini alır.|
| [`binary_search(self, item)`](/cells/python-net/tr/aspose.cells/horizontalpagebreakcollection/binary_search/#aspose.cells.horizontalpagebreak) | Varsayılan karşılaştırıcıyı kullanarak sıralanmış dizi listesinin tamamında bir öğe arar ve öğenin sıfırdan başlayan dizinini döndürür.|



###  Örnek

```python
from aspose.cells import Workbook

excel = Workbook()
# Add a pagebreak at G5
excel.worksheets[0].horizontal_page_breaks.add("G5")
excel.worksheets[0].vertical_page_breaks.add("G5")

```

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
* sınıf [`HorizontalPageBreak`](/cells/python-net/tr/aspose.cells/horizontalpagebreak)
