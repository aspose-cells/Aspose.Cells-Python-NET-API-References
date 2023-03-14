---
title: metodo get_threaded_comments
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 60
url: /it/aspose.cells/commentcollection/get_threaded_comments/
is_root: false
---
##  get_threaded_comments(cell_name) {#str}
Ottiene i commenti in thread in base al nome della cella.


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


##  get_threaded_comments(row, column) {#int-int}
Ottiene i commenti in thread per indice di riga e colonna.


###  ritorna




```python
def get_threaded_comments(self, row, column):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| row | int | L'indice di riga.|
| column | int | L'indice di colonna.|

###  Esempio

```python

threadedComments1 = comments.get_threaded_comments(1, 1)
for i in range(len(threadedComments1)):
    tc = threadedComments1[i]
    note = tc.notes

```



###  Guarda anche
* modulo [aspose.cells](../../)
* classe [CommentCollection](/cells/python-net/it/aspose.cells/commentcollection)
