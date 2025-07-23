---
title: méthode get_enumerator
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 70
url: /fr/aspose.cells/row/get_enumerator/
is_root: false
---
##  get_enumerator(self, reversed, sync) {#bool-bool}
Obtient un énumérateur qui parcourt les cellules de cette ligne.


###  Retour

L'énumérateur de cellules


```python

def get_enumerator(self, reversed, sync):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| reversed | bool |si énumérer les cellules dans l'ordre inverse|
| sync | bool | si l'énumérateur renvoyé doit vérifier la modification des cellules de cette ligne<br/> et restez synchronisé avec lui.|
###  Remarques

Si la ligne doit être modifiée (par des opérations qui peuvent provoquer l'instanciation d'un nouveau Cell ou
existant Cell à supprimer) lors de la traversée avec l'énumérateur,
l'énumérateur synchronisé doit être utilisé à la place de l'énumérateur normal afin que la traversée puisse continuer
à partir de la position juste après celle qui a été parcourue par le dernier MoveNext().
Cependant, outre l'avantage qu'aucun élément ne peut être ignoré ou parcouru à plusieurs reprises,
l'inconvénient de l'énumérateur synchronisé est que les performances seront légèrement dégradées
en comparant avec un énumérateur normal.


###  Voir également
* module [`aspose.cells`](../../)
* classe [`Row`](/cells/python-net/fr/aspose.cells/row)
