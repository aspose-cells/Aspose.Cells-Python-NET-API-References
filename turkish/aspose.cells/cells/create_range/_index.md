---
title: create_range yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 190
url: /tr/aspose.cells/cells/create_range/
is_root: false
---
##  create_range(self, address) {#str}
Aralığın bir adresinden [`Range`](/cells/python-net/tr/aspose.cells/range) nesnesini oluşturur.


###  İadeler

[`Range`](/cells/python-net/tr/aspose.cells/range) nesnesi


```python

def create_range(self, address):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| address | str | Aralığın adresi.|


##  create_range(self, upper_left_cell, lower_right_cell) {#str-str}
Bir hücre aralığından [`Range`](/cells/python-net/tr/aspose.cells/range) nesnesini oluşturur.


###  İadeler

[`Range`](/cells/python-net/tr/aspose.cells/range) nesnesi


```python

def create_range(self, upper_left_cell, lower_right_cell):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| upper_left_cell | str | Sol üst hücre adı.|
| lower_right_cell | str | Sağ alt hücre adı.|


##  create_range(self, first_index, number, is_vertical) {#int-int-bool}
Hücre satırlarından veya hücre sütunlarından [`Range`](/cells/python-net/tr/aspose.cells/range) nesnesini oluşturur.


###  İadeler

[`Range`](/cells/python-net/tr/aspose.cells/range) nesnesi.


```python

def create_range(self, first_index, number, is_vertical):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| first_index | int | İlk satır indeksi veya ilk sütun indeksi, sıfır tabanlı.|
| number | int | Toplam satır veya sütun sayısı, bir baz alınarak.|
| is_vertical | bool | Doğru - Hücre sütunlarından oluşturulan aralık. Yanlış - Hücre satırlarından oluşturulan aralık.|


##  create_range(self, first_row, first_column, total_rows, total_columns) {#int-int-int-int}
Bir hücre aralığından [`Range`](/cells/python-net/tr/aspose.cells/range) nesnesini oluşturur.


###  İadeler

[`Range`](/cells/python-net/tr/aspose.cells/range) nesnesi


```python

def create_range(self, first_row, first_column, total_rows, total_columns):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| first_row | int |Bu aralığın ilk satırı|
| first_column | int | Bu aralığın ilk sütunu|
| total_rows | int | Satır sayısı|
| total_columns | int | Sütun sayısı|



###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Cells`](/cells/python-net/tr/aspose.cells/cells)
* sınıf [`Range`](/cells/python-net/tr/aspose.cells/range)
