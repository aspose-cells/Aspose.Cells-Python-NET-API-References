---
title: método add_icon_filter
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 60
url: /es/aspose.cells/autofilter/add_icon_filter/
is_root: false
---
##  add_icon_filter(self, field_index, icon_set_type, icon_id) {#int-aspose.cells.IconSetType-int}
Agrega un filtro de iconos.



```python

def add_icon_filter(self, field_index, icon_set_type, icon_id):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| field_index | int | El desplazamiento entero del campo en el que desea basar el filtro<br/> (desde la izquierda de la lista; el campo más a la izquierda es el campo 0).|
| icon_set_type | [`IconSetType`](/cells/python-net/es/aspose.cells/iconsettype) | El tipo de conjunto de iconos.|
| icon_id | int | El id del icono.|
###  Observaciones

Solo admite agregar el filtro de íconos.
No es posible comprobar qué fila es visible si el filtro es un filtro de íconos.


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`AutoFilter`](/cells/python-net/es/aspose.cells/autofilter)
