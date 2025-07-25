---
title: aspose.cells.drawing.equations
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 10
url: /de/aspose.cells.drawing.equations/
is_root: false
---
 Der**Aspose.Cells.Drawing.Equations** Der Namespace bietet Klassen zum Erstellen verschiedener Gleichungsformen (wie Bruchgleichungen, Potenzgleichungen usw.) über Gleichungsknoten.

###  Klassen
| Klasse| Beschreibung|
| :- | :- |
| [`AccentEquationNode`](/cells/python-net/de/aspose.cells.drawing.equations/accentequationnode) | Diese Klasse gibt eine Akzentgleichung an, die aus einer Basiskomponente und einem kombinierenden diakritischen Zeichen besteht.|
| [`ArrayEquationNode`](/cells/python-net/de/aspose.cells.drawing.equations/arrayequationnode) | Gibt die Gleichungs-Array-Funktion an, ein Objekt, das aus einer oder mehreren Gleichungen besteht.|
| [`BarEquationNode`](/cells/python-net/de/aspose.cells.drawing.equations/barequationnode) |Diese Klasse gibt die Balkengleichung an, die aus einem Basisargument und einem Über- oder Unterstrich besteht.|
| [`BorderBoxEquationNode`](/cells/python-net/de/aspose.cells.drawing.equations/borderboxequationnode) | Diese Klasse gibt die Border-Box-Funktion an, die aus einem Rahmen besteht, der um eine Gleichung gezeichnet wird.|
| [`BoxEquationNode`](/cells/python-net/de/aspose.cells.drawing.equations/boxequationnode) | Diese Klasse gibt die Boxfunktion an, die zum Gruppieren von Komponenten einer Gleichung verwendet wird.|
| [`DelimiterEquationNode`](/cells/python-net/de/aspose.cells.drawing.equations/delimiterequationnode) | Diese Klasse gibt die Trennzeichengleichung an, die aus öffnenden und schließenden Trennzeichen (wie Klammern, geschweiften Klammern, eckigen Klammern und senkrechten Strichen) und einer darin enthaltenen Komponente besteht.<br/> Das Trennzeichen kann mehr als eine Komponente haben, wobei zwischen jeder Komponente ein bestimmtes Trennzeichen stehen muss.|
| [`EquationComponentNode`](/cells/python-net/de/aspose.cells.drawing.equations/equationcomponentnode) | Diese Klasse gibt die Komponenten einer Gleichung oder eines mathematischen Ausdrucks an.<br/>Verschiedene Arten von Komponenten werden zu unterschiedlichen Gleichungen kombiniert.<br/>Beispielsweise besteht ein Bruch aus zwei Teilen, einem Zählerbestandteil und einem Nennerbestandteil.<br/> Weitere Komponententypen finden Sie unter „EquationNodeType“.|
| [`EquationNodeParagraph`](/cells/python-net/de/aspose.cells.drawing.equations/equationnodeparagraph) | Diese Klasse gibt einen mathematischen Absatz an, der ein oder mehrere MathEquationNode(OMath)-Elemente enthält.|
| [`FractionEquationNode`](/cells/python-net/de/aspose.cells.drawing.equations/fractionequationnode) |Diese Klasse gibt die Bruchgleichung an, bestehend aus Zähler und Nenner, getrennt durch einen Bruchstrich. Der Bruchstrich kann je nach Brucheigenschaften horizontal oder diagonal sein. Die Bruchgleichung dient auch zur Darstellung der Stapelfunktion, die ein Element über dem anderen platziert, ohne Bruchstrich.|
| [`FunctionEquationNode`](/cells/python-net/de/aspose.cells.drawing.equations/functionequationnode) | Diese Klasse gibt die Function-Apply-Gleichung an, die aus einem Funktionsnamen und einem Argument besteht, auf das eingewirkt wird.<br/> Die Typen der Namens- und Argumentkomponenten sind „EquationNodeType.FunctionName“ bzw. „EquationNodeType.Base“.|
| [`GroupCharacterEquationNode`](/cells/python-net/de/aspose.cells.drawing.equations/groupcharacterequationnode) | Diese Klasse gibt die Funktion „Zeichen gruppieren“ an, die aus einem Zeichen besteht, das über oder unter dem Text gezeichnet wird, häufig mit dem Zweck, Elemente visuell zu gruppieren.|
| [`LimLowUppEquationNode`](/cells/python-net/de/aspose.cells.drawing.equations/limlowuppequationnode) | Diese Klasse gibt die Grenzwertfunktion an.|
| [`MathematicalEquationNode`](/cells/python-net/de/aspose.cells.drawing.equations/mathematicalequationnode) | Diese Klasse gibt eine Gleichung oder einen mathematischen Ausdruck an. Der gesamte mathematische Text von Gleichungen oder mathematischen Ausdrücken ist in dieser Klasse enthalten.|
| [`MatrixEquationNode`](/cells/python-net/de/aspose.cells.drawing.equations/matrixequationnode) |Diese Klasse gibt die Matrixgleichung an, die aus einem oder mehreren Elementen besteht, die in einer oder mehreren Zeilen und einer oder mehreren Spalten angeordnet sind.|
| [`NaryEquationNode`](/cells/python-net/de/aspose.cells.drawing.equations/naryequationnode) | Diese Klasse gibt eine n-äre Operatorgleichung an, die aus einem n-ären Operator, einer Basis (oder einem Operanden) und optionalen Ober- und Untergrenzen besteht.|
| [`RadicalEquationNode`](/cells/python-net/de/aspose.cells.drawing.equations/radicalequationnode) | Diese Klasse gibt die Wurzelgleichung an, die aus einem optionalen Grad deg(EquationNodeType.Degree) und einer Basis besteht.|
| [`SubSupEquationNode`](/cells/python-net/de/aspose.cells.drawing.equations/subsupequationnode) | Diese Klasse gibt eine Gleichung an, die wahlweise hochgestellt oder tiefgestellt sein kann.<br/> Es gibt vier Hauptformen dieser Gleichung: Hochstellung, Tiefstellung, Hochstellung und Tiefstellung links von der Basis, Hochstellung und Tiefstellung rechts von der Basis.|
| [`TextRunEquationNode`](/cells/python-net/de/aspose.cells.drawing.equations/textrunequationnode) | Diese Klasse im Gleichungsknoten wird verwendet, um den eigentlichen Inhalt (eine Folge mathematischen Textes) der Gleichung zu speichern.<br/> Normalerweise ein Knotenobjekt pro Zeichen.|
| [`UnknowEquationNode`](/cells/python-net/de/aspose.cells.drawing.equations/unknowequationnode) | Gleichungsknotenklasse unbekannten Typs|


