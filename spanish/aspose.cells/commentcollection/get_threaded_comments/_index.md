---
title: método get_threaded_comments
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 70
url: /es/aspose.cells/commentcollection/get_threaded_comments/
is_root: false
---
##  get_threaded_comments(self, cell_name) {#str}
Obtiene los comentarios enhebrados por nombre de celda.


###  Devoluciones




```python

def get_threaded_comments(self, cell_name):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| cell_name | str | El nombre de la celda.|

###  Ejemplo

```python

threadedComments2 = comments.get_threaded_comments("B2")
for i in range(len(threadedComments2)):
    tc = threadedComments2[i]
    note = tc.notes

```


##  get_threaded_comments(self, row, column) {#int-int}
Obtiene los comentarios enhebrados por índice de fila y columna.


###  Devoluciones




```python

def get_threaded_comments(self, row, column):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| row | int | El índice de fila.|
| column | int | El índice de la columna.|

###  Ejemplo

```python

threadedComments1 = comments.get_threaded_comments(1, 1)
for i in range(len(threadedComments1)):
    tc = threadedComments1[i]
    note = tc.notes

```



###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`CommentCollection`](/cells/python-net/es/aspose.cells/commentcollection)
