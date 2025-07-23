---
title: método add
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 20
url: /es/aspose.cells/commentcollection/add/
is_root: false
---
##  add(self, cell_name) {#str}
Agrega un comentario a la colección.


###  Devoluciones

Índice de objeto [`Comment`](/cells/python-net/es/aspose.cells/comment).


```python

def add(self, cell_name):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| cell_name | str | Cell nombre.|

###  Ejemplo

```python

commentIndex2 = comments.add("B2")
comment2 = comments[commentIndex2]
comment2.note = "Second note."
comment2.font.name = "Times New Roman"

```


##  add(self, row, column) {#int-int}
Agrega un comentario a la colección.


###  Devoluciones

Índice de objeto [`Comment`](/cells/python-net/es/aspose.cells/comment).


```python

def add(self, row, column):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| row | int | Índice de fila Cell.|
| column | int | Índice de columna Cell.|

###  Ejemplo

```python

commentIndex1 = comments.add(0, 0)
comment1 = comments[commentIndex1]
comment1.note = "First note."
comment1.font.name = "Times New Roman"

```



###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Comment`](/cells/python-net/es/aspose.cells/comment)
* clase [`CommentCollection`](/cells/python-net/es/aspose.cells/commentcollection)
