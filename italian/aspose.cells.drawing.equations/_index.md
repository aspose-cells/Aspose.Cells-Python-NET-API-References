---
title: aspose.cells.drawing.equations
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 10
url: /it/aspose.cells.drawing.equations/
is_root: false
---
 IL**Aspose.Cells.Drawing.Equations** namespace fornisce classi per creare varie forme di equazioni (ad esempio equazioni frazionarie, equazioni di potenza, ecc.) tramite nodi di equazione.

###  Classi
| Classe| Descrizione|
| :- | :- |
| [`AccentEquationNode`](/cells/python-net/it/aspose.cells.drawing.equations/accentequationnode) | Questa classe specifica un'equazione di accento, costituita da una componente base e da un segno diacritico di combinazione.|
| [`ArrayEquationNode`](/cells/python-net/it/aspose.cells.drawing.equations/arrayequationnode) | Specifica la funzione Equation-Array, un oggetto costituito da una o più equazioni.|
| [`BarEquationNode`](/cells/python-net/it/aspose.cells.drawing.equations/barequationnode) |Questa classe specifica l'equazione della barra, costituita da un argomento di base e da una barra superiore o inferiore.|
| [`BorderBoxEquationNode`](/cells/python-net/it/aspose.cells.drawing.equations/borderboxequationnode) | Questa classe specifica la funzione Border Box, che consiste in un bordo disegnato attorno a un'equazione.|
| [`BoxEquationNode`](/cells/python-net/it/aspose.cells.drawing.equations/boxequationnode) | Questa classe specifica la funzione box, utilizzata per raggruppare i componenti di un'equazione.|
| [`DelimiterEquationNode`](/cells/python-net/it/aspose.cells.drawing.equations/delimiterequationnode) | Questa classe specifica l'equazione del delimitatore, costituita da delimitatori di apertura e chiusura (ad esempio parentesi tonde, graffe, quadre e barre verticali) e da un componente contenuto al suo interno.<br/> Il delimitatore può avere più di un componente, con un carattere separatore designato tra ciascun componente.|
| [`EquationComponentNode`](/cells/python-net/it/aspose.cells.drawing.equations/equationcomponentnode) | Questa classe specifica i componenti di un'equazione o di un'espressione matematica.<br/>Diversi tipi di componenti combinati in equazioni diverse.<br/>Ad esempio, una frazione è composta da due parti: una componente numeratore e una componente denominatore.<br/> Per altri tipi di componenti, fare riferimento a 'EquationNodeType'.|
| [`EquationNodeParagraph`](/cells/python-net/it/aspose.cells.drawing.equations/equationnodeparagraph) | Questa classe specifica un paragrafo matematico contenente uno o più elementi MathEquationNode(OMath).|
| [`FractionEquationNode`](/cells/python-net/it/aspose.cells.drawing.equations/fractionequationnode) |Questa classe specifica l'equazione di frazione, costituita da un numeratore e un denominatore separati da una barra di frazione. La barra di frazione può essere orizzontale o diagonale, a seconda delle proprietà della frazione. L'equazione di frazione viene anche utilizzata per rappresentare la funzione di pila, che posiziona un elemento sopra l'altro, senza barra di frazione.|
| [`FunctionEquationNode`](/cells/python-net/it/aspose.cells.drawing.equations/functionequationnode) | Questa classe specifica l'equazione Function-Apply, che consiste in un nome di funzione e in un argomento su cui si agisce.<br/> I tipi dei componenti nome e argomento sono rispettivamente 'EquationNodeType.FunctionName' e 'EquationNodeType.Base'.|
| [`GroupCharacterEquationNode`](/cells/python-net/it/aspose.cells.drawing.equations/groupcharacterequationnode) | Questa classe specifica la funzione Group-Character, consistente in un carattere disegnato sopra o sotto il testo, spesso con lo scopo di raggruppare visivamente gli elementi.|
| [`LimLowUppEquationNode`](/cells/python-net/it/aspose.cells.drawing.equations/limlowuppequationnode) | Questa classe specifica la funzione limite.|
| [`MathematicalEquationNode`](/cells/python-net/it/aspose.cells.drawing.equations/mathematicalequationnode) | Questa classe specifica un'equazione o un'espressione matematica. Tutto il testo matematico di equazioni o espressioni matematiche è contenuto in questa classe.|
| [`MatrixEquationNode`](/cells/python-net/it/aspose.cells.drawing.equations/matrixequationnode) |Questa classe specifica l'equazione della matrice, costituita da uno o più elementi disposti su una o più righe e una o più colonne.|
| [`NaryEquationNode`](/cells/python-net/it/aspose.cells.drawing.equations/naryequationnode) | Questa classe specifica un'equazione di un operatore n-ario costituita da un operatore n-ario, una base (o operando) e limiti superiori e inferiori facoltativi.|
| [`RadicalEquationNode`](/cells/python-net/it/aspose.cells.drawing.equations/radicalequationnode) | Questa classe specifica l'equazione radicale, costituita da un grado facoltativo deg(EquationNodeType.Degree) e da una base.|
| [`SubSupEquationNode`](/cells/python-net/it/aspose.cells.drawing.equations/subsupequationnode) | Questa classe specifica un'equazione che può essere facoltativamente espressa in apice o pedice.<br/> Esistono quattro forme principali di questa equazione: apice, pedice, apice e pedice posti a sinistra della base, apice e pedice posti a destra della base.|
| [`TextRunEquationNode`](/cells/python-net/it/aspose.cells.drawing.equations/textrunequationnode) | Questa classe nel nodo equazione viene utilizzata per memorizzare il contenuto effettivo (una sequenza di testo matematico) dell'equazione.<br/> Solitamente un oggetto nodo per carattere.|
| [`UnknowEquationNode`](/cells/python-net/it/aspose.cells.drawing.equations/unknowequationnode) | Classe di nodi di equazione di tipo sconosciuto|


