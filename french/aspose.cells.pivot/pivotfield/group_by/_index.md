---
title: méthode group_by
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 80
url: /fr/aspose.cells.pivot/pivotfield/group_by/
is_root: false
---
##  group_by {#float-bool}
Regrouper automatiquement le champ avec les informations internes



```python
def group_by(self, interval, new_field):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| interval | float | L'interne du groupe.<br/> Une valeur automatique sera attribuée si elle est nulle,|
| new_field | bool | Indique si vous ajoutez un nouveau champ au tableau croisé dynamique.|


##  group_by {#list-bool}
Groupe personnalisé le champ.



```python
def group_by(self, custom_group_items, new_field):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| custom_group_items | list | Les éléments de groupe personnalisés.|
| new_field | bool |Indique si l'ajout d'un nouveau champ au tableau croisé dynamique|


##  group_by {#float-float-float-bool}
Regroupez le fichier par numéro.



```python
def group_by(self, start, end, interval, new_field):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| start | float | La valeur de départ|
| end | float | La fin de la valeur|
| interval | float | L'intervalle|
| new_field | bool |Indique si l'ajout d'un nouveau champ au tableau croisé dynamique|


##  group_by {#DateTime-DateTime-list-float-bool}
Regroupez le fichier par types de groupes de dates.



```python
def group_by(self, start, end, groups, interval, first_as_new_field):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| start | DateTime | La date/heure de début|
| end | DateTime | La fin de datetime|
| groups | list | Types de groupes|
| interval | float | L'intervalle|
| first_as_new_field | bool | Indique si vous ajoutez un nouveau champ au tableau croisé dynamique.<br/> Uniquement pour le premier élément du groupe.|



###  Voir également
* module [`aspose.cells.pivot`](../../)
* classe [`PivotField`](/cells/python-net/fr/aspose.cells.pivot/pivotfield)
