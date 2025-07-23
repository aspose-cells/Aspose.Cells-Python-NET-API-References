---
title: memory_setting propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 1160
url: /es/aspose.cells/cells/memory_setting/
is_root: false
---
##  memory_setting propiedad

Obtiene o establece la opción de uso de memoria para estas celdas.

###  Observaciones

Límites notables y operaciones recomendadas para algunos modos:
| Modo| Observaciones| Apoyado|
| :- | :- | :- |
|
 Para reducir el costo de memoria. Por otro lado, los datos compactos también pueden
 Provoca un mayor coste de tiempo, especialmente al actualizar los datos de las celdas,
 o acceder a celdas/filas aleatoriamente| v8.0.0 |
|
 Cuando se utiliza este modo para cualquier hoja de cálculo de un libro, |
 Debe llamarse al final del trabajo para liberar todos los recursos, como los archivos temporales.
            | 
 El acceso aleatorio a las celdas dará un rendimiento deficiente porque se necesitan datos.
 para ser leído/actualizado aleatoriamente y repetidamente (por lo que el puntero en el archivo será
(se cambiará en consecuencia y se requerirán operaciones de E/S repetidamente).
 Si es posible, acceda siempre a los datos de forma secuencial (fila por fila).
            | 
 Cuando se cambian los datos de una fila/celda, se modifican los datos de otras celdas/filas.
 También puede verse influenciado (por ejemplo, si los datos se desplazan o se mueven a otros lugares).
 para asignar suficientes espacios para los datos modificados).
 Por lo tanto, cada cambio de cada dato requiere la sincronización de otros objetos existentes.
 como por ejemplo Fila o el objeto Cell).
 Por lo tanto, para obtener un mejor rendimiento, no mantenga varias filas/Cells
 Al mismo tiempo. Procesarlos uno por uno reducirá la sincronización de datos.
 para que se pueda mejorar un poco el rendimiento.
 | v25.7 |
###  Definición:
```python
@property
def memory_setting(self):
    ...
@memory_setting.setter
def memory_setting(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Cells`](/cells/python-net/es/aspose.cells/cells)
* clase [`MemorySetting`](/cells/python-net/es/aspose.cells/memorysetting)
