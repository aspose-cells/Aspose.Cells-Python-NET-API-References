---
title: Metodo merge
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 780
url: /it/aspose.cells/cells/merge/
is_root: false
---
##  merge {#int-int-int-int}
Unisce un intervallo specificato di celle in un'unica cella.



```python
def merge(self, first_row, first_column, total_rows, total_columns):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| first_row | int | Prima riga di questo intervallo (in base zero)|
| first_column | int | Prima colonna di questo intervallo (in base zero)|
| total_rows | int | Numero di righe (una in base)|
| total_columns | int | Numero di colonne (una in base)|
###  Osservazioni

Fai riferimento alla cella unita tramite l'indirizzo della cella in alto a sinistra nell'intervallo.

##  merge {#int-int-int-int-bool}

Unisce un intervallo specificato di celle in un'unica cella.



```python
def merge(self, first_row, first_column, total_rows, total_columns, merge_conflict):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| first_row | int | Prima riga di questo intervallo (in base zero)|
| first_column | int | Prima colonna di questo intervallo (in base zero)|
| total_rows | int | Numero di righe (una in base)|
| total_columns | int | Numero di colonne (una in base)|
| merge_conflict | bool | Unisci intervalli uniti in conflitto.|
###  Osservazioni

Fai riferimento alla cella unita tramite l'indirizzo della cella in alto a sinistra nell'intervallo.
Se mergeConflitto è true e l'intervallo unito è in conflitto con altre celle unite,
le altre celle unite verranno rimosse automaticamente.

##  merge {#int-int-int-int-bool-bool}
Unisce un intervallo specificato di celle in un'unica cella.



```python
def merge(self, first_row, first_column, total_rows, total_columns, check_conflict, merge_conflict):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| first_row | int | Prima riga di questo intervallo (in base zero)|
| first_column | int | Prima colonna di questo intervallo (in base zero)|
| total_rows | int | Numero di righe (una in base)|
| total_columns | int | Numero di colonne (una in base)|
| check_conflict | bool | Indica se il controllo delle celle unite interseca altre celle unite|
| merge_conflict | bool | Unisci intervalli uniti in conflitto.|
###  Osservazioni

Fai riferimento alla cella unita tramite l'indirizzo della cella in alto a sinistra nell'intervallo.
Se mergeConflitto è true e l'intervallo unito è in conflitto con altre celle unite,
le altre celle unite verranno rimosse automaticamente.


###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Cells`](/cells/python-net/it/aspose.cells/cells)
