---
title: calculate_on_save propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 40
url: /es/aspose.cells/formulasettings/calculate_on_save/
is_root: false
---
##  calculate_on_save propiedad

Indica si se vuelve a calcular el libro de trabajo antes de guardar el documento, cuando está en modo de cálculo manual.

###  Observaciones

Esta propiedad es solo para guardar la configuración en el archivo de hoja de cálculo resultante
para que otras aplicaciones (como MS Excel) puedan actuar en consecuencia al cargar y manipular el archivo resultante.
Para tener en cuenta el rendimiento de las aplicaciones de la mayoría de los usuarios, no calculamos ninguna fórmula en el libro de forma automática,
independientemente del valor que se haya establecido para esta propiedad.
###  Definición:
```python
@property
def calculate_on_save(self):
    ...
@calculate_on_save.setter
def calculate_on_save(self, value):
    ...
```

###  Ver también
* módulo [aspose.cells](../../)
* clase [FormulaSettings](/cells/python-net/es/aspose.cells/formulasettings)
