---
title: RowCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1350
url: /tr/aspose.cells/rowcollection/
is_root: false
---
##  RowCollection sınıfı
Bir çalışma sayfasındaki tek tek satırları temsil eden [`Row`](/cells/python-net/tr/aspose.cells/row) nesneyi toplar.



RowCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [count](/cells/python-net/tr/aspose.cells/rowcollection/count) | Bu koleksiyondaki satır sayısını alır.|



Verilen satır indeksine göre [`Row`](/cells/python-net/tr/aspose.cells/row) nesnesini alır. Verilen satır indeksinin Row nesnesi, daha önce mevcut değilse başlatılacaktır.
###  Dizin oluşturucu
| İsim| Tanım|
| :- | :- |
| [index] |  |


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [get_enumerator](/cells/python-net/tr/aspose.cells/rowcollection/get_enumerator/#bool-bool) | Bu koleksiyondaki satırları yineleyen bir numaralandırıcı alır|
| [get_row_by_index](/cells/python-net/tr/aspose.cells/rowcollection/get_row_by_index/#int) | Satır nesnesini listedeki konuma göre alır.|
| [clear](/cells/python-net/tr/aspose.cells/rowcollection/clear/#) | Tüm satırları ve hücreleri temizleyin.|
| [remove_at](/cells/python-net/tr/aspose.cells/rowcollection/remove_at/#int) | Bu koleksiyonda belirtilen dizindeki (konumdaki) satır öğesini kaldırın.|



###  Örnek

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the first worksheet
worksheet = workbook.worksheets[0]
# Get first row
row = worksheet.cells.rows[0]

```

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
* sınıf [`Row`](/cells/python-net/tr/aspose.cells/row)
