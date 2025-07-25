---
title: trim_tailing_blank_cells propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 240
url: /es/aspose.cells/txtsaveoptions/trim_tailing_blank_cells/
is_root: false
---
##  trim_tailing_blank_cells propiedad

Indica si se deben recortar las celdas vacías de una fila. El valor predeterminado es falso.

###  Observaciones

Al guardar con el modo LightCells y no se ha especificado el [`TxtSaveOptions.export_area`](/cells/python-net/es/aspose.cells/txtsaveoptions#export_area),
Esta opción no tiene efecto y se extenderá una fila solo hasta la última celda proporcionada por
la implementación [`TxtSaveOptions.LightCellsDataProvider`](/cells/python-net/es/aspose.cells/txtsaveoptions)
###  Definición:
```python
@property
def trim_tailing_blank_cells(self):
    ...
@trim_tailing_blank_cells.setter
def trim_tailing_blank_cells(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`TxtSaveOptions`](/cells/python-net/es/aspose.cells/txtsaveoptions)
