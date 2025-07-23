---
title: max_column_count propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 270
url: /fr/aspose.cells/txtloadoptions/max_column_count/
is_root: false
---
##  max_column_count propriété

Le nombre maximal de colonnes à importer pour une feuille.

###  Remarques

Les colonnes dépassant cette limite seront ignorées
ou étendu à la feuille suivante selon [`TxtLoadOptions.extend_to_next_sheet`](/cells/python-net/fr/aspose.cells/txtloadoptions#extend_to_next_sheet).
Ce décompte inclut les colonnes d'en-tête ([`TxtLoadOptions.header_columns_count`](/cells/python-net/fr/aspose.cells/txtloadoptions#header_columns_count)).
Sa valeur maximale est la limite de colonne du format de fichier correspondant, par exemple pour le fichier xlsx, elle est de 16384.
Si cette propriété n'a pas été spécifiée ou si la valeur spécifiée n'est pas positive, la limite maximale sera également utilisée.
###  Définition:
```python
@property
def max_column_count(self):
    ...
@max_column_count.setter
def max_column_count(self, value):
    ...
```

###  Voir également
* module [`aspose.cells`](../../)
* classe [`TxtLoadOptions`](/cells/python-net/fr/aspose.cells/txtloadoptions)
