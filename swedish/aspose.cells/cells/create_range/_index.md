---
title: create_range metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 190
url: /sv/aspose.cells/cells/create_range/
is_root: false
---
##  create_range(self, address) {#str}
Skapar ett [`Range`](/cells/python-net/sv/aspose.cells/range)-objekt från en adress i intervallet.


###  Returnerar

Ett [`Range`](/cells/python-net/sv/aspose.cells/range)-objekt


```python

def create_range(self, address):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| address | str | Adressen för intervallet.|


##  create_range(self, upper_left_cell, lower_right_cell) {#str-str}
Skapar ett [`Range`](/cells/python-net/sv/aspose.cells/range)-objekt från ett cellområde.


###  Returnerar

Ett [`Range`](/cells/python-net/sv/aspose.cells/range)-objekt


```python

def create_range(self, upper_left_cell, lower_right_cell):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| upper_left_cell | str | Cellnamn övre vänstra.|
| lower_right_cell | str | Cellnamn längst ner till höger.|


##  create_range(self, first_index, number, is_vertical) {#int-int-bool}
Skapar ett [`Range`](/cells/python-net/sv/aspose.cells/range)-objekt från rader av celler eller kolumner av celler.


###  Returnerar

Ett [`Range`](/cells/python-net/sv/aspose.cells/range)-objekt.


```python

def create_range(self, first_index, number, is_vertical):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| first_index | int | Index för första raden eller index för första kolumnen, nollbaserat.|
| number | int | Totalt antal rader eller kolumner, baserat på en.|
| is_vertical | bool | Sant - Område skapat från kolumner av celler. Falskt - Område skapat från rader av celler.|


##  create_range(self, first_row, first_column, total_rows, total_columns) {#int-int-int-int}
Skapar ett [`Range`](/cells/python-net/sv/aspose.cells/range)-objekt från ett cellområde.


###  Returnerar

Ett [`Range`](/cells/python-net/sv/aspose.cells/range)-objekt


```python

def create_range(self, first_row, first_column, total_rows, total_columns):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| first_row | int |Första raden i detta intervall|
| first_column | int | Första kolumnen i detta intervall|
| total_rows | int | Antal rader|
| total_columns | int | Antal kolumner|



###  Se även
* modul [`aspose.cells`](../../)
* klass [`Cells`](/cells/python-net/sv/aspose.cells/cells)
* klass [`Range`](/cells/python-net/sv/aspose.cells/range)
