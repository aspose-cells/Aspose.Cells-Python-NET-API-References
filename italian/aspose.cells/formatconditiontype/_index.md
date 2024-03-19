---
title: Enumerazione FormatConditionType
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 2170
url: /it/aspose.cells/formatconditiontype/
is_root: false
---
##  Enumerazione FormatConditionType
Tipo di regola di formato condizionale.



Il tipo FormatConditionType espone i seguenti membri:

###  Campi
| Campo| Descrizione|
| :- | :- |
| CELL_VALUE | Questa regola di formattazione condizionale confronta il valore di una cella<br/> al risultato calcolato di una formula, utilizzando un operatore.|
| EXPRESSION | Questa regola di formattazione condizionale contiene una formula per<br/>valutare. Quando il risultato della formula è vero, la cella lo è<br/> evidenziato.|
| TOP10 | Questa regola di formattazione condizionale evidenzia le celle di cui<br/>i valori rientrano nella parentesi superiore N o inferiore N, come<br/> specificato.|
| UNIQUE_VALUES |Questa regola di formattazione condizionale evidenzia unicità<br/> valori nell'intervallo.|
| DUPLICATE_VALUES | Questa regola di formattazione condizionale evidenzia i duplicati<br/> valori.|
| CONTAINS_TEXT | Questa regola di formattazione condizionale evidenzia le celle<br/>contenente un determinato testo. Equivalente all'utilizzo di SEARCH()<br/>funzione sheet per determinare se la cella contiene<br/> il testo.|
| NOT_CONTAINS_TEXT | Questa regola di formattazione condizionale evidenzia le celle che<br/>non contengono il testo specificato. Equivalente all'utilizzo di SEARCH()<br/>funzione sheet per determinare se la cella contiene<br/> il testo oppure no.|
| BEGINS_WITH | Questa regola di formattazione condizionale evidenzia le celle nel file<br/>intervallo che inizia con il testo specificato. Equivalente a<br/> utilizzando la funzione del foglio LEFT() e confrontando i valori.|
| ENDS_WITH | Questa regola di formattazione condizionale evidenzia la fine delle celle<br/>con il testo dato. Equivalente all'utilizzo del foglio RIGHT()<br/> funzione e confronto dei valori.|
| CONTAINS_BLANKS | Questa regola di formattazione condizionale evidenzia le celle che<br/>sono completamente vuoti. Equivalente all'utilizzo di LEN(TRIM()).<br/>Ciò significa che se la cella contiene solo caratteri<br/>che TRIM() verrebbe rimosso, viene considerato vuoto.<br/> Anche una cella vuota è considerata vuota.|
| NOT_CONTAINS_BLANKS | Questa regola di formattazione condizionale evidenzia le celle che<br/>non sono vuoti. Equivalente all'utilizzo di LEN(TRIM()). Questo<br/>significa che se la cella contiene solo caratteri quello<br/>TRIM() verrebbe rimosso, quindi viene considerato vuoto. UN<br/> anche la cella vuota è considerata vuota.|
| CONTAINS_ERRORS | Questa regola di formattazione condizionale evidenzia le celle con<br/>errori di formula. Equivalente all'utilizzo del foglio ISERROR()<br/> funzione per determinare se c'è un errore nella formula.|
| NOT_CONTAINS_ERRORS | Questa regola di formattazione condizionale evidenzia le celle<br/>senza errori di formula. Equivalente all'utilizzo di ISERROR()<br/> funzione foglio per determinare se c'è un errore nella formula.|
| TIME_PERIOD | Questa regola di formattazione condizionale evidenzia le celle<br/>contenenti date nel periodo di tempo specificato. IL<br/>viene valutato il valore sottostante della cella, quindi il<br/>non è necessario che la cella sia formattata come data<br/>valutato. Ad esempio, con una cella contenente il<br/>valore 38913 il formato condizionale deve essere applicato se<br/> la regola richiede un valore pari a 7/14/2006.|
| ABOVE_AVERAGE | Questa regola di formattazione condizionale evidenzia le celle che<br/>sono superiori o inferiori alla media per tutti i valori in<br/> allineare.|
| COLOR_SCALE | Questa regola di formattazione condizionale crea un file graduato<br/> scala di colori sulle celle.|
| DATA_BAR | Questa regola di formattazione condizionale visualizza un file graduato<br/> barra dei dati nell'intervallo di celle.|
| ICON_SET | Questa regola di formattazione condizionale applica le icone alle celle<br/> secondo i loro valori.|



###  Guarda anche
* modulo [`aspose.cells`](..)
