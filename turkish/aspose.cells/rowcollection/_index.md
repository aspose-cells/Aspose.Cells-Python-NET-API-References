---
title: RowCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1310
url: /tr/aspose.cells/rowcollection/
is_root: false
---
##  RowCollection sınıfı
Bir çalışma sayfasındaki tek tek satırları temsil eden [Row](/cells/python-net/tr/aspose.cells/row) nesnelerini toplar.



RowCollection türü aşağıdaki üyeleri gösterir:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [count](/cells/python-net/tr/aspose.cells/rowcollection/count) | Bu koleksiyondaki satır sayısını alır.|



Verilen satır dizinine göre bir [Row](/cells/python-net/tr/aspose.cells/row) nesnesi alır. Daha önce mevcut değilse, verilen satır dizininin Row nesnesi başlatılacaktır.
###  İndeksleyici
| İsim| Tanım|
| :- | :- |
| [index] |  |


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [get_row_by_index(index)](/cells/python-net/tr/aspose.cells/rowcollection/get_row_by_index/#int) | Satır nesnesini listedeki konuma göre alır.|
| [clear()](/cells/python-net/tr/aspose.cells/rowcollection/clear/#) | Tüm satırları ve hücreleri temizleyin.|
| [remove_at(index)](/cells/python-net/tr/aspose.cells/rowcollection/remove_at/#int) | Belirtilen dizindeki satırı kaldır|



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
* modül [aspose.cells](..)
* sınıf [Row](/cells/python-net/tr/aspose.cells/row)
