---
title: método delete_rows
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 260
url: /es/aspose.cells/cells/delete_rows/
is_root: false
---
##  delete_rows(self, row_index, total_rows) {#int-int}
Elimina varias filas.



```python

def delete_rows(self, row_index, total_rows):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| row_index | int | El primer índice de fila que se eliminará.|
| total_rows | int | Recuento de filas que se eliminarán.|
###  Observaciones

Si el rango eliminado contiene la parte superior (no toda) de la tabla (ListObject),
No se pudo eliminar el rango y no se hará nada.
Funciona de la misma manera con MS Excel.

##  delete_rows(self, row_index, total_rows, update_reference) {#int-int-bool}
Elimina varias filas en la hoja de cálculo.


###  Devoluciones




```python

def delete_rows(self, row_index, total_rows, update_reference):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| row_index | int | Índice de la primera fila a eliminar.|
| total_rows | int | Recuento de filas que se eliminarán.|
| update_reference | bool | Indica si se deben actualizar referencias en otras hojas de trabajo.|


##  delete_rows(self, row_index, total_rows, options) {#int-int-aspose.cells.DeleteOptions}
Elimina varias filas en la hoja de cálculo.


###  Devoluciones




```python

def delete_rows(self, row_index, total_rows, options):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| row_index | int | Índice de la primera fila a eliminar.|
| total_rows | int | Recuento de filas que se eliminarán.|
| options | [`DeleteOptions`](/cells/python-net/es/aspose.cells/deleteoptions) | Opciones para la operación de eliminación|



###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Cells`](/cells/python-net/es/aspose.cells/cells)
