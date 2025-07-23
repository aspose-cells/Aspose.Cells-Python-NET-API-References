---
title: cell propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 70
url: /es/aspose.cells/calculationdata/cell/
is_root: false
---
##  cell propiedad

Obtiene el objeto Cell donde se encuentra la función.

###  Observaciones

Al calcular una fórmula sin configurarla en cell,
como por ejemplo [`Worksheet.calculate_formula`](/cells/python-net/es/aspose.cells/worksheet/calculate_formula),
La fórmula se calculará tal como se configuró en cell A1.
Entonces, tanto [`CalculationData.cell_row`](/cells/python-net/es/aspose.cells/calculationdata#cell_row) como [`CalculationData.cell_column`](/cells/python-net/es/aspose.cells/calculationdata#cell_column) son 0.
Sin embargo, es posible que no se haya creado una instancia de cell A1 en la hoja de cálculo.
Entonces, para este tipo de situación, esta propiedad será nula.
###  Definición:
```python
@property
def cell(self):
    ...
```

###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`CalculationData`](/cells/python-net/es/aspose.cells/calculationdata)
* clase [`Cell`](/cells/python-net/es/aspose.cells/cell)
