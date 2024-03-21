---
title: keep_unparsed_data propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 230
url: /fr/aspose.cells/txtloadoptions/keep_unparsed_data/
is_root: false
---
##  keep_unparsed_data propriété

Indique si les données non analysées sont conservées en mémoire pour le classeur lorsqu'il est chargé à partir du fichier modèle. La valeur par défaut est vraie.

###  Remarques

Pour les scénarios dans lesquels l'utilisateur n'a besoin que de lire certains contenus du fichier modèle et n'a pas besoin de réenregistrer le classeur,
définir cette propriété sur false peut améliorer les performances, en particulier lorsque vous l'utilisez avec une sorte de LoadFilter,
###  Définition:
```python
@property
def keep_unparsed_data(self):
    ...
@keep_unparsed_data.setter
def keep_unparsed_data(self, value):
    ...
```

###  Voir également
* module [`aspose.cells`](../../)
* classe [`TxtLoadOptions`](/cells/python-net/fr/aspose.cells/txtloadoptions)
