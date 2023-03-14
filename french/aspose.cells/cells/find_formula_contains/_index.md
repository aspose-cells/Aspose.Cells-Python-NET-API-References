---
title: find_formula_contains méthode
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 310
url: /fr/aspose.cells/cells/find_formula_contains/
is_root: false
---
##  find_formula_contains(formula, previous_cell) {#str-Cell}
Recherche la cellule avec la formule qui contient la chaîne d'entrée.


###  Retour

Cell objet.


```python
def find_formula_contains(self, formula, previous_cell):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| formula | str | La formule à rechercher.|
| previous_cell | [Cell](/cells/python-net/fr/aspose.cells/cell) |Cellule précédente avec la même formule. Ce paramètre peut être défini sur null en cas de recherche depuis le début.|
###  Remarques

Renvoie null (Nothing) si aucune cellule n'est trouvée.
 REMARQUE : ce membre est désormais obsolète. Plutôt,
veuillez utiliser la méthode Cells.Find(object,Cell,FindOptions) avec LookInType comme LookInType.OnlyFormulas
 et LookAtType comme LookAtType.Contains.
 Ce membre sera supprimé 12 mois plus tard depuis novembre 2018.
Aspose s'excuse pour tout inconvénient que vous pourriez avoir rencontré.


###  Voir également
* module [aspose.cells](../../)
* classe [Cells](/cells/python-net/fr/aspose.cells/cells)
