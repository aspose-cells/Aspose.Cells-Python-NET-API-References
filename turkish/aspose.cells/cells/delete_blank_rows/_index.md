---
title: delete_blank_rows yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 210
url: /tr/aspose.cells/cells/delete_blank_rows/
is_root: false
---
##  delete_blank_rows(self) {#}
Herhangi bir veri veya başka nesne içermeyen tüm boş satırları silin.



```python

def delete_blank_rows(self):
    ...
```




##  delete_blank_rows(self, options) {#aspose.cells.DeleteOptions}
Herhangi bir veri veya görünür yorum, pivot tablo gibi bazı özel nesneleri içermeyen tüm boş satırları silin.



```python

def delete_blank_rows(self, options):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| options | [`DeleteOptions`](/cells/python-net/tr/aspose.cells/deleteoptions) | Aralığı silme seçenekleri.|
###  Notlar

Silinecek boş satırlar için sadece [`Row.is_blank`](/cells/python-net/tr/aspose.cells/row#is_blank)'in true olması gerekmiyor,
ancak bu satırlardaki herhangi bir hücre için tanımlanmış görünür bir yorum da olmamalıdır,
ve aralıkları bunlarla kesişen bir pivot tablo yok.


###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Cells`](/cells/python-net/tr/aspose.cells/cells)
