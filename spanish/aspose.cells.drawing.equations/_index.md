---
title: aspose.cells.drawing.equations
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 10
url: /es/aspose.cells.drawing.equations/
is_root: false
---
 El**Aspose.Cells.Drawing.Equations** El espacio de nombres proporciona clases para crear varias formas de ecuaciones (como ecuaciones fraccionarias, ecuaciones de potencia, etc.) a través de nodos de ecuación.

###  Clases
| Clase| Descripción|
| :- | :- |
| [`AccentEquationNode`](/cells/python-net/es/aspose.cells.drawing.equations/accentequationnode) | Esta clase especifica una ecuación de acento, que consta de un componente base y un diacrítico combinatorio.|
| [`ArrayEquationNode`](/cells/python-net/es/aspose.cells.drawing.equations/arrayequationnode) | Especifica la función Equation-Array, un objeto que consta de una o más ecuaciones.|
| [`BarEquationNode`](/cells/python-net/es/aspose.cells.drawing.equations/barequationnode) |Esta clase especifica la ecuación de barras, que consta de un argumento base y una barra superior o inferior.|
| [`BorderBoxEquationNode`](/cells/python-net/es/aspose.cells.drawing.equations/borderboxequationnode) | Esta clase especifica la función Border Box, que consiste en un borde dibujado alrededor de una ecuación.|
| [`BoxEquationNode`](/cells/python-net/es/aspose.cells.drawing.equations/boxequationnode) | Esta clase especifica la función de cuadro, que se utiliza para agrupar los componentes de una ecuación.|
| [`DelimiterEquationNode`](/cells/python-net/es/aspose.cells.drawing.equations/delimiterequationnode) | Esta clase especifica la ecuación delimitadora, que consta de delimitadores de apertura y cierre (como paréntesis, llaves, corchetes y barras verticales) y un componente contenido en su interior.<br/> El delimitador puede tener más de un componente, con un carácter separador designado entre cada componente.|
| [`EquationComponentNode`](/cells/python-net/es/aspose.cells.drawing.equations/equationcomponentnode) | Esta clase especifica los componentes de una ecuación o expresión matemática.<br/>Diferentes tipos de componentes combinados en diferentes ecuaciones.<br/>Por ejemplo, una fracción consta de dos partes, un componente numerador y un componente denominador.<br/> Para conocer más tipos de componentes, consulte 'EquationNodeType'.|
| [`EquationNodeParagraph`](/cells/python-net/es/aspose.cells.drawing.equations/equationnodeparagraph) | Esta clase especifica un párrafo matemático que contiene uno o más elementos MathEquationNode(OMath).|
| [`FractionEquationNode`](/cells/python-net/es/aspose.cells.drawing.equations/fractionequationnode) |Esta clase especifica la ecuación fraccionaria, que consta de un numerador y un denominador separados por una barra de fracciones. Esta barra puede ser horizontal o diagonal, según las propiedades de la fracción. La ecuación fraccionaria también se utiliza para representar la función de apilamiento, que coloca un elemento sobre otro, sin barra de fracciones.|
| [`FunctionEquationNode`](/cells/python-net/es/aspose.cells.drawing.equations/functionequationnode) | Esta clase especifica la ecuación Function-Apply, que consta de un nombre de función y un argumento sobre el que se actúa.<br/> Los tipos de los componentes de nombre y argumento son 'EquationNodeType.FunctionName' y 'EquationNodeType.Base' respectivamente.|
| [`GroupCharacterEquationNode`](/cells/python-net/es/aspose.cells.drawing.equations/groupcharacterequationnode) | Esta clase especifica la función Grupo-Carácter, que consiste en un carácter dibujado encima o debajo del texto, a menudo con el propósito de agrupar elementos visualmente.|
| [`LimLowUppEquationNode`](/cells/python-net/es/aspose.cells.drawing.equations/limlowuppequationnode) | Esta clase especifica la función límite.|
| [`MathematicalEquationNode`](/cells/python-net/es/aspose.cells.drawing.equations/mathematicalequationnode) | Esta clase especifica una ecuación o expresión matemática. Contiene todo el texto matemático de ecuaciones o expresiones matemáticas.|
| [`MatrixEquationNode`](/cells/python-net/es/aspose.cells.drawing.equations/matrixequationnode) |Esta clase especifica la ecuación matricial, que consta de uno o más elementos dispuestos en una o más filas y una o más columnas.|
| [`NaryEquationNode`](/cells/python-net/es/aspose.cells.drawing.equations/naryequationnode) | Esta clase especifica una ecuación de operador n-ario que consta de un operador n-ario, una base (u operando) y límites superior e inferior opcionales.|
| [`RadicalEquationNode`](/cells/python-net/es/aspose.cells.drawing.equations/radicalequationnode) | Esta clase especifica la ecuación radical, que consta de un grado opcional deg(EquationNodeType.Degree) y una base.|
| [`SubSupEquationNode`](/cells/python-net/es/aspose.cells.drawing.equations/subsupequationnode) | Esta clase especifica una ecuación que opcionalmente puede ser superíndice o subíndice.<br/> Hay cuatro formas principales de esta ecuación: superíndice, subíndice, superíndice y subíndice colocados a la izquierda de la base, superíndice y subíndice colocados a la derecha de la base.|
| [`TextRunEquationNode`](/cells/python-net/es/aspose.cells.drawing.equations/textrunequationnode) | Esta clase en el nodo de ecuación se utiliza para almacenar el contenido real (una secuencia de texto matemático) de la ecuación.<br/> Generalmente un objeto de nodo por carácter.|
| [`UnknowEquationNode`](/cells/python-net/es/aspose.cells.drawing.equations/unknowequationnode) | Clase de nodo de ecuación de tipo desconocido|


