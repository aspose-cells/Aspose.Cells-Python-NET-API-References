---
title: number_category_type propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 670
url: /fr/aspose.cells/cell/number_category_type/
is_root: false
---
##  number_category_type propriété

Représente le type de catégorie du formatage numérique de cette cellule.

###  Remarques

Lorsque le modèle de formatage de la cellule est combiné avec des modèles de formatage conditionnel,
alors le type renvoyé correspond à la partie qui est utilisée pour la valeur actuelle de cette cellule.
Par exemple, si le modèle de formatage de cette cellule est "#,##0;(#,##0);"-";@",
puis lorsque la valeur de la cellule est numérique et non 0, le type renvoyé est [`NumberCategoryType.NUMBER`](/cells/python-net/fr/aspose.cells/numbercategorytype#NUMBER) ;
Lorsque la valeur de la cellule est 0 ou non numérique, le type renvoyé est [`NumberCategoryType.TEXT`](/cells/python-net/fr/aspose.cells/numbercategorytype#TEXT).
###  Définition:
```python
@property
def number_category_type(self):
    ...
```

###  Voir également
* module [`aspose.cells`](../../)
* classe [`Cell`](/cells/python-net/fr/aspose.cells/cell)
* classe [`NumberCategoryType`](/cells/python-net/fr/aspose.cells/numbercategorytype)
