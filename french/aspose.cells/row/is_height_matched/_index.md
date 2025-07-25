---
title: is_height_matched propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 190
url: /fr/aspose.cells/row/is_height_matched/
is_root: false
---
##  is_height_matched propriété

Indique si la hauteur de ligne correspond au paramètre de police par défaut actuel du classeur.
La valeur de cette propriété indique également que la hauteur de ligne est « automatique » sans valeur de hauteur personnalisée définie par l'utilisateur.

###  Remarques

Lorsque cette propriété est vraie, si le contenu de cette ligne change,
généralement, la hauteur de la ligne doit être recalculée (par exemple par [`Worksheet.auto_fit_rows`](/cells/python-net/fr/aspose.cells/worksheet/auto_fit_rows))
pour obtenir le même résultat avec ce qui est affiché dans MS Excel lorsque vous ouvrez le classeur.
###  Définition:
```python
@property
def is_height_matched(self):
    ...
@is_height_matched.setter
def is_height_matched(self, value):
    ...
```

###  Voir également
* module [`aspose.cells`](../../)
* classe [`Row`](/cells/python-net/fr/aspose.cells/row)
