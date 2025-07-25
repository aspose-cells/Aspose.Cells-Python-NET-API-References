---
title: refer_to_sheet_with_same_name propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 90
url: /fr/aspose.cells/copyoptions/refer_to_sheet_with_same_name/
is_root: false
---
##  refer_to_sheet_with_same_name propriété

Dans MS Excel, lors de la copie de formules qui font référence à d'autres feuilles de calcul lors de la copie d'une feuille de calcul vers une autre,
les formules copiées doivent faire référence au classeur source.
Cependant, dans certaines situations, l'utilisateur peut avoir besoin que les formules copiées se réfèrent à des feuilles de calcul portant le même nom.
dans le même classeur, par exemple lorsque ces feuilles de calcul ont été copiées avant cette opération de copie,
alors cette propriété doit être conservée comme vraie.

###  Remarques

La valeur par défaut est vrai.
###  Définition:
```python
@property
def refer_to_sheet_with_same_name(self):
    ...
@refer_to_sheet_with_same_name.setter
def refer_to_sheet_with_same_name(self, value):
    ...
```

###  Voir également
* module [`aspose.cells`](../../)
* classe [`CopyOptions`](/cells/python-net/fr/aspose.cells/copyoptions)
