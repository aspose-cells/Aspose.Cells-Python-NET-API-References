---
title: NaryEquationNode Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 150
url: /de/aspose.cells.drawing.equations/naryequationnode/
is_root: false
---
##  NaryEquationNode Klasse
Diese Klasse gibt eine n-äre Operatorgleichung an, die aus einem n-ären Operator, einer Basis (oder einem Operanden) und optionalen Ober- und Untergrenzen besteht.



**Nachlass:** [`NaryEquationNode`](/cells/python-net/de/aspose.cells.drawing.equations/naryequationnode)



Der Typ NaryEquationNode macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [type](/cells/python-net/de/aspose.cells.drawing.equations/naryequationnode/type) |  |
| [start_index](/cells/python-net/de/aspose.cells.drawing.equations/naryequationnode/start_index) |  |
| [length](/cells/python-net/de/aspose.cells.drawing.equations/naryequationnode/length) |  |
| [font](/cells/python-net/de/aspose.cells.drawing.equations/naryequationnode/font) |  |
| [text_options](/cells/python-net/de/aspose.cells.drawing.equations/naryequationnode/text_options) |  |
| [equation_type](/cells/python-net/de/aspose.cells.drawing.equations/naryequationnode/equation_type) |  |
| [is_hide_subscript](/cells/python-net/de/aspose.cells.drawing.equations/naryequationnode/is_hide_subscript) | Ob die Untergrenze angezeigt werden soll|
| [is_hide_superscript](/cells/python-net/de/aspose.cells.drawing.equations/naryequationnode/is_hide_superscript) | Ob die Obergrenze angezeigt werden soll|
| [limit_location](/cells/python-net/de/aspose.cells.drawing.equations/naryequationnode/limit_location) | Dieses Attribut gibt die Position von Grenzwerten in n-stelligen Operatoren an. Grenzwerte können entweder zentriert über und unter dem n-stelligen Operator oder direkt rechts neben dem Operator positioniert werden.|
| [nary_operator](/cells/python-net/de/aspose.cells.drawing.equations/naryequationnode/nary_operator) | ein n-ärer Operator, zB "∑".<br/>Es wird dringend empfohlen, das Attribut NaryOperatorType zum Festlegen des n-ären Operators zu verwenden.<br/> Verwenden Sie diese Eigenschaftseinstellung, wenn Sie das benötigte Zeichen in einem bekannten Typ nicht finden können.|
| [nary_operator_type](/cells/python-net/de/aspose.cells.drawing.equations/naryequationnode/nary_operator_type) | ein n-stelliger Operator, zB "∑"|
| [nary_grow](/cells/python-net/de/aspose.cells.drawing.equations/naryequationnode/nary_grow) | Dieses Attribut gibt die Wachstumseigenschaft von n-ären Operatoren auf Dokumentebene an. Ist diese Eigenschaft deaktiviert, wachsen n-äre Operatoren wie Integrale und Summationen nicht entsprechend der Höhe ihres Operanden. Ist sie aktiviert, wächst der n-äre Operator vertikal entsprechend seiner Operandenhöhe.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`add_child(self, equation_type)`](/cells/python-net/de/aspose.cells.drawing.equations/naryequationnode/add_child/#aspose.cells.drawing.equations.equationnodetype) |  |
| [`add_child(self, node)`](/cells/python-net/de/aspose.cells.drawing.equations/naryequationnode/add_child/#equationnode) |  |
| [`remove_child(self, node)`](/cells/python-net/de/aspose.cells.drawing.equations/naryequationnode/remove_child/#equationnode) |  |
| [`remove_child(self, index)`](/cells/python-net/de/aspose.cells.drawing.equations/naryequationnode/remove_child/#int) |  |
| [`set_word_art_style(self, style)`](/cells/python-net/de/aspose.cells.drawing.equations/naryequationnode/set_word_art_style/#aspose.cells.drawing.presetwordartstyle) |  |
| [`to_la_te_x(self)`](/cells/python-net/de/aspose.cells.drawing.equations/naryequationnode/to_la_te_x/#) |  |
| [`to_math_ml(self)`](/cells/python-net/de/aspose.cells.drawing.equations/naryequationnode/to_math_ml/#) |  |
| [`insert_child(self, index, equation_type)`](/cells/python-net/de/aspose.cells.drawing.equations/naryequationnode/insert_child/#int-aspose.cells.drawing.equations.equationnodetype) |  |
| [`insert_after(self, equation_type)`](/cells/python-net/de/aspose.cells.drawing.equations/naryequationnode/insert_after/#aspose.cells.drawing.equations.equationnodetype) |  |
| [`insert_before(self, equation_type)`](/cells/python-net/de/aspose.cells.drawing.equations/naryequationnode/insert_before/#aspose.cells.drawing.equations.equationnodetype) |  |
| [`get_child(self, index)`](/cells/python-net/de/aspose.cells.drawing.equations/naryequationnode/get_child/#int) |  |
| [`remove(self)`](/cells/python-net/de/aspose.cells.drawing.equations/naryequationnode/remove/#) |  |
| [`remove_all_children(self)`](/cells/python-net/de/aspose.cells.drawing.equations/naryequationnode/remove_all_children/#) |  |
| [`create_node(, equation_type, workbook, parent)`](/cells/python-net/de/aspose.cells.drawing.equations/naryequationnode/create_node/#aspose.cells.drawing.equations.equationnodetype-aspose.cells.workbook-equationnode) |  |



###  Siehe auch
* Modul [`aspose.cells.drawing.equations`](..)
* Klasse [`NaryEquationNode`](/cells/python-net/de/aspose.cells.drawing.equations/naryequationnode)
