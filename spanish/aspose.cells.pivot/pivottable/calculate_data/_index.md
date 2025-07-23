---
title: método calculate_data
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 40
url: /es/aspose.cells.pivot/pivottable/calculate_data/
is_root: false
---
##  calculate_data(self) {#}
Calcula los datos de la tabla dinámica en celdas.



```python

def calculate_data(self):
    ...
```


###  Observaciones

Cell.El valor en el rango pivote no pudo devolver el resultado correcto si no se llamó al método.
Este método calcula datos con un caché pivote interno, no con una fuente de datos original.
Entonces, si se cambia la fuente de datos, llame primero al método RefreshData().

##  calculate_data(self, option) {#aspose.cells.pivot.PivotTableCalculateOption}
Cálculo de tablas dinámicas con opciones



```python

def calculate_data(self, option):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| option | [`PivotTableCalculateOption`](/cells/python-net/es/aspose.cells.pivot/pivottablecalculateoption) |  |



###  Ver también
* módulo [`aspose.cells.pivot`](../../)
* clase [`PivotTable`](/cells/python-net/es/aspose.cells.pivot/pivottable)
