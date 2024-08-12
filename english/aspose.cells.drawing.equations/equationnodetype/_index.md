---
title: EquationNodeType enumeration
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 260
url: /aspose.cells.drawing.equations/equationnodetype/
is_root: false
---

## EquationNodeType enumeration

Equation node type.
Notice:
(1)[1-99] Currently there is only one node in the scope, and its enumeration value is 1. The node it specifies is used to store mathematical text.
(2)[100-199] Indicates that the node is a component of some special function nodes.
(3)[200-] Indicates that the node has some special functions(Usually with 'Equation' suffix. 'EquationParagraph' is a special case.).



The EquationNodeType type exposes the following members:

### Fields
| Field | Description |
| :- | :- |
| UN_KNOW | UnKnow |
| TEXT | specifies a node that stores math text |
| BASE | Specifies a Base component |
| DENOMINATOR | Specifies a Denominator component |
| NUMERATOR | Specifies a Numerator component |
| FUNCTION_NAME | Specifies a FunctionName component |
| SUBSCRIPT | Specifies a Subscript component |
| SUPERSCRIPT | Specifies a Superscript component |
| DEGREE | Specifies a Degree component |
| MATRIX_ROW | Specifies a MatrixRow component.A single row of the matrix |
| LIMIT | If the parent object is limLow,the object of this type specifies the lower limit of the limLow function; if the parent objectis limUpp, the object of this type specifies the Upper-Limit function, consisting of text on the baseline and reduced-size text just above the baseline. |
| EQUATION_PARAGRAPH | Specifies a mathematical paragraph(oMathPara). |
| MATHEMATICAL_EQUATION | Specifies an equation or mathematical expression(OMath). |
| FRACTION_EQUATION | Specifies fractional equation |
| FUNCTION_EQUATION | Specifies function equation |
| DELIMITER_EQUATION | Specifies delimiter equation |
| NARY_EQUATION | Specifies n-ary operator equation |
| RADICAL_EQUATION | Specifies the radical equation |
| SUPERSCRIPT_EQUATION | Specifies superscript equation |
| SUBSCRIPT_EQUATION | Specifies subscript equation |
| SUB_SUP_EQUATION | Specifies an equation with superscripts and subscripts to the right of the operands. |
| PRE_SUB_SUP_EQUATION | Specifies an equation with superscripts and subscripts to the left of the operands. |
| ACCENT_EQUATION | Specifies accent equation |
| BAR_EQUATION | Specifies bar equation |
| BORDER_BOX_EQUATION | Specifies border box equation |
| BOX_EQUATION | Specifies box equation |
| GROUP_CHARACTER_EQUATION | Specifies Group-Character equation |
| MATRIX_EQUATION | Specifies the Matrix equation, |
| LOWER_LIMIT | Specifies the Lower-Limit function |
| UPPER_LIMIT | Specifies the Upper-Limit function |



### See Also
* module [`aspose.cells.drawing.equations`](..)
