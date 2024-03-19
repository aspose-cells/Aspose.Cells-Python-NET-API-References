---
title: método start_access_cache
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 300
url: /es/aspose.cells/worksheet/start_access_cache/
is_root: false
---
##  start_access_cache {#aspose.cells.AccessCacheOptions}
Inicia la sesión que utiliza cachés para acceder a los datos de esta hoja de trabajo.



```python
def start_access_cache(self, opts):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| opts | [`AccessCacheOptions`](/cells/python-net/es/aspose.cells/accesscacheoptions) | opciones de acceso a datos|
###  Observaciones

Después de finalizar el acceso a los datos, [`Worksheet.close_access_cache`](/cells/python-net/es/aspose.cells/worksheet/close_access_cache) debería
se invocará con las mismas opciones para borrar todos los cachés y recuperar el modo de acceso normal.


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Worksheet`](/cells/python-net/es/aspose.cells/worksheet)
