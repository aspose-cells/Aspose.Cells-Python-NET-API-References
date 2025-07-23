---
title: delete_rows yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 260
url: /tr/aspose.cells/cells/delete_rows/
is_root: false
---
##  delete_rows(self, row_index, total_rows) {#int-int}
Birden fazla satırı siler.



```python

def delete_rows(self, row_index, total_rows):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| row_index | int | Silinecek ilk satır indeksi.|
| total_rows | int | Silinecek satır sayısı.|
###  Notlar

Silinen aralık tablonun (ListObject) en üst kısmını (tamamını değil) içeriyorsa,
menzil silinemedi ve hiçbir şey yapılmayacak.
MS Excel ile de aynı şekilde çalışır.

##  delete_rows(self, row_index, total_rows, update_reference) {#int-int-bool}
Çalışma sayfasındaki birden fazla satırı siler.


###  İadeler




```python

def delete_rows(self, row_index, total_rows, update_reference):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| row_index | int | Silinecek ilk satırın indeksi.|
| total_rows | int | Silinecek satır sayısı.|
| update_reference | bool | Diğer çalışma sayfalarındaki referansların güncellenip güncellenmeyeceğini belirtir.|


##  delete_rows(self, row_index, total_rows, options) {#int-int-aspose.cells.DeleteOptions}
Çalışma sayfasındaki birden fazla satırı siler.


###  İadeler




```python

def delete_rows(self, row_index, total_rows, options):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| row_index | int | Silinecek ilk satırın indeksi.|
| total_rows | int | Silinecek satır sayısı.|
| options | [`DeleteOptions`](/cells/python-net/tr/aspose.cells/deleteoptions) | Silme işlemi için seçenekler|



###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Cells`](/cells/python-net/tr/aspose.cells/cells)
