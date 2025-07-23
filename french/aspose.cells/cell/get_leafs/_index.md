---
title: méthode get_leafs
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 160
url: /fr/aspose.cells/cell/get_leafs/
is_root: false
---
##  get_leafs(self) {#}
Obtenez toutes les cellules qui font directement référence à cette cellule et doivent être mises à jour lorsque cette cellule est modifiée.


###  Retour

Recenseur pour énumérer toutes les personnes à charge (Cell)


```python

def get_leafs(self):
    ...
```


###  Remarques

REMARQUE : Cette classe est désormais obsolète. À la place,
veuillez utiliser Cell.GetDependentsInCalculation(bool) pour obtenir tous les dépendants dans la chaîne de calcul.
Cette propriété sera supprimée 12 mois plus tard soit en mai 2022.
Aspose s'excuse pour tout inconvénient que vous avez pu rencontrer.

##  get_leafs(self, recursive) {#bool}
Obtenez toutes les cellules qui seront mises à jour lorsque cette cellule est modifiée.


###  Retour

Recenseur pour énumérer toutes les personnes à charge (Cell)


```python

def get_leafs(self, recursive):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| recursive | bool | Si renvoie les feuilles qui ne font pas directement référence à cette cellule<br/> mais référence à d'autres feuilles de cette cellule|
###  Remarques

REMARQUE : Cette classe est désormais obsolète. À la place,
veuillez utiliser Cell.GetDependentsInCalculation(bool) pour obtenir tous les dépendants dans la chaîne de calcul.
Cette propriété sera supprimée 12 mois plus tard soit en mai 2022.
Aspose s'excuse pour tout inconvénient que vous avez pu rencontrer.


###  Voir également
* module [`aspose.cells`](../../)
* classe [`Cell`](/cells/python-net/fr/aspose.cells/cell)
