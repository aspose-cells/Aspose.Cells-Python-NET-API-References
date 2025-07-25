---
title: invariant_custom propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 260
url: /es/aspose.cells/style/invariant_custom/
is_root: false
---
##  invariant_custom propiedad

Obtiene la cadena de patrón independiente de la cultura para el formato de número.
Si no se ha establecido ningún formato de número para este objeto, se devolverá nulo.
Si el formato de número está incorporado, se devolverá la cadena de patrón correspondiente al número incorporado.

###  Observaciones

Para los formatos de números incorporados, el contenido del patrón devuelto aún depende de la cultura.
por ejemplo, para algunas configuraciones regionales devuelve "m/d/y" y para otras configuraciones regionales devuelve "d/m/y".
La diferencia con [`Style.culture_custom`](/cells/python-net/es/aspose.cells/style#culture_custom) es (esto es también lo que significa independiente de la cultura):
Los especificadores de formato y separadores se mantienen como estándar, por ejemplo, '/' siempre se utilizará como separador de fecha y hora.
y "y" siempre se usará como parte del "año" sin importar qué otro carácter especial se use para la configuración regional específica.
###  Definición:
```python
@property
def invariant_custom(self):
    ...
```

###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Style`](/cells/python-net/es/aspose.cells/style)
