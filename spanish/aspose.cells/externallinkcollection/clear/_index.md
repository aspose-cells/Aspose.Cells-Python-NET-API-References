---
title: método clear
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 30
url: /es/aspose.cells/externallinkcollection/clear/
is_root: false
---
##  clear(self) {#}
Elimina todos los enlaces externos.



```python

def clear(self):
    ...
```


###  Observaciones

Al eliminar enlaces externos, también se eliminarán todas las fórmulas que hagan referencia a ellos porque
Las referencias dejan de ser válidas.

##  clear(self, update_references_as_local) {#bool}
Elimina todos los enlaces externos.



```python

def clear(self, update_references_as_local):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| update_references_as_local | bool |Si desea actualizar todas las referencias de enlaces externos en las fórmulas a referencias del libro de trabajo actual.|
###  Observaciones

Si se requiere actualizar las referencias, se deben incluir aquellas referencias de enlaces externos en las fórmulas.
Se cambiará al libro de trabajo actual cuando sea posible.
Por ejemplo, la fórmula original de una celda es "='externalsource.xlam'!customfunction()",
después de eliminar los enlaces externos, la fórmula se convertirá en "=customfunction()";
Cuando la fórmula original es "='[externalsource.xlam]Sheet1'!$A$1",
según si hay una hoja con el nombre "Hoja1" en el libro de trabajo actual:
si es verdadero, la fórmula se convertirá en "=Hoja1!$A$1";
si es falso, la fórmula se convertirá en "=#REF!$A$1".

Si no es necesario actualizar las referencias, se deben usar todas las fórmulas con referencias a enlaces externos.
También se eliminarán porque esas referencias dejarán de ser válidas.


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`ExternalLinkCollection`](/cells/python-net/es/aspose.cells/externallinkcollection)
