---
title: PivotItem classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 180
url: /fr/aspose.cells.pivot/pivotitem/
is_root: false
---
##  PivotItem classe
Représente un élément dans un rapport PivotField.



Le type PivotItem expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [is_hidden](/cells/python-net/fr/aspose.cells.pivot/pivotitem/is_hidden) | Obtient et définit si l'élément pivot est masqué.|
| [position](/cells/python-net/fr/aspose.cells.pivot/pivotitem/position) | Spécification de l'index de position dans tous les éléments de tableau croisé dynamique, et non dans les éléments de tableau croisé dynamique sous le même nœud parent.|
| [position_in_same_parent_node](/cells/python-net/fr/aspose.cells.pivot/pivotitem/position_in_same_parent_node) | Spécification de l'index de position dans les PivotItems sous le même nœud parent.|
| [is_hide_detail](/cells/python-net/fr/aspose.cells.pivot/pivotitem/is_hide_detail) | Obtient et définit si l'élément pivot masque les détails.|
| [is_detail_hidden](/cells/python-net/fr/aspose.cells.pivot/pivotitem/is_detail_hidden) |Obtient et définit si les détails de cet élément pivot sont masqués.|
| [is_calculated_item](/cells/python-net/fr/aspose.cells.pivot/pivotitem/is_calculated_item) | Indique si cet élément pivot est un élément de formule calculé.|
| [is_formula](/cells/python-net/fr/aspose.cells.pivot/pivotitem/is_formula) | Indique si cet élément pivot est un élément de formule calculé.|
| [is_missing](/cells/python-net/fr/aspose.cells.pivot/pivotitem/is_missing) | Indique si l'élément est supprimé de la source de données.|
| [value](/cells/python-net/fr/aspose.cells.pivot/pivotitem/value) | Obtient la valeur de l'élément pivot|
| [name](/cells/python-net/fr/aspose.cells.pivot/pivotitem/name) | Obtient le nom de l'élément pivot.|
| [index](/cells/python-net/fr/aspose.cells.pivot/pivotitem/index) | Obtient l'index de l'élément pivot dans le champ de cache.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`move(self, count, is_same_parent)`](/cells/python-net/fr/aspose.cells.pivot/pivotitem/move/#int-bool) | Déplace l'élément vers le haut ou vers le bas|
| [`get_formula(self)`](/cells/python-net/fr/aspose.cells.pivot/pivotitem/get_formula/#) | Obtient la formule de cet élément calculé.<br/> Fonctionne uniquement lorsque cet élément est un élément calculé.|
| [`get_string_value(self)`](/cells/python-net/fr/aspose.cells.pivot/pivotitem/get_string_value/#) | Obtient la valeur de chaîne de l'élément pivot<br/> Si la valeur est nulle, elle renverra ""|
| [`get_double_value(self)`](/cells/python-net/fr/aspose.cells.pivot/pivotitem/get_double_value/#) | Obtient la valeur double de l'élément pivot<br/> Si la valeur est nulle ou n'est pas un nombre, elle renverra 0|
| [`get_date_time_value(self)`](/cells/python-net/fr/aspose.cells.pivot/pivotitem/get_date_time_value/#) | Obtient la valeur date/heure de l'élément pivot<br/> Si la valeur est nulle, elle renverra DateTime.MinValue|



###  Voir également
* module [`aspose.cells.pivot`](..)
