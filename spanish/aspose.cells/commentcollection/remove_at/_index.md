---
title: remove_at método
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 90
url: /es/aspose.cells/commentcollection/remove_at/
is_root: false
---
##  remove_at(cell_name) {#str}
Elimina el comentario de la celda específica.



```python
def remove_at(self, cell_name):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| cell_name | str | El nombre de la celda que contiene un comentario.|

###  Ejemplo

```python

comments.remove_at("B2")

```


##  remove_at(row, column) {#int-int}
Elimina el comentario de la celda específica.



```python
def remove_at(self, row, column):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| row | int | El índice de fila.|
| column | int | el índice de la columna.|

###  Ejemplo

```python

comments.remove_at(1, 1)

```



###  Ver también
* módulo [aspose.cells](../../)
* clase [CommentCollection](/cells/python-net/es/aspose.cells/commentcollection)
