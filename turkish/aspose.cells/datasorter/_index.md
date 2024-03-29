---
title: DataSorter sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 440
url: /tr/aspose.cells/datasorter/
is_root: false
---
##  DataSorter sınıfı
DataSorter için özet açıklama.



DataSorter türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [keys](/cells/python-net/tr/aspose.cells/datasorter/keys) | Veri sıralayıcının anahtar listesini alır.|
| [has_headers](/cells/python-net/tr/aspose.cells/datasorter/has_headers) | Aralığın üstbilgileri olup olmadığını temsil eder.|
| [key1](/cells/python-net/tr/aspose.cells/datasorter/key1) | İlk sıralanan sütun dizinini temsil eder (mutlak konum, A sütunu 0'dır, B 1'dir, ...).|
| [order1](/cells/python-net/tr/aspose.cells/datasorter/order1) | İlk anahtarın sıralama düzenini temsil eder.|
| [key2](/cells/python-net/tr/aspose.cells/datasorter/key2) | İkinci sıralanmış sütun dizinini temsil eder (mutlak konum, A sütunu 0'dır, B 1'dir, ...).|
| [order2](/cells/python-net/tr/aspose.cells/datasorter/order2) | İkinci anahtarın sıralama düzenini temsil eder.|
| [key3](/cells/python-net/tr/aspose.cells/datasorter/key3) | Üçüncü sıralanmış sütun dizinini temsil eder (mutlak konum, A sütunu 0'dır, B 1'dir, ...).|
| [order3](/cells/python-net/tr/aspose.cells/datasorter/order3) | Üçüncü anahtarın sıralama düzenini temsil eder.|
| [sort_left_to_right](/cells/python-net/tr/aspose.cells/datasorter/sort_left_to_right) | Doğru, sıralama yönünün soldan sağa olduğu anlamına gelir.<br/>Yanlış, sıralama yönünün yukarıdan aşağıya doğru olduğu anlamına gelir.<br/> Varsayılan değer false'tur.|
| [case_sensitive](/cells/python-net/tr/aspose.cells/datasorter/case_sensitive) | Dizeyi karşılaştırırken büyük/küçük harfe duyarlı olup olmayacağını alır ve ayarlar.|
| [sort_as_number](/cells/python-net/tr/aspose.cells/datasorter/sort_as_number) |Sayıya benzeyen herhangi bir şeyin sıralanıp sıralanmayacağını belirtir.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [add_key](/cells/python-net/tr/aspose.cells/datasorter/add_key/#int-aspose.cells.SortOrder) | Sıralanmış sütun dizini ve sıralama düzeni ekler.|
| [add_key](/cells/python-net/tr/aspose.cells/datasorter/add_key/#int-aspose.cells.SortOrder-str) | Özel sıralama listesiyle sıralanmış sütun dizini ve sıralama düzeni ekler.|
| [add_key](/cells/python-net/tr/aspose.cells/datasorter/add_key/#int-aspose.cells.SortOnType-aspose.cells.SortOrder-any) | Özel sıralama listesiyle sıralanmış sütun dizini ve sıralama düzeni ekler.|
| [add_key](/cells/python-net/tr/aspose.cells/datasorter/add_key/#int-aspose.cells.SortOrder-list) | Özel sıralama listesiyle sıralanmış sütun dizini ve sıralama düzeni ekler.|
| [sort](/cells/python-net/tr/aspose.cells/datasorter/sort/#aspose.cells.Cells-int-int-int-int) | Bölgeye ait verileri sıralar.|
| [sort](/cells/python-net/tr/aspose.cells/datasorter/sort/#aspose.cells.Cells-aspose.cells.CellArea) | Alanın verilerini sıralayın.|
| [sort](/cells/python-net/tr/aspose.cells/datasorter/sort/#) | Aralıktaki verileri sıralayın.|
| [clear](/cells/python-net/tr/aspose.cells/datasorter/clear/#) | Tüm ayarları temizleyin.|



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
