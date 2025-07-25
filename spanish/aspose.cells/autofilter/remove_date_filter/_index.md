---
title: método remove_date_filter
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 150
url: /es/aspose.cells/autofilter/remove_date_filter/
is_root: false
---
##  remove_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second) {#int-aspose.cells.DateTimeGroupingType-int-int-int-int-int-int}
Elimina un filtro de fecha.



```python

def remove_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| field_index | int | El desplazamiento entero del campo en el que desea basar el filtro<br/> (desde la izquierda de la lista; el campo más a la izquierda es el campo 0).|
| date_time_grouping_type | [`DateTimeGroupingType`](/cells/python-net/es/aspose.cells/datetimegroupingtype) | El tipo de agrupación|
| year | int | El año.|
| month | int | El mes.|
| day | int | El día.|
| hour | int | La hora.|
| minute | int | El minuto.|
| second | int | El segundo.|
###  Observaciones

Si DateTimeGroupingType es Año, solo tiene efecto el parámetro año.
Si DateTiemGroupingType es Mes, solo tienen efecto los parámetros año y mes.


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`AutoFilter`](/cells/python-net/es/aspose.cells/autofilter)
