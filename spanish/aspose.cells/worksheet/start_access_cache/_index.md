---
title: start_access_cache método
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 280
url: /es/aspose.cells/worksheet/start_access_cache/
is_root: false
---
##  start_access_cache(opts) {#AccessCacheOptions}
Inicia la sesión que utiliza cachés para acceder a los datos de esta hoja de trabajo.



```python
def start_access_cache(self, opts):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| opts | [AccessCacheOptions](/cells/python-net/es/aspose.cells/accesscacheoptions) | opciones de acceso a datos|
###  Observaciones

Después de finalizar el acceso a los datos, [Worksheet.close_access_cache(opts)](/cells/python-net/es/aspose.cells/worksheet/close_access_cache) debería
ser invocado con las mismas opciones para borrar todos los cachés y recuperar el modo de acceso normal.


###  Ver también
* módulo [aspose.cells](../../)
* clase [Worksheet](/cells/python-net/es/aspose.cells/worksheet)
