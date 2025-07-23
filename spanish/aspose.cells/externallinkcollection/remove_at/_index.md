---
title: método remove_at
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 40
url: /es/aspose.cells/externallinkcollection/remove_at/
is_root: false
---
##  remove_at(self, index) {#int}
Elimina el enlace externo especificado del libro de trabajo.



```python

def remove_at(self, index):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| index | int | el índice del enlace externo que se eliminará.|
###  Observaciones

Al eliminar el enlace externo, también se eliminarán todas las fórmulas que hagan referencia a él porque
Las referencias dejan de ser válidas.

##  remove_at(self, index, update_references_as_local) {#int-bool}
Elimina el enlace externo especificado del libro de trabajo.



```python

def remove_at(self, index, update_references_as_local):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| index | int | el índice del enlace externo que se eliminará.|
| update_references_as_local | bool | Si desea actualizar todas las referencias del enlace externo dado a la referencia del libro de trabajo actual.<br/> Consulte [`ExternalLinkCollection.clear`](/cells/python-net/es/aspose.cells/externallinkcollection/clear) para obtener más detalles sobre este parámetro.|



###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`ExternalLinkCollection`](/cells/python-net/es/aspose.cells/externallinkcollection)
