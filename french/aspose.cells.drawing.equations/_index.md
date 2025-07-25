---
title: aspose.cells.drawing.equations
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 10
url: /fr/aspose.cells.drawing.equations/
is_root: false
---
 Le**Aspose.Cells.Drawing.Equations** namespace fournit des classes pour créer diverses formes d'équations (telles que des équations fractionnaires, des équations de puissance, etc.) via des nœuds d'équation.

###  Des classes
| Classe| Description|
| :- | :- |
| [`AccentEquationNode`](/cells/python-net/fr/aspose.cells.drawing.equations/accentequationnode) | Cette classe spécifie une équation d'accent, composée d'un composant de base et d'un diacritique de combinaison.|
| [`ArrayEquationNode`](/cells/python-net/fr/aspose.cells.drawing.equations/arrayequationnode) | Spécifie la fonction Equation-Array, un objet composé d'une ou plusieurs équations.|
| [`BarEquationNode`](/cells/python-net/fr/aspose.cells.drawing.equations/barequationnode) |Cette classe spécifie l'équation de barre, composée d'un argument de base et d'une barre supérieure ou inférieure.|
| [`BorderBoxEquationNode`](/cells/python-net/fr/aspose.cells.drawing.equations/borderboxequationnode) | Cette classe spécifie la fonction Border Box, constituée d'une bordure dessinée autour d'une équation.|
| [`BoxEquationNode`](/cells/python-net/fr/aspose.cells.drawing.equations/boxequationnode) | Cette classe spécifie la fonction box, qui est utilisée pour regrouper les composants d'une équation.|
| [`DelimiterEquationNode`](/cells/python-net/fr/aspose.cells.drawing.equations/delimiterequationnode) | Cette classe spécifie l'équation délimiteur, composée de délimiteurs ouvrants et fermants (tels que des parenthèses, des accolades, des crochets et des barres verticales) et d'un composant contenu à l'intérieur.<br/> Le délimiteur peut avoir plusieurs composants, avec un caractère séparateur désigné entre chaque composant.|
| [`EquationComponentNode`](/cells/python-net/fr/aspose.cells.drawing.equations/equationcomponentnode) | Cette classe spécifie les composants d'une équation ou d'une expression mathématique.<br/>Différents types de composants combinés dans différentes équations.<br/>Par exemple, une fraction se compose de deux parties, un numérateur et un dénominateur.<br/> Pour plus de types de composants, veuillez vous référer à « EquationNodeType ».|
| [`EquationNodeParagraph`](/cells/python-net/fr/aspose.cells.drawing.equations/equationnodeparagraph) | Cette classe spécifie un paragraphe mathématique contenant un ou plusieurs éléments MathEquationNode(OMath).|
| [`FractionEquationNode`](/cells/python-net/fr/aspose.cells.drawing.equations/fractionequationnode) |Cette classe spécifie l'équation de fraction, composée d'un numérateur et d'un dénominateur séparés par une barre de fraction. Cette barre peut être horizontale ou diagonale, selon les propriétés de la fraction. L'équation de fraction est également utilisée pour représenter la fonction de pile, qui place un élément au-dessus d'un autre, sans barre de fraction.|
| [`FunctionEquationNode`](/cells/python-net/fr/aspose.cells.drawing.equations/functionequationnode) | Cette classe spécifie l'équation Function-Apply, qui se compose d'un nom de fonction et d'un argument sur lequel on agit.<br/> Les types des composants nom et argument sont respectivement « EquationNodeType.FunctionName » et « EquationNodeType.Base ».|
| [`GroupCharacterEquationNode`](/cells/python-net/fr/aspose.cells.drawing.equations/groupcharacterequationnode) | Cette classe spécifie la fonction Group-Character, constituée d'un caractère dessiné au-dessus ou au-dessous du texte, souvent dans le but de regrouper visuellement des éléments.|
| [`LimLowUppEquationNode`](/cells/python-net/fr/aspose.cells.drawing.equations/limlowuppequationnode) | Cette classe spécifie la fonction limite.|
| [`MathematicalEquationNode`](/cells/python-net/fr/aspose.cells.drawing.equations/mathematicalequationnode) | Cette classe spécifie une équation ou une expression mathématique. Elle contient tout le texte mathématique des équations ou expressions mathématiques.|
| [`MatrixEquationNode`](/cells/python-net/fr/aspose.cells.drawing.equations/matrixequationnode) |Cette classe spécifie l'équation matricielle, constituée d'un ou plusieurs éléments disposés sur une ou plusieurs lignes et une ou plusieurs colonnes.|
| [`NaryEquationNode`](/cells/python-net/fr/aspose.cells.drawing.equations/naryequationnode) | Cette classe spécifie une équation d'opérateur n-aire composée d'un opérateur n-aire, d'une base (ou opérande) et de limites supérieures et inférieures facultatives.|
| [`RadicalEquationNode`](/cells/python-net/fr/aspose.cells.drawing.equations/radicalequationnode) | Cette classe spécifie l'équation radicale, composée d'un degré facultatif deg(EquationNodeType.Degree) et d'une base.|
| [`SubSupEquationNode`](/cells/python-net/fr/aspose.cells.drawing.equations/subsupequationnode) | Cette classe spécifie une équation qui peut éventuellement être en exposant ou en indice.<br/> Il existe quatre formes principales de cette équation : exposant, indice, exposant et indice placés à gauche de la base, exposant et indice placés à droite de la base.|
| [`TextRunEquationNode`](/cells/python-net/fr/aspose.cells.drawing.equations/textrunequationnode) | Cette classe dans le nœud d'équation est utilisée pour stocker le contenu réel (une séquence de texte mathématique) de l'équation.<br/> Généralement un objet nœud par caractère.|
| [`UnknowEquationNode`](/cells/python-net/fr/aspose.cells.drawing.equations/unknowequationnode) | Classe de nœuds d'équation de type inconnu|


