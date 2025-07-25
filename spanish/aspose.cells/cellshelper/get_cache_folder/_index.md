---
title: método get_cache_folder
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 100
url: /es/aspose.cells/cellshelper/get_cache_folder/
is_root: false
---
##  get_cache_folder() {#}
Obtiene la carpeta para archivos temporales que pueden usarse como caché de datos.


###  Devoluciones

Carpeta para los archivos de caché que se han especificado.
Si no se ha especificado, se devolverá null
y la ruta temporal del sistema se utilizará cuando sea necesario.


```python

@staticmethod
def get_cache_folder():
    ...
```


###  Observaciones

Los archivos de caché se utilizan generalmente para algunas funciones que tienen en cuenta el rendimiento de la memoria.
como guardar un conjunto de datos grande en un archivo xls,
o utilizando el modo de memoria con caché de archivos para el modelo de celdas.


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`CellsHelper`](/cells/python-net/es/aspose.cells/cellshelper)
