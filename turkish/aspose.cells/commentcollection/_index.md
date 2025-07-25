---
title: CommentCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 270
url: /tr/aspose.cells/commentcollection/
is_root: false
---
##  CommentCollection sınıfı
[`Comment`](/cells/python-net/tr/aspose.cells/comment) nesneden oluşan bir koleksiyonu kapsüller.



CommentCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [capacity](/cells/python-net/tr/aspose.cells/commentcollection/capacity) | Dizi listesinin içerebileceği eleman sayısını alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`add_threaded_comment(self, row, column, text, author)`](/cells/python-net/tr/aspose.cells/commentcollection/add_threaded_comment/#int-int-str-aspose.cells.threadedcommentauthor) | Konuya yorum ekler.|
| [`add_threaded_comment(self, cell_name, text, author)`](/cells/python-net/tr/aspose.cells/commentcollection/add_threaded_comment/#str-str-aspose.cells.threadedcommentauthor) | Konuya yorum ekler.|
| [`get_threaded_comments(self, row, column)`](/cells/python-net/tr/aspose.cells/commentcollection/get_threaded_comments/#int-int) | Satır ve sütun indeksine göre iş parçacıklı yorumları alır.|
| [`get_threaded_comments(self, cell_name)`](/cells/python-net/tr/aspose.cells/commentcollection/get_threaded_comments/#str) | Hücre adına göre iş parçacıklı yorumları alır.|
| [`add(self, row, column)`](/cells/python-net/tr/aspose.cells/commentcollection/add/#int-int) | Koleksiyona bir yorum ekler.|
| [`add(self, cell_name)`](/cells/python-net/tr/aspose.cells/commentcollection/add/#str) | Koleksiyona bir yorum ekler.|
| [`get(self, row, column)`](/cells/python-net/tr/aspose.cells/commentcollection/get/#int-int) | API for Python'i .Net.since aracılığıyla ekleyin, bu[int, int] desteklenmiyor|
| [`get(self, index)`](/cells/python-net/tr/aspose.cells/commentcollection/get/#int) | Belirtilen indeksteki [`Comment`](/cells/python-net/tr/aspose.cells/comment) öğesini alır.|
| [`get(self, cell_name)`](/cells/python-net/tr/aspose.cells/commentcollection/get/#str) | Belirtilen hücredeki [`Comment`](/cells/python-net/tr/aspose.cells/comment) öğesini alır.|
| [`remove_at(self, cell_name)`](/cells/python-net/tr/aspose.cells/commentcollection/remove_at/#str) | Belirli hücrenin yorumunu kaldırır.|
| [`remove_at(self, row, column)`](/cells/python-net/tr/aspose.cells/commentcollection/remove_at/#int-int) | Belirli hücrenin yorumunu kaldırır.|
| [`copy_to(self, array)`](/cells/python-net/tr/aspose.cells/commentcollection/copy_to/#list) |Hedef dizi listesinin başından başlayarak tüm dizi listesini uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/tr/aspose.cells/commentcollection/copy_to/#int-list-int-int) | Hedef dizi listesinin belirtilen indeksinden başlayarak, dizi listesindeki bir dizi öğeyi uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`index_of(self, item, index)`](/cells/python-net/tr/aspose.cells/commentcollection/index_of/#aspose.cells.comment-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının, belirtilen indeksten son elemana kadar uzanan ilk oluşumunun sıfırdan başlayan indeksini döndürür.|
| [`index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells/commentcollection/index_of/#aspose.cells.comment-int-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığında belirtilen indeksten başlayıp belirtilen sayıda eleman içeren ilk oluşumun sıfırdan başlayan indeksini döndürür.|
| [`last_index_of(self, item)`](/cells/python-net/tr/aspose.cells/commentcollection/last_index_of/#aspose.cells.comment) | Belirtilen nesneyi arar ve tüm dizi listesindeki son oluşumun sıfırdan başlayan dizinini döndürür.|
| [`last_index_of(self, item, index)`](/cells/python-net/tr/aspose.cells/commentcollection/last_index_of/#aspose.cells.comment-int) |Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının ilk elemanından belirtilen dizine kadar uzanan son oluşumun sıfır tabanlı dizinini döndürür.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells/commentcollection/last_index_of/#aspose.cells.comment-int-int) | Belirtilen nesneyi arar ve dizi listesindeki belirtilen sayıda öğeyi içeren ve belirtilen dizinde sona eren öğe aralığındaki son oluşumun sıfır tabanlı dizinini döndürür.|
| [`binary_search(self, item)`](/cells/python-net/tr/aspose.cells/commentcollection/binary_search/#aspose.cells.comment) | Varsayılan karşılaştırıcıyı kullanarak sıralanmış dizi listesinin tamamında bir öğe arar ve öğenin sıfırdan başlayan dizinini döndürür.|



###  Örnek

```python
from aspose.cells import Workbook

workbook = Workbook()
comments = workbook.worksheets[0].comments

```

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
* sınıf [`Comment`](/cells/python-net/tr/aspose.cells/comment)
