---
title: max_column_count mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 270
url: /tr/aspose.cells/txtloadoptions/max_column_count/
is_root: false
---
##  max_column_count mülk

Bir sayfa için içe aktarılacak maksimum sütun sayısı.

###  Notlar

Bu sınırı aşan sütunlar yok sayılacaktır
veya [`TxtLoadOptions.extend_to_next_sheet`](/cells/python-net/tr/aspose.cells/txtloadoptions#extend_to_next_sheet)'e göre bir sonraki sayfaya uzatılabilir.
Bu sayıya başlık sütunları ([`TxtLoadOptions.header_columns_count`](/cells/python-net/tr/aspose.cells/txtloadoptions#header_columns_count)) da dahildir.
Bunun maksimum değeri, ilgili dosya biçiminin sütun sınırıdır, örneğin xlsx dosyası için 16384'tür.
Eğer bu özellik belirtilmemişse veya belirtilen değer pozitif değilse, o zaman maksimum sınır da kullanılacaktır.
###  Tanım:
```python
@property
def max_column_count(self):
    ...
@max_column_count.setter
def max_column_count(self, value):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`TxtLoadOptions`](/cells/python-net/tr/aspose.cells/txtloadoptions)
