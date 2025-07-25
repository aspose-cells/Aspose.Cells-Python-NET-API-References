---
title: NaryEquationNode classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 150
url: /it/aspose.cells.drawing.equations/naryequationnode/
is_root: false
---
##  NaryEquationNode classe
Questa classe specifica un'equazione di un operatore n-ario costituita da un operatore n-ario, una base (o operando) e limiti superiori e inferiori facoltativi.



**Eredità:** [`NaryEquationNode`](/cells/python-net/it/aspose.cells.drawing.equations/naryequationnode)



Il tipo NaryEquationNode espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [type](/cells/python-net/it/aspose.cells.drawing.equations/naryequationnode/type) |  |
| [start_index](/cells/python-net/it/aspose.cells.drawing.equations/naryequationnode/start_index) |  |
| [length](/cells/python-net/it/aspose.cells.drawing.equations/naryequationnode/length) |  |
| [font](/cells/python-net/it/aspose.cells.drawing.equations/naryequationnode/font) |  |
| [text_options](/cells/python-net/it/aspose.cells.drawing.equations/naryequationnode/text_options) |  |
| [equation_type](/cells/python-net/it/aspose.cells.drawing.equations/naryequationnode/equation_type) |  |
| [is_hide_subscript](/cells/python-net/it/aspose.cells.drawing.equations/naryequationnode/is_hide_subscript) | Se visualizzare il limite inferiore|
| [is_hide_superscript](/cells/python-net/it/aspose.cells.drawing.equations/naryequationnode/is_hide_superscript) | Se visualizzare il limite superiore|
| [limit_location](/cells/python-net/it/aspose.cells.drawing.equations/naryequationnode/limit_location) | Questo attributo specifica la posizione dei limiti negli operatori n-ari. I limiti possono essere centrati sopra e sotto l'operatore n-ario, oppure posizionati appena a destra dell'operatore.|
| [nary_operator](/cells/python-net/it/aspose.cells.drawing.equations/naryequationnode/nary_operator) | un operatore n-ario, ad esempio "∑".<br/>Si consiglia vivamente di utilizzare l'attributo NaryOperatorType per impostare l'operatore n-ario.<br/> Utilizzare questa impostazione di proprietà se non si riesce a trovare il carattere necessario in un tipo noto.|
| [nary_operator_type](/cells/python-net/it/aspose.cells.drawing.equations/naryequationnode/nary_operator_type) | un operatore n-ario, ad esempio "∑"|
| [nary_grow](/cells/python-net/it/aspose.cells.drawing.equations/naryequationnode/nary_grow) | Questo attributo specifica la proprietà di crescita degli operatori n-ari a livello di documento. Quando è disattivato, gli operatori n-ari come integrali e sommatorie non crescono in base all'altezza del loro operando. Quando è attivato, l'operatore n-ario cresce verticalmente in base all'altezza del suo operando.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`add_child(self, equation_type)`](/cells/python-net/it/aspose.cells.drawing.equations/naryequationnode/add_child/#aspose.cells.drawing.equations.equationnodetype) |  |
| [`add_child(self, node)`](/cells/python-net/it/aspose.cells.drawing.equations/naryequationnode/add_child/#equationnode) |  |
| [`remove_child(self, node)`](/cells/python-net/it/aspose.cells.drawing.equations/naryequationnode/remove_child/#equationnode) |  |
| [`remove_child(self, index)`](/cells/python-net/it/aspose.cells.drawing.equations/naryequationnode/remove_child/#int) |  |
| [`set_word_art_style(self, style)`](/cells/python-net/it/aspose.cells.drawing.equations/naryequationnode/set_word_art_style/#aspose.cells.drawing.presetwordartstyle) |  |
| [`to_la_te_x(self)`](/cells/python-net/it/aspose.cells.drawing.equations/naryequationnode/to_la_te_x/#) |  |
| [`to_math_ml(self)`](/cells/python-net/it/aspose.cells.drawing.equations/naryequationnode/to_math_ml/#) |  |
| [`insert_child(self, index, equation_type)`](/cells/python-net/it/aspose.cells.drawing.equations/naryequationnode/insert_child/#int-aspose.cells.drawing.equations.equationnodetype) |  |
| [`insert_after(self, equation_type)`](/cells/python-net/it/aspose.cells.drawing.equations/naryequationnode/insert_after/#aspose.cells.drawing.equations.equationnodetype) |  |
| [`insert_before(self, equation_type)`](/cells/python-net/it/aspose.cells.drawing.equations/naryequationnode/insert_before/#aspose.cells.drawing.equations.equationnodetype) |  |
| [`get_child(self, index)`](/cells/python-net/it/aspose.cells.drawing.equations/naryequationnode/get_child/#int) |  |
| [`remove(self)`](/cells/python-net/it/aspose.cells.drawing.equations/naryequationnode/remove/#) |  |
| [`remove_all_children(self)`](/cells/python-net/it/aspose.cells.drawing.equations/naryequationnode/remove_all_children/#) |  |
| [`create_node(, equation_type, workbook, parent)`](/cells/python-net/it/aspose.cells.drawing.equations/naryequationnode/create_node/#aspose.cells.drawing.equations.equationnodetype-aspose.cells.workbook-equationnode) |  |



###  Guarda anche
* modulo [`aspose.cells.drawing.equations`](..)
* classe [`NaryEquationNode`](/cells/python-net/it/aspose.cells.drawing.equations/naryequationnode)
