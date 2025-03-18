---
title: EquationNodeParagraph class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 90
url: /aspose.cells.drawing.equations/equationnodeparagraph/
is_root: false
---

## EquationNodeParagraph class

This class specifies a mathematical paragraph containing one or more MathEquationNode(OMath) elements.



**Inheritance:** [`EquationNodeParagraph`](/cells/python-net/aspose.cells.drawing.equations/equationnodeparagraph) → 
[`EquationNode`](/cells/python-net/aspose.cells.drawing.equations/equationnode) → 
[`FontSetting`](/cells/python-net/aspose.cells/fontsetting)



The EquationNodeParagraph type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [type](/cells/python-net/aspose.cells.drawing.equations/equationnodeparagraph/type) | Represents the type of the node. |
| [start_index](/cells/python-net/aspose.cells.drawing.equations/equationnodeparagraph/start_index) | Gets the start index of the characters. |
| [length](/cells/python-net/aspose.cells.drawing.equations/equationnodeparagraph/length) | Gets the length of the characters. |
| [font](/cells/python-net/aspose.cells.drawing.equations/equationnodeparagraph/font) | Returns the font of this object. |
| [text_options](/cells/python-net/aspose.cells.drawing.equations/equationnodeparagraph/text_options) | Returns the text options. |
| [parent_node](/cells/python-net/aspose.cells.drawing.equations/equationnodeparagraph/parent_node) | Specifies the parent node of the current node |
| [equation_type](/cells/python-net/aspose.cells.drawing.equations/equationnodeparagraph/equation_type) | Get the equation type of the current node |
| [justification](/cells/python-net/aspose.cells.drawing.equations/equationnodeparagraph/justification) | This specifies justification of the math paragraph (a series of adjacent equations within the same paragraph). A math paragraph can be Left Justified, Right Justified, Centered, or Centered as Group. By default, the math paragraph is Centered as Group. This means that the equations can be aligned with respect to each other, but the entire group of equations is centered as a whole. |


### Methods
| Method | Description |
| :- | :- |
| [`add_child(self, equation_type)`](/cells/python-net/aspose.cells.drawing.equations/equationnodeparagraph/add_child/#aspose.cells.drawing.equations.equationnodetype) | Insert a node of the specified type at the end of the child node list of the current node. |
| [`add_child(self, node)`](/cells/python-net/aspose.cells.drawing.equations/equationnodeparagraph/add_child/#aspose.cells.drawing.equations.equationnode) | Inserts the specified node at the end of the current node's list of child nodes. |
| [`remove_child(self, node)`](/cells/python-net/aspose.cells.drawing.equations/equationnodeparagraph/remove_child/#aspose.cells.drawing.equations.equationnode) | Removes the specified node from the current node's children. |
| [`remove_child(self, index)`](/cells/python-net/aspose.cells.drawing.equations/equationnodeparagraph/remove_child/#int) | Removes the node at the specified index from the current node's children. |
| [`set_word_art_style(self, style)`](/cells/python-net/aspose.cells.drawing.equations/equationnodeparagraph/set_word_art_style/#aspose.cells.drawing.presetwordartstyle) | Sets the preset WordArt style. |
| [`to_la_te_x(self)`](/cells/python-net/aspose.cells.drawing.equations/equationnodeparagraph/to_la_te_x/#) | Convert this equtation to LaTeX expression. |
| [`to_math_ml(self)`](/cells/python-net/aspose.cells.drawing.equations/equationnodeparagraph/to_math_ml/#) | Convert this equtation to MathML expression. |
| [`insert_child(self, index, equation_type)`](/cells/python-net/aspose.cells.drawing.equations/equationnodeparagraph/insert_child/#int-aspose.cells.drawing.equations.equationnodetype) | Inserts a node of the specified type at the specified index position in the current node's child node list. |
| [`insert_after(self, equation_type)`](/cells/python-net/aspose.cells.drawing.equations/equationnodeparagraph/insert_after/#aspose.cells.drawing.equations.equationnodetype) | Inserts the specified node after the current node. |
| [`insert_before(self, equation_type)`](/cells/python-net/aspose.cells.drawing.equations/equationnodeparagraph/insert_before/#aspose.cells.drawing.equations.equationnodetype) | Inserts the specified node before the current node. |
| [`get_child(self, index)`](/cells/python-net/aspose.cells.drawing.equations/equationnodeparagraph/get_child/#int) | Returns the node at the specified index among the children of the current node. |
| [`remove(self)`](/cells/python-net/aspose.cells.drawing.equations/equationnodeparagraph/remove/#) | Removes itself from the parent. |
| [`remove_all_children(self)`](/cells/python-net/aspose.cells.drawing.equations/equationnodeparagraph/remove_all_children/#) | Removes all the child nodes of the current node. |
| [`create_node(, equation_type, workbook, parent)`](/cells/python-net/aspose.cells.drawing.equations/equationnodeparagraph/create_node/#aspose.cells.drawing.equations.equationnodetype-aspose.cells.workbook-aspose.cells.drawing.equations.equationnode) | Create a node of the specified type. |



### See Also
* module [`aspose.cells.drawing.equations`](..)
* class [`EquationNode`](/cells/python-net/aspose.cells.drawing.equations/equationnode)
* class [`EquationNodeParagraph`](/cells/python-net/aspose.cells.drawing.equations/equationnodeparagraph)
* class [`FontSetting`](/cells/python-net/aspose.cells/fontsetting)
