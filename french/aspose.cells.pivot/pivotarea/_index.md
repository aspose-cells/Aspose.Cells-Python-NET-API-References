---
title: PivotArea classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 20
url: /fr/aspose.cells.pivot/pivotarea/
is_root: false
---
##  PivotArea classe
Présente la zone sélectionnée du tableau croisé dynamique.



Le type PivotArea expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [`__init__(self, table)`](/cells/python-net/fr/aspose.cells.pivot/pivotarea/__init__/#aspose.cells.pivot.pivottable) | Présente la zone sélectionnée du tableau croisé dynamique.|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [filters](/cells/python-net/fr/aspose.cells.pivot/pivotarea/filters) | Obtient tous les filtres pour cette zone pivot.|
| [only_data](/cells/python-net/fr/aspose.cells.pivot/pivotarea/only_data) |Indique si seules les valeurs de données (dans la zone de données de la vue) pour un élément<br/> la sélection est sélectionnée et n'inclut pas les étiquettes des éléments.|
| [only_label](/cells/python-net/fr/aspose.cells.pivot/pivotarea/only_label) | Indique si seules les étiquettes de données d'une sélection d'éléments sont sélectionnées.|
| [is_row_grand_included](/cells/python-net/fr/aspose.cells.pivot/pivotarea/is_row_grand_included) | Indique si le total général de la ligne est inclus.|
| [is_column_grand_included](/cells/python-net/fr/aspose.cells.pivot/pivotarea/is_column_grand_included) | Indique si le total général de la colonne est inclus.|
| [axis_type](/cells/python-net/fr/aspose.cells.pivot/pivotarea/axis_type) | Obtient et définit la région du tableau croisé dynamique à laquelle cette règle s'applique.|
| [rule_type](/cells/python-net/fr/aspose.cells.pivot/pivotarea/rule_type) | Obtient et définit le type de règle de sélection.|
| [is_outline](/cells/python-net/fr/aspose.cells.pivot/pivotarea/is_outline) | Indique si la règle fait référence à une zone qui est en mode contour.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`select_field(self, axis_type, field_name)`](/cells/python-net/fr/aspose.cells.pivot/pivotarea/select_field/#aspose.cells.pivot.pivotfieldtype-str) | Sélectionnez un champ dans la région comme zone.|
| [`select_field(self, axis_type, field)`](/cells/python-net/fr/aspose.cells.pivot/pivotarea/select_field/#aspose.cells.pivot.pivotfieldtype-aspose.cells.pivot.pivotfield) | Sélectionnez un champ dans la région comme zone.|
| [`select(self, axis_type, field_position, selection_type)`](/cells/python-net/fr/aspose.cells.pivot/pivotarea/select/#aspose.cells.pivot.pivotfieldtype-int-aspose.cells.pivot.pivottableselectiontype) | Sélectionnez la zone avec des filtres.|
| [`get_cell_areas(self)`](/cells/python-net/fr/aspose.cells.pivot/pivotarea/get_cell_areas/#) | Obtient les zones de cellules de cette zone pivot.|



###  Voir également
* module [`aspose.cells.pivot`](..)
