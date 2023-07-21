---
title: aspose.cells.drawing.equations
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 10
url: /aspose.cells.drawing.equations/
is_root: false
---

The **Aspose.Cells.Drawing.Equations**  namespace provides classes for creating various equation shapes (such as fractional equations, power equations, etc.) through equation nodes.

### Classes
| Class | Description |
| :- | :- |
| [`AccentEquationNode`](/cells/python-net/aspose.cells.drawing.equations/accentequationnode) | This class specifies an accent equation, consisting of a base component and a combining diacritic. |
| [`BarEquationNode`](/cells/python-net/aspose.cells.drawing.equations/barequationnode) | This class specifies the bar equation, consisting of a base argument and an overbar or underbar. |
| [`BorderBoxEquationNode`](/cells/python-net/aspose.cells.drawing.equations/borderboxequationnode) | This class specifies the Border Box function, consisting of a border drawn around an equation. |
| [`BoxEquationNode`](/cells/python-net/aspose.cells.drawing.equations/boxequationnode) | This class specifies the box function, which is used to group components of an equation. |
| [`DelimiterEquationNode`](/cells/python-net/aspose.cells.drawing.equations/delimiterequationnode) | This class specifies the delimiter equation, consisting of opening and closing delimiters (such as parentheses, braces, brackets, and vertical bars), and a component contained inside. <br/>The delimiter may have more than one component, with a designated separator character between each component. |
| [`EquationComponentNode`](/cells/python-net/aspose.cells.drawing.equations/equationcomponentnode) | This class specifies the components of an equation or mathematical expression. <br/>Different types of components combined into different equations.<br/>For example, a fraction consists of two parts, a numerator component and a denominator component.<br/>For more component types, please refer to 'EquationNodeType'. |
| [`EquationNode`](/cells/python-net/aspose.cells.drawing.equations/equationnode) | Abstract class for deriving other equation nodes. |
| [`EquationNodeParagraph`](/cells/python-net/aspose.cells.drawing.equations/equationnodeparagraph) | This class specifies a mathematical paragraph containing one or more MathEquationNode(OMath) elements. |
| [`FractionEquationNode`](/cells/python-net/aspose.cells.drawing.equations/fractionequationnode) | This class  specifies the fraction equation, consisting of a numerator and denominator separated by a fraction bar. The fraction bar can be horizontal or diagonal, depending on the fraction properties. The fraction equation is also used to represent the stack function, which places one element above another, with no fraction bar. |
| [`FunctionEquationNode`](/cells/python-net/aspose.cells.drawing.equations/functionequationnode) | This class specifies the Function-Apply equation, which consists of a function name and an argument acted upon.<br/>The types of the name and argument components are 'EquationNodeType.FunctionName' and 'EquationNodeType.Base' respectively. |
| [`GroupCharacterEquationNode`](/cells/python-net/aspose.cells.drawing.equations/groupcharacterequationnode) | This class specifies the Group-Character function, consisting of a character drawn above or below text, often with the purpose of visually grouping items. |
| [`MathematicalEquationNode`](/cells/python-net/aspose.cells.drawing.equations/mathematicalequationnode) | This class specifies an equation or mathematical expression. All mathematical text of equations or mathematical expressions are contained by this class. |
| [`MatrixEquationNode`](/cells/python-net/aspose.cells.drawing.equations/matrixequationnode) | This class specifies the Matrix equation, consisting of one or more elements laid out in one or more rows and one or more columns. |
| [`NaryEquationNode`](/cells/python-net/aspose.cells.drawing.equations/naryequationnode) | This class specifies an n-ary operator equation consisting of an n-ary operator, a base (or operand), and optional upper and lower bounds. |
| [`RadicalEquationNode`](/cells/python-net/aspose.cells.drawing.equations/radicalequationnode) | This class specifies the radical equation, consisting of an optional degree deg(EquationNodeType.Degree) and a base. |
| [`SubSupEquationNode`](/cells/python-net/aspose.cells.drawing.equations/subsupequationnode) | This class specifies an equation that can optionally be superscript or subscript.<br/>There are four main forms of this equation, superscript，subscript，superscript and subscript placed to the left of the base, superscript and subscript placed to the right of the base. |
| [`TextRunEquationNode`](/cells/python-net/aspose.cells.drawing.equations/textrunequationnode) | This class in the equation node is used to store the actual content(a sequence of mathematical text) of the equation.<br/>Usually a node object per character. |
| [`UnknowEquationNode`](/cells/python-net/aspose.cells.drawing.equations/unknowequationnode) | Equation node class of unknown type |


### Enumerations
| Enumeration | Description |
| :- | :- |
| [`EquationCharacterPositionType`](/cells/python-net/aspose.cells.drawing.equations/equationcharacterpositiontype) | Specifies the position of a particular subobject within its parent |
| [`EquationCombiningCharacterType`](/cells/python-net/aspose.cells.drawing.equations/equationcombiningcharactertype) | Type of combining characters. |
| [`EquationDelimiterShapeType`](/cells/python-net/aspose.cells.drawing.equations/equationdelimitershapetype) | This specifies the shape of delimiters in the delimiter object. |
| [`EquationFractionType`](/cells/python-net/aspose.cells.drawing.equations/equationfractiontype) | This specifies the display style of the fraction bar. |
| [`EquationHorizontalJustificationType`](/cells/python-net/aspose.cells.drawing.equations/equationhorizontaljustificationtype) | This specifies the default horizontal justification of equations in the document. |
| [`EquationLimitLocationType`](/cells/python-net/aspose.cells.drawing.equations/equationlimitlocationtype) | Specifies the limit location on an operator. |
| [`EquationMathematicalOperatorType`](/cells/python-net/aspose.cells.drawing.equations/equationmathematicaloperatortype) | Mathematical Operators Type |
| [`EquationNodeType`](/cells/python-net/aspose.cells.drawing.equations/equationnodetype) | Equation node type.<br/>Notice:<br/>(1)[1-99] Currently there is only one node in the scope, and its enumeration value is 1. The node it specifies is used to store mathematical text.<br/>(2)[100-199] Indicates that the node is a component of some special function nodes.<br/>(3)[200-] Indicates that the node has some special functions(Usually with 'Equation' suffix. 'EquationParagraph' is a special case.). |
| [`EquationVerticalJustificationType`](/cells/python-net/aspose.cells.drawing.equations/equationverticaljustificationtype) | This specifies the default vertical justification of equations in the document. |


