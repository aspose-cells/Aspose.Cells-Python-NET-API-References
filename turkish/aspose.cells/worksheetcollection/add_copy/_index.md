---
title: add_copy yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 30
url: /tr/aspose.cells/worksheetcollection/add_copy/
is_root: false
---
##  add_copy {#str}
Koleksiyona bir çalışma sayfası ekler ve mevcut bir çalışma sayfasından verileri kopyalar.


###  İadeler

[`Worksheet`](/cells/python-net/tr/aspose.cells/worksheet) nesne dizini.


```python
def add_copy(self, sheet_name):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| sheet_name | str | Kaynak çalışma sayfasının adı.|
###  İstisnalar
| İstisna| Tanım|
| :- | :- |
| [`CellsException`](/cells/python-net/tr/aspose.cells/cellsexception) | Geçersiz bir çalışma sayfası adını belirtir.|




##  add_copy {#int}
Koleksiyona bir çalışma sayfası ekler ve mevcut bir çalışma sayfasından verileri kopyalar.


###  İadeler

[`Worksheet`](/cells/python-net/tr/aspose.cells/worksheet) nesne dizini.


```python
def add_copy(self, sheet_index):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| sheet_index | int | Kaynak çalışma sayfasının dizini.|


##  add_copy {#list-list}
Bir grup çalışma sayfasını kopyalayın.



```python
def add_copy(self, source, dest_sheet_names):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| source | list | Kaynak çalışma sayfaları.|
| dest_sheet_names | list | Kopyalanan sayfaların adları.|



###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`CellsException`](/cells/python-net/tr/aspose.cells/cellsexception)
* sınıf [`Worksheet`](/cells/python-net/tr/aspose.cells/worksheet)
* sınıf [`WorksheetCollection`](/cells/python-net/tr/aspose.cells/worksheetcollection)
