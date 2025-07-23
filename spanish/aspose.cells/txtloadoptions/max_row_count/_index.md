---
title: max_row_count propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 280
url: /es/aspose.cells/txtloadoptions/max_row_count/
is_root: false
---
##  max_row_count propiedad

El recuento máximo de filas que se importarán para una hoja.

###  Observaciones

Aquellas filas que excedan este límite serán ignoradas.
o ampliado a la siguiente hoja según [`TxtLoadOptions.extend_to_next_sheet`](/cells/python-net/es/aspose.cells/txtloadoptions#extend_to_next_sheet).
Este recuento incluye las filas de encabezado ([`TxtLoadOptions.header_rows_count`](/cells/python-net/es/aspose.cells/txtloadoptions#header_rows_count)).
El valor máximo permitido es el límite de filas del formato de archivo correspondiente, como por ejemplo para un archivo xlsx es 1048576.
Si no se ha especificado esta propiedad o el valor especificado no es positivo, también se utilizará el límite máximo.
###  Definición:
```python
@property
def max_row_count(self):
    ...
@max_row_count.setter
def max_row_count(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`TxtLoadOptions`](/cells/python-net/es/aspose.cells/txtloadoptions)
