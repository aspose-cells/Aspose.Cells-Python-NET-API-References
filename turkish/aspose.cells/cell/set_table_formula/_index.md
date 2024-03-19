---
title: set_table_formula yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 370
url: /tr/aspose.cells/cell/set_table_formula/
is_root: false
---
##  set_table_formula {#int-int-str-str-list}
Bu hücreden başlayarak verilen aralık için iki değişkenli veri tablosu oluşturun.



```python
def set_table_formula(self, row_number, column_number, row_input_cell, column_input_cell, values):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| row_number | int | Formülün doldurulacağı satır sayısı.|
| column_number | int | Formülün doldurulacağı sütun sayısı.|
| row_input_cell | str | satır giriş hücresi|
| column_input_cell | str | sütun giriş hücresi|
| values | list | tablo formül aralığındaki hücreler için değerler|


##  set_table_formula {#int-int-str-bool-list}
Bu hücreden başlayarak verilen aralık için tek değişkenli veri tablosu oluşturun.



```python
def set_table_formula(self, row_number, column_number, input_cell, is_row_input, values):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| row_number | int | Formülün doldurulacağı satır sayısı.|
| column_number | int | Formülün doldurulacağı sütun sayısı.|
| input_cell | str | giriş hücresi|
| is_row_input | bool | Giriş hücresinin satır giriş hücresi mi (doğru) yoksa sütun giriş hücresi mi (yanlış) olduğunu belirtir.|
| values | list | tablo formül aralığındaki hücreler için değerler|


##  set_table_formula {#int-int-int-int-bool-list}
Bu hücreden başlayarak verilen aralık için tek değişkenli veri tablosu oluşturun.



```python
def set_table_formula(self, row_number, column_number, row_index_of_input_cell, column_index_of_input_cell, is_row_input, values):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| row_number | int | Formülün doldurulacağı satır sayısı.|
| column_number | int | Formülün doldurulacağı sütun sayısı.|
| row_index_of_input_cell | int | giriş hücresinin satır dizini|
| column_index_of_input_cell | int | giriş hücresinin sütun dizini|
| is_row_input | bool | Giriş hücresinin satır giriş hücresi mi (doğru) yoksa sütun giriş hücresi mi (yanlış) olduğunu belirtir.|
| values | list | tablo formül aralığındaki hücreler için değerler|


##  set_table_formula {#int-int-int-int-int-int-list}
Bu hücreden başlayarak verilen aralık için iki değişkenli veri tablosu oluşturun.



```python
def set_table_formula(self, row_number, column_number, row_index_of_row_input_cell, column_index_of_row_input_cell, row_index_of_column_input_cell, column_index_of_column_input_cell, values):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| row_number | int | Formülün doldurulacağı satır sayısı.|
| column_number | int | Formülün doldurulacağı sütun sayısı.|
| row_index_of_row_input_cell | int | satır giriş hücresinin satır dizini|
| column_index_of_row_input_cell | int | satır giriş hücresinin sütun dizini|
| row_index_of_column_input_cell | int | sütun giriş hücresinin satır dizini|
| column_index_of_column_input_cell | int | sütun giriş hücresinin sütun dizini|
| values | list | tablo formül aralığındaki hücreler için değerler|



###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Cell`](/cells/python-net/tr/aspose.cells/cell)
