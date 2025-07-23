---
title: get_list_value yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 70
url: /tr/aspose.cells/validation/get_list_value/
is_root: false
---
##  get_list_value(self, row, column) {#int-int}
Belirtilen hücre için doğrulama listesinin değerini al.


###  İadeler

Belirtilen hücre için bu doğrulama listesini üretecek değer.
Eğer liste bir aralığa referans veriyorsa, döndürülen değer [`ReferredArea`](/cells/python-net/tr/aspose.cells/referredarea) nesnesi olacaktır;
Aksi takdirde döndürülen değer null, object[] veya simple object olabilir.


```python

def get_list_value(self, row, column):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| row | int | Satır dizini.|
| column | int | Sütun dizini.|
###  Notlar

Yalnızca türü Liste olan ve verilen hücreye uygulanan doğrulama için,
aksi takdirde null döndürülecektir.


###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`ReferredArea`](/cells/python-net/tr/aspose.cells/referredarea)
* sınıf [`Validation`](/cells/python-net/tr/aspose.cells/validation)
