---
title: Metodo get_threaded_comments
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 70
url: /it/aspose.cells/commentcollection/get_threaded_comments/
is_root: false
---
##  get_threaded_comments(self, cell_name) {#str}
Ottiene i commenti ordinati in base al nome della cella.


###  ritorna




```python

def get_threaded_comments(self, cell_name):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| cell_name | str | Il nome della cella.|

###  Esempio

```python

threadedComments2 = comments.get_threaded_comments("B2")
for i in range(len(threadedComments2)):
    tc = threadedComments2[i]
    note = tc.notes

```


##  get_threaded_comments(self, row, column) {#int-int}
Ottiene i commenti suddivisi in base all'indice di riga e di colonna.


###  ritorna




```python

def get_threaded_comments(self, row, column):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| row | int | Indice di riga.|
| column | int | L'indice della colonna.|

###  Esempio

```python

threadedComments1 = comments.get_threaded_comments(1, 1)
for i in range(len(threadedComments1)):
    tc = threadedComments1[i]
    note = tc.notes

```



###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`CommentCollection`](/cells/python-net/it/aspose.cells/commentcollection)
