---
title: CommentCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 290
url: /tr/aspose.cells/commentcollection/
is_root: false
---
##  CommentCollection sınıfı
[Comment](/cells/python-net/tr/aspose.cells/comment) nesne koleksiyonunu kapsüller.



CommentCollection türü aşağıdaki üyeleri gösterir:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [capacity](/cells/python-net/tr/aspose.cells/commentcollection/capacity) | Dizi listesinin içerebileceği öğe sayısını alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [add_threaded_comment(row, column, text, author)](/cells/python-net/tr/aspose.cells/commentcollection/add_threaded_comment/#int-int-str-ThreadedCommentAuthor) | Zincirleme bir yorum ekler.|
| [add_threaded_comment(cell_name, text, author)](/cells/python-net/tr/aspose.cells/commentcollection/add_threaded_comment/#str-str-ThreadedCommentAuthor) | Zincirleme bir yorum ekler.|
| [get_threaded_comments(row, column)](/cells/python-net/tr/aspose.cells/commentcollection/get_threaded_comments/#int-int) | Zincirleme açıklamaları satır ve sütun indeksine göre alır.|
| [get_threaded_comments(cell_name)](/cells/python-net/tr/aspose.cells/commentcollection/get_threaded_comments/#str) | Zincirlenmiş açıklamaları hücre adına göre alır.|
| [add(row, column)](/cells/python-net/tr/aspose.cells/commentcollection/add/#int-int) | Koleksiyona bir yorum ekler.|
| [add(cell_name)](/cells/python-net/tr/aspose.cells/commentcollection/add/#str) | Koleksiyona bir yorum ekler.|
| [remove_at(cell_name)](/cells/python-net/tr/aspose.cells/commentcollection/remove_at/#str) | Belirli hücrenin yorumunu kaldırır.|
| [remove_at(row, column)](/cells/python-net/tr/aspose.cells/commentcollection/remove_at/#int-int) | Belirli hücrenin yorumunu kaldırır.|
| [copy_to(array)](/cells/python-net/tr/aspose.cells/commentcollection/copy_to/#list) | Hedef dizi listesinin başından başlayarak tüm dizi listesini uyumlu bir tek boyutlu dizi listesine kopyalar.|
| [copy_to(index, array, array_index, count)](/cells/python-net/tr/aspose.cells/commentcollection/copy_to/#int-list-int-int) |Dizi listesindeki bir dizi öğeyi, hedef dizi listesinin belirtilen dizininden başlayarak uyumlu bir tek boyutlu dizi listesine kopyalar.|
| [index_of(item, index)](/cells/python-net/tr/aspose.cells/commentcollection/index_of/#Comment-int) | Belirtilen nesneyi arar ve belirtilen dizinden son öğeye uzanan dizi listesindeki öğelerin aralığındaki ilk oluşumun sıfır tabanlı dizinini döndürür.|
| [index_of(item, index, count)](/cells/python-net/tr/aspose.cells/commentcollection/index_of/#Comment-int-int) | Belirtilen nesneyi arar ve belirtilen dizinde başlayan ve belirtilen sayıda öğe içeren dizi listesindeki öğe aralığı içindeki ilk oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of(item)](/cells/python-net/tr/aspose.cells/commentcollection/last_index_of/#Comment) | Belirtilen nesneyi arar ve tüm dizi listesindeki son oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of(item, index)](/cells/python-net/tr/aspose.cells/commentcollection/last_index_of/#Comment-int) | Belirtilen nesneyi arar ve ilk öğeden belirtilen dizine kadar uzanan dizi listesindeki öğe aralığı içindeki son oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of(item, index, count)](/cells/python-net/tr/aspose.cells/commentcollection/last_index_of/#Comment-int-int) |Belirtilen nesneyi arar ve belirtilen sayıda öğeyi içeren ve belirtilen dizinde biten dizi listesindeki öğe aralığındaki son oluşumun sıfır tabanlı dizinini döndürür.|
| [binary_search(item)](/cells/python-net/tr/aspose.cells/commentcollection/binary_search/#Comment) | Varsayılan karşılaştırıcıyı kullanarak sıralanmış dizi listesinin tamamında bir öğe arar ve öğenin sıfır tabanlı dizinini döndürür.|



###  Örnek

```python
from aspose.cells import Workbook

workbook = Workbook()
comments = workbook.worksheets[0].comments

```

###  Ayrıca bakınız
* modül [aspose.cells](..)
* sınıf [Comment](/cells/python-net/tr/aspose.cells/comment)
