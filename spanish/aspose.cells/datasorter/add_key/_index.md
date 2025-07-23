---
title: método add_key
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 30
url: /es/aspose.cells/datasorter/add_key/
is_root: false
---
##  add_key(self, key, order) {#int-aspose.cells.SortOrder}
Agrega índice de columna ordenado y orden de clasificación.



```python

def add_key(self, key, order):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| key | int | El índice de la columna ordenada (posición absoluta, columna A es 0, B es 1, ...)|
| order | [`SortOrder`](/cells/python-net/es/aspose.cells/sortorder) | El orden de clasificación|


##  add_key(self, key, order, custom_list) {#int-aspose.cells.SortOrder-str}
Agrega un índice de columna ordenado y un orden de clasificación con una lista de clasificación personalizada.



```python

def add_key(self, key, order, custom_list):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| key | int | El índice de la columna ordenada (posición absoluta, columna A es 0, B es 1, ...)|
| order | [`SortOrder`](/cells/python-net/es/aspose.cells/sortorder) | El orden de clasificación.|
| custom_list | str | La lista de ordenación personalizada.|


##  add_key(self, key, order, custom_list) {#int-aspose.cells.SortOrder-list}
Agrega un índice de columna ordenado y un orden de clasificación con una lista de clasificación personalizada.



```python

def add_key(self, key, order, custom_list):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| key | int | El índice de la columna ordenada (posición absoluta, columna A es 0, B es 1, ...)|
| order | [`SortOrder`](/cells/python-net/es/aspose.cells/sortorder) | El orden de clasificación.|
| custom_list | list | La lista de ordenación personalizada.|


##  add_key(self, key, type, order, custom_list) {#int-aspose.cells.SortOnType-aspose.cells.SortOrder-any}
Agrega un índice de columna ordenado y un orden de clasificación con una lista de clasificación personalizada.



```python

def add_key(self, key, type, order, custom_list):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| key | int | El índice de la columna ordenada (posición absoluta, columna A es 0, B es 1, ...)|
| type | [`SortOnType`](/cells/python-net/es/aspose.cells/sortontype) | El tipo de valor ordenado.|
| order | [`SortOrder`](/cells/python-net/es/aspose.cells/sortorder) | El orden de clasificación.|
| custom_list | any | La lista de ordenación personalizada.|
###  Observaciones

Si el tipo es SortOnType.CellColor o SortOnType.FontColor, la lista personalizada es Color.


###  Ver también

* módulo [`aspose.cells`](../../)
* clase [`DataSorter`](/cells/python-net/es/aspose.cells/datasorter)
