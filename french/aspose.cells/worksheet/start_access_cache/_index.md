---
title: méthode start_access_cache
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 300
url: /fr/aspose.cells/worksheet/start_access_cache/
is_root: false
---
##  start_access_cache {#aspose.cells.AccessCacheOptions}
Démarre la session qui utilise les caches pour accéder aux données de cette feuille de calcul.



```python
def start_access_cache(self, opts):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| opts | [`AccessCacheOptions`](/cells/python-net/fr/aspose.cells/accesscacheoptions) | options d'accès aux données|
###  Remarques

Après avoir terminé l'accès aux données, [`Worksheet.close_access_cache`](/cells/python-net/fr/aspose.cells/worksheet/close_access_cache) devrait
être invoqué avec les mêmes options pour vider tous les caches et récupérer le mode d'accès normal.


###  Voir également
* module [`aspose.cells`](../../)
* classe [`Worksheet`](/cells/python-net/fr/aspose.cells/worksheet)
