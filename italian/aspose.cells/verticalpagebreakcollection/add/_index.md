---
title: Metodo add
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 20
url: /it/aspose.cells/verticalpagebreakcollection/add/
is_root: false
---
##  add(self, column) {#int}
Aggiunge un'interruzione di pagina verticale alla raccolta.


###  ritorna

[`VerticalPageBreak`](/cells/python-net/it/aspose.cells/verticalpagebreak) indice oggetto.


```python

def add(self, column):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| column | int | Cell indice di colonna, a partire da zero.|
###  Osservazioni

L'interruzione di pagina viene aggiunta in alto a sinistra della cella.
Impostare contemporaneamente un'interruzione di pagina orizzontale e un'interruzione di pagina verticale.

##  add(self, cell_name) {#str}
Aggiunge un'interruzione di pagina verticale alla raccolta.


###  ritorna

[`VerticalPageBreak`](/cells/python-net/it/aspose.cells/verticalpagebreak) indice oggetto.


```python

def add(self, cell_name):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| cell_name | str | Cell nome.|
###  Osservazioni

L'interruzione di pagina viene aggiunta in alto a sinistra della cella.
Impostare contemporaneamente un'interruzione di pagina orizzontale e un'interruzione di pagina verticale.

##  add(self, row, column) {#int-int}
Aggiunge un'interruzione di pagina verticale alla raccolta.


###  ritorna

[`VerticalPageBreak`](/cells/python-net/it/aspose.cells/verticalpagebreak) indice oggetto.


```python

def add(self, row, column):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| row | int | Cell indice di riga, a partire da zero.|
| column | int | Cell indice di colonna, a partire da zero.|
###  Osservazioni

L'interruzione di pagina viene aggiunta in alto a sinistra della cella.
Impostare contemporaneamente un'interruzione di pagina orizzontale e un'interruzione di pagina verticale.

##  add(self, start_row, end_row, column) {#int-int-int}
Aggiunge un'interruzione di pagina verticale alla raccolta.


###  ritorna

[`VerticalPageBreak`](/cells/python-net/it/aspose.cells/verticalpagebreak) indice oggetto.


```python

def add(self, start_row, end_row, column):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| start_row | int | Indice della riga iniziale, a partire da zero.|
| end_row | int | Indice di riga finale, basato su zero.|
| column | int | Indice di colonna, a partire da zero.|
###  Osservazioni

Questo metodo viene utilizzato per inserire un'interruzione di pagina verticale all'interno di un'area di stampa.


###  Guarda anche

* modulo [`aspose.cells`](../../)
* classe [`VerticalPageBreak`](/cells/python-net/it/aspose.cells/verticalpagebreak)
* classe [`VerticalPageBreakCollection`](/cells/python-net/it/aspose.cells/verticalpagebreakcollection)
