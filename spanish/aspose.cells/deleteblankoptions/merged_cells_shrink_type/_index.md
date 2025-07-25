---
title: merged_cells_shrink_type propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 70
url: /es/aspose.cells/deleteblankoptions/merged_cells_shrink_type/
is_root: false
---
##  merged_cells_shrink_type propiedad

Indica cómo procesar celdas fusionadas al eliminar filas/columnas en blanco.

###  Observaciones

Para [`MergedCellsShrinkType.KEEP_HEADER_ONLY`](/cells/python-net/es/aspose.cells/mergedcellsshrinktype#KEEP_HEADER_ONLY), todas las celdas se considerarán en blanco, excepto la celda superior izquierda que no esté en blanco. Este es el valor predeterminado de esta propiedad.

Para [`MergedCellsShrinkType.NONE`](/cells/python-net/es/aspose.cells/mergedcellsshrinktype#NONE), todas las celdas que contiene se tomarán como no en blanco.

Para [`MergedCellsShrinkType.SHRINK_TO_FIT`](/cells/python-net/es/aspose.cells/mergedcellsshrinktype#SHRINK_TO_FIT), todas las celdas fuera del área de visualización de contenido se tomarán como en blanco.
###  Definición:
```python
@property
def merged_cells_shrink_type(self):
    ...
@merged_cells_shrink_type.setter
def merged_cells_shrink_type(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`DeleteBlankOptions`](/cells/python-net/es/aspose.cells/deleteblankoptions)
* clase [`MergedCellsShrinkType`](/cells/python-net/es/aspose.cells/mergedcellsshrinktype)
