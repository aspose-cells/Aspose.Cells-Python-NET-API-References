---
title: UnionRange classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1510
url: /fr/aspose.cells/unionrange/
is_root: false
---
##  UnionRange classe
Représente la plage syndicale.



Le type UnionRange expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [first_row](/cells/python-net/fr/aspose.cells/unionrange/first_row) | Obtient l'index de la première ligne de la plage.|
| [first_column](/cells/python-net/fr/aspose.cells/unionrange/first_column) | Obtient l'index de la première colonne de la plage.|
| [row_count](/cells/python-net/fr/aspose.cells/unionrange/row_count) | Obtient le nombre de lignes dans la plage.|
| [column_count](/cells/python-net/fr/aspose.cells/unionrange/column_count) | Obtient le nombre de lignes dans la plage.|
| [value](/cells/python-net/fr/aspose.cells/unionrange/value) | Obtient et définit les valeurs de la plage.|
| [name](/cells/python-net/fr/aspose.cells/unionrange/name) | Obtient ou définit le nom de la plage.|
| [refers_to](/cells/python-net/fr/aspose.cells/unionrange/refers_to) | Obtient la plage à laquelle se réfère.|
| [has_range](/cells/python-net/fr/aspose.cells/unionrange/has_range) | Indique si cela a une portée.|
| [hyperlinks](/cells/python-net/fr/aspose.cells/unionrange/hyperlinks) | Obtient tous les hyperliens de la plage.|
| [cell_count](/cells/python-net/fr/aspose.cells/unionrange/cell_count) | Obtient le nombre total de cellules dans la plage.|
| [range_count](/cells/python-net/fr/aspose.cells/unionrange/range_count) |Obtient le nombre de plages.|
| [ranges](/cells/python-net/fr/aspose.cells/unionrange/ranges) | Obtient toutes les plages d'union.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`set_outline_borders(self, border_styles, border_colors)`](/cells/python-net/fr/aspose.cells/unionrange/set_outline_borders/#list-aspose.pydrawing.color[]) | Définit les bordures de ligne autour d'une plage de cellules.|
| [`set_outline_borders(self, border_style, border_color)`](/cells/python-net/fr/aspose.cells/unionrange/set_outline_borders/#aspose.cells.cellbordertype-aspose.pydrawing.color) | Définit les bordures de contour autour d'une plage de cellules avec le même style de bordure et la même couleur.|
| [`intersect(self, range)`](/cells/python-net/fr/aspose.cells/unionrange/intersect/#str) | Intersecte une autre plage.|
| [`intersect(self, union_range)`](/cells/python-net/fr/aspose.cells/unionrange/intersect/#aspose.cells.unionrange) | Intersecte une autre plage.|
| [`intersect(self, ranges)`](/cells/python-net/fr/aspose.cells/unionrange/intersect/#list) | Intersecte une autre plage.|
| [`union(self, range)`](/cells/python-net/fr/aspose.cells/unionrange/union/#str) | Union une autre gamme.|
| [`union(self, union_range)`](/cells/python-net/fr/aspose.cells/unionrange/union/#aspose.cells.unionrange) | Union une autre gamme.|
| [`union(self, ranges)`](/cells/python-net/fr/aspose.cells/unionrange/union/#list) | Union des gammes.|
| [`merge(self)`](/cells/python-net/fr/aspose.cells/unionrange/merge/#) |Combine une plage de cellules en une seule cellule.|
| [`un_merge(self)`](/cells/python-net/fr/aspose.cells/unionrange/un_merge/#) | Annule la fusion des cellules fusionnées de cette plage.|
| [`put_value(self, string_value, is_converted, set_style)`](/cells/python-net/fr/aspose.cells/unionrange/put_value/#str-bool-bool) | Place une valeur dans la plage, si nécessaire, la valeur sera convertie en un autre type de données et le format numérique de la cellule sera réinitialisé.|
| [`set_style(self, style)`](/cells/python-net/fr/aspose.cells/unionrange/set_style/#aspose.cells.style) | Définit le style de la plage.|
| [`apply_style(self, style, flag)`](/cells/python-net/fr/aspose.cells/unionrange/apply_style/#aspose.cells.style-aspose.cells.styleflag) | Applique des formats pour toute une gamme.|
| [`copy(self, range, options)`](/cells/python-net/fr/aspose.cells/unionrange/copy/#aspose.cells.unionrange-aspose.cells.pasteoptions) | Copie de la plage avec les options de collage spécial.|



###  Voir également
* module [`aspose.cells`](..)
