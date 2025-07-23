---
title: add yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 20
url: /tr/aspose.cells.pivot/pivottablecollection/add/
is_root: false
---
##  add(self, source_data, dest_cell_name, table_name) {#str-str-str}
Yeni bir PivotTable ekler.


###  İadeler

Yeni eklenen önbellek dizini.


```python

def add(self, source_data, dest_cell_name, table_name):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| source_data | str | Yeni PivotTable önbelleğine ait veriler.|
| dest_cell_name | str | PivotTable raporunun hedef aralığının sol üst köşesindeki hücre.|
| table_name | str | Yeni PivotTable raporunun adı.|


##  add(self, pivot_table, dest_cell_name, table_name) {#aspose.cells.pivot.PivotTable-str-str}
Başka bir PivotTable'a dayalı yeni bir PivotTable ekler.


###  İadeler

Yeni eklenen PivotTable dizini.


```python

def add(self, pivot_table, dest_cell_name, table_name):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| pivot_table | [`PivotTable`](/cells/python-net/tr/aspose.cells.pivot/pivottable) | Kaynak pivotTable.|
| dest_cell_name | str | PivotTable raporunun hedef aralığının sol üst köşesindeki hücre.|
| table_name | str | Yeni PivotTable raporunun adı.|


##  add(self, source_data, dest_cell_name, table_name, use_same_source) {#str-str-str-bool}
Yeni bir PivotTable ekler.


###  İadeler

Yeni eklenen önbellek dizini.


```python

def add(self, source_data, dest_cell_name, table_name, use_same_source):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| source_data | str | Yeni PivotTable önbelleğine ait veriler.|
| dest_cell_name | str | PivotTable raporunun hedef aralığının sol üst köşesindeki hücre.|
| table_name | str | Yeni PivotTable raporunun adı.|
| use_same_source | bool | Mevcut başka bir pivot tablonun bu veri kaynağını kullanmış olması durumunda aynı veri kaynağının kullanılıp kullanılmadığını belirtir.<br/> Özellik doğruysa hafızadan tasarruf edilecektir.|


##  add(self, source_data, row, column, table_name) {#str-int-int-str}
Yeni bir PivotTable ekler.


###  İadeler

Yeni eklenen önbellek dizini.


```python

def add(self, source_data, row, column, table_name):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| source_data | str | Yeni PivotTable için veri hücre aralığı.Örnek: Sheet1!A1:C8|
| row | int |PivotTable raporunun hedef aralığının sol üst köşesindeki hücrenin satır dizini.|
| column | int | PivotTable raporunun hedef aralığının sol üst köşesindeki hücrenin sütun dizini.|
| table_name | str | Yeni PivotTable raporunun adı.|


##  add(self, pivot_table, row, column, table_name) {#aspose.cells.pivot.PivotTable-int-int-str}
Başka bir PivotTable'a dayalı yeni bir PivotTable ekler.


###  İadeler

Yeni eklenen PivotTable dizini.


```python

def add(self, pivot_table, row, column, table_name):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| pivot_table | [`PivotTable`](/cells/python-net/tr/aspose.cells.pivot/pivottable) | Kaynak pivotTable.|
| row | int |PivotTable raporunun hedef aralığının sol üst köşesindeki hücrenin satır dizini.|
| column | int | PivotTable raporunun hedef aralığının sol üst köşesindeki hücrenin sütun dizini.|
| table_name | str | Yeni PivotTable raporunun adı.|


##  add(self, source_data, row, column, table_name, use_same_source) {#str-int-int-str-bool}
Yeni bir PivotTable ekler.


###  İadeler

Yeni eklenen önbellek dizini.


```python

def add(self, source_data, row, column, table_name, use_same_source):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| source_data | str | Yeni PivotTable için veri hücre aralığı.Örnek: Sheet1!A1:C8|
| row | int |PivotTable raporunun hedef aralığının sol üst köşesindeki hücrenin satır dizini.|
| column | int | PivotTable raporunun hedef aralığının sol üst köşesindeki hücrenin sütun dizini.|
| table_name | str | Yeni PivotTable raporunun adı.|
| use_same_source | bool | Mevcut başka bir pivot tablonun bu veri kaynağını kullanmış olması durumunda aynı veri kaynağının kullanılıp kullanılmadığını belirtir.<br/> Özellik doğruysa hafızadan tasarruf edilecektir.|


##  add(self, source_data, cell, table_name, use_same_source, is_xls_classic) {#str-str-str-bool-bool}
Yeni bir PivotTable ekler.


