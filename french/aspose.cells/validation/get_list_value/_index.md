---
title: méthode get_list_value
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 70
url: /fr/aspose.cells/validation/get_list_value/
is_root: false
---
##  get_list_value(self, row, column) {#int-int}
Obtenez la valeur de la liste de validation pour la cellule spécifiée.


###  Retour

La valeur pour produire la liste de cette validation pour la cellule spécifiée.
Si la liste fait référence à une plage, la valeur renvoyée sera un objet [`ReferredArea`](/cells/python-net/fr/aspose.cells/referredarea) ;
Sinon, la valeur renvoyée peut être null, object[] ou simple object.


```python

def get_list_value(self, row, column):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| row | int | L'index de ligne.|
| column | int | L'index des colonnes.|
###  Remarques

Uniquement pour la validation dont le type est Liste et a été appliquée à la cellule donnée,
sinon null sera renvoyé.


###  Voir également
* module [`aspose.cells`](../../)
* classe [`ReferredArea`](/cells/python-net/fr/aspose.cells/referredarea)
* classe [`Validation`](/cells/python-net/fr/aspose.cells/validation)
