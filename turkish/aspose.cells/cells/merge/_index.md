---
title: merge yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 800
url: /tr/aspose.cells/cells/merge/
is_root: false
---
##  merge(self, first_row, first_column, total_rows, total_columns) {#int-int-int-int}
Belirtilen hücre aralığını tek bir hücrede birleştirir.



```python

def merge(self, first_row, first_column, total_rows, total_columns):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| first_row | int | Bu aralığın ilk satırı (sıfır tabanlı)|
| first_column | int | Bu aralığın ilk sütunu (sıfır tabanlı)|
| total_rows | int |Satır sayısı (bir tabanlı)|
| total_columns | int | Sütun sayısı (bir tabanlı)|
###  Notlar

Birleştirilmiş hücreye, aralıktaki sol üst hücrenin adresi aracılığıyla başvurun.

##  merge(self, first_row, first_column, total_rows, total_columns, merge_conflict) {#int-int-int-int-bool}

Belirtilen hücre aralığını tek bir hücrede birleştirir.



```python

def merge(self, first_row, first_column, total_rows, total_columns, merge_conflict):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| first_row | int | Bu aralığın ilk satırı (sıfır tabanlı)|
| first_column | int | Bu aralığın ilk sütunu (sıfır tabanlı)|
| total_rows | int |Satır sayısı (bir tabanlı)|
| total_columns | int | Sütun sayısı (bir tabanlı)|
| merge_conflict | bool | Birleştirme çatışması birleştirilmiş aralıklar.|
###  Notlar

Birleştirilmiş hücreye, aralıktaki sol üst hücrenin adresi aracılığıyla başvurun.
mergeConflict doğruysa ve birleştirilmiş aralık diğer birleştirilmiş hücrelerle çakışıyorsa,
diğer birleştirilmiş hücreler otomatik olarak kaldırılacaktır.

##  merge(self, first_row, first_column, total_rows, total_columns, check_conflict, merge_conflict) {#int-int-int-int-bool-bool}
Belirtilen hücre aralığını tek bir hücrede birleştirir.



```python

def merge(self, first_row, first_column, total_rows, total_columns, check_conflict, merge_conflict):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| first_row | int | Bu aralığın ilk satırı (sıfır tabanlı)|
| first_column | int | Bu aralığın ilk sütunu (sıfır tabanlı)|
| total_rows | int |Satır sayısı (bir tabanlı)|
| total_columns | int | Sütun sayısı (bir tabanlı)|
| check_conflict | bool | Birleştirilmiş hücrelerin diğer birleştirilmiş hücrelerle kesişip kesişmediğini belirtir|
| merge_conflict | bool | Birleştirme çatışması birleştirilmiş aralıklar.|
###  Notlar

Birleştirilmiş hücreye, aralıktaki sol üst hücrenin adresi aracılığıyla başvurun.
mergeConflict doğruysa ve birleştirilmiş aralık diğer birleştirilmiş hücrelerle çakışıyorsa,
diğer birleştirilmiş hücreler otomatik olarak kaldırılacaktır.


###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Cells`](/cells/python-net/tr/aspose.cells/cells)
