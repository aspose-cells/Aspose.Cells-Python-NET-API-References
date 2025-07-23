---
title: méthode get_precedents_in_calculation
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 190
url: /fr/aspose.cells/cell/get_precedents_in_calculation/
is_root: false
---
##  get_precedents_in_calculation(self) {#}
Obtient tous les précédents (référence aux cellules du classeur actuel) utilisés par la formule de cette cellule lors de son calcul.


###  Retour

Énumérateur pour énumérer toutes les références (ReferredArea)


```python

def get_precedents_in_calculation(self):
    ...
```


###  Remarques

Cette méthode ne peut fonctionner que dans la situation où [`FormulaSettings.enable_calculation_chain`](/cells/python-net/fr/aspose.cells/formulasettings#enable_calculation_chain)
est vrai pour le classeur et le classeur a été entièrement calculé.
Si cette cellule n'est pas une formule ou ne fait référence à aucune autre cellule, null sera renvoyé.
###  Exemple

```python
from aspose.cells import Workbook

workbook = Workbook()
cells = workbook.worksheets[0].cells
cells.get("A2").formula = "=IF(TRUE,B2,B1)"
workbook.settings.formula_settings.enable_calculation_chain = True
workbook.calculate_formula()
en = cells.get("A2").get_precedents_in_calculation()
print("A2's calculation precedents:")
for r in en:
    print(r)

```



###  Voir également
* module [`aspose.cells`](../../)
* classe [`Cell`](/cells/python-net/fr/aspose.cells/cell)
