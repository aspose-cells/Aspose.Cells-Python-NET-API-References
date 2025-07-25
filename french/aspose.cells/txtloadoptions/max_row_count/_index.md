---
title: max_row_count propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 280
url: /fr/aspose.cells/txtloadoptions/max_row_count/
is_root: false
---
##  max_row_count propriété

Le nombre maximal de lignes à importer pour une feuille.

###  Remarques

Les lignes dépassant cette limite seront ignorées
ou étendu à la feuille suivante selon [`TxtLoadOptions.extend_to_next_sheet`](/cells/python-net/fr/aspose.cells/txtloadoptions#extend_to_next_sheet).
Ce nombre inclut les lignes d'en-tête ([`TxtLoadOptions.header_rows_count`](/cells/python-net/fr/aspose.cells/txtloadoptions#header_rows_count)).
La valeur maximale autorisée est la limite de ligne du format de fichier correspondant, par exemple pour le fichier xlsx, 1048576.
Si cette propriété n'a pas été spécifiée ou si la valeur spécifiée n'est pas positive, la limite maximale sera également utilisée.
###  Définition:
```python
@property
def max_row_count(self):
    ...
@max_row_count.setter
def max_row_count(self, value):
    ...
```

###  Voir également
* module [`aspose.cells`](../../)
* classe [`TxtLoadOptions`](/cells/python-net/fr/aspose.cells/txtloadoptions)
