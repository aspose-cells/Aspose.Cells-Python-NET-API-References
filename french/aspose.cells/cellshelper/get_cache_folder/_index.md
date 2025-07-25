---
title: méthode get_cache_folder
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 100
url: /fr/aspose.cells/cellshelper/get_cache_folder/
is_root: false
---
##  get_cache_folder() {#}
Obtient le dossier des fichiers temporaires qui peuvent être utilisés comme cache de données.


###  Retour

Dossier pour les fichiers de cache qui a été spécifié.
Si cela n'a pas été spécifié, null sera renvoyé
et le chemin temporaire du système sera utilisé en cas de besoin.


```python

@staticmethod
def get_cache_folder():
    ...
```


###  Remarques

Les fichiers cache sont généralement utilisés pour certaines fonctionnalités afin de prendre en compte les performances de la mémoire.
comme l'enregistrement d'un grand ensemble de données dans un fichier xls,
ou en utilisant le mode mémoire avec cache de fichiers pour le modèle de cellules.


###  Voir également
* module [`aspose.cells`](../../)
* classe [`CellsHelper`](/cells/python-net/fr/aspose.cells/cellshelper)
