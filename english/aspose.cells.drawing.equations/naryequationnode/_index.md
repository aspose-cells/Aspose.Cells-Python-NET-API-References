---
title: NaryEquationNode class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 160
url: /aspose.cells.drawing.equations/naryequationnode/
is_root: false
---

## NaryEquationNode class

This class specifies an n-ary operator equation consisting of an n-ary operator, a base (or operand), and optional upper and lower bounds.



**Inheritance:** [`NaryEquationNode`](/cells/python-net/aspose.cells.drawing.equations/naryequationnode) → 
[`EquationNode`](/cells/python-net/aspose.cells.drawing.equations/equationnode) → 
[`FontSetting`](/cells/python-net/aspose.cells/fontsetting)



The NaryEquationNode type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [type](/cells/python-net/aspose.cells.drawing.equations/naryequationnode/type) | Represents the type of the node. |
| [start_index](/cells/python-net/aspose.cells.drawing.equations/naryequationnode/start_index) | Gets the start index of the characters. |
| [length](/cells/python-net/aspose.cells.drawing.equations/naryequationnode/length) | Gets the length of the characters. |
| [font](/cells/python-net/aspose.cells.drawing.equations/naryequationnode/font) | Returns the font of this object. |
| [text_options](/cells/python-net/aspose.cells.drawing.equations/naryequationnode/text_options) | Returns the text options. |
| [parent_node](/cells/python-net/aspose.cells.drawing.equations/naryequationnode/parent_node) | Specifies the parent node of the current node |
| [equation_type](/cells/python-net/aspose.cells.drawing.equations/naryequationnode/equation_type) | Get the equation type of the current node |
| [is_hide_subscript](/cells/python-net/aspose.cells.drawing.equations/naryequationnode/is_hide_subscript) | Whether to display the lower bound |
| [is_hide_superscript](/cells/python-net/aspose.cells.drawing.equations/naryequationnode/is_hide_superscript) | Whether to display the upper bound |
| [limit_location](/cells/python-net/aspose.cells.drawing.equations/naryequationnode/limit_location) | This attribute specifies the location of limits in n-ary operators. Limits can be either centered above and below the n-ary operator, or positioned just to the right of the operator. |
| [nary_operator](/cells/python-net/aspose.cells.drawing.equations/naryequationnode/nary_operator) | an n-ary operator.e.g "∑".<br/>It is strongly recommended to use attribute NaryOperatorType to set n-ary operator.<br/>Use this property setting if you cannot find the character you need in a known type. |
| [nary_operator_type](/cells/python-net/aspose.cells.drawing.equations/naryequationnode/nary_operator_type) | an n-ary operator.e.g "∑" |
| [nary_grow](/cells/python-net/aspose.cells.drawing.equations/naryequationnode/nary_grow) | This attribute specifies the growth property of n-ary operators at the document level. When off, n-ary operators such as integrals and summations do not grow to match the size of their operand height. When on, the n-ary operator grows vertically to match its operand height. |


### Methods
| Method | Description |
| :- | :- |
| [add_child](/cells/python-net/aspose.cells.drawing.equations/naryequationnode/add_child/#aspose.cells.drawing.equations.EquationNodeType) | Insert a node of the specified type at the end of the child node list of the current node. |
| [add_child](/cells/python-net/aspose.cells.drawing.equations/naryequationnode/add_child/#aspose.cells.drawing.equations.EquationNode) | Inserts the specified node at the end of the current node's list of child nodes. |
| [remove_child](/cells/python-net/aspose.cells.drawing.equations/naryequationnode/remove_child/#aspose.cells.drawing.equations.EquationNode) | Removes the specified node from the current node's children. |
| [remove_child](/cells/python-net/aspose.cells.drawing.equations/naryequationnode/remove_child/#int) | Removes the node at the specified index from the current node's children. |
| [set_word_art_style](/cells/python-net/aspose.cells.drawing.equations/naryequationnode/set_word_art_style/#aspose.cells.drawing.PresetWordArtStyle) | Sets the preset WordArt style. |
| [to_la_te_x](/cells/python-net/aspose.cells.drawing.equations/naryequationnode/to_la_te_x/#) | Convert this equtation to LaTeX expression. |
| [to_math_ml](/cells/python-net/aspose.cells.drawing.equations/naryequationnode/to_math_ml/#) | Convert this equtation to MathML expression. |
| [insert_child](/cells/python-net/aspose.cells.drawing.equations/naryequationnode/insert_child/#int-aspose.cells.drawing.equations.EquationNodeType) | Inserts a node of the specified type at the specified index position in the current node's child node list. |
| [insert_after](/cells/python-net/aspose.cells.drawing.equations/naryequationnode/insert_after/#aspose.cells.drawing.equations.EquationNodeType) | Inserts the specified node after the current node. |
| [insert_before](/cells/python-net/aspose.cells.drawing.equations/naryequationnode/insert_before/#aspose.cells.drawing.equations.EquationNodeType) | Inserts the specified node before the current node. |
| [get_child](/cells/python-net/aspose.cells.drawing.equations/naryequationnode/get_child/#int) | Returns the node at the specified index among the children of the current node. |
| [remove](/cells/python-net/aspose.cells.drawing.equations/naryequationnode/remove/#) | Removes itself from the parent. |
| [remove_all_children](/cells/python-net/aspose.cells.drawing.equations/naryequationnode/remove_all_children/#) | Removes all the child nodes of the current node. |
| [create_node](/cells/python-net/aspose.cells.drawing.equations/naryequationnode/create_node/#aspose.cells.drawing.equations.EquationNodeType-aspose.cells.Workbook-aspose.cells.drawing.equations.EquationNode) | Create a node of the specified type. |



### See Also
* module [`aspose.cells.drawing.equations`](..)
* class [`EquationNode`](/cells/python-net/aspose.cells.drawing.equations/equationnode)
* class [`FontSetting`](/cells/python-net/aspose.cells/fontsetting)
* class [`NaryEquationNode`](/cells/python-net/aspose.cells.drawing.equations/naryequationnode)