###  Enumeraciones
| Enumeración| Descripción|
| :- | :- |
| [`EquationCharacterPositionType`](/cells/python-net/es/aspose.cells.drawing.equations/equationcharacterpositiontype) | Especifica la posición de un subobjeto particular dentro de su padre.|
| [`EquationCombiningCharacterType`](/cells/python-net/es/aspose.cells.drawing.equations/equationcombiningcharactertype) | Tipo de combinación de caracteres.|
| [`EquationDelimiterShapeType`](/cells/python-net/es/aspose.cells.drawing.equations/equationdelimitershapetype) |Esto especifica la forma de los delimitadores en el objeto delimitador.|
| [`EquationFractionType`](/cells/python-net/es/aspose.cells.drawing.equations/equationfractiontype) | Esto especifica el estilo de visualización de la barra de fracción.|
| [`EquationHorizontalJustificationType`](/cells/python-net/es/aspose.cells.drawing.equations/equationhorizontaljustificationtype) | Esto especifica la justificación horizontal predeterminada de las ecuaciones en el documento.|
| [`EquationLimitLocationType`](/cells/python-net/es/aspose.cells.drawing.equations/equationlimitlocationtype) | Especifica la ubicación límite de un operador.|
| [`EquationMathematicalOperatorType`](/cells/python-net/es/aspose.cells.drawing.equations/equationmathematicaloperatortype) | Tipos de operadores matemáticos|
| [`EquationNodeType`](/cells/python-net/es/aspose.cells.drawing.equations/equationnodetype) | Tipo de nodo de ecuación.<br/>Aviso:<br/>(1)[1-99] Actualmente solo hay un nodo en el alcance, y su valor de enumeración es 1. El nodo que especifica se utiliza para almacenar texto matemático.<br/>(2)[100-199] Indica que el nodo es un componente de algunos nodos de función especial.<br/> (3)[200-] Indica que el nodo tiene algunas funciones especiales.|
| [`EquationVerticalJustificationType`](/cells/python-net/es/aspose.cells.drawing.equations/equationverticaljustificationtype) | Esto especifica la justificación vertical predeterminada de las ecuaciones en el documento.|


