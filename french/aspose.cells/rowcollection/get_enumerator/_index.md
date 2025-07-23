---
title: méthode get_enumerator
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 30
url: /fr/aspose.cells/rowcollection/get_enumerator/
is_root: false
---
##  get_enumerator(self, reversed, sync) {#bool-bool}
Obtient un énumérateur qui parcourt les lignes de cette collection


###  Retour

L'énumérateur de lignes


```python

def get_enumerator(self, reversed, sync):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| reversed | bool | si énumérer les lignes dans l'ordre inverse|
| sync | bool | si l'énumérateur renvoyé doit vérifier la modification de la collection de lignes<br/> et restez synchronisé avec lui.|
###  Remarques

Si la collection de lignes doit être modifiée (par des opérations pouvant entraîner l'instanciation d'une nouvelle ligne ou
(la ligne existante doit être supprimée) pendant la traversée avec l'énumérateur,
l'énumérateur synchronisé doit être utilisé à la place de l'énumérateur normal afin que la traversée puisse continuer
à partir de la position juste après celle qui a été parcourue par le dernier MoveNext().
Cependant, outre l'avantage qu'aucun élément ne peut être ignoré ou parcouru à plusieurs reprises,
l'inconvénient de l'énumérateur synchronisé est que les performances seront légèrement dégradées
en comparant avec un énumérateur normal.


###  Voir également
* module [`aspose.cells`](../../)
* classe [`RowCollection`](/cells/python-net/fr/aspose.cells/rowcollection)
