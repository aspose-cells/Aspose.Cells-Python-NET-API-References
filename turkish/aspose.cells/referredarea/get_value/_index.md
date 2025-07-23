---
title: get_value yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 20
url: /tr/aspose.cells/referredarea/get_value/
is_root: false
---
##  get_value(self, row_offset, col_offset) {#int-int}
Bu alanın sol üst köşesinden verilen uzaklığa göre hücre değerini alır.


###  İadeler

"#REF!" bu alan geçersizse;
Bu alanın dışında bir uzaklık verilmişse "#N/A";
Aksi takdirde, hücre değerini verilen konumdaki döndürün.


```python

def get_value(self, row_offset, col_offset):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| row_offset | int | bu alanın başlangıç satırından satır uzaklığı|
| col_offset | int | bu alanın başlangıç satırından sütun uzaklığı|


##  get_value(self, row_offset, col_offset, calculate_formulas) {#int-int-bool}
Bu alanın sol üst köşesinden verilen uzaklığa göre hücre değerini alır.


###  İadeler

"#REF!" bu alan geçersizse;
Bu alanın dışında bir uzaklık verilmişse "#N/A";
Aksi takdirde, hücre değerini verilen konumdaki döndürün.


```python

def get_value(self, row_offset, col_offset, calculate_formulas):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| row_offset | int | bu alanın başlangıç satırından satır uzaklığı|
| col_offset | int | bu alanın başlangıç satırından sütun uzaklığı|
| calculate_formulas | bool | Belirtilen referans formül ise, bunu yinelemeli olarak hesaplayın.|



###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`ReferredArea`](/cells/python-net/tr/aspose.cells/referredarea)
