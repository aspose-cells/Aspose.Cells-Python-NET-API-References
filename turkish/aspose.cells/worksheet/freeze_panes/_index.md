---
title: freeze_panes yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 140
url: /tr/aspose.cells/worksheet/freeze_panes/
is_root: false
---
##  freeze_panes {#str-int-int}
Çalışma sayfasında belirtilen hücredeki bölmeleri dondurur.



```python
def freeze_panes(self, cell_name, freezed_rows, freezed_columns):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| cell_name | str | Cell adı.|
| freezed_rows | int | Üst bölmedeki görünür satırların sayısı, satır dizininden fazla değil.|
| freezed_columns | int | Sol bölmedeki görünür sütunların sayısı, sütun dizininden fazla değil.|
###  Notlar

Satır indeksi ve sütun indeksinin tümü sıfır olamaz. Satır sayısı ve sütun sayısı
ayrıca hepsi sıfır olamaz.

##  freeze_panes {#int-int-int-int}
Çalışma sayfasında belirtilen hücredeki bölmeleri dondurur.



```python
def freeze_panes(self, row, column, freezed_rows, freezed_columns):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| row | int | Satır dizini.|
| column | int | Sütun dizini.|
| freezed_rows | int | Üst bölmedeki görünür satırların sayısı, satır dizininden fazla değil.|
| freezed_columns | int | Sol bölmedeki görünür sütunların sayısı, sütun dizininden fazla değil.|
###  Notlar

Satır indeksi ve sütun indeksinin tümü sıfır olamaz. Satır sayısı ve sütun sayısı
ayrıca hepsi sıfır olamaz.


İlk iki parametre donma konumunu belirtir ve son iki parametre sol üst bölmede dondurulan alanı belirtir.


###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Worksheet`](/cells/python-net/tr/aspose.cells/worksheet)
