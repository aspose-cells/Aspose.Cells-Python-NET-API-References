---
title: get_formula1 yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 20
url: /tr/aspose.cells/formatcondition/get_formula1/
is_root: false
---
##  get_formula1(self, is_r1c1, is_local) {#bool-bool}
Bu biçim koşuluyla ilişkili değeri veya ifadeyi alır.


###  İadeler

Bu biçim koşuluyla ilişkili değer veya ifade.


```python

def get_formula1(self, is_r1c1, is_local):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| is_r1c1 | bool | Formülün R1C1 olarak biçimlendirilmesi gerekip gerekmediği.|
| is_local | bool | Formülün yerel ayarlara göre biçimlendirilmesi gerekip gerekmediği.|


##  get_formula1(self, row, column) {#int-int}
Hücrenin koşullu biçimlendirmesinin formülünü alır.


###  İadeler

Formül.


```python

def get_formula1(self, row, column):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| row | int | Satır dizini.|
| column | int | Sütun dizini.|


##  get_formula1(self, is_r1c1, is_local, row, column) {#bool-bool-int-int}
Hücrenin koşullu biçimlendirmesinin değerini veya ifadesini alır.


###  İadeler

Hücrenin koşullu biçimlendirmesiyle ilişkili değer veya ifade.


```python

def get_formula1(self, is_r1c1, is_local, row, column):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| is_r1c1 | bool | Formülün R1C1 olarak biçimlendirilmesi gerekip gerekmediği.|
| is_local | bool | Formülün yerel ayarlara göre biçimlendirilmesi gerekip gerekmediği.|
| row | int | Satır dizini.|
| column | int | Sütun dizini.|
###  Notlar

Belirtilen hücrenin bu koşullu biçimlendirmeye tabi olması gerekir, aksi takdirde null döndürülür.


###  Ayrıca bakınız

* modül [`aspose.cells`](../../)
* sınıf [`FormatCondition`](/cells/python-net/tr/aspose.cells/formatcondition)
