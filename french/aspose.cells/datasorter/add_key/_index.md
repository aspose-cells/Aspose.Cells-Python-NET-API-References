---
title: méthode add_key
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 30
url: /fr/aspose.cells/datasorter/add_key/
is_root: false
---
##  add_key(self, key, order) {#int-aspose.cells.SortOrder}
Ajoute un index de colonne trié et un ordre de tri.



```python

def add_key(self, key, order):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| key | int | L'index de colonne trié (position absolue, la colonne A est 0, B est 1, ...)|
| order | [`SortOrder`](/cells/python-net/fr/aspose.cells/sortorder) | L'ordre de tri|


##  add_key(self, key, order, custom_list) {#int-aspose.cells.SortOrder-str}
Ajoute un index de colonne trié et un ordre de tri avec une liste de tri personnalisée.



```python

def add_key(self, key, order, custom_list):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| key | int | L'index de colonne trié (position absolue, la colonne A est 0, B est 1, ...)|
| order | [`SortOrder`](/cells/python-net/fr/aspose.cells/sortorder) | L'ordre de tri.|
| custom_list | str | La liste de tri personnalisée.|


##  add_key(self, key, order, custom_list) {#int-aspose.cells.SortOrder-list}
Ajoute un index de colonne trié et un ordre de tri avec une liste de tri personnalisée.



```python

def add_key(self, key, order, custom_list):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| key | int | L'index de colonne trié (position absolue, la colonne A est 0, B est 1, ...)|
| order | [`SortOrder`](/cells/python-net/fr/aspose.cells/sortorder) | L'ordre de tri.|
| custom_list | list | La liste de tri personnalisée.|


##  add_key(self, key, type, order, custom_list) {#int-aspose.cells.SortOnType-aspose.cells.SortOrder-any}
Ajoute un index de colonne trié et un ordre de tri avec une liste de tri personnalisée.



```python

def add_key(self, key, type, order, custom_list):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| key | int | L'index de colonne trié (position absolue, la colonne A est 0, B est 1, ...)|
| type | [`SortOnType`](/cells/python-net/fr/aspose.cells/sortontype) | Le type de valeur triée.|
| order | [`SortOrder`](/cells/python-net/fr/aspose.cells/sortorder) | L'ordre de tri.|
| custom_list | any | La liste de tri personnalisée.|
###  Remarques

Si le type est SortOnType.CellColor ou SortOnType.FontColor, la liste personnalisée est Color.


###  Voir également

* module [`aspose.cells`](../../)
* classe [`DataSorter`](/cells/python-net/fr/aspose.cells/datasorter)
