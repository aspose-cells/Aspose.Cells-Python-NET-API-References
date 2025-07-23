---
title: méthode add_area
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 20
url: /fr/aspose.cells/validation/add_area/
is_root: false
---
##  add_area(self, cell_area) {#aspose.cells.CellArea}
Applique la validation à la zone.



```python

def add_area(self, cell_area):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| cell_area | [`CellArea`](/cells/python-net/fr/aspose.cells/cellarea) | La zone.|
###  Remarques

Cela équivaut à utiliser [`Validation.add_area`](/cells/python-net/fr/aspose.cells/validation/add_area)
avec vérification de l'intersection et du bord.

##  add_area(self, cell_area, check_intersection, check_edge) {#aspose.cells.CellArea-bool-bool}
Applique la validation à la zone.



```python

def add_area(self, cell_area, check_intersection, check_edge):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| cell_area | [`CellArea`](/cells/python-net/fr/aspose.cells/cellarea) | La zone.|
| check_intersection | bool | Vérifiez si l'intersection de la zone donnée avec les zones de validation existantes.<br/>Si une validation a été appliquée dans une zone donnée (ou une partie de celle-ci),<br/>alors la validation existante doit d'abord être supprimée de la zone donnée.<br/>Dans le cas contraire, une corruption peut être provoquée pour les validations générées.<br/>Si l'utilisateur est sûr que la zone ajoutée n'intersecte aucune zone existante,<br/> ce paramètre peut être défini sur faux pour des raisons de performances.|
| check_edge | bool | Vérifiez si le bord des zones appliquées de cette validation.<br/>Les paramètres internes de la validation dépendent de la plage supérieure gauche de ses plages appliquées,<br/>donc si la zone donnée devient la nouvelle zone supérieure gauche des plages appliquées,<br/>les paramètres internes doivent être modifiés et reconstruits, sinon un résultat inattendu peut être provoqué.<br/>Si l'utilisateur est sûr que la zone ajoutée n'est pas celle en haut à gauche,<br/> ce paramètre peut être défini sur faux pour des raisons de performances.|
###  Remarques

Dans cette méthode, nous supprimerons toutes les anciennes validations dans la zone donnée.
Pour la plage appliquée en haut à gauche de la validation, tout d'abord, sa ligne de départ est la plus petite,
deuxièmement, sa StartColumn est la plus petite de ces zones qui ont la même plus petite StartRow.


###  Voir également
* module [`aspose.cells`](../../)
* classe [`Validation`](/cells/python-net/fr/aspose.cells/validation)
