---
title: force_full_calculation propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 90
url: /es/aspose.cells/formulasettings/force_full_calculation/
is_root: false
---
##  force_full_calculation propiedad

Indica si calcula todas las fórmulas cada vez que se activa un cálculo.

###  Observaciones

Esta propiedad es solo para guardar la configuración en el archivo de hoja de cálculo resultante
para que otras aplicaciones (como MS Excel) puedan actuar en consecuencia al cargar y manipular el archivo resultante.
Para tener en cuenta el rendimiento de las aplicaciones de la mayoría de los usuarios, no calculamos ninguna fórmula en el libro de forma automática,
independientemente del valor que se haya establecido para esta propiedad.
###  Definición:
```python
@property
def force_full_calculation(self):
    ...
@force_full_calculation.setter
def force_full_calculation(self, value):
    ...
```

###  Ver también
* módulo [aspose.cells](../../)
* clase [FormulaSettings](/cells/python-net/es/aspose.cells/formulasettings)