###  Énumérations
| Énumération| Description|
| :- | :- |
| [`EquationCharacterPositionType`](/cells/python-net/fr/aspose.cells.drawing.equations/equationcharacterpositiontype) | Spécifie la position d'un sous-objet particulier dans son parent|
| [`EquationCombiningCharacterType`](/cells/python-net/fr/aspose.cells.drawing.equations/equationcombiningcharactertype) | Type de caractères combinés.|
| [`EquationDelimiterShapeType`](/cells/python-net/fr/aspose.cells.drawing.equations/equationdelimitershapetype) |Ceci spécifie la forme des délimiteurs dans l'objet délimiteur.|
| [`EquationFractionType`](/cells/python-net/fr/aspose.cells.drawing.equations/equationfractiontype) | Ceci spécifie le style d'affichage de la barre de fraction.|
| [`EquationHorizontalJustificationType`](/cells/python-net/fr/aspose.cells.drawing.equations/equationhorizontaljustificationtype) | Ceci spécifie la justification horizontale par défaut des équations dans le document.|
| [`EquationLimitLocationType`](/cells/python-net/fr/aspose.cells.drawing.equations/equationlimitlocationtype) | Spécifie l'emplacement limite sur un opérateur.|
| [`EquationMathematicalOperatorType`](/cells/python-net/fr/aspose.cells.drawing.equations/equationmathematicaloperatortype) | Type d'opérateurs mathématiques|
| [`EquationNodeType`](/cells/python-net/fr/aspose.cells.drawing.equations/equationnodetype) | Type de nœud d'équation.<br/>Avis:<br/>(1)[1-99] Actuellement, il n'y a qu'un seul nœud dans la portée, et sa valeur d'énumération est 1. Le nœud qu'il spécifie est utilisé pour stocker du texte mathématique.<br/>(2)[100-199] Indique que le nœud est un composant de certains nœuds de fonction spéciaux.<br/> (3)[200-] Indique que le nœud possède des fonctions spéciales.|
| [`EquationVerticalJustificationType`](/cells/python-net/fr/aspose.cells.drawing.equations/equationverticaljustificationtype) | Ceci spécifie la justification verticale par défaut des équations dans le document.|


