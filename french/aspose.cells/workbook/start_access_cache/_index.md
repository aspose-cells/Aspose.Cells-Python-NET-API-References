---
title: méthode start_access_cache
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 400
url: /fr/aspose.cells/workbook/start_access_cache/
is_root: false
---
##  start_access_cache(self, opts) {#aspose.cells.AccessCacheOptions}
Démarre la session qui utilise les caches pour accéder aux données.



```python

def start_access_cache(self, opts):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| opts | [`AccessCacheOptions`](/cells/python-net/fr/aspose.cells/accesscacheoptions) | options d'accès aux données|
###  Remarques

Si le cache d'accès aux données spécifié nécessite que certains modèles de données dans la feuille de calcul soient en « lecture seule »,
alors les modèles de données correspondants dans chaque feuille de calcul de ce classeur seront considérés comme « en lecture seule »
et l'utilisateur ne doit modifier aucun d'entre eux.


Après avoir terminé l'accès aux données, [`Workbook.close_access_cache`](/cells/python-net/fr/aspose.cells/workbook/close_access_cache) devrait
être invoqué avec les mêmes options pour effacer tous les caches et récupérer le mode d'accès normal.


###  Voir également
* module [`aspose.cells`](../../)
* classe [`Workbook`](/cells/python-net/fr/aspose.cells/workbook)
