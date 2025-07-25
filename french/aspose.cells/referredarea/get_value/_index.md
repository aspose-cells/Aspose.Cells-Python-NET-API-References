---
title: méthode get_value
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 20
url: /fr/aspose.cells/referredarea/get_value/
is_root: false
---
##  get_value(self, row_offset, col_offset) {#int-int}
Obtient la valeur de la cellule avec un décalage donné par rapport au coin supérieur gauche de cette zone.


###  Retour

"#REF!" si cette zone est invalide ;
« #N/A » si le décalage est donné en dehors de cette zone ;
Sinon, renvoie la valeur de la cellule à la position donnée.


```python

def get_value(self, row_offset, col_offset):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| row_offset | int | décalage de ligne par rapport à la ligne de début de cette zone|
| col_offset | int | décalage de colonne par rapport à la ligne de début de cette zone|


##  get_value(self, row_offset, col_offset, calculate_formulas) {#int-int-bool}
Obtient la valeur de la cellule avec un décalage donné par rapport au coin supérieur gauche de cette zone.


###  Retour

"#REF!" si cette zone est invalide ;
« #N/A » si le décalage est donné en dehors de cette zone ;
Sinon, renvoie la valeur de la cellule à la position donnée.


```python

def get_value(self, row_offset, col_offset, calculate_formulas):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| row_offset | int | décalage de ligne par rapport à la ligne de début de cette zone|
| col_offset | int | décalage de colonne par rapport à la ligne de début de cette zone|
| calculate_formulas | bool | Calculer récursivement si la référence spécifiée est une formule|



###  Voir également
* module [`aspose.cells`](../../)
* classe [`ReferredArea`](/cells/python-net/fr/aspose.cells/referredarea)
