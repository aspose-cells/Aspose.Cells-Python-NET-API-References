---
title: set_table_formula metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 380
url: /sv/aspose.cells/cell/set_table_formula/
is_root: false
---
##  set_table_formula(self, row_number, column_number, row_input_cell, column_input_cell, values) {#int-int-str-str-list}
Skapa en datatabell med två variabler för ett givet område med början från den här cellen.



```python

def set_table_formula(self, row_number, column_number, row_input_cell, column_input_cell, values):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| row_number | int | Antal rader att fylla i formeln.|
| column_number | int | Antal kolumner som formeln ska fyllas i.|
| row_input_cell | str | radens inmatningscell|
| column_input_cell | str | kolumnens inmatningscell|
| values | list | värden för celler i tabellformelintervallet|


##  set_table_formula(self, row_number, column_number, input_cell, is_row_input, values) {#int-int-str-bool-list}
Skapa en variabel datatabell för ett givet område med början från den här cellen.



```python

def set_table_formula(self, row_number, column_number, input_cell, is_row_input, values):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| row_number | int | Antal rader att fylla i formeln.|
| column_number | int | Antal kolumner som formeln ska fyllas i.|
| input_cell | str |inmatningscellen|
| is_row_input | bool | Anger om inmatningscellen är en radinmatningscell (sant) eller en kolumninmatningscell (falskt).|
| values | list | värden för celler i tabellformelintervallet|


##  set_table_formula(self, row_number, column_number, row_index_of_input_cell, column_index_of_input_cell, is_row_input, values) {#int-int-int-int-bool-list}
Skapa en variabel datatabell för ett givet område med början från den här cellen.



```python

def set_table_formula(self, row_number, column_number, row_index_of_input_cell, column_index_of_input_cell, is_row_input, values):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| row_number | int | Antal rader att fylla i formeln.|
| column_number | int | Antal kolumner som formeln ska fyllas i.|
| row_index_of_input_cell | int | radindex för inmatningscellen|
| column_index_of_input_cell | int | kolumnindex för inmatningscellen|
| is_row_input | bool | Anger om inmatningscellen är en radinmatningscell (sant) eller en kolumninmatningscell (falskt).|
| values | list | värden för celler i tabellformelintervallet|


##  set_table_formula(self, row_number, column_number, row_index_of_row_input_cell, column_index_of_row_input_cell, row_index_of_column_input_cell, column_index_of_column_input_cell, values) {#int-int-int-int-int-int-list}
Skapa en datatabell med två variabler för ett givet område med början från den här cellen.



```python

def set_table_formula(self, row_number, column_number, row_index_of_row_input_cell, column_index_of_row_input_cell, row_index_of_column_input_cell, column_index_of_column_input_cell, values):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| row_number | int | Antal rader att fylla i formeln.|
| column_number | int | Antal kolumner som formeln ska fyllas i.|
| row_index_of_row_input_cell | int | radindex för radinmatningscellen|
| column_index_of_row_input_cell | int | kolumnindex för radinmatningscellen|
| row_index_of_column_input_cell | int | radindex för kolumnens inmatningscell|
| column_index_of_column_input_cell | int | kolumnindex för kolumnens inmatningscell|
| values | list | värden för celler i tabellformelintervallet|



###  Se även
* modul [`aspose.cells`](../../)
* klass [`Cell`](/cells/python-net/sv/aspose.cells/cell)
