---
title: méthode group_by
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 140
url: /fr/aspose.cells.pivot/pivotfield/group_by/
is_root: false
---
##  group_by(self, interval, new_field) {#float-bool}
Regrouper automatiquement le champ avec les champs internes



```python

def group_by(self, interval, new_field):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| interval | float | L'intérieur du groupe.<br/> Une valeur automatique sera attribuée si elle est égale à zéro,|
| new_field | bool | Indique si un nouveau champ doit être ajouté au tableau croisé dynamique.|


##  group_by(self, custom_group_items, new_field) {#list-bool}
Personnalisez le groupe de champs.


###  Retour

Faux signifie que ce champ n'a pas pu être regroupé par date et heure.


```python

def group_by(self, custom_group_items, new_field):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| custom_group_items | list | Les éléments du groupe personnalisé.|
| new_field | bool | Indique si l'ajout d'un nouveau champ au tableau croisé dynamique|


##  group_by(self, start, end, interval, new_field) {#float-float-float-bool}
Regroupez le fichier par numéro.


###  Retour

Faux signifie que ce champ n'a pas pu être regroupé par date et heure.


```python

def group_by(self, start, end, interval, new_field):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| start | float | La valeur de départ|
| end | float | La fin de la valeur|
| interval | float | L'intervalle|
| new_field | bool | Indique si l'ajout d'un nouveau champ au tableau croisé dynamique|


##  group_by(self, start, end, groups, interval, first_as_new_field) {#DateTime-DateTime-list-float-bool}
Regroupez le fichier par types de groupes de dates.


###  Retour

Faux signifie que ce champ n'a pas pu être regroupé par date et heure.


```python

def group_by(self, start, end, groups, interval, first_as_new_field):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| start | DateTime | La date et l'heure de début|
| end | DateTime | La fin de datetime|
| groups | list | Types de groupes|
| interval | float | L'intervalle|
| first_as_new_field | bool | Indique si un nouveau champ doit être ajouté au tableau croisé dynamique.<br/> Uniquement pour le premier élément du groupe.|



###  Voir également
* module [`aspose.cells.pivot`](../../)
* classe [`PivotField`](/cells/python-net/fr/aspose.cells.pivot/pivotfield)
