---
title: cached_file_folder propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 40
url: /fr/aspose.cells.saving/sqlscriptsaveoptions/cached_file_folder/
is_root: false
---
##  cached_file_folder propriété

Le dossier pour les fichiers temporaires qui peuvent être utilisés comme cache de données.

###  Remarques

Si le dossier n'a pas été spécifié,
la valeur par défaut est [`CellsHelper.get_cache_folder`](/cells/python-net/fr/aspose.cells/cellshelper/get_cache_folder).
Si sa valeur par défaut est nulle ou vide, ou a été spécifiée comme nulle ou vide,
alors aucun fichier cache ne sera utilisé lors de l'enregistrement du classeur.
###  Définition:
```python
@property
def cached_file_folder(self):
    ...
@cached_file_folder.setter
def cached_file_folder(self, value):
    ...
```

###  Voir également
* module [`aspose.cells.saving`](../../)
* classe [`SqlScriptSaveOptions`](/cells/python-net/fr/aspose.cells.saving/sqlscriptsaveoptions)
