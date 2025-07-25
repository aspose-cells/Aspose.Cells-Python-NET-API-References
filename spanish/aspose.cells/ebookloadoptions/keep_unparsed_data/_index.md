---
title: keep_unparsed_data propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 210
url: /es/aspose.cells/ebookloadoptions/keep_unparsed_data/
is_root: false
---
##  keep_unparsed_data propiedad

Si se conservan los datos no analizados en memoria para el libro de trabajo al cargarlo desde el archivo de plantilla. El valor predeterminado es "true".

###  Observaciones

Para escenarios en los que el usuario solo necesita leer algunos contenidos del archivo de plantilla y no necesita volver a guardar el libro de trabajo,
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
* clase [`EbookLoadOptions`](/cells/python-net/es/aspose.cells/ebookloadoptions)
