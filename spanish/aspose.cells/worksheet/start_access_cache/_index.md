---
title: método start_access_cache
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 320
url: /es/aspose.cells/worksheet/start_access_cache/
is_root: false
---
##  start_access_cache(self, opts) {#aspose.cells.AccessCacheOptions}
Inicia la sesión que utiliza cachés para acceder a los datos de esta hoja de trabajo.



```python

def start_access_cache(self, opts):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| opts | [`AccessCacheOptions`](/cells/python-net/es/aspose.cells/accesscacheoptions) | opciones de acceso a los datos|
###  Observaciones

Una vez finalizado el acceso a los datos, deberá ingresar [`Worksheet.close_access_cache`](/cells/python-net/es/aspose.cells/worksheet/close_access_cache)
Se puede invocar con las mismas opciones para borrar todos los cachés y recuperar el modo de acceso normal.


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Worksheet`](/cells/python-net/es/aspose.cells/worksheet)
