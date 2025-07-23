---
title: preferred_parsers propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 330
url: /fr/aspose.cells/txtloadoptions/preferred_parsers/
is_root: false
---
##  preferred_parsers propriété

Obtient et définit les analyseurs de valeurs préférés pour le chargement du fichier texte.

###  Remarques

parsers[0] est l'analyseur qui sera utilisé pour la première colonne du fichier de modèle de texte,
parsers[1] est l'analyseur qui sera utilisé pour la deuxième colonne, ...etc.
Le dernier (parsers[parsers.length-1]) sera utilisé pour toutes les autres colonnes à partir de parsers.length-1.
Si un élément est nul, la colonne correspondante sera analysée par l'analyseur par défaut Aspose.Cells.
###  Définition:
```python
@property
def preferred_parsers(self):
    ...
@preferred_parsers.setter
def preferred_parsers(self, value):
    ...
```

###  Voir également
* module [`aspose.cells`](../../)
* classe [`TxtLoadOptions`](/cells/python-net/fr/aspose.cells/txtloadoptions)
