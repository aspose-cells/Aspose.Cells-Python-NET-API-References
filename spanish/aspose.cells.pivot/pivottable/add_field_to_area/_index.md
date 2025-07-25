---
title: método add_field_to_area
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 30
url: /es/aspose.cells.pivot/pivottable/add_field_to_area/
is_root: false
---
##  add_field_to_area(self, field_type, field_name) {#aspose.cells.pivot.PivotFieldType-str}
Agrega el campo al área específica.


###  Devoluciones

La posición del campo en los campos específicos. Si no hay ningún campo nombrado como este, devuelve -1.


```python

def add_field_to_area(self, field_type, field_name):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| field_type | [`PivotFieldType`](/cells/python-net/es/aspose.cells.pivot/pivotfieldtype) | Los campos son de tipo área.|
| field_name | str |El nombre en los campos base.|


##  add_field_to_area(self, field_type, base_field_index) {#aspose.cells.pivot.PivotFieldType-int}
Agrega el campo al área específica.


###  Devoluciones

La posición del campo en los campos específicos.


```python

def add_field_to_area(self, field_type, base_field_index):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| field_type | [`PivotFieldType`](/cells/python-net/es/aspose.cells.pivot/pivotfieldtype) | Los campos son de tipo área.|
| base_field_index | int | El índice de campo en los campos base.|


##  add_field_to_area(self, field_type, pivot_field) {#aspose.cells.pivot.PivotFieldType-aspose.cells.pivot.PivotField}
Agrega el campo al área específica.


###  Devoluciones

la posición del campo en los campos específicos.


```python

def add_field_to_area(self, field_type, pivot_field):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| field_type | [`PivotFieldType`](/cells/python-net/es/aspose.cells.pivot/pivotfieldtype) | El tipo de área de campos.|
| pivot_field | [`PivotField`](/cells/python-net/es/aspose.cells.pivot/pivotfield) | el campo en los campos base.|



###  Ver también
* módulo [`aspose.cells.pivot`](../../)
* clase [`PivotTable`](/cells/python-net/es/aspose.cells.pivot/pivottable)
