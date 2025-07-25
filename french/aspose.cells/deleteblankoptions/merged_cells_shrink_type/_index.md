---
title: merged_cells_shrink_type propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 70
url: /fr/aspose.cells/deleteblankoptions/merged_cells_shrink_type/
is_root: false
---
##  merged_cells_shrink_type propriété

Indique comment traiter les cellules fusionnées lors de la suppression de lignes/colonnes vides.

###  Remarques

Pour [`MergedCellsShrinkType.KEEP_HEADER_ONLY`](/cells/python-net/fr/aspose.cells/mergedcellsshrinktype#KEEP_HEADER_ONLY), toutes les cellules seront considérées comme vides, à l'exception de la cellule non vide en haut à gauche. Il s'agit de la valeur par défaut de cette propriété.

Pour [`MergedCellsShrinkType.NONE`](/cells/python-net/fr/aspose.cells/mergedcellsshrinktype#NONE), toutes les cellules qu'il contient seront considérées comme non vides.

Pour [`MergedCellsShrinkType.SHRINK_TO_FIT`](/cells/python-net/fr/aspose.cells/mergedcellsshrinktype#SHRINK_TO_FIT), toutes les cellules en dehors de la zone d'affichage du contenu seront considérées comme vides.
###  Définition:
```python
@property
def merged_cells_shrink_type(self):
    ...
@merged_cells_shrink_type.setter
def merged_cells_shrink_type(self, value):
    ...
```

###  Voir également
* module [`aspose.cells`](../../)
* classe [`DeleteBlankOptions`](/cells/python-net/fr/aspose.cells/deleteblankoptions)
* classe [`MergedCellsShrinkType`](/cells/python-net/fr/aspose.cells/mergedcellsshrinktype)
