---
title: HyperlinkCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 850
url: /tr/aspose.cells/hyperlinkcollection/
is_root: false
---
##  HyperlinkCollection sınıfı
[`Hyperlink`](/cells/python-net/tr/aspose.cells/hyperlink) nesneden oluşan bir koleksiyonu kapsüller.



HyperlinkCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [capacity](/cells/python-net/tr/aspose.cells/hyperlinkcollection/capacity) | Dizi listesinin içerebileceği öğe sayısını alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [add](/cells/python-net/tr/aspose.cells/hyperlinkcollection/add/#int-int-int-int-str) | Belirtilen bir hücreye veya hücre aralığına köprü ekler.|
| [add](/cells/python-net/tr/aspose.cells/hyperlinkcollection/add/#str-int-int-str) | Belirtilen bir hücreye veya hücre aralığına köprü ekler.|
| [add](/cells/python-net/tr/aspose.cells/hyperlinkcollection/add/#str-str-str-str-str) | Belirtilen bir hücreye veya hücre aralığına köprü ekler.|
| [copy_to](/cells/python-net/tr/aspose.cells/hyperlinkcollection/copy_to/#list) | Hedef dizi listesinin başından başlayarak dizi listesinin tamamını uyumlu bir tek boyutlu dizi listesine kopyalar.|
| [copy_to](/cells/python-net/tr/aspose.cells/hyperlinkcollection/copy_to/#int-list-int-int) | Hedef dizi listesinin belirtilen dizininden başlayarak, dizi listesinden bir dizi öğeyi uyumlu bir tek boyutlu dizi listesine kopyalar.|
| [index_of](/cells/python-net/tr/aspose.cells/hyperlinkcollection/index_of/#aspose.cells.Hyperlink-int) | Belirtilen nesneyi arar ve belirtilen dizinden son öğeye kadar uzanan dizi listesindeki öğe aralığı içindeki ilk oluşumun sıfır tabanlı dizinini döndürür.|
| [index_of](/cells/python-net/tr/aspose.cells/hyperlinkcollection/index_of/#aspose.cells.Hyperlink-int-int) |Belirtilen nesneyi arar ve belirtilen dizinde başlayan ve belirtilen sayıda öğeyi içeren dizi listesindeki öğe aralığı içindeki ilk oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of](/cells/python-net/tr/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.Hyperlink) | Belirtilen nesneyi arar ve dizi listesinin tamamındaki son oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of](/cells/python-net/tr/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.Hyperlink-int) | Belirtilen nesneyi arar ve ilk öğeden belirtilen dizine kadar uzanan dizi listesindeki öğe aralığı içindeki son oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of](/cells/python-net/tr/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.Hyperlink-int-int) | Belirtilen nesneyi arar ve belirtilen sayıda öğeyi içeren ve belirtilen dizinde biten dizi listesindeki öğe aralığı içindeki son oluşumun sıfır tabanlı dizinini döndürür.|
| [binary_search](/cells/python-net/tr/aspose.cells/hyperlinkcollection/binary_search/#aspose.cells.Hyperlink) | Varsayılan karşılaştırıcıyı kullanarak bir öğe için sıralanmış dizi listesinin tamamını arar ve öğenin sıfır tabanlı dizinini döndürür.|



###  Örnek

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[0]
# Get Hyperlinks Collection
hyperlinks = worksheet.hyperlinks
# Adding a hyperlink to a URL at "A1" cell
hyperlinks.add("A1", 1, 1, "http://www.aspose.com")
# Saving the Excel file
workbook.save("book1.xls")

```

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
* sınıf [`Hyperlink`](/cells/python-net/tr/aspose.cells/hyperlink)
