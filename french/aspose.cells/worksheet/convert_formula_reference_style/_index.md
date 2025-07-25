---
title: méthode convert_formula_reference_style
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 120
url: /fr/aspose.cells/worksheet/convert_formula_reference_style/
is_root: false
---
##  convert_formula_reference_style(self, formula, to_r1c1, base_cell_row, base_cell_column) {#str-bool-int-int}
Convertit le style de référence de formule.


###  Retour

La formule convertie.


```python

def convert_formula_reference_style(self, formula, to_r1c1, base_cell_row, base_cell_column):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| formula | str | La formule à convertir.|
| to_r1c1 | bool | Vers quel style de référence convertir la formule.<br/>Si la formule originale est de style de référence A1,<br/>alors cette valeur doit être vraie donc la formule sera convertie du style de référence A1 au style de référence R1C1 ;<br/>Si la formule originale est de style de référence R1C1,<br/> alors cette valeur doit être fausse afin que la formule soit convertie du style de référence R1C1 au style de référence A1 ;|
| base_cell_row | int | L'index de ligne de la cellule de base.|
| base_cell_column | int | L'index de colonne de la cellule de base.|



###  Voir également
* module [`aspose.cells`](../../)
* classe [`Worksheet`](/cells/python-net/fr/aspose.cells/worksheet)
