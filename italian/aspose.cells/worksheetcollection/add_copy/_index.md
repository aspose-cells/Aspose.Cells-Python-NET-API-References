---
title: Metodo add_copy
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 30
url: /it/aspose.cells/worksheetcollection/add_copy/
is_root: false
---
##  add_copy(self, sheet_name) {#str}
Aggiunge un foglio di lavoro alla raccolta e copia i dati da un foglio di lavoro esistente.


###  ritorna

[`Worksheet`](/cells/python-net/it/aspose.cells/worksheet) indice oggetto.


```python

def add_copy(self, sheet_name):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| sheet_name | str | Nome del foglio di lavoro di origine.|
###  Eccezioni
| Eccezione| Descrizione|
| :- | :- |
| [`CellsException`](/cells/python-net/it/aspose.cells/cellsexception) | Specifica un nome di foglio di lavoro non valido.|




##  add_copy(self, sheet_index) {#int}
Aggiunge un foglio di lavoro alla raccolta e copia i dati da un foglio di lavoro esistente.


###  ritorna

[`Worksheet`](/cells/python-net/it/aspose.cells/worksheet) indice oggetto.


```python

def add_copy(self, sheet_index):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| sheet_index | int | Indice del foglio di lavoro sorgente.|


##  add_copy(self, source, dest_sheet_names) {#list-list}
Copia un gruppo di fogli di lavoro.



```python

def add_copy(self, source, dest_sheet_names):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| source | list | I fogli di lavoro originali.|
| dest_sheet_names | list | I nomi dei fogli copiati.|



###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`CellsException`](/cells/python-net/it/aspose.cells/cellsexception)
* classe [`Worksheet`](/cells/python-net/it/aspose.cells/worksheet)
* classe [`WorksheetCollection`](/cells/python-net/it/aspose.cells/worksheetcollection)
