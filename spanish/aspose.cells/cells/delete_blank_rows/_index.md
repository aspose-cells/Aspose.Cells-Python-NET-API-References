---
title: método delete_blank_rows
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 210
url: /es/aspose.cells/cells/delete_blank_rows/
is_root: false
---
##  delete_blank_rows(self) {#}
Elimina todas las filas en blanco que no contengan datos ni ningún otro objeto.



```python

def delete_blank_rows(self):
    ...
```




##  delete_blank_rows(self, options) {#aspose.cells.DeleteOptions}
Elimine todas las filas en blanco que no contengan datos o algunos objetos especiales, como comentarios visibles o tablas dinámicas.



```python

def delete_blank_rows(self, options):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| options | [`DeleteOptions`](/cells/python-net/es/aspose.cells/deleteoptions) | Las opciones para eliminar rango.|
###  Observaciones

Para las filas en blanco que se eliminarán, no solo se requiere que [`Row.is_blank`](/cells/python-net/es/aspose.cells/row#is_blank) sea verdadero,
pero tampoco debería haber ningún comentario visible definido para ninguna celda en esas filas,
y ninguna tabla dinámica cuyo rango se interseca con ellos.


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Cells`](/cells/python-net/es/aspose.cells/cells)
