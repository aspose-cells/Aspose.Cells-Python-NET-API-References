---
title: max_row_count mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 300
url: /tr/aspose.cells/txtloadoptions/max_row_count/
is_root: false
---
##  max_row_count mülk

Bir sayfa için içe aktarılacak maksimum satır sayısı.

###  Notlar

Bu sınırı aşan satırlar göz ardı edilecek
veya [`TxtLoadOptions.extend_to_next_sheet`](/cells/python-net/tr/aspose.cells/txtloadoptions#extend_to_next_sheet)'e göre bir sonraki sayfaya genişletilebilir.
Bu sayıya başlık satırları da dahildir ([`TxtLoadOptions.header_rows_count`](/cells/python-net/tr/aspose.cells/txtloadoptions#header_rows_count)).
İzin verilen maksimum değer, xlsx dosyası için 1048576 gibi ilgili dosya biçiminin satır sınırıdır.
Bu özellik belirtilmemişse veya belirtilen değer pozitif değilse bu durumda da maksimum sınır kullanılacaktır.
###  Tanım:
```python
@property
def max_row_count(self):
    ...
@max_row_count.setter
def max_row_count(self, value):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`TxtLoadOptions`](/cells/python-net/tr/aspose.cells/txtloadoptions)
