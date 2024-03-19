---
title: método group_by
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 80
url: /es/aspose.cells.pivot/pivotfield/group_by/
is_root: false
---
##  group_by {#float-bool}
Agrupa automáticamente el campo con interno.



```python
def group_by(self, interval, new_field):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| interval | float | Lo interno del grupo.<br/> Se asignará un valor automático si es cero,|
| new_field | bool | Indica si se agrega un nuevo campo a la tabla dinámica.|


##  group_by {#list-bool}
Grupo personalizado del campo.



```python
def group_by(self, custom_group_items, new_field):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| custom_group_items | list | Los elementos del grupo personalizado.|
| new_field | bool |Indica si agregar un nuevo campo a la tabla dinámica|


##  group_by {#float-float-float-bool}
Agrupe el archivo por número.



```python
def group_by(self, start, end, interval, new_field):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| start | float | El valor inicial|
| end | float | El fin del valor|
| interval | float | El intervalo|
| new_field | bool |Indica si agregar un nuevo campo a la tabla dinámica|


##  group_by {#DateTime-DateTime-list-float-bool}
Agrupe el archivo por tipos de grupos de fechas.



```python
def group_by(self, start, end, groups, interval, first_as_new_field):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| start | DateTime | La fecha de inicio|
| end | DateTime | El final de la fecha y hora|
| groups | list | Tipos de grupo|
| interval | float | El intervalo|
| first_as_new_field | bool | Indica si se agrega un nuevo campo a la tabla dinámica.<br/> Sólo para el primer elemento del grupo.|



###  Ver también
* módulo [`aspose.cells.pivot`](../../)
* clase [`PivotField`](/cells/python-net/es/aspose.cells.pivot/pivotfield)
