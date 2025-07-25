---
title: NaryEquationNode classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 150
url: /fr/aspose.cells.drawing.equations/naryequationnode/
is_root: false
---
##  NaryEquationNode classe
Cette classe spécifie une équation d'opérateur n-aire composée d'un opérateur n-aire, d'une base (ou opérande) et de limites supérieures et inférieures facultatives.



**Héritage:** [`NaryEquationNode`](/cells/python-net/fr/aspose.cells.drawing.equations/naryequationnode)



Le type NaryEquationNode expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [type](/cells/python-net/fr/aspose.cells.drawing.equations/naryequationnode/type) |  |
| [start_index](/cells/python-net/fr/aspose.cells.drawing.equations/naryequationnode/start_index) |  |
| [length](/cells/python-net/fr/aspose.cells.drawing.equations/naryequationnode/length) |  |
| [font](/cells/python-net/fr/aspose.cells.drawing.equations/naryequationnode/font) |  |
| [text_options](/cells/python-net/fr/aspose.cells.drawing.equations/naryequationnode/text_options) |  |
| [equation_type](/cells/python-net/fr/aspose.cells.drawing.equations/naryequationnode/equation_type) |  |
| [is_hide_subscript](/cells/python-net/fr/aspose.cells.drawing.equations/naryequationnode/is_hide_subscript) | S'il faut afficher la limite inférieure|
| [is_hide_superscript](/cells/python-net/fr/aspose.cells.drawing.equations/naryequationnode/is_hide_superscript) | S'il faut afficher la limite supérieure|
| [limit_location](/cells/python-net/fr/aspose.cells.drawing.equations/naryequationnode/limit_location) | Cet attribut spécifie l'emplacement des limites dans les opérateurs n-aires. Les limites peuvent être centrées au-dessus et en dessous de l'opérateur n-aire, ou positionnées juste à droite de celui-ci.|
| [nary_operator](/cells/python-net/fr/aspose.cells.drawing.equations/naryequationnode/nary_operator) | un opérateur n-aire, par exemple « ∑ ».<br/>Il est fortement recommandé d'utiliser l'attribut NaryOperatorType pour définir l'opérateur n-aire.<br/> Utilisez ce paramètre de propriété si vous ne trouvez pas le caractère dont vous avez besoin dans un type connu.|
| [nary_operator_type](/cells/python-net/fr/aspose.cells.drawing.equations/naryequationnode/nary_operator_type) | un opérateur n-aire, par exemple « ∑ »|
| [nary_grow](/cells/python-net/fr/aspose.cells.drawing.equations/naryequationnode/nary_grow) | Cet attribut spécifie la propriété de croissance des opérateurs n-aires au niveau du document. Lorsqu'il est désactivé, les opérateurs n-aires, tels que les intégrales et les sommations, ne croissent pas à la hauteur de leur opérande. Lorsqu'il est activé, l'opérateur n-aire croît verticalement à la hauteur de son opérande.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`add_child(self, equation_type)`](/cells/python-net/fr/aspose.cells.drawing.equations/naryequationnode/add_child/#aspose.cells.drawing.equations.equationnodetype) |  |
| [`add_child(self, node)`](/cells/python-net/fr/aspose.cells.drawing.equations/naryequationnode/add_child/#equationnode) |  |
| [`remove_child(self, node)`](/cells/python-net/fr/aspose.cells.drawing.equations/naryequationnode/remove_child/#equationnode) |  |
| [`remove_child(self, index)`](/cells/python-net/fr/aspose.cells.drawing.equations/naryequationnode/remove_child/#int) |  |
| [`set_word_art_style(self, style)`](/cells/python-net/fr/aspose.cells.drawing.equations/naryequationnode/set_word_art_style/#aspose.cells.drawing.presetwordartstyle) |  |
| [`to_la_te_x(self)`](/cells/python-net/fr/aspose.cells.drawing.equations/naryequationnode/to_la_te_x/#) |  |
| [`to_math_ml(self)`](/cells/python-net/fr/aspose.cells.drawing.equations/naryequationnode/to_math_ml/#) |  |
| [`insert_child(self, index, equation_type)`](/cells/python-net/fr/aspose.cells.drawing.equations/naryequationnode/insert_child/#int-aspose.cells.drawing.equations.equationnodetype) |  |
| [`insert_after(self, equation_type)`](/cells/python-net/fr/aspose.cells.drawing.equations/naryequationnode/insert_after/#aspose.cells.drawing.equations.equationnodetype) |  |
| [`insert_before(self, equation_type)`](/cells/python-net/fr/aspose.cells.drawing.equations/naryequationnode/insert_before/#aspose.cells.drawing.equations.equationnodetype) |  |
| [`get_child(self, index)`](/cells/python-net/fr/aspose.cells.drawing.equations/naryequationnode/get_child/#int) |  |
| [`remove(self)`](/cells/python-net/fr/aspose.cells.drawing.equations/naryequationnode/remove/#) |  |
| [`remove_all_children(self)`](/cells/python-net/fr/aspose.cells.drawing.equations/naryequationnode/remove_all_children/#) |  |
| [`create_node(, equation_type, workbook, parent)`](/cells/python-net/fr/aspose.cells.drawing.equations/naryequationnode/create_node/#aspose.cells.drawing.equations.equationnodetype-aspose.cells.workbook-equationnode) |  |



###  Voir également
* module [`aspose.cells.drawing.equations`](..)
* classe [`NaryEquationNode`](/cells/python-net/fr/aspose.cells.drawing.equations/naryequationnode)
