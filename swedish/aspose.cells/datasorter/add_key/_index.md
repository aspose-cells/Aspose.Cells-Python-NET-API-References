---
title: add_key metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 30
url: /sv/aspose.cells/datasorter/add_key/
is_root: false
---
##  add_key(self, key, order) {#int-aspose.cells.SortOrder}
Lägger till sorterat kolumnindex och sorteringsordning.



```python

def add_key(self, key, order):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| key | int | Det sorterade kolumnindexet (absolut position, kolumn A är 0, B är 1, ...)|
| order | [`SortOrder`](/cells/python-net/sv/aspose.cells/sortorder) | Sorteringsordningen|


##  add_key(self, key, order, custom_list) {#int-aspose.cells.SortOrder-str}
Lägger till sorterat kolumnindex och sorteringsordning med anpassad sorteringslista.



```python

def add_key(self, key, order, custom_list):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| key | int | Det sorterade kolumnindexet (absolut position, kolumn A är 0, B är 1, ...)|
| order | [`SortOrder`](/cells/python-net/sv/aspose.cells/sortorder) | Sorteringsordningen.|
| custom_list | str | Den anpassade sorteringslistan.|


##  add_key(self, key, order, custom_list) {#int-aspose.cells.SortOrder-list}
Lägger till sorterat kolumnindex och sorteringsordning med anpassad sorteringslista.



```python

def add_key(self, key, order, custom_list):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| key | int | Det sorterade kolumnindexet (absolut position, kolumn A är 0, B är 1, ...)|
| order | [`SortOrder`](/cells/python-net/sv/aspose.cells/sortorder) | Sorteringsordningen.|
| custom_list | list | Den anpassade sorteringslistan.|


##  add_key(self, key, type, order, custom_list) {#int-aspose.cells.SortOnType-aspose.cells.SortOrder-any}
Lägger till sorterat kolumnindex och sorteringsordning med anpassad sorteringslista.



```python

def add_key(self, key, type, order, custom_list):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| key | int | Det sorterade kolumnindexet (absolut position, kolumn A är 0, B är 1, ...)|
| type | [`SortOnType`](/cells/python-net/sv/aspose.cells/sortontype) | Den sorterade värdetypen.|
| order | [`SortOrder`](/cells/python-net/sv/aspose.cells/sortorder) | Sorteringsordningen.|
| custom_list | any | Den anpassade sorteringslistan.|
###  Anmärkningar

Om typen är SortOnType.CellColor eller SortOnType.FontColor, är customList Color.


###  Se även

* modul [`aspose.cells`](../../)
* klass [`DataSorter`](/cells/python-net/sv/aspose.cells/datasorter)
