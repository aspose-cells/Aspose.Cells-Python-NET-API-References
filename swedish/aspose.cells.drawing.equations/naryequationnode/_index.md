---
title: NaryEquationNode klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 150
url: /sv/aspose.cells.drawing.equations/naryequationnode/
is_root: false
---
##  NaryEquationNode klass
Denna klass specificerar en n-är operatorekvation som består av en n-är operator, en bas (eller operand) och valfria övre och undre gränser.



**Arv:** [`NaryEquationNode`](/cells/python-net/sv/aspose.cells.drawing.equations/naryequationnode)



Typen NaryEquationNode avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [type](/cells/python-net/sv/aspose.cells.drawing.equations/naryequationnode/type) |  |
| [start_index](/cells/python-net/sv/aspose.cells.drawing.equations/naryequationnode/start_index) |  |
| [length](/cells/python-net/sv/aspose.cells.drawing.equations/naryequationnode/length) |  |
| [font](/cells/python-net/sv/aspose.cells.drawing.equations/naryequationnode/font) |  |
| [text_options](/cells/python-net/sv/aspose.cells.drawing.equations/naryequationnode/text_options) |  |
| [equation_type](/cells/python-net/sv/aspose.cells.drawing.equations/naryequationnode/equation_type) |  |
| [is_hide_subscript](/cells/python-net/sv/aspose.cells.drawing.equations/naryequationnode/is_hide_subscript) | Om den nedre gränsen ska visas|
| [is_hide_superscript](/cells/python-net/sv/aspose.cells.drawing.equations/naryequationnode/is_hide_superscript) | Om den övre gränsen ska visas|
| [limit_location](/cells/python-net/sv/aspose.cells.drawing.equations/naryequationnode/limit_location) | Detta attribut anger placeringen av gränsvärden i n-ära operatorer. Gränser kan antingen centreras ovanför och under den n-ära operatorn, eller placeras precis till höger om operatorn.|
| [nary_operator](/cells/python-net/sv/aspose.cells.drawing.equations/naryequationnode/nary_operator) | en n-är operator, t.ex. "∑".<br/>Det rekommenderas starkt att använda attributet NaryOperatorType för att ange n-ary-operatorn.<br/> Använd den här egenskapsinställningen om du inte hittar det tecken du behöver i en känd typ.|
| [nary_operator_type](/cells/python-net/sv/aspose.cells.drawing.equations/naryequationnode/nary_operator_type) | en n-är operator.t.ex. "∑"|
| [nary_grow](/cells/python-net/sv/aspose.cells.drawing.equations/naryequationnode/nary_grow) | Det här attributet anger tillväxtegenskapen för n-ära operatorer på dokumentnivå. När den är avstängd växer inte n-ära operatorer, såsom integraler och summeringar, för att matcha storleken på deras operandhöjd. När den är påslagen växer n-ära operatorn vertikalt för att matcha sin operandhöjd.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`add_child(self, equation_type)`](/cells/python-net/sv/aspose.cells.drawing.equations/naryequationnode/add_child/#aspose.cells.drawing.equations.equationnodetype) |  |
| [`add_child(self, node)`](/cells/python-net/sv/aspose.cells.drawing.equations/naryequationnode/add_child/#equationnode) |  |
| [`remove_child(self, node)`](/cells/python-net/sv/aspose.cells.drawing.equations/naryequationnode/remove_child/#equationnode) |  |
| [`remove_child(self, index)`](/cells/python-net/sv/aspose.cells.drawing.equations/naryequationnode/remove_child/#int) |  |
| [`set_word_art_style(self, style)`](/cells/python-net/sv/aspose.cells.drawing.equations/naryequationnode/set_word_art_style/#aspose.cells.drawing.presetwordartstyle) |  |
| [`to_la_te_x(self)`](/cells/python-net/sv/aspose.cells.drawing.equations/naryequationnode/to_la_te_x/#) |  |
| [`to_math_ml(self)`](/cells/python-net/sv/aspose.cells.drawing.equations/naryequationnode/to_math_ml/#) |  |
| [`insert_child(self, index, equation_type)`](/cells/python-net/sv/aspose.cells.drawing.equations/naryequationnode/insert_child/#int-aspose.cells.drawing.equations.equationnodetype) |  |
| [`insert_after(self, equation_type)`](/cells/python-net/sv/aspose.cells.drawing.equations/naryequationnode/insert_after/#aspose.cells.drawing.equations.equationnodetype) |  |
| [`insert_before(self, equation_type)`](/cells/python-net/sv/aspose.cells.drawing.equations/naryequationnode/insert_before/#aspose.cells.drawing.equations.equationnodetype) |  |
| [`get_child(self, index)`](/cells/python-net/sv/aspose.cells.drawing.equations/naryequationnode/get_child/#int) |  |
| [`remove(self)`](/cells/python-net/sv/aspose.cells.drawing.equations/naryequationnode/remove/#) |  |
| [`remove_all_children(self)`](/cells/python-net/sv/aspose.cells.drawing.equations/naryequationnode/remove_all_children/#) |  |
| [`create_node(, equation_type, workbook, parent)`](/cells/python-net/sv/aspose.cells.drawing.equations/naryequationnode/create_node/#aspose.cells.drawing.equations.equationnodetype-aspose.cells.workbook-equationnode) |  |



###  Se även
* modul [`aspose.cells.drawing.equations`](..)
* klass [`NaryEquationNode`](/cells/python-net/sv/aspose.cells.drawing.equations/naryequationnode)
