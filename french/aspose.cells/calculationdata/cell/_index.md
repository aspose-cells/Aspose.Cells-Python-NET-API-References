---
title: cell propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 70
url: /fr/aspose.cells/calculationdata/cell/
is_root: false
---
##  cell propriété

Obtient l'objet Cell dans lequel se trouve la fonction.

###  Remarques

Lors du calcul d'une formule sans la définir sur cell,
comme par exemple au [`Worksheet.calculate_formula`](/cells/python-net/fr/aspose.cells/worksheet/calculate_formula),
la formule sera calculée comme elle a été définie sur cell A1,
donc [`CalculationData.cell_row`](/cells/python-net/fr/aspose.cells/calculationdata#cell_row) et [`CalculationData.cell_column`](/cells/python-net/fr/aspose.cells/calculationdata#cell_column) sont tous deux 0.
Cependant, cell A1 dans la feuille de calcul n'a peut-être pas été instancié.
Donc, pour ce genre de situation, cette propriété sera nulle.
###  Définition:
```python
@property
def cell(self):
    ...
```

###  Voir également
* module [`aspose.cells`](../../)
* classe [`CalculationData`](/cells/python-net/fr/aspose.cells/calculationdata)
* classe [`Cell`](/cells/python-net/fr/aspose.cells/cell)
