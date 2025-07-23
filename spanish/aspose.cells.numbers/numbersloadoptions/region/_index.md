---
title: region propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 220
url: /es/aspose.cells.numbers/numbersloadoptions/region/
is_root: false
---
##  region propiedad

Obtiene o establece la configuración regional utilizada para el libro de trabajo que se cargará.

###  Observaciones

La configuración regional se puede utilizar para inicializar algunas funciones del libro de trabajo.
como fuentes, temas, etc.
Para formatos de archivo basados en texto, como CSV, HTML, ..., la configuración regional
También se utilizará para detectar formatos de números y analizar valores de texto en valores numéricos.
o valores de fecha y hora para las celdas.
Esta configuración se mantendrá para el libro instanciado más adelante, es decir,
[`WorkbookSettings.region`](/cells/python-net/es/aspose.cells/workbooksettings#region) del libro de trabajo utilizará el mismo region
con esta propiedad.
###  Definición:
```python
@property
def region(self):
    ...
@region.setter
def region(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells.numbers`](../../)
* clase [`CountryCode`](/cells/python-net/es/aspose.cells/countrycode)
* clase [`NumbersLoadOptions`](/cells/python-net/es/aspose.cells.numbers/numbersloadoptions)
