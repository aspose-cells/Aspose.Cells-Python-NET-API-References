---
title: part_index propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 30
url: /fr/aspose.cells.lowcode/splitpartinfo/part_index/
is_root: false
---
##  part_index propriété

Index de la partie courante dans la séquence (basé sur 0).
-1 signifie qu'il n'y a pas de parties multiples, donc le résultat est unique.

###  Remarques

Si plusieurs feuilles doivent être traitées et que chaque feuille est traitée (divisée)
séparément, l'index de pièce commence toujours à 0 pour chaque feuille.
Par exemple, lors de la conversion d'un classeur en images,
il représente l'index de la page de sortie de la feuille actuellement traitée.
Et -1 indique qu'il n'y a qu'une seule page pour la feuille actuelle.
###  Définition:
```python
@property
def part_index(self):
    ...
```

###  Voir également
* module [`aspose.cells.lowcode`](../../)
* classe [`SplitPartInfo`](/cells/python-net/fr/aspose.cells.lowcode/splitpartinfo)
