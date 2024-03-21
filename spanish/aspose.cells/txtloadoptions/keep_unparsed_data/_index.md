---
title: keep_unparsed_data propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 230
url: /es/aspose.cells/txtloadoptions/keep_unparsed_data/
is_root: false
---
##  keep_unparsed_data propiedad

Si se mantienen los datos no analizados en la memoria para el libro de trabajo cuando se carga desde un archivo de plantilla. El valor predeterminado es verdadero.

###  Observaciones

Para escenarios en los que el usuario solo necesita leer algunos contenidos del archivo de plantilla y no necesita guardar el libro nuevamente,
Establecer esta propiedad como falsa puede mejorar el rendimiento, especialmente cuando se usa junto con algún tipo de LoadFilter.
###  Definición:
```python
@property
def keep_unparsed_data(self):
    ...
@keep_unparsed_data.setter
def keep_unparsed_data(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`TxtLoadOptions`](/cells/python-net/es/aspose.cells/txtloadoptions)
