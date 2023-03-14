---
title: metodo find
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 290
url: /it/aspose.cells/cells/find/
is_root: false
---
##  find(what, previous_cell) {#any-Cell}
Trova la cella contenente l'oggetto di input.


###  ritorna

Cell oggetto.


```python
def find(self, what, previous_cell):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| what | any | L'oggetto da cercare.<br/> Il tipo deve essere int,double,DateTime,string,bool.|
| previous_cell | [Cell](/cells/python-net/it/aspose.cells/cell) | Cella precedente con lo stesso oggetto.<br/> Questo parametro può essere impostato su null se si esegue la ricerca dall'inizio.|
###  Osservazioni

Restituisce null (Niente) se non viene trovata alcuna cella.

##  find(what, previous_cell, find_options) {#any-Cell-FindOptions}

Trova la cella contenente l'oggetto di input.


###  ritorna

Cell oggetto.


```python
def find(self, what, previous_cell, find_options):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| what | any | L'oggetto da cercare.<br/> Il tipo deve essere int,double,DateTime,string,bool.|
| previous_cell | [Cell](/cells/python-net/it/aspose.cells/cell) | Cella precedente con lo stesso oggetto.<br/> Questo parametro può essere impostato su null se si esegue la ricerca dall'inizio.|
| find_options | [FindOptions](/cells/python-net/it/aspose.cells/findoptions) | Trova le opzioni|
###  Osservazioni

Restituisce null (Niente) se non viene trovata alcuna cella.


###  Guarda anche

* modulo [aspose.cells](../../)
* classe [Cells](/cells/python-net/it/aspose.cells/cells)
