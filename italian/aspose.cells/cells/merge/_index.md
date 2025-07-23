---
title: Metodo merge
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 800
url: /it/aspose.cells/cells/merge/
is_root: false
---
##  merge(self, first_row, first_column, total_rows, total_columns) {#int-int-int-int}
Unisce un intervallo di celle specificato in un'unica cella.



```python

def merge(self, first_row, first_column, total_rows, total_columns):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| first_row | int | Prima riga di questo intervallo (a partire da zero)|
| first_column | int | Prima colonna di questo intervallo (a partire da zero)|
| total_rows | int |Numero di righe (in base a uno)|
| total_columns | int | Numero di colonne (base uno)|
###  Osservazioni

Fare riferimento alla cella unita tramite l'indirizzo della cella in alto a sinistra nell'intervallo.

##  merge(self, first_row, first_column, total_rows, total_columns, merge_conflict) {#int-int-int-int-bool}

Unisce un intervallo di celle specificato in un'unica cella.



```python

def merge(self, first_row, first_column, total_rows, total_columns, merge_conflict):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| first_row | int | Prima riga di questo intervallo (a partire da zero)|
| first_column | int | Prima colonna di questo intervallo (a partire da zero)|
| total_rows | int |Numero di righe (in base a uno)|
| total_columns | int | Numero di colonne (base uno)|
| merge_conflict | bool | Unisci intervalli uniti in conflitto.|
###  Osservazioni

Fare riferimento alla cella unita tramite l'indirizzo della cella in alto a sinistra nell'intervallo.
Se mergeConflict è vero e l'intervallo unito è in conflitto con altre celle unite,
le altre celle unite verranno rimosse automaticamente.

##  merge(self, first_row, first_column, total_rows, total_columns, check_conflict, merge_conflict) {#int-int-int-int-bool-bool}
Unisce un intervallo di celle specificato in un'unica cella.



```python

def merge(self, first_row, first_column, total_rows, total_columns, check_conflict, merge_conflict):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| first_row | int | Prima riga di questo intervallo (a partire da zero)|
| first_column | int | Prima colonna di questo intervallo (a partire da zero)|
| total_rows | int |Numero di righe (in base a uno)|
| total_columns | int | Numero di colonne (base uno)|
| check_conflict | bool | Indica se il controllo delle celle unite interseca altre celle unite|
| merge_conflict | bool | Unisci intervalli uniti in conflitto.|
###  Osservazioni

Fare riferimento alla cella unita tramite l'indirizzo della cella in alto a sinistra nell'intervallo.
Se mergeConflict è vero e l'intervallo unito è in conflitto con altre celle unite,
le altre celle unite verranno rimosse automaticamente.


###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Cells`](/cells/python-net/it/aspose.cells/cells)
