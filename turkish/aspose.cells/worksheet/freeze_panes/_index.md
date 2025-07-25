---
title: freeze_panes yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 140
url: /tr/aspose.cells/worksheet/freeze_panes/
is_root: false
---
##  freeze_panes(self, cell_name, freezed_rows, freezed_columns) {#str-int-int}
Çalışma sayfasındaki belirtilen hücredeki bölmeleri dondurur.



```python

def freeze_panes(self, cell_name, freezed_rows, freezed_columns):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| cell_name | str | Cell adı.|
| freezed_rows | int | Üst bölmede görünen satır sayısı, satır indeksinden fazla olamaz.|
| freezed_columns | int | Sol bölmede görünen sütun sayısı, sütun indeksinden fazla olamaz.|
###  Notlar

Satır dizini ve sütun dizini sıfır olamaz. Satır sayısı ve sütun sayısı
ayrıca hepsi sıfır olamaz.

##  freeze_panes(self, row, column, freezed_rows, freezed_columns) {#int-int-int-int}
Çalışma sayfasındaki belirtilen hücredeki bölmeleri dondurur.



```python

def freeze_panes(self, row, column, freezed_rows, freezed_columns):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| row | int | Satır dizini.|
| column | int | Sütun dizini.|
| freezed_rows | int | Üst bölmede görünen satır sayısı, satır indeksinden fazla olamaz.|
| freezed_columns | int | Sol bölmede görünen sütun sayısı, sütun indeksinden fazla olamaz.|
###  Notlar

Satır dizini ve sütun dizini sıfır olamaz. Satır sayısı ve sütun sayısı
ayrıca hepsi sıfır olamaz.


İlk iki parametre dondurulan konumu, son iki parametre ise sol üst bölmede dondurulan alanı belirtir.


###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Worksheet`](/cells/python-net/tr/aspose.cells/worksheet)
