---
title: aspose.cells.drawing.equations
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 10
url: /sv/aspose.cells.drawing.equations/
is_root: false
---
 De**Aspose.Cells.Drawing.Equations** namnrymden tillhandahåller klasser för att skapa olika ekvationsformer (såsom bråkformade ekvationer, potensformler etc.) genom ekvationsnoder.

###  Klasser
| Klass| Beskrivning|
| :- | :- |
| [`AccentEquationNode`](/cells/python-net/sv/aspose.cells.drawing.equations/accentequationnode) | Denna klass specificerar en accentekvation, bestående av en baskomponent och ett kombinerande diakritiskt tecken.|
| [`ArrayEquationNode`](/cells/python-net/sv/aspose.cells.drawing.equations/arrayequationnode) | Anger funktionen Equation-Array, ett objekt som består av en eller flera ekvationer.|
| [`BarEquationNode`](/cells/python-net/sv/aspose.cells.drawing.equations/barequationnode) |Den här klassen specificerar stapekvationen, bestående av ett basargument och en överstapel eller understapel.|
| [`BorderBoxEquationNode`](/cells/python-net/sv/aspose.cells.drawing.equations/borderboxequationnode) | Den här klassen anger funktionen Border Box, som består av en kantlinje ritad runt en ekvation.|
| [`BoxEquationNode`](/cells/python-net/sv/aspose.cells.drawing.equations/boxequationnode) | Denna klass anger boxfunktionen, som används för att gruppera komponenterna i en ekvation.|
| [`DelimiterEquationNode`](/cells/python-net/sv/aspose.cells.drawing.equations/delimiterequationnode) | Den här klassen specificerar avgränsarekvationen, som består av inledande och avslutande avgränsare (såsom parenteser, klammerparenteser, hakparenteser och vertikala streck), och en komponent som finns inuti.<br/> Avgränsaren kan ha mer än en komponent, med ett angivet avgränsningstecken mellan varje komponent.|
| [`EquationComponentNode`](/cells/python-net/sv/aspose.cells.drawing.equations/equationcomponentnode) | Den här klassen anger komponenterna i en ekvation eller ett matematiskt uttryck.<br/>Olika typer av komponenter kombinerade till olika ekvationer.<br/>Till exempel består ett bråk av två delar, en täljarkomponent och en nämnarkomponent.<br/> För fler komponenttyper, se 'EquationNodeType'.|
| [`EquationNodeParagraph`](/cells/python-net/sv/aspose.cells.drawing.equations/equationnodeparagraph) | Den här klassen anger ett matematiskt stycke som innehåller ett eller flera MathEquationNode(OMath)-element.|
| [`FractionEquationNode`](/cells/python-net/sv/aspose.cells.drawing.equations/fractionequationnode) |Denna klass anger bråkekvationen, bestående av en täljare och nämnare separerade med en bråkstreck. Bråkstrecket kan vara horisontellt eller diagonalt, beroende på bråkets egenskaper. Bråkekvationen används också för att representera stackfunktionen, som placerar ett element ovanför ett annat, utan bråkstreck.|
| [`FunctionEquationNode`](/cells/python-net/sv/aspose.cells.drawing.equations/functionequationnode) | Den här klassen anger Function-Apply-ekvationen, som består av ett funktionsnamn och ett argument som utförs.<br/> Typerna för namn- och argumentkomponenterna är 'EquationNodeType.FunctionName' respektive 'EquationNodeType.Base'.|
| [`GroupCharacterEquationNode`](/cells/python-net/sv/aspose.cells.drawing.equations/groupcharacterequationnode) | Den här klassen specificerar funktionen Group-Character, som består av ett tecken som ritas ovanför eller under text, ofta i syfte att visuellt gruppera objekt.|
| [`LimLowUppEquationNode`](/cells/python-net/sv/aspose.cells.drawing.equations/limlowuppequationnode) | Denna klass anger gränsfunktionen.|
| [`MathematicalEquationNode`](/cells/python-net/sv/aspose.cells.drawing.equations/mathematicalequationnode) | Denna klass anger en ekvation eller ett matematiskt uttryck. All matematisk text i ekvationer eller matematiska uttryck finns i denna klass.|
| [`MatrixEquationNode`](/cells/python-net/sv/aspose.cells.drawing.equations/matrixequationnode) |Denna klass anger matrisekvationen, som består av ett eller flera element utlagda i en eller flera rader och en eller flera kolumner.|
| [`NaryEquationNode`](/cells/python-net/sv/aspose.cells.drawing.equations/naryequationnode) | Denna klass specificerar en n-är operatorekvation som består av en n-är operator, en bas (eller operand) och valfria övre och undre gränser.|
| [`RadicalEquationNode`](/cells/python-net/sv/aspose.cells.drawing.equations/radicalequationnode) | Den här klassen anger radikalekvationen, som består av en valfri grad deg(EquationNodeType.Degree) och en bas.|
| [`SubSupEquationNode`](/cells/python-net/sv/aspose.cells.drawing.equations/subsupequationnode) | Den här klassen anger en ekvation som valfritt kan vara upphöjd eller nedsänkt.<br/> Det finns fyra huvudformer av denna ekvation: upphöjd skrift, nedsänkt skrift, upphöjd skrift och nedsänkt skrift placerade till vänster om basen, och upphöjd skrift och nedsänkt skrift placerade till höger om basen.|
| [`TextRunEquationNode`](/cells/python-net/sv/aspose.cells.drawing.equations/textrunequationnode) | Denna klass i ekvationsnoden används för att lagra ekvationens faktiska innehåll (en sekvens av matematisk text).<br/> Vanligtvis ett nodobjekt per tecken.|
| [`UnknowEquationNode`](/cells/python-net/sv/aspose.cells.drawing.equations/unknowequationnode) | Ekvationsnodklass av okänd typ|


