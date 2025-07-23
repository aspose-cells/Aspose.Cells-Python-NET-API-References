---
title: multi_thread_reading propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 1220
url: /es/aspose.cells/cells/multi_thread_reading/
is_root: false
---
##  multi_thread_reading propiedad

Obtiene o establece si el modelo de datos de celdas debe admitir la lectura de múltiples subprocesos.
El valor predeterminado de esta propiedad es falso.

###  Observaciones

Si hay varios subprocesos para leer objetos Row/Cell en esta colección simultáneamente,
Esta propiedad debe establecerse como verdadera, de lo contrario se podría producir un resultado inesperado.
La compatibilidad con la lectura de múltiples subprocesos puede degradar el rendimiento para acceder a los objetos Row/Cell de esta colección.
Tenga en cuenta que algunas funciones no admiten la lectura multiproceso.
como formatear valores (por [`Cell.string_value`](/cells/python-net/es/aspose.cells/cell#string_value), [`Cell.display_string_value`](/cells/python-net/es/aspose.cells/cell#display_string_value), .etc.).
Por lo tanto, incluso con esta propiedad establecida como verdadera, esas API aún pueden generar un resultado inesperado para la lectura de múltiples subprocesos.
###  Definición:
```python
@property
def multi_thread_reading(self):
    ...
@multi_thread_reading.setter
def multi_thread_reading(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Cells`](/cells/python-net/es/aspose.cells/cells)
