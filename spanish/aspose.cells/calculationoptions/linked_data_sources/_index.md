---
title: linked_data_sources propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 60
url: /es/aspose.cells/calculationoptions/linked_data_sources/
is_root: false
---
##  linked_data_sources propiedad

Especifica las fuentes de datos para los enlaces externos utilizados en las fórmulas.

###  Observaciones

Al igual que [`Workbook.update_linked_data_source`](/cells/python-net/es/aspose.cells/workbook/update_linked_data_source), aquí puede especificar
fuentes de datos para enlaces externos utilizados en fórmulas a calcular, especialmente aquellos
Se utiliza en la función INDIRECTO. Para los enlaces externos utilizados en la función INDIRECTO,
No se toman como parte de los enlaces externos del libro de trabajo y no se pueden actualizar.
por [`Workbook.update_linked_data_source`](/cells/python-net/es/aspose.cells/workbook/update_linked_data_source).
La coincidencia de aquellos libros de trabajo con enlaces externos está determinada por [`Workbook.file_name`](/cells/python-net/es/aspose.cells/workbook#file_name)
y [`ExternalLink.data_source`](/cells/python-net/es/aspose.cells/externallink#data_source). Así que asegúrese de que [`Workbook.file_name`](/cells/python-net/es/aspose.cells/workbook#file_name) tenga
se ha especificado con el valor adecuado (generalmente debería ser el mismo que el correspondiente)
[`ExternalLink.data_source`](/cells/python-net/es/aspose.cells/externallink#data_source)) para cada libro de trabajo para que puedan vincularse como se espera.
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
