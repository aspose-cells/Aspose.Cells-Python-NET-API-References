---
title: aspose.cells.drawing.equations
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 10
url: /zh/aspose.cells.drawing.equations/
is_root: false
---
这**Aspose.Cells.Drawing.Equations**命名空间提供了通过方程节点创建各种方程形状（如分数方程、幂方程等）的类。

### 类
|类|描述|
| :- | :- |
| [`AccentEquationNode`](/cells/python-net/zh/aspose.cells.drawing.equations/accentequationnode) |此类指定重音方程，由基本成分和组合变音符号组成。|
| [`ArrayEquationNode`](/cells/python-net/zh/aspose.cells.drawing.equations/arrayequationnode) |指定 Equation-Array 函数，即由一个或多个方程组成的对象。|
| [`BarEquationNode`](/cells/python-net/zh/aspose.cells.drawing.equations/barequationnode) |该类指定了条形方程，由一个基本参数和一个上划线或下划线组成。|
| [`BorderBoxEquationNode`](/cells/python-net/zh/aspose.cells.drawing.equations/borderboxequationnode) |此类指定了边框功能，由围绕方程绘制的边框组成。|
| [`BoxEquationNode`](/cells/python-net/zh/aspose.cells.drawing.equations/boxequationnode) |该类指定了框函数，用于对方程的组成部分进行分组。|
| [`DelimiterEquationNode`](/cells/python-net/zh/aspose.cells.drawing.equations/delimiterequationnode) |该类指定分隔符方程，由打开和关闭分隔符（例如括号、大括号、方括号和竖线）以及其中包含的组件组成。<br/>分隔符可以有多个组成部分，每个组成部分之间都有一个指定的分隔符。|
| [`EquationComponentNode`](/cells/python-net/zh/aspose.cells.drawing.equations/equationcomponentnode) |此类指定方程或数学表达式的组成部分。<br/>不同类型的组件组合成不同的方程式。<br/>例如，分数由两部分组成：分子部分和分母部分。<br/>更多组件类型请参考‘EquationNodeType’。|
| [`EquationNodeParagraph`](/cells/python-net/zh/aspose.cells.drawing.equations/equationnodeparagraph) |此类指定包含一个或多个 MathEquationNode(OMath) 元素的数学段落。|
| [`FractionEquationNode`](/cells/python-net/zh/aspose.cells.drawing.equations/fractionequationnode) |该类指定分数方程，由分子和分母组成，分子和分母之间用分号分隔。分号可以是水平的，也可以是对角的，具体取决于分数的属性。分数方程也用于表示堆叠函数，该函数将一个元素放置在另一个元素上方，并且不使用分号。|
| [`FunctionEquationNode`](/cells/python-net/zh/aspose.cells.drawing.equations/functionequationnode) |该类指定函数应用方程，该方程由函数名称和所作用的参数组成。<br/>名称和参数组件的类型分别为“EquationNodeType.FunctionName”和“EquationNodeType.Base”。|
| [`GroupCharacterEquationNode`](/cells/python-net/zh/aspose.cells.drawing.equations/groupcharacterequationnode) |此类指定组字符功能，由在文本上方或下方绘制的字符组成，通常用于视觉上对项目进行分组。|
| [`LimLowUppEquationNode`](/cells/python-net/zh/aspose.cells.drawing.equations/limlowuppequationnode) |该类指定限制函数。|
| [`MathematicalEquationNode`](/cells/python-net/zh/aspose.cells.drawing.equations/mathematicalequationnode) |此类指定一个方程式或数学表达式。此类包含所有方程式或数学表达式的数学文本。|
| [`MatrixEquationNode`](/cells/python-net/zh/aspose.cells.drawing.equations/matrixequationnode) |此类指定矩阵方程，由一行或多行和一列或多列中的一个或多个元素组成。|
| [`NaryEquationNode`](/cells/python-net/zh/aspose.cells.drawing.equations/naryequationnode) |此类指定一个 n 元运算符方程，由一个 n 元运算符、一个基数（或操作数）以及可选的上限和下限组成。|
| [`RadicalEquationNode`](/cells/python-net/zh/aspose.cells.drawing.equations/radicalequationnode) |该类指定根式方程，由可选的度数 deg(EquationNodeType.Degree) 和基数组成。|
| [`SubSupEquationNode`](/cells/python-net/zh/aspose.cells.drawing.equations/subsupequationnode) |此类指定可选为上标或下标的方程。<br/>该等式主要有四种形式，即上标，下标，上标和下标位于底边左侧，上标和下标位于底边右侧。|
| [`TextRunEquationNode`](/cells/python-net/zh/aspose.cells.drawing.equations/textrunequationnode) |方程节点中的此类用于存储方程的实际内容（一系列数学文本）。<br/>通常每个角色一个节点对象。|
| [`UnknowEquationNode`](/cells/python-net/zh/aspose.cells.drawing.equations/unknowequationnode) |未知类型的方程节点类|


### 枚举
|枚举|描述|
| :- | :- |
| [`EquationCharacterPositionType`](/cells/python-net/zh/aspose.cells.drawing.equations/equationcharacterpositiontype) |指定特定子对象在其父对象中的位置|
| [`EquationCombiningCharacterType`](/cells/python-net/zh/aspose.cells.drawing.equations/equationcombiningcharactertype) |组合字符的类型。|
| [`EquationDelimiterShapeType`](/cells/python-net/zh/aspose.cells.drawing.equations/equationdelimitershapetype) |这指定了分隔符对象中的分隔符的形状。|
| [`EquationFractionType`](/cells/python-net/zh/aspose.cells.drawing.equations/equationfractiontype) |这指定了分数条的显示样式。|
| [`EquationHorizontalJustificationType`](/cells/python-net/zh/aspose.cells.drawing.equations/equationhorizontaljustificationtype) |这指定了文档中方程的默认水平对齐方式。|
| [`EquationLimitLocationType`](/cells/python-net/zh/aspose.cells.drawing.equations/equationlimitlocationtype) |指定操作员的限制位置。|
| [`EquationMathematicalOperatorType`](/cells/python-net/zh/aspose.cells.drawing.equations/equationmathematicaloperatortype) |数学运算符类型|
| [`EquationNodeType`](/cells/python-net/zh/aspose.cells.drawing.equations/equationnodetype) |方程节点类型。<br/>注意：<br/>（1）[1-99] 当前作用域内只有一个节点，其枚举值为1，它指定的节点用于存储数学文本。<br/>（2）[100-199] 表示该节点是某些特殊功能节点的组件。<br/> （3）[200-] 表示该节点具有某些特殊功能。|
| [`EquationVerticalJustificationType`](/cells/python-net/zh/aspose.cells.drawing.equations/equationverticaljustificationtype) |这指定了文档中方程的默认垂直对齐方式。|


