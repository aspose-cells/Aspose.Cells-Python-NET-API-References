---
title: método delete_rows
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 260
url: /es/aspose.cells/cells/delete_rows/
is_root: false
---
##  delete_rows {#int-int}
Elimina varias filas.



```python
def delete_rows(self, row_index, total_rows):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| row_index | int | El índice de la primera fila que se eliminará.|
| total_rows | int | Recuento de filas que se eliminarán.|
###  Observaciones

Si el rango eliminado contiene la parte superior (no completa) de la tabla (ListObject),
el rango no se pudo eliminar y no se hará nada.
Funciona de la misma manera con MS Excel.

##  delete_rows {#int-int-bool}
Elimina varias filas en la hoja de trabajo.


###  Devoluciones




```python
def delete_rows(self, row_index, total_rows, update_reference):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| row_index | int | Índice de la primera fila que se eliminará.|
| total_rows | int | Recuento de filas que se eliminarán.|
| update_reference | bool | Indica si se actualizan las referencias en otras hojas de trabajo.|



###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Cells`](/cells/python-net/es/aspose.cells/cells)