###  Enumerazioni
| Enumerazione| Descrizione|
| :- | :- |
| [`EquationCharacterPositionType`](/cells/python-net/it/aspose.cells.drawing.equations/equationcharacterpositiontype) | Specifica la posizione di un particolare sotto-oggetto all'interno del suo genitore|
| [`EquationCombiningCharacterType`](/cells/python-net/it/aspose.cells.drawing.equations/equationcombiningcharactertype) | Tipo di combinazione di caratteri.|
| [`EquationDelimiterShapeType`](/cells/python-net/it/aspose.cells.drawing.equations/equationdelimitershapetype) |Specifica la forma dei delimitatori nell'oggetto delimitatore.|
| [`EquationFractionType`](/cells/python-net/it/aspose.cells.drawing.equations/equationfractiontype) | Specifica lo stile di visualizzazione della barra delle frazioni.|
| [`EquationHorizontalJustificationType`](/cells/python-net/it/aspose.cells.drawing.equations/equationhorizontaljustificationtype) | Specifica la giustificazione orizzontale predefinita delle equazioni nel documento.|
| [`EquationLimitLocationType`](/cells/python-net/it/aspose.cells.drawing.equations/equationlimitlocationtype) | Specifica la posizione del limite su un operatore.|
| [`EquationMathematicalOperatorType`](/cells/python-net/it/aspose.cells.drawing.equations/equationmathematicaloperatortype) | Tipo di operatori matematici|
| [`EquationNodeType`](/cells/python-net/it/aspose.cells.drawing.equations/equationnodetype) | Tipo di nodo equazione.<br/>Avviso:<br/>(1)[1-99] Attualmente c'è un solo nodo nell'ambito e il suo valore di enumerazione è 1. Il nodo che specifica viene utilizzato per memorizzare testo matematico.<br/>(2)[100-199] Indica che il nodo è un componente di alcuni nodi di funzione speciale.<br/> (3)[200-] Indica che il nodo ha alcune funzioni speciali.|
| [`EquationVerticalJustificationType`](/cells/python-net/it/aspose.cells.drawing.equations/equationverticaljustificationtype) | Specifica la giustificazione verticale predefinita delle equazioni nel documento.|


