---
title: Metodo create_range
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 190
url: /it/aspose.cells/cells/create_range/
is_root: false
---
##  create_range(self, address) {#str}
Crea un oggetto [`Range`](/cells/python-net/it/aspose.cells/range) da un indirizzo compreso nell'intervallo.


###  ritorna

Un oggetto [`Range`](/cells/python-net/it/aspose.cells/range)


```python

def create_range(self, address):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| address | str | L'indirizzo dell'intervallo.|


##  create_range(self, upper_left_cell, lower_right_cell) {#str-str}
Crea un oggetto [`Range`](/cells/python-net/it/aspose.cells/range) da un intervallo di celle.


###  ritorna

Un oggetto [`Range`](/cells/python-net/it/aspose.cells/range)


```python

def create_range(self, upper_left_cell, lower_right_cell):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| upper_left_cell | str | Nome della cella in alto a sinistra.|
| lower_right_cell | str | Nome della cella in basso a destra.|


##  create_range(self, first_index, number, is_vertical) {#int-int-bool}
Crea un oggetto [`Range`](/cells/python-net/it/aspose.cells/range) da righe di celle o colonne di celle.


###  ritorna

Un oggetto [`Range`](/cells/python-net/it/aspose.cells/range).


```python

def create_range(self, first_index, number, is_vertical):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| first_index | int | Indice della prima riga o indice della prima colonna, a partire da zero.|
| number | int | Numero totale di righe o colonne, in base uno.|
| is_vertical | bool | Vero - Intervallo creato da colonne di celle. Falso - Intervallo creato da righe di celle.|


##  create_range(self, first_row, first_column, total_rows, total_columns) {#int-int-int-int}
Crea un oggetto [`Range`](/cells/python-net/it/aspose.cells/range) da un intervallo di celle.


###  ritorna

Un oggetto [`Range`](/cells/python-net/it/aspose.cells/range)


```python

def create_range(self, first_row, first_column, total_rows, total_columns):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| first_row | int |Prima riga di questa gamma|
| first_column | int | Prima colonna di questo intervallo|
| total_rows | int | Numero di righe|
| total_columns | int | Numero di colonne|



###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Cells`](/cells/python-net/it/aspose.cells/cells)
* classe [`Range`](/cells/python-net/it/aspose.cells/range)
