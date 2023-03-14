---
title: create_range metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 190
url: /sv/aspose.cells/cells/create_range/
is_root: false
---
##  create_range(address) {#str}
Skapar ett [Range](/cells/python-net/sv/aspose.cells/range)-objekt från en adress i intervallet.


###  Returnerar

Ett [Range](/cells/python-net/sv/aspose.cells/range) objekt


```python
def create_range(self, address):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| address | str | Adressen till området.|


##  create_range(upper_left_cell, lower_right_cell) {#str-str}
Skapar ett [Range](/cells/python-net/sv/aspose.cells/range)-objekt från ett cellintervall.


###  Returnerar

Ett [Range](/cells/python-net/sv/aspose.cells/range) objekt


```python
def create_range(self, upper_left_cell, lower_right_cell):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| upper_left_cell | str | Uppe till vänster cellnamn.|
| lower_right_cell | str | Nedre höger cellnamn.|


##  create_range(first_index, number, is_vertical) {#int-int-bool}
Skapar ett [Range](/cells/python-net/sv/aspose.cells/range)-objekt från rader med celler eller kolumner med celler.


###  Returnerar

Ett [Range](/cells/python-net/sv/aspose.cells/range) objekt.


```python
def create_range(self, first_index, number, is_vertical):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| first_index | int | Första radens index eller första kolumnindex, nollbaserat.|
| number | int | Totalt antal rader eller kolumner, baserat på en.|
| is_vertical | bool | True - Område skapat från kolumner med celler. Falskt – intervall skapat från rader med celler.|


##  create_range(first_row, first_column, total_rows, total_columns) {#int-int-int-int}
Skapar ett [Range](/cells/python-net/sv/aspose.cells/range)-objekt från ett cellintervall.


###  Returnerar

Ett [Range](/cells/python-net/sv/aspose.cells/range) objekt


```python
def create_range(self, first_row, first_column, total_rows, total_columns):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| first_row | int | Första raden i detta intervall|
| first_column | int | Första kolumnen i detta intervall|
| total_rows | int | Antal rader|
| total_columns | int | Antal kolumner|



###  Se även
* modul [aspose.cells](../../)
* klass [Cells](/cells/python-net/sv/aspose.cells/cells)
* klass [Range](/cells/python-net/sv/aspose.cells/range)
