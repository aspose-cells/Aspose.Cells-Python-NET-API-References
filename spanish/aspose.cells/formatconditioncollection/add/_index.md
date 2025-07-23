---
title: método add
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 20
url: /es/aspose.cells/formatconditioncollection/add/
is_root: false
---
##  add(self, cell_area, type, operator_type, formula1, formula2) {#aspose.cells.CellArea-aspose.cells.FormatConditionType-aspose.cells.OperatorType-str-str}
Agrega una condición de formato y un rango de celdas afectado a FormatConditions
Las condiciones de formato pueden contener hasta tres formatos condicionales.
No se permiten referencias a otras hojas en las fórmulas de formato condicional.


###  Devoluciones

[0]: Índice de objeto de condición de formato;[1] Índice de rango de celda afectado.


```python

def add(self, cell_area, type, operator_type, formula1, formula2):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| cell_area | [`CellArea`](/cells/python-net/es/aspose.cells/cellarea) |Rango de celdas con formato condicional.|
| type | [`FormatConditionType`](/cells/python-net/es/aspose.cells/formatconditiontype) | Tipo de formato condicional. Podría ser uno de los miembros de FormatConditionType.|
| operator_type | [`OperatorType`](/cells/python-net/es/aspose.cells/operatortype) | Operador de comparación. Podría ser uno de los miembros de OperatorType.|
| formula1 | str | El valor o la expresión asociada con el formato condicional.|
| formula2 | str | El valor o expresión asociada con el formato condicional|



###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`FormatConditionCollection`](/cells/python-net/es/aspose.cells/formatconditioncollection)
