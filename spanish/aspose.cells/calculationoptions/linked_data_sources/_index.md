---
title: linked_data_sources propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 80
url: /es/aspose.cells/calculationoptions/linked_data_sources/
is_root: false
---
##  linked_data_sources propiedad

Especifica las fuentes de datos para enlaces externos utilizados en fórmulas.

###  Observaciones

Como [`Workbook.update_linked_data_source`](/cells/python-net/es/aspose.cells/workbook/update_linked_data_source), aquí puedes especificar
fuentes de datos para enlaces externos utilizados en las fórmulas a calcular, especialmente aquellas
utilizado en la función INDIRECTA. Para aquellos enlaces externos utilizados en la función INDIRECTA,
no se toman como parte de los enlaces externos del libro de trabajo y no se pueden actualizar
por [`Workbook.update_linked_data_source`](/cells/python-net/es/aspose.cells/workbook/update_linked_data_source).
###  Definición:
```python
@property
def linked_data_sources(self):
    ...
@linked_data_sources.setter
def linked_data_sources(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`CalculationOptions`](/cells/python-net/es/aspose.cells/calculationoptions)
