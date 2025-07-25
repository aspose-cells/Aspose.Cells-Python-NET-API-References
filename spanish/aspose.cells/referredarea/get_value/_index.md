---
title: método get_value
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 20
url: /es/aspose.cells/referredarea/get_value/
is_root: false
---
##  get_value(self, row_offset, col_offset) {#int-int}
Obtiene el valor de la celda con un desplazamiento dado desde la parte superior izquierda de esta área.


###  Devoluciones

"#¡ÁRBITRO!" si esta área no es válida;
"#N/A" si se le asigna un desplazamiento fuera de esta área;
De lo contrario, devuelve el valor de la celda en la posición dada.


```python

def get_value(self, row_offset, col_offset):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| row_offset | int | desplazamiento de fila desde la fila inicial de esta área|
| col_offset | int | desplazamiento de columna desde la fila inicial de esta área|


##  get_value(self, row_offset, col_offset, calculate_formulas) {#int-int-bool}
Obtiene el valor de la celda con un desplazamiento dado desde la parte superior izquierda de esta área.


###  Devoluciones

"#¡ÁRBITRO!" si esta área no es válida;
"#N/A" si se le asigna un desplazamiento fuera de esta área;
De lo contrario, devuelve el valor de la celda en la posición dada.


```python

def get_value(self, row_offset, col_offset, calculate_formulas):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| row_offset | int | desplazamiento de fila desde la fila inicial de esta área|
| col_offset | int | desplazamiento de columna desde la fila inicial de esta área|
| calculate_formulas | bool | Si se calcula recursivamente si la referencia especificada es una fórmula|



###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`ReferredArea`](/cells/python-net/es/aspose.cells/referredarea)
