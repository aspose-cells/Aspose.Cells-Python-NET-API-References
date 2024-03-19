---
title: método set_manual_group_field
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 210
url: /es/aspose.cells.pivot/pivottable/set_manual_group_field/
is_root: false
---
##  set_manual_group_field {#int-float-float-list-float}
Establece el grupo de campos manual según la tabla dinámica.



```python
def set_manual_group_field(self, base_field_index, start_val, end_val, group_by_list, interval_num):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| base_field_index | int | El índice de campo de fila o columna en los campos base.|
| start_val | float | Especifica el valor inicial para la agrupación numérica.|
| end_val | float | Especifica el valor final para la agrupación numérica.|
| group_by_list | list | Especifica la lista de tipos de agrupación. Especificado por PivotTableGroupType|
| interval_num | float | Especifica el grupo de números de intervalo por agrupación numérica.|
###  Observaciones

NOTA: Este método ahora está obsoleto. En cambio,
utilice el método PivotField.GroupBy().
 Este método se eliminará 12 meses después, desde octubre de 2023.
Aspose se disculpa por cualquier inconveniente que pueda haber experimentado.

##  set_manual_group_field {#aspose.cells.pivot.PivotField-float-float-list-float}
Establece el grupo de campos manual según la tabla dinámica.



```python
def set_manual_group_field(self, pivot_field, start_val, end_val, group_by_list, interval_num):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| pivot_field | [`PivotField`](/cells/python-net/es/aspose.cells.pivot/pivotfield) | El campo de fila o columna en los campos base.|
| start_val | float | Especifica el valor inicial para la agrupación numérica.|
| end_val | float | Especifica el valor final para la agrupación numérica.|
| group_by_list | list | Especifica la lista de tipos de agrupación. Especificado por PivotTableGroupType|
| interval_num | float | Especifica el grupo de números de intervalo por agrupación numérica.|
###  Observaciones

NOTA: Este método ahora está obsoleto. En cambio,
utilice el método PivotField.GroupBy().
 Este método se eliminará 12 meses después, desde octubre de 2023.
Aspose se disculpa por cualquier inconveniente que pueda haber experimentado.

##  set_manual_group_field {#int-DateTime-DateTime-list-int}
Establece el grupo de campos manual según la tabla dinámica.



```python
def set_manual_group_field(self, base_field_index, start_val, end_val, group_by_list, interval_num):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| base_field_index | int | El índice de campo de fila o columna en los campos base.|
| start_val | DateTime | Especifica el valor inicial para la agrupación de fechas.|
| end_val | DateTime | Especifica el valor final para la agrupación de fechas.|
| group_by_list | list | Especifica la lista de tipos de agrupación. Especificado por PivotTableGroupType|
| interval_num | int | Especifica el grupo de números de intervalo en la agrupación de días. El número de días debe ser un entero positivo distinto de cero.|
###  Observaciones

NOTA: Este método ahora está obsoleto. En cambio,
utilice el método PivotField.GroupBy().
 Este método se eliminará 12 meses después, desde octubre de 2023.
Aspose se disculpa por cualquier inconveniente que pueda haber experimentado.

##  set_manual_group_field {#aspose.cells.pivot.PivotField-DateTime-DateTime-list-int}
Establece el grupo de campos manual según la tabla dinámica.



```python
def set_manual_group_field(self, pivot_field, start_val, end_val, group_by_list, interval_num):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| pivot_field | [`PivotField`](/cells/python-net/es/aspose.cells.pivot/pivotfield) | El campo de fila o columna en los campos base.|
| start_val | DateTime | Especifica el valor inicial para la agrupación de fechas.|
| end_val | DateTime | Especifica el valor final para la agrupación de fechas.|
| group_by_list | list | Especifica la lista de tipos de agrupación. Especificado por PivotTableGroupType|
| interval_num | int | Especifica el grupo de números de intervalo en la agrupación de días. El número de días debe ser un entero positivo distinto de cero.|
###  Observaciones

NOTA: Este método ahora está obsoleto. En cambio,
utilice el método PivotField.GroupBy().
 Este método se eliminará 12 meses después, desde octubre de 2023.
Aspose se disculpa por cualquier inconveniente que pueda haber experimentado.


###  Ver también
* módulo [`aspose.cells.pivot`](../../)
* clase [`PivotTable`](/cells/python-net/es/aspose.cells.pivot/pivottable)
