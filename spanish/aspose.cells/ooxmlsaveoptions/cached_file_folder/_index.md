---
title: cached_file_folder propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 30
url: /es/aspose.cells/ooxmlsaveoptions/cached_file_folder/
is_root: false
---
##  cached_file_folder propiedad

La carpeta para archivos temporales que pueden usarse como caché de datos.

###  Observaciones

Si no se ha especificado la carpeta,
El valor predeterminado es [`CellsHelper.get_cache_folder`](/cells/python-net/es/aspose.cells/cellshelper/get_cache_folder).
Si su valor predeterminado es nulo o vacío, o se ha especificado como nulo o vacío,
Entonces no se utilizará ningún archivo de caché al guardar el libro de trabajo.
###  Definición:
```python
@property
def cached_file_folder(self):
    ...
@cached_file_folder.setter
def cached_file_folder(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`OoxmlSaveOptions`](/cells/python-net/es/aspose.cells/ooxmlsaveoptions)
