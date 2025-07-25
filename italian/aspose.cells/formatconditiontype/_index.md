---
title: Enumerazione FormatConditionType
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 2110
url: /it/aspose.cells/formatconditiontype/
is_root: false
---
##  Enumerazione FormatConditionType
Tipo di regola di formattazione condizionale.



Il tipo FormatConditionType espone i seguenti membri:

###  Campi
| Campo| Descrizione|
| :- | :- |
| CELL_VALUE | Questa regola di formattazione condizionale confronta il valore di una cella<br/> al risultato calcolato da una formula, utilizzando un operatore.|
| EXPRESSION | Questa regola di formattazione condizionale contiene una formula per<br/>valutare. Quando il risultato della formula è vero, la cella è<br/> evidenziato.|
| TOP10 | Questa regola di formattazione condizionale evidenzia le celle i cui<br/>i valori rientrano nella fascia N superiore o N inferiore, come<br/> specificato.|
| UNIQUE_VALUES | Questa regola di formattazione condizionale evidenzia i caratteri unici<br/> valori nell'intervallo.|
| DUPLICATE_VALUES | Questa regola di formattazione condizionale evidenzia i duplicati<br/> valori.|
| CONTAINS_TEXT | Questa regola di formattazione condizionale evidenzia le celle<br/>contenente il testo specificato. Equivale all'utilizzo della funzione SEARCH()<br/>funzione foglio per determinare se la cella contiene<br/> il testo.|
| NOT_CONTAINS_TEXT | Questa regola di formattazione condizionale evidenzia le celle che<br/>non contengono il testo specificato. Equivale a usare SEARCH()<br/>funzione foglio per determinare se la cella contiene<br/> il testo oppure no.|
| BEGINS_WITH | Questa regola di formattazione condizionale evidenzia le celle in<br/>intervallo che inizia con il testo dato. Equivalente a<br/> utilizzando la funzione del foglio LEFT() e confrontando i valori.|
| ENDS_WITH | Questa regola di formattazione condizionale evidenzia le celle che terminano<br/>con il testo dato. Equivale all'utilizzo del foglio RIGHT()<br/> funzione e confronto dei valori.|
| CONTAINS_BLANKS | Questa regola di formattazione condizionale evidenzia le celle che<br/>sono completamente vuoti. Equivale a usare LEN(TRIM()).<br/>Ciò significa che se la cella contiene solo caratteri<br/>che TRIM() rimuoverebbe, allora viene considerato vuoto.<br/> Anche una cella vuota è considerata vuota.|
| NOT_CONTAINS_BLANKS | Questa regola di formattazione condizionale evidenzia le celle che<br/>non sono vuoti. Equivale all'utilizzo di LEN(TRIM()). Questo<br/>significa che se la cella contiene solo caratteri che<br/>TRIM() verrebbe rimosso, quindi viene considerato vuoto. Un<br/> Anche una cella vuota è considerata vuota.|
| CONTAINS_ERRORS | Questa regola di formattazione condizionale evidenzia le celle con<br/>Errori di formula. Equivale all'utilizzo del foglio ISERROR()<br/> funzione per determinare se c'è un errore nella formula.|
| NOT_CONTAINS_ERRORS | Questa regola di formattazione condizionale evidenzia le celle<br/>senza errori di formula. Equivale a usare ISERROR()<br/> funzione foglio per determinare se c'è un errore nella formula.|
| TIME_PERIOD | Questa regola di formattazione condizionale evidenzia le celle<br/>contenenti date nel periodo di tempo specificato. Il<br/>viene valutato il valore sottostante della cella, quindi il<br/>la cella non ha bisogno di essere formattata come una data da<br/>valutato. Ad esempio, con una cella contenente il<br/>valore 38913 il formato condizionale verrà applicato se<br/> la regola richiede un valore pari a 7/14/2006.|
| ABOVE_AVERAGE | Questa regola di formattazione condizionale evidenzia le celle che<br/>sono al di sopra o al di sotto della media per tutti i valori nel<br/> allineare.|
| COLOR_SCALE | Questa regola di formattazione condizionale crea una graduazione<br/> scala di colori sulle celle.|
| DATA_BAR | Questa regola di formattazione condizionale visualizza una graduazione<br/> barra dati nell'intervallo di celle.|
| ICON_SET |Questa regola di formattazione condizionale applica le icone alle celle<br/> in base ai loro valori.|



###  Guarda anche
* modulo [`aspose.cells`](..)
