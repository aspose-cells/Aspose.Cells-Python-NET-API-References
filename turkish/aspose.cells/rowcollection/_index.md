---
title: RowCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1240
url: /tr/aspose.cells/rowcollection/
is_root: false
---
##  RowCollection sınıfı
Bir çalışma sayfasındaki ayrı satırları temsil eden [`Row`](/cells/python-net/tr/aspose.cells/row) nesnesini toplar.



RowCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [count](/cells/python-net/tr/aspose.cells/rowcollection/count) | Bu koleksiyondaki satır sayısını alır.|



Belirtilen satır dizinine göre [`Row`](/cells/python-net/tr/aspose.cells/row) nesnesini alır. Belirtilen satır dizinine sahip Satır nesnesi daha önce mevcut değilse örneklendirilir.
###  Dizinleyici
| İsim| Tanım|
| :- | :- |
| [index] |  |


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`get_enumerator(self, reversed, sync)`](/cells/python-net/tr/aspose.cells/rowcollection/get_enumerator/#bool-bool) | Bu koleksiyondaki satırları yineleyen bir numaralandırıcı alır|
| [`get_row_by_index(self, index)`](/cells/python-net/tr/aspose.cells/rowcollection/get_row_by_index/#int) | Listedeki konumuna göre satır nesnesini alır.|
| [`clear(self)`](/cells/python-net/tr/aspose.cells/rowcollection/clear/#) | Tüm satırları ve hücreleri temizle.|
| [`remove_at(self, index)`](/cells/python-net/tr/aspose.cells/rowcollection/remove_at/#int) | Bu koleksiyondaki belirtilen dizindeki (konumdaki) satır öğesini kaldır.|



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
