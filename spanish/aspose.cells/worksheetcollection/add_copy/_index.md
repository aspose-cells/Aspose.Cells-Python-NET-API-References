---
title: método add_copy
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 30
url: /es/aspose.cells/worksheetcollection/add_copy/
is_root: false
---
##  add_copy {#str}
Agrega una hoja de trabajo a la colección y copia datos de una hoja de trabajo existente.


###  Devoluciones

[`Worksheet`](/cells/python-net/es/aspose.cells/worksheet) índice de objetos.


```python
def add_copy(self, sheet_name):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| sheet_name | str | Nombre de la hoja de trabajo de origen.|
###  Excepciones
| Excepción| Descripción|
| :- | :- |
| [`CellsException`](/cells/python-net/es/aspose.cells/cellsexception) | Especifica un nombre de hoja de cálculo no válido.|




##  add_copy {#int}
Agrega una hoja de trabajo a la colección y copia datos de una hoja de trabajo existente.


###  Devoluciones

[`Worksheet`](/cells/python-net/es/aspose.cells/worksheet) índice de objetos.


```python
def add_copy(self, sheet_index):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| sheet_index | int | Índice de la hoja de trabajo fuente.|


##  add_copy {#list-list}
Copie un grupo de hojas de trabajo.



```python
def add_copy(self, source, dest_sheet_names):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| source | list | Las hojas de trabajo de origen.|
| dest_sheet_names | list | Los nombres de las hojas copiadas.|



###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`CellsException`](/cells/python-net/es/aspose.cells/cellsexception)
* clase [`Worksheet`](/cells/python-net/es/aspose.cells/worksheet)
* clase [`WorksheetCollection`](/cells/python-net/es/aspose.cells/worksheetcollection)
