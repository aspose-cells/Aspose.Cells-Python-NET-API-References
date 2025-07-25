---
title: método start_access_cache
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 400
url: /es/aspose.cells/workbook/start_access_cache/
is_root: false
---
##  start_access_cache(self, opts) {#aspose.cells.AccessCacheOptions}
Inicia la sesión que utiliza cachés para acceder a los datos.



```python

def start_access_cache(self, opts):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| opts | [`AccessCacheOptions`](/cells/python-net/es/aspose.cells/accesscacheoptions) | opciones de acceso a los datos|
###  Observaciones

Si la memoria caché del acceso a datos especificado requiere que algunos modelos de datos en la hoja de cálculo sean de "solo lectura",
Entonces, los modelos de datos correspondientes en cada hoja de trabajo de este libro se tomarán como "solo lectura".
y el usuario no debe cambiar ninguno de ellos.


Una vez finalizado el acceso a los datos, deberá ingresar [`Workbook.close_access_cache`](/cells/python-net/es/aspose.cells/workbook/close_access_cache)
Se puede invocar con las mismas opciones para borrar todos los cachés y recuperar el modo de acceso normal.


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Workbook`](/cells/python-net/es/aspose.cells/workbook)
