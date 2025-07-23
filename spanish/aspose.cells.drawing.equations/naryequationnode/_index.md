---
title: NaryEquationNode clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 150
url: /es/aspose.cells.drawing.equations/naryequationnode/
is_root: false
---
##  NaryEquationNode clase
Esta clase especifica una ecuación de operador n-ario que consta de un operador n-ario, una base (u operando) y límites superior e inferior opcionales.



**Herencia:** [`NaryEquationNode`](/cells/python-net/es/aspose.cells.drawing.equations/naryequationnode)



El tipo NaryEquationNode expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [type](/cells/python-net/es/aspose.cells.drawing.equations/naryequationnode/type) |  |
| [start_index](/cells/python-net/es/aspose.cells.drawing.equations/naryequationnode/start_index) |  |
| [length](/cells/python-net/es/aspose.cells.drawing.equations/naryequationnode/length) |  |
| [font](/cells/python-net/es/aspose.cells.drawing.equations/naryequationnode/font) |  |
| [text_options](/cells/python-net/es/aspose.cells.drawing.equations/naryequationnode/text_options) |  |
| [equation_type](/cells/python-net/es/aspose.cells.drawing.equations/naryequationnode/equation_type) |  |
| [is_hide_subscript](/cells/python-net/es/aspose.cells.drawing.equations/naryequationnode/is_hide_subscript) | Si se debe mostrar el límite inferior|
| [is_hide_superscript](/cells/python-net/es/aspose.cells.drawing.equations/naryequationnode/is_hide_superscript) | Si se debe mostrar el límite superior|
| [limit_location](/cells/python-net/es/aspose.cells.drawing.equations/naryequationnode/limit_location) | Este atributo especifica la ubicación de los límites en los operadores n-arios. Los límites pueden estar centrados por encima y por debajo del operador n-ario, o posicionados justo a la derecha del operador.|
| [nary_operator](/cells/python-net/es/aspose.cells.drawing.equations/naryequationnode/nary_operator) | un operador n-ario, por ejemplo "∑".<br/>Se recomienda encarecidamente utilizar el atributo NaryOperatorType para establecer el operador n-ario.<br/> Utilice esta configuración de propiedad si no puede encontrar el carácter que necesita en un tipo conocido.|
| [nary_operator_type](/cells/python-net/es/aspose.cells.drawing.equations/naryequationnode/nary_operator_type) | un operador n-ario, por ejemplo "∑"|
| [nary_grow](/cells/python-net/es/aspose.cells.drawing.equations/naryequationnode/nary_grow) | Este atributo especifica la propiedad de crecimiento de los operadores n-arios a nivel de documento. Cuando está desactivado, los operadores n-arios, como las integrales y las sumatorias, no crecen para igualar la altura de su operando. Cuando está activado, el operador n-ario crece verticalmente para igualar la altura de su operando.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`add_child(self, equation_type)`](/cells/python-net/es/aspose.cells.drawing.equations/naryequationnode/add_child/#aspose.cells.drawing.equations.equationnodetype) |  |
| [`add_child(self, node)`](/cells/python-net/es/aspose.cells.drawing.equations/naryequationnode/add_child/#equationnode) |  |
| [`remove_child(self, node)`](/cells/python-net/es/aspose.cells.drawing.equations/naryequationnode/remove_child/#equationnode) |  |
| [`remove_child(self, index)`](/cells/python-net/es/aspose.cells.drawing.equations/naryequationnode/remove_child/#int) |  |
| [`set_word_art_style(self, style)`](/cells/python-net/es/aspose.cells.drawing.equations/naryequationnode/set_word_art_style/#aspose.cells.drawing.presetwordartstyle) |  |
| [`to_la_te_x(self)`](/cells/python-net/es/aspose.cells.drawing.equations/naryequationnode/to_la_te_x/#) |  |
| [`to_math_ml(self)`](/cells/python-net/es/aspose.cells.drawing.equations/naryequationnode/to_math_ml/#) |  |
| [`insert_child(self, index, equation_type)`](/cells/python-net/es/aspose.cells.drawing.equations/naryequationnode/insert_child/#int-aspose.cells.drawing.equations.equationnodetype) |  |
| [`insert_after(self, equation_type)`](/cells/python-net/es/aspose.cells.drawing.equations/naryequationnode/insert_after/#aspose.cells.drawing.equations.equationnodetype) |  |
| [`insert_before(self, equation_type)`](/cells/python-net/es/aspose.cells.drawing.equations/naryequationnode/insert_before/#aspose.cells.drawing.equations.equationnodetype) |  |
| [`get_child(self, index)`](/cells/python-net/es/aspose.cells.drawing.equations/naryequationnode/get_child/#int) |  |
| [`remove(self)`](/cells/python-net/es/aspose.cells.drawing.equations/naryequationnode/remove/#) |  |
| [`remove_all_children(self)`](/cells/python-net/es/aspose.cells.drawing.equations/naryequationnode/remove_all_children/#) |  |
| [`create_node(, equation_type, workbook, parent)`](/cells/python-net/es/aspose.cells.drawing.equations/naryequationnode/create_node/#aspose.cells.drawing.equations.equationnodetype-aspose.cells.workbook-equationnode) |  |



###  Ver también
* módulo [`aspose.cells.drawing.equations`](..)
* clase [`NaryEquationNode`](/cells/python-net/es/aspose.cells.drawing.equations/naryequationnode)
