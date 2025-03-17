---
title: FunctionEquationNode class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 110
url: /aspose.cells.drawing.equations/functionequationnode/
is_root: false
---

## FunctionEquationNode class

This class specifies the Function-Apply equation, which consists of a function name and an argument acted upon.
The types of the name and argument components are 'EquationNodeType.FunctionName' and 'EquationNodeType.Base' respectively.



**Inheritance:** [`FunctionEquationNode`](/cells/python-net/aspose.cells.drawing.equations/functionequationnode) → 
[`EquationNode`](/cells/python-net/aspose.cells.drawing.equations/equationnode) → 
[`FontSetting`](/cells/python-net/aspose.cells/fontsetting)



The FunctionEquationNode type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [type](/cells/python-net/aspose.cells.drawing.equations/functionequationnode/type) | Represents the type of the node. |
| [start_index](/cells/python-net/aspose.cells.drawing.equations/functionequationnode/start_index) | Gets the start index of the characters. |
| [length](/cells/python-net/aspose.cells.drawing.equations/functionequationnode/length) | Gets the length of the characters. |
| [font](/cells/python-net/aspose.cells.drawing.equations/functionequationnode/font) | Returns the font of this object. |
| [text_options](/cells/python-net/aspose.cells.drawing.equations/functionequationnode/text_options) | Returns the text options. |
| [parent_node](/cells/python-net/aspose.cells.drawing.equations/functionequationnode/parent_node) | Specifies the parent node of the current node |
| [equation_type](/cells/python-net/aspose.cells.drawing.equations/functionequationnode/equation_type) | Get the equation type of the current node |


### Methods
| Method | Description |
| :- | :- |
| [`add_child(self, equation_type)`](/cells/python-net/aspose.cells.drawing.equations/functionequationnode/add_child/#aspose.cells.drawing.equations.equationnodetype) | Insert a node of the specified type at the end of the child node list of the current node. |
| [`add_child(self, node)`](/cells/python-net/aspose.cells.drawing.equations/functionequationnode/add_child/#aspose.cells.drawing.equations.equationnode) | Inserts the specified node at the end of the current node's list of child nodes. |
| [`remove_child(self, node)`](/cells/python-net/aspose.cells.drawing.equations/functionequationnode/remove_child/#aspose.cells.drawing.equations.equationnode) | Removes the specified node from the current node's children. |
| [`remove_child(self, index)`](/cells/python-net/aspose.cells.drawing.equations/functionequationnode/remove_child/#int) | Removes the node at the specified index from the current node's children. |
| [`set_word_art_style(self, style)`](/cells/python-net/aspose.cells.drawing.equations/functionequationnode/set_word_art_style/#aspose.cells.drawing.presetwordartstyle) | Sets the preset WordArt style. |
| [`to_la_te_x(self)`](/cells/python-net/aspose.cells.drawing.equations/functionequationnode/to_la_te_x/#) | Convert this equtation to LaTeX expression. |
| [`to_math_ml(self)`](/cells/python-net/aspose.cells.drawing.equations/functionequationnode/to_math_ml/#) | Convert this equtation to MathML expression. |
| [`insert_child(self, index, equation_type)`](/cells/python-net/aspose.cells.drawing.equations/functionequationnode/insert_child/#int-aspose.cells.drawing.equations.equationnodetype) | Inserts a node of the specified type at the specified index position in the current node's child node list. |
| [`insert_after(self, equation_type)`](/cells/python-net/aspose.cells.drawing.equations/functionequationnode/insert_after/#aspose.cells.drawing.equations.equationnodetype) | Inserts the specified node after the current node. |
| [`insert_before(self, equation_type)`](/cells/python-net/aspose.cells.drawing.equations/functionequationnode/insert_before/#aspose.cells.drawing.equations.equationnodetype) | Inserts the specified node before the current node. |
| [`get_child(self, index)`](/cells/python-net/aspose.cells.drawing.equations/functionequationnode/get_child/#int) | Returns the node at the specified index among the children of the current node. |
| [`remove(self)`](/cells/python-net/aspose.cells.drawing.equations/functionequationnode/remove/#) | Removes itself from the parent. |
| [`remove_all_children(self)`](/cells/python-net/aspose.cells.drawing.equations/functionequationnode/remove_all_children/#) | Removes all the child nodes of the current node. |
| [`create_node(, equation_type, workbook, parent)`](/cells/python-net/aspose.cells.drawing.equations/functionequationnode/create_node/#aspose.cells.drawing.equations.equationnodetype-aspose.cells.workbook-aspose.cells.drawing.equations.equationnode) | Create a node of the specified type. |



### See Also
* module [`aspose.cells.drawing.equations`](..)
* class [`EquationNode`](/cells/python-net/aspose.cells.drawing.equations/equationnode)
* class [`FontSetting`](/cells/python-net/aspose.cells/fontsetting)
* class [`FunctionEquationNode`](/cells/python-net/aspose.cells.drawing.equations/functionequationnode)