###  Uppräkningar
| Uppräkning| Beskrivning|
| :- | :- |
| [`EquationCharacterPositionType`](/cells/python-net/sv/aspose.cells.drawing.equations/equationcharacterpositiontype) | Anger positionen för ett visst underobjekt inom dess överordnade objekt|
| [`EquationCombiningCharacterType`](/cells/python-net/sv/aspose.cells.drawing.equations/equationcombiningcharactertype) | Typ av kombination av tecken.|
| [`EquationDelimiterShapeType`](/cells/python-net/sv/aspose.cells.drawing.equations/equationdelimitershapetype) |Detta anger formen på avgränsare i avgränsarobjektet.|
| [`EquationFractionType`](/cells/python-net/sv/aspose.cells.drawing.equations/equationfractiontype) | Detta anger visningsstilen för bråkstapeln.|
| [`EquationHorizontalJustificationType`](/cells/python-net/sv/aspose.cells.drawing.equations/equationhorizontaljustificationtype) | Detta anger den horisontella standardjusteringen för ekvationer i dokumentet.|
| [`EquationLimitLocationType`](/cells/python-net/sv/aspose.cells.drawing.equations/equationlimitlocationtype) | Anger gränsläget för en operator.|
| [`EquationMathematicalOperatorType`](/cells/python-net/sv/aspose.cells.drawing.equations/equationmathematicaloperatortype) | Typ av matematiska operatorer|
| [`EquationNodeType`](/cells/python-net/sv/aspose.cells.drawing.equations/equationnodetype) | Typ av ekvationsnod.<br/>Varsel:<br/>(1)[1-99] För närvarande finns det bara en nod i omfånget, och dess uppräkningsvärde är 1. Noden som den anger används för att lagra matematisk text.<br/>(2)[100-199] Indikerar att noden är en komponent i några specialfunktionsnoder.<br/> (3)[200-] Indikerar att noden har några specialfunktioner.|
| [`EquationVerticalJustificationType`](/cells/python-net/sv/aspose.cells.drawing.equations/equationverticaljustificationtype) | Detta anger standardinställningen för vertikal justering av ekvationer i dokumentet.|


