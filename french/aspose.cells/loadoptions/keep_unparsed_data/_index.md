---
title: keep_unparsed_data propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 120
url: /fr/aspose.cells/loadoptions/keep_unparsed_data/
is_root: false
---
##  keep_unparsed_data propriété

Conserver les données non analysées en mémoire lors du chargement du classeur à partir du fichier modèle. La valeur par défaut est « true ».

###  Remarques

Pour les scénarios dans lesquels l'utilisateur a uniquement besoin de lire une partie du contenu du fichier modèle et n'a pas besoin de sauvegarder le classeur,
définir cette propriété sur false peut améliorer les performances, en particulier lors de son utilisation avec une sorte de LoadFilter,
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
* classe [`LoadOptions`](/cells/python-net/fr/aspose.cells/loadoptions)
