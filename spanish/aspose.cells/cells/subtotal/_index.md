---
title: método subtotal
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 930
url: /es/aspose.cells/cells/subtotal/
is_root: false
---
##  subtotal(self, ca, group_by, function, total_list) {#aspose.cells.CellArea-int-aspose.cells.ConsolidationFunction-list}
Crea subtotales para el rango.



```python

def subtotal(self, ca, group_by, function, total_list):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| ca | [`CellArea`](/cells/python-net/es/aspose.cells/cellarea) | La gama|
| group_by | int | El campo por el que se agrupará, como un desplazamiento entero basado en cero|
| function | [`ConsolidationFunction`](/cells/python-net/es/aspose.cells/consolidationfunction) | La función subtotal.|
| total_list | list |Una matriz de compensaciones de campos basadas en cero, que indican los campos a los que se agregan los subtotales.|


##  subtotal(self, ca, group_by, function, total_list, replace, page_breaks, summary_below_data) {#aspose.cells.CellArea-int-aspose.cells.ConsolidationFunction-list-bool-bool-bool}
Crea subtotales para el rango.



```python

def subtotal(self, ca, group_by, function, total_list, replace, page_breaks, summary_below_data):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| ca | [`CellArea`](/cells/python-net/es/aspose.cells/cellarea) | La gama|
| group_by | int | El campo por el que se agrupará, como un desplazamiento entero basado en cero|
| function | [`ConsolidationFunction`](/cells/python-net/es/aspose.cells/consolidationfunction) | La función subtotal.|
| total_list | list |Una matriz de compensaciones de campos basadas en cero, que indican los campos a los que se agregan los subtotales.|
| replace | bool | Indica si se deben reemplazar los subtotales actuales|
| page_breaks | bool | Indica si se agrega un salto de página entre grupos|
| summary_below_data | bool | Indica si desea agregar un resumen debajo de los datos.|



###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Cells`](/cells/python-net/es/aspose.cells/cells)
