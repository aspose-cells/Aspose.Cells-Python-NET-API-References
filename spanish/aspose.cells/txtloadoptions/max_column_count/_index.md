---
title: max_column_count propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 290
url: /es/aspose.cells/txtloadoptions/max_column_count/
is_root: false
---
##  max_column_count propiedad

El recuento máximo de columnas que se importarán para una hoja.

###  Observaciones

Aquellas columnas que excedan este límite serán ignoradas.
o ampliado a la siguiente hoja según [`TxtLoadOptions.extend_to_next_sheet`](/cells/python-net/es/aspose.cells/txtloadoptions#extend_to_next_sheet).
Este recuento incluye las columnas de encabezado ([`TxtLoadOptions.header_columns_count`](/cells/python-net/es/aspose.cells/txtloadoptions#header_columns_count)).
Su valor máximo es el límite de columnas del formato de archivo correspondiente, como para el archivo xlsx es 16384.
Si esta propiedad no se ha especificado o el valor especificado no es positivo, también se utilizará el límite máximo.
###  Definición:
```python
@property
def max_column_count(self):
    ...
@max_column_count.setter
def max_column_count(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`TxtLoadOptions`](/cells/python-net/es/aspose.cells/txtloadoptions)
