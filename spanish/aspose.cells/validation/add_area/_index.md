---
title: método add_area
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 20
url: /es/aspose.cells/validation/add_area/
is_root: false
---
##  add_area(self, cell_area) {#aspose.cells.CellArea}
Aplica la validación al área.



```python

def add_area(self, cell_area):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| cell_area | [`CellArea`](/cells/python-net/es/aspose.cells/cellarea) | El área.|
###  Observaciones

Es equivalente a utilizar [`Validation.add_area`](/cells/python-net/es/aspose.cells/validation/add_area)
con comprobación de intersección y arista.

##  add_area(self, cell_area, check_intersection, check_edge) {#aspose.cells.CellArea-bool-bool}
Aplica la validación al área.



```python

def add_area(self, cell_area, check_intersection, check_edge):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| cell_area | [`CellArea`](/cells/python-net/es/aspose.cells/cellarea) | El área.|
| check_intersection | bool | Si verifica la intersección del área dada con las áreas de validaciones existentes.<br/>Si se ha aplicado una validación en un área determinada (o parte de ella),<br/>Entonces, la validación existente debe eliminarse primero del área determinada.<br/>De lo contrario, se podrían producir daños en las validaciones generadas.<br/>Si el usuario está seguro de que el área agregada no se interseca con ninguna área existente,<br/> Este parámetro se puede establecer como falso por cuestiones de rendimiento.|
| check_edge | bool | Si verifica el borde de las áreas aplicadas de esta validación.<br/>La configuración interna de la validación depende del rango superior izquierdo de sus rangos aplicados.<br/>Entonces, si el área dada se convierte en el nuevo rango superior izquierdo de los rangos aplicados,<br/>La configuración interna debe cambiarse y reconstruirse, de lo contrario, podrían producirse resultados inesperados.<br/>Si el usuario está seguro de que el área agregada no es la superior izquierda,<br/> Este parámetro se puede establecer como falso por cuestiones de rendimiento.|
###  Observaciones

En este método, eliminaremos todas las validaciones antiguas en el área determinada.
Para el rango aplicado de Validación superior izquierdo, en primer lugar su StartRow es el más pequeño,
En segundo lugar, su StartColumn es la más pequeña de aquellas áreas que tienen la misma StartRow más pequeña.


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Validation`](/cells/python-net/es/aspose.cells/validation)
