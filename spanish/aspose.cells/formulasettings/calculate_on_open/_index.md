---
title: calculate_on_open propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 30
url: /es/aspose.cells/formulasettings/calculate_on_open/
is_root: false
---
##  calculate_on_open propiedad

Indica si es necesario que la aplicación realice un cálculo completo cuando se abre el libro de trabajo.

###  Observaciones

Esta propiedad solo sirve para guardar la configuración en el archivo de hoja de cálculo resultante.
para que otras aplicaciones (como MS Excel) puedan actuar en consecuencia al cargar el archivo resultante.
Para tener en cuenta el rendimiento de las aplicaciones de la mayoría de los usuarios, no calculamos ninguna fórmula en el libro de trabajo automáticamente,
No importa qué valor se haya establecido para esta propiedad.
###  Definición:
```python
@property
def calculate_on_open(self):
    ...
@calculate_on_open.setter
def calculate_on_open(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`FormulaSettings`](/cells/python-net/es/aspose.cells/formulasettings)