###  Aufzählungen
| Aufzählung| Beschreibung|
| :- | :- |
| [`EquationCharacterPositionType`](/cells/python-net/de/aspose.cells.drawing.equations/equationcharacterpositiontype) | Gibt die Position eines bestimmten Unterobjekts innerhalb seines übergeordneten Objekts an|
| [`EquationCombiningCharacterType`](/cells/python-net/de/aspose.cells.drawing.equations/equationcombiningcharactertype) | Art der Zeichenkombination.|
| [`EquationDelimiterShapeType`](/cells/python-net/de/aspose.cells.drawing.equations/equationdelimitershapetype) |Dies gibt die Form der Trennzeichen im Trennzeichenobjekt an.|
| [`EquationFractionType`](/cells/python-net/de/aspose.cells.drawing.equations/equationfractiontype) | Dies gibt den Anzeigestil des Bruchstrichs an.|
| [`EquationHorizontalJustificationType`](/cells/python-net/de/aspose.cells.drawing.equations/equationhorizontaljustificationtype) | Dies gibt die standardmäßige horizontale Ausrichtung von Gleichungen im Dokument an.|
| [`EquationLimitLocationType`](/cells/python-net/de/aspose.cells.drawing.equations/equationlimitlocationtype) | Gibt die Grenzposition eines Operators an.|
| [`EquationMathematicalOperatorType`](/cells/python-net/de/aspose.cells.drawing.equations/equationmathematicaloperatortype) | Typ der mathematischen Operatoren|
| [`EquationNodeType`](/cells/python-net/de/aspose.cells.drawing.equations/equationnodetype) | Gleichungsknotentyp.<br/>Beachten:<br/>(1)[1-99] Derzeit gibt es nur einen Knoten im Bereich und sein Enumerationswert ist 1. Der von ihm angegebene Knoten wird zum Speichern von mathematischem Text verwendet.<br/>(2)[100-199] Zeigt an, dass der Knoten eine Komponente einiger Spezialfunktionsknoten ist.<br/> (3)[200-] Zeigt an, dass der Knoten einige spezielle Funktionen hat.|
| [`EquationVerticalJustificationType`](/cells/python-net/de/aspose.cells.drawing.equations/equationverticaljustificationtype) | Dies gibt die standardmäßige vertikale Ausrichtung von Gleichungen im Dokument an.|