###  İadeler

Yeni eklenen önbellek dizini.


```python

def add(self, source_data, cell, table_name, use_same_source, is_xls_classic):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| source_data | str | Yeni PivotTable için veri hücre aralığı.Örnek: Sheet1!A1:C8|
| cell | str | PivotTable raporunun hedef aralığının sol üst köşesindeki hücre.|
| table_name | str | Yeni PivotTable raporunun adı.|
| use_same_source | bool | Mevcut başka bir pivot tablonun bu veri kaynağını kullanmış olması durumunda aynı veri kaynağının kullanılıp kullanılmadığını belirtir.<br/> Özellik doğruysa hafızadan tasarruf edilecektir.|
| is_xls_classic | bool | Excel 97-2003'ün klasik pivot tablosunun eklenip eklenmeyeceğini belirtir.|


##  add(self, source_data, is_auto_page, page_fields, dest_cell_name, table_name) {#list-bool-aspose.cells.pivot.PivotPageFields-str-str}
Veri kaynağı olarak birden fazla birleştirme aralığına sahip yeni bir PivotTable Nesnesi koleksiyona ekler.


###  İadeler

Yeni eklenen PivotTable dizini.


```python

def add(self, source_data, is_auto_page, page_fields, dest_cell_name, table_name):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| source_data | list | {"Sayfa1!A1:C8","Sayfa2!A1:B8"} gibi çoklu konsolidasyon aralıkları |
| is_auto_page | bool | Tek sayfalık alanın otomatik olarak oluşturulması.<br/> Eğer doğruysa, pageFields parametresi göz ardı edilecektir.|
| page_fields | [`PivotPageFields`](/cells/python-net/tr/aspose.cells.pivot/pivotpagefields) | Pivot sayfa alan öğeleri.|
| dest_cell_name | str | destCellName Yeni PivotTable raporunun adı.|
| table_name | str | yeni PivotTable raporunun adı.|


##  add(self, source_data, row, column, table_name, use_same_source, is_xls_classic) {#str-int-int-str-bool-bool}
Yeni bir PivotTable ekler.


###  İadeler

Yeni eklenen önbellek dizini.


```python

def add(self, source_data, row, column, table_name, use_same_source, is_xls_classic):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| source_data | str | Yeni PivotTable için veri hücre aralığı.Örnek: Sheet1!A1:C8|
| row | int |PivotTable raporunun hedef aralığının sol üst köşesindeki hücrenin satır dizini.|
| column | int | PivotTable raporunun hedef aralığının sol üst köşesindeki hücrenin sütun dizini.|
| table_name | str | Yeni PivotTable raporunun adı.|
| use_same_source | bool | Mevcut başka bir pivot tablonun bu veri kaynağını kullanmış olması durumunda aynı veri kaynağının kullanılıp kullanılmadığını belirtir.<br/> Özellik doğruysa hafızadan tasarruf edilecektir.|
| is_xls_classic | bool | Excel 97-2003'ün klasik pivot tablosunun eklenip eklenmeyeceğini belirtir.|


##  add(self, source_data, is_auto_page, page_fields, row, column, table_name) {#list-bool-aspose.cells.pivot.PivotPageFields-int-int-str}
Veri kaynağı olarak birden fazla birleştirme aralığına sahip yeni bir PivotTable Nesnesi koleksiyona ekler.


###  İadeler

Yeni eklenen PivotTable dizini.


```python

def add(self, source_data, is_auto_page, page_fields, row, column, table_name):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| source_data | list | {"Sayfa1!A1:C8","Sayfa2!A1:B8"} gibi çoklu konsolidasyon aralıkları |
| is_auto_page | bool | Tek sayfalık alanın otomatik olarak oluşturulması.<br/> Doğruysa, aşağıdaki parametre pageFields yok sayılacaktır|
| page_fields | [`PivotPageFields`](/cells/python-net/tr/aspose.cells.pivot/pivotpagefields) | Pivot sayfa alan öğeleri.|
| row | int |PivotTable raporunun hedef aralığının sol üst köşesindeki hücrenin satır dizini.|
| column | int | PivotTable raporunun hedef aralığının sol üst köşesindeki hücrenin sütun dizini.|
| table_name | str | Yeni PivotTable raporunun adı.|



###  Ayrıca bakınız
* modül [`aspose.cells.pivot`](../../)
* sınıf [`PivotTableCollection`](/cells/python-net/tr/aspose.cells.pivot/pivottablecollection)
