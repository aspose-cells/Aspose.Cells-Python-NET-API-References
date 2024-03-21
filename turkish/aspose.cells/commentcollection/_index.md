---
title: CommentCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 300
url: /tr/aspose.cells/commentcollection/
is_root: false
---
##  CommentCollection sınıfı
[`Comment`](/cells/python-net/tr/aspose.cells/comment) nesneden oluşan bir koleksiyonu kapsüller.



CommentCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [capacity](/cells/python-net/tr/aspose.cells/commentcollection/capacity) | Dizi listesinin içerebileceği öğe sayısını alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [add_threaded_comment](/cells/python-net/tr/aspose.cells/commentcollection/add_threaded_comment/#int-int-str-aspose.cells.ThreadedCommentAuthor) | Mesaj dizili bir yorum ekler.|
| [add_threaded_comment](/cells/python-net/tr/aspose.cells/commentcollection/add_threaded_comment/#str-str-aspose.cells.ThreadedCommentAuthor) | Mesaj dizili bir yorum ekler.|
| [get_threaded_comments](/cells/python-net/tr/aspose.cells/commentcollection/get_threaded_comments/#int-int) | Zincirli yorumları satır ve sütun dizinine göre alır.|
| [get_threaded_comments](/cells/python-net/tr/aspose.cells/commentcollection/get_threaded_comments/#str) |İş parçacığı yorumlarını hücre adına göre alır.|
| [add](/cells/python-net/tr/aspose.cells/commentcollection/add/#int-int) | Koleksiyona bir yorum ekler.|
| [add](/cells/python-net/tr/aspose.cells/commentcollection/add/#str) | Koleksiyona bir yorum ekler.|
| [remove_at](/cells/python-net/tr/aspose.cells/commentcollection/remove_at/#str) | Belirli bir hücrenin yorumunu kaldırır.|
| [remove_at](/cells/python-net/tr/aspose.cells/commentcollection/remove_at/#int-int) | Belirli bir hücrenin yorumunu kaldırır.|
| [copy_to](/cells/python-net/tr/aspose.cells/commentcollection/copy_to/#list) | Hedef dizi listesinin başından başlayarak dizi listesinin tamamını uyumlu bir tek boyutlu dizi listesine kopyalar.|
| [copy_to](/cells/python-net/tr/aspose.cells/commentcollection/copy_to/#int-list-int-int) | Hedef dizi listesinin belirtilen dizininden başlayarak, dizi listesinden bir dizi öğeyi uyumlu bir tek boyutlu dizi listesine kopyalar.|
| [index_of](/cells/python-net/tr/aspose.cells/commentcollection/index_of/#aspose.cells.Comment-int) | Belirtilen nesneyi arar ve belirtilen dizinden son öğeye kadar uzanan dizi listesindeki öğe aralığı içindeki ilk oluşumun sıfır tabanlı dizinini döndürür.|
| [index_of](/cells/python-net/tr/aspose.cells/commentcollection/index_of/#aspose.cells.Comment-int-int) |Belirtilen nesneyi arar ve belirtilen dizinde başlayan ve belirtilen sayıda öğeyi içeren dizi listesindeki öğe aralığı içindeki ilk oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of](/cells/python-net/tr/aspose.cells/commentcollection/last_index_of/#aspose.cells.Comment) | Belirtilen nesneyi arar ve dizi listesinin tamamındaki son oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of](/cells/python-net/tr/aspose.cells/commentcollection/last_index_of/#aspose.cells.Comment-int) | Belirtilen nesneyi arar ve ilk öğeden belirtilen dizine kadar uzanan dizi listesindeki öğe aralığı içindeki son oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of](/cells/python-net/tr/aspose.cells/commentcollection/last_index_of/#aspose.cells.Comment-int-int) | Belirtilen nesneyi arar ve belirtilen sayıda öğeyi içeren ve belirtilen dizinde biten dizi listesindeki öğe aralığı içindeki son oluşumun sıfır tabanlı dizinini döndürür.|
| [binary_search](/cells/python-net/tr/aspose.cells/commentcollection/binary_search/#aspose.cells.Comment) | Varsayılan karşılaştırıcıyı kullanarak bir öğe için sıralanmış dizi listesinin tamamını arar ve öğenin sıfır tabanlı dizinini döndürür.|



###  Örnek

```python
from aspose.cells import Workbook

workbook = Workbook()
comments = workbook.worksheets[0].comments

```

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
* sınıf [`Comment`](/cells/python-net/tr/aspose.cells/comment)
