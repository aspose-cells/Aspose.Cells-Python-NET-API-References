---
title: método get_leafs
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 160
url: /es/aspose.cells/cell/get_leafs/
is_root: false
---
##  get_leafs(self) {#}
Obtenga todas las celdas que hacen referencia a esta celda directamente y que deben actualizarse cuando se modifica esta celda.


###  Devoluciones

Enumerador para enumerar todos los dependientes (Cell)


```python

def get_leafs(self):
    ...
```


###  Observaciones

NOTA: Esta clase ya no está disponible. En su lugar,
Utilice Cell.GetDependentsInCalculation(bool) para obtener todos los dependientes en la cadena de cálculo.
Esta propiedad será eliminada 12 meses después desde mayo de 2022.
Aspose le pide disculpas por cualquier inconveniente que pueda haber experimentado.

##  get_leafs(self, recursive) {#bool}
Obtenga todas las celdas que se actualizarán cuando se modifique esta celda.


###  Devoluciones

Enumerador para enumerar todos los dependientes (Cell)


```python

def get_leafs(self, recursive):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| recursive | bool | Si devuelve aquellas hojas que no hacen referencia a esta celda directamente<br/> pero referencia a otras hojas de esta celda|
###  Observaciones

NOTA: Esta clase ya no está disponible. En su lugar,
Utilice Cell.GetDependentsInCalculation(bool) para obtener todos los dependientes en la cadena de cálculo.
Esta propiedad será eliminada 12 meses después desde mayo de 2022.
Aspose le pide disculpas por cualquier inconveniente que pueda haber experimentado.


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Cell`](/cells/python-net/es/aspose.cells/cell)
