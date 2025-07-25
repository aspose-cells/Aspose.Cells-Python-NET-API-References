---
title: HyperlinkCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 830
url: /tr/aspose.cells/hyperlinkcollection/
is_root: false
---
##  HyperlinkCollection sınıfı
[`Hyperlink`](/cells/python-net/tr/aspose.cells/hyperlink) nesneden oluşan bir koleksiyonu kapsüller.



HyperlinkCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [capacity](/cells/python-net/tr/aspose.cells/hyperlinkcollection/capacity) | Dizi listesinin içerebileceği eleman sayısını alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`add(self, first_row, first_column, total_rows, total_columns, address)`](/cells/python-net/tr/aspose.cells/hyperlinkcollection/add/#int-int-int-int-str) | Belirtilen bir hücreye veya hücre aralığına köprü ekler.|
| [`add(self, cell_name, total_rows, total_columns, address)`](/cells/python-net/tr/aspose.cells/hyperlinkcollection/add/#str-int-int-str) | Belirtilen bir hücreye veya hücre aralığına köprü ekler.|
| [`add(self, start_cell_name, end_cell_name, address, text_to_display, screen_tip)`](/cells/python-net/tr/aspose.cells/hyperlinkcollection/add/#str-str-str-str-str) | Belirtilen bir hücreye veya hücre aralığına köprü ekler.|
| [`copy_to(self, array)`](/cells/python-net/tr/aspose.cells/hyperlinkcollection/copy_to/#list) |Hedef dizi listesinin başından başlayarak tüm dizi listesini uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/tr/aspose.cells/hyperlinkcollection/copy_to/#int-list-int-int) | Hedef dizi listesinin belirtilen indeksinden başlayarak, dizi listesindeki bir dizi öğeyi uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`index_of(self, item, index)`](/cells/python-net/tr/aspose.cells/hyperlinkcollection/index_of/#aspose.cells.hyperlink-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının, belirtilen indeksten son elemana kadar uzanan ilk oluşumunun sıfırdan başlayan indeksini döndürür.|
| [`index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells/hyperlinkcollection/index_of/#aspose.cells.hyperlink-int-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığında belirtilen indeksten başlayıp belirtilen sayıda eleman içeren ilk oluşumun sıfırdan başlayan indeksini döndürür.|
| [`last_index_of(self, item)`](/cells/python-net/tr/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.hyperlink) | Belirtilen nesneyi arar ve tüm dizi listesindeki son oluşumun sıfırdan başlayan dizinini döndürür.|
| [`last_index_of(self, item, index)`](/cells/python-net/tr/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.hyperlink-int) |Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının ilk elemanından belirtilen dizine kadar uzanan son oluşumun sıfır tabanlı dizinini döndürür.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.hyperlink-int-int) | Belirtilen nesneyi arar ve dizi listesindeki belirtilen sayıda öğeyi içeren ve belirtilen dizinde sona eren öğe aralığındaki son oluşumun sıfır tabanlı dizinini döndürür.|
| [`binary_search(self, item)`](/cells/python-net/tr/aspose.cells/hyperlinkcollection/binary_search/#aspose.cells.hyperlink) | Varsayılan karşılaştırıcıyı kullanarak sıralanmış dizi listesinin tamamında bir öğe arar ve öğenin sıfırdan başlayan dizinini döndürür.|



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
