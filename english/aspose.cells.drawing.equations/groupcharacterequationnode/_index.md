---
title: GroupCharacterEquationNode class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 120
url: /aspose.cells.drawing.equations/groupcharacterequationnode/
is_root: false
---

## GroupCharacterEquationNode class

This class specifies the Group-Character function, consisting of a character drawn above or below text, often with the purpose of visually grouping items.



**Inheritance:** [`GroupCharacterEquationNode`](/cells/python-net/aspose.cells.drawing.equations/groupcharacterequationnode) → 
[`EquationNode`](/cells/python-net/aspose.cells.drawing.equations/equationnode) → 
[`FontSetting`](/cells/python-net/aspose.cells/fontsetting)



The GroupCharacterEquationNode type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [type](/cells/python-net/aspose.cells.drawing.equations/groupcharacterequationnode/type) | Represents the type of the node. |
| [start_index](/cells/python-net/aspose.cells.drawing.equations/groupcharacterequationnode/start_index) | Gets the start index of the characters. |
| [length](/cells/python-net/aspose.cells.drawing.equations/groupcharacterequationnode/length) | Gets the length of the characters. |
| [font](/cells/python-net/aspose.cells.drawing.equations/groupcharacterequationnode/font) | Returns the font of this object. |
| [text_options](/cells/python-net/aspose.cells.drawing.equations/groupcharacterequationnode/text_options) | Returns the text options. |
| [parent_node](/cells/python-net/aspose.cells.drawing.equations/groupcharacterequationnode/parent_node) | Specifies the parent node of the current node |
| [equation_type](/cells/python-net/aspose.cells.drawing.equations/groupcharacterequationnode/equation_type) | Get the equation type of the current node |
| [group_chr](/cells/python-net/aspose.cells.drawing.equations/groupcharacterequationnode/group_chr) | Specifies a symbol(default U+23DF).<br/>It is strongly recommended to use attribute ChrType to set accent character.<br/>Use this property setting if you cannot find the character you need in a known type. |
| [chr_type](/cells/python-net/aspose.cells.drawing.equations/groupcharacterequationnode/chr_type) | Specify combining characters by type value. |
| [position](/cells/python-net/aspose.cells.drawing.equations/groupcharacterequationnode/position) | This attribute specifies the position of the character in the object |
| [vert_jc](/cells/python-net/aspose.cells.drawing.equations/groupcharacterequationnode/vert_jc) | This attribute, combined with pos of groupChrPr, specifies the vertical layout of the groupChr object. Where pos specifies the position of the grouping character, vertJc specifies the alignment of the object with respect to the baseline. |


### Methods
| Method | Description |
| :- | :- |
| [`add_child(self, equation_type)`](/cells/python-net/aspose.cells.drawing.equations/groupcharacterequationnode/add_child/#aspose.cells.drawing.equations.equationnodetype) | Insert a node of the specified type at the end of the child node list of the current node. |
| [`add_child(self, node)`](/cells/python-net/aspose.cells.drawing.equations/groupcharacterequationnode/add_child/#aspose.cells.drawing.equations.equationnode) | Inserts the specified node at the end of the current node's list of child nodes. |
| [`remove_child(self, node)`](/cells/python-net/aspose.cells.drawing.equations/groupcharacterequationnode/remove_child/#aspose.cells.drawing.equations.equationnode) | Removes the specified node from the current node's children. |
| [`remove_child(self, index)`](/cells/python-net/aspose.cells.drawing.equations/groupcharacterequationnode/remove_child/#int) | Removes the node at the specified index from the current node's children. |
| [`set_word_art_style(self, style)`](/cells/python-net/aspose.cells.drawing.equations/groupcharacterequationnode/set_word_art_style/#aspose.cells.drawing.presetwordartstyle) | Sets the preset WordArt style. |
| [`to_la_te_x(self)`](/cells/python-net/aspose.cells.drawing.equations/groupcharacterequationnode/to_la_te_x/#) | Convert this equtation to LaTeX expression. |
| [`to_math_ml(self)`](/cells/python-net/aspose.cells.drawing.equations/groupcharacterequationnode/to_math_ml/#) | Convert this equtation to MathML expression. |
| [`insert_child(self, index, equation_type)`](/cells/python-net/aspose.cells.drawing.equations/groupcharacterequationnode/insert_child/#int-aspose.cells.drawing.equations.equationnodetype) | Inserts a node of the specified type at the specified index position in the current node's child node list. |
| [`insert_after(self, equation_type)`](/cells/python-net/aspose.cells.drawing.equations/groupcharacterequationnode/insert_after/#aspose.cells.drawing.equations.equationnodetype) | Inserts the specified node after the current node. |
| [`insert_before(self, equation_type)`](/cells/python-net/aspose.cells.drawing.equations/groupcharacterequationnode/insert_before/#aspose.cells.drawing.equations.equationnodetype) | Inserts the specified node before the current node. |
| [`get_child(self, index)`](/cells/python-net/aspose.cells.drawing.equations/groupcharacterequationnode/get_child/#int) | Returns the node at the specified index among the children of the current node. |
| [`remove(self)`](/cells/python-net/aspose.cells.drawing.equations/groupcharacterequationnode/remove/#) | Removes itself from the parent. |
| [`remove_all_children(self)`](/cells/python-net/aspose.cells.drawing.equations/groupcharacterequationnode/remove_all_children/#) | Removes all the child nodes of the current node. |
| [`create_node(, equation_type, workbook, parent)`](/cells/python-net/aspose.cells.drawing.equations/groupcharacterequationnode/create_node/#aspose.cells.drawing.equations.equationnodetype-aspose.cells.workbook-aspose.cells.drawing.equations.equationnode) | Create a node of the specified type. |



### See Also
* module [`aspose.cells.drawing.equations`](..)
* class [`EquationNode`](/cells/python-net/aspose.cells.drawing.equations/equationnode)
* class [`FontSetting`](/cells/python-net/aspose.cells/fontsetting)
* class [`GroupCharacterEquationNode`](/cells/python-net/aspose.cells.drawing.equations/groupcharacterequationnode)
