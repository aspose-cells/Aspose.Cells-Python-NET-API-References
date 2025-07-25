---
title: cell proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 70
url: /it/aspose.cells/calculationdata/cell/
is_root: false
---
##  cell proprietà

Ottiene l'oggetto Cell in cui si trova la funzione.

###  Osservazioni

Quando si calcola una formula senza impostarla su cell,
come ad esempio [`Worksheet.calculate_formula`](/cells/python-net/it/aspose.cells/worksheet/calculate_formula),
la formula verrà calcolata esattamente come se fosse stata impostata su cell A1,
quindi sia [`CalculationData.cell_row`](/cells/python-net/it/aspose.cells/calculationdata#cell_row) che [`CalculationData.cell_column`](/cells/python-net/it/aspose.cells/calculationdata#cell_column) sono 0.
Tuttavia, cell A1 nel foglio di lavoro potrebbe non essere stato istanziato.
Quindi, per questo tipo di situazione, questa proprietà sarà nulla.
###  Definizione:
```python
@property
def cell(self):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`CalculationData`](/cells/python-net/it/aspose.cells/calculationdata)
* classe [`Cell`](/cells/python-net/it/aspose.cells/cell)
