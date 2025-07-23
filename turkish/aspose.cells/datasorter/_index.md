---
title: DataSorter sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 410
url: /tr/aspose.cells/datasorter/
is_root: false
---
##  DataSorter sınıfı
DataSorter için özet açıklama.



DataSorter türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [keys](/cells/python-net/tr/aspose.cells/datasorter/keys) | Veri sıralayıcısının anahtar listesini alır.|
| [has_headers](/cells/python-net/tr/aspose.cells/datasorter/has_headers) | Aralığın başlıkları olup olmadığını gösterir.|
| [key1](/cells/python-net/tr/aspose.cells/datasorter/key1) | İlk sıralı sütun indeksini temsil eder (mutlak konum, sütun A 0, B 1, ...).|
| [order1](/cells/python-net/tr/aspose.cells/datasorter/order1) | İlk anahtarın sıralama düzenini temsil eder.|
| [key2](/cells/python-net/tr/aspose.cells/datasorter/key2) | İkinci sıralı sütun indeksini temsil eder (mutlak konum, sütun A 0, B 1, ...).|
| [order2](/cells/python-net/tr/aspose.cells/datasorter/order2) | İkinci anahtarın sıralama düzenini temsil eder.|
| [key3](/cells/python-net/tr/aspose.cells/datasorter/key3) | Üçüncü sıralı sütun indeksini temsil eder (mutlak konum, sütun A 0, B 1, ...).|
| [order3](/cells/python-net/tr/aspose.cells/datasorter/order3) | Üçüncü anahtarın sıralama düzenini temsil eder.|
| [sort_left_to_right](/cells/python-net/tr/aspose.cells/datasorter/sort_left_to_right) |Doğru, sıralama yönünün soldan sağa doğru olduğu anlamına gelir.<br/>Yanlış, sıralama yönünün yukarıdan aşağıya doğru olduğu anlamına gelir.<br/> Varsayılan değer false'tur.|
| [case_sensitive](/cells/python-net/tr/aspose.cells/datasorter/case_sensitive) | Dizeyi karşılaştırırken büyük/küçük harfe duyarlı olup olmadığını alır ve ayarlar.|
| [sort_as_number](/cells/python-net/tr/aspose.cells/datasorter/sort_as_number) | Sayıya benzeyen herhangi bir şeyin sıralanıp sıralanmayacağını belirtir.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`add_key(self, key, order)`](/cells/python-net/tr/aspose.cells/datasorter/add_key/#int-aspose.cells.sortorder) | Sıralanmış sütun indeksi ve sıralama düzenini ekler.|
| [`add_key(self, key, order, custom_list)`](/cells/python-net/tr/aspose.cells/datasorter/add_key/#int-aspose.cells.sortorder-str) | Özel sıralama listesiyle sıralı sütun dizini ve sıralama düzeni ekler.|
| [`add_key(self, key, type, order, custom_list)`](/cells/python-net/tr/aspose.cells/datasorter/add_key/#int-aspose.cells.sortontype-aspose.cells.sortorder-any) | Özel sıralama listesiyle sıralı sütun dizini ve sıralama düzeni ekler.|
| [`add_key(self, key, order, custom_list)`](/cells/python-net/tr/aspose.cells/datasorter/add_key/#int-aspose.cells.sortorder-list) | Özel sıralama listesiyle sıralı sütun dizini ve sıralama düzeni ekler.|
| [`sort(self, cells, start_row, start_column, end_row, end_column)`](/cells/python-net/tr/aspose.cells/datasorter/sort/#aspose.cells.cells-int-int-int-int) | Alanın verilerini sıralar.|
| [`sort(self, cells, area)`](/cells/python-net/tr/aspose.cells/datasorter/sort/#aspose.cells.cells-aspose.cells.cellarea) | Alanın verilerini sıralayın.|
| [`sort(self)`](/cells/python-net/tr/aspose.cells/datasorter/sort/#) | Verileri aralıkta sıralayın.|
| [`clear(self)`](/cells/python-net/tr/aspose.cells/datasorter/clear/#) | Tüm ayarları temizle.|
| [`add_color_key(self, key, type, order, color)`](/cells/python-net/tr/aspose.cells/datasorter/add_color_key/#int-aspose.cells.sortontype-aspose.cells.sortorder-aspose.pydrawing.color) | Renk sıralama anahtarı ekler.|



###  Örnek

```python
from aspose.cells import CellArea, SortOrder, Workbook

# Instantiate a new Workbook object.
workbook = Workbook("Book1.xls")
# Get the workbook datasorter object.
sorter = workbook.data_sorter
# Set the first order for datasorter object.
sorter.order1 = SortOrder.DESCENDING
# Define the first key.
sorter.key1 = 0
# Set the second order for datasorter object.
sorter.order2 = SortOrder.ASCENDING
# Define the second key.
sorter.key2 = 1
# Create a cells area (range).
ca = CellArea()
# Specify the start row index.
ca.start_row = 0
# Specify the start column index.
ca.start_column = 0
# Specify the last row index.
ca.end_row = 13
# Specify the last column index.
ca.end_column = 1
# Sort data in the specified data range (A1:B14)
sorter.sort(workbook.worksheets[0].cells, ca)
# Save the excel file.
workbook.save("outBook.xls")

```

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
