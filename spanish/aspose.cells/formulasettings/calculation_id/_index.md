---
title: calculation_id propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 50
url: /es/aspose.cells/formulasettings/calculation_id/
is_root: false
---
##  calculation_id propiedad

Especifica la versión del motor de cálculo utilizado para calcular valores en el libro de trabajo.

###  Observaciones

Esta propiedad solo sirve para guardar la configuración en el archivo de hoja de cálculo resultante.
para que otras aplicaciones (como MS Excel) puedan actuar en consecuencia al cargar y manipular el archivo resultante.
En el caso de MS Excel, si el valor de esta propiedad es menor que el identificador del motor de recálculo asociado
Con la aplicación que abre el archivo resultante, la aplicación recalculará los resultados de todas las fórmulas.
en este libro de trabajo inmediatamente después de cargar el archivo.
Para tener en cuenta el rendimiento de las aplicaciones de la mayoría de los usuarios, no calculamos ninguna fórmula en el libro de trabajo automáticamente.
No importa qué valor se haya establecido para esta propiedad.
###  Definición:
```python
@property
def calculation_id(self):
    ...
@calculation_id.setter
def calculation_id(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`FormulaSettings`](/cells/python-net/es/aspose.cells/formulasettings)
