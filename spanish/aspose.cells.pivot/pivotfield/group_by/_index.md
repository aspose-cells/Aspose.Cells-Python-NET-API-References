---
title: método group_by
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 140
url: /es/aspose.cells.pivot/pivotfield/group_by/
is_root: false
---
##  group_by(self, interval, new_field) {#float-bool}
Agrupar automáticamente el campo con interno



```python

def group_by(self, interval, new_field):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| interval | float | El interno del grupo.<br/> Se asignará un valor automático si es cero,|
| new_field | bool | Indica si se agrega un nuevo campo a la tabla dinámica.|


##  group_by(self, custom_group_items, new_field) {#list-bool}
Agrupar el campo de forma personalizada.


###  Devoluciones

Falso significa que este campo no se pudo agrupar por fecha y hora.


```python

def group_by(self, custom_group_items, new_field):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| custom_group_items | list | Los elementos del grupo personalizado.|
| new_field | bool | Indica si se debe agregar un nuevo campo a la tabla dinámica|


##  group_by(self, start, end, interval, new_field) {#float-float-float-bool}
Agrupar el archivo por número.


###  Devoluciones

Falso significa que este campo no se pudo agrupar por fecha y hora.


```python

def group_by(self, start, end, interval, new_field):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| start | float | El valor inicial|
| end | float | El fin del valor|
| interval | float | El intervalo|
| new_field | bool | Indica si se debe agregar un nuevo campo a la tabla dinámica|


##  group_by(self, start, end, groups, interval, first_as_new_field) {#DateTime-DateTime-list-float-bool}
Agrupe el archivo por los tipos de grupo de fechas.


###  Devoluciones

Falso significa que este campo no se pudo agrupar por fecha y hora.


```python

def group_by(self, start, end, groups, interval, first_as_new_field):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| start | DateTime | La fecha y hora de inicio|
| end | DateTime | El fin de la fecha y hora|
| groups | list | Tipos de grupos|
| interval | float | El intervalo|
| first_as_new_field | bool | Indica si se agrega un nuevo campo a la tabla dinámica.<br/> Sólo para el primer artículo del grupo.|



###  Ver también
* módulo [`aspose.cells.pivot`](../../)
* clase [`PivotField`](/cells/python-net/es/aspose.cells.pivot/pivotfield)
