---
title: Enumerazione AccessCacheOptions
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 1710
url: /it/aspose.cells/accesscacheoptions/
is_root: false
---
##  Enumerazione AccessCacheOptions
Opzioni di cache per l'accesso ai dati. Possono essere combinate con l'operatore | per ottenere più opzioni contemporaneamente.



Il tipo AccessCacheOptions espone i seguenti membri:

###  Campi
| Campo| Descrizione|
| :- | :- |
| NONE | Nessuna cache per l'accesso ai dati.|
| ALL | Applicare tutte le ottimizzazioni possibili per tutti i tipi di accesso ai dati nella cartella di lavoro.<br/> Durante l'accesso ottimizzato non si devono modificare né le impostazioni né i dati.|
| POSITION_AND_SIZE | Applicare l'ottimizzazione possibile per ottenere la posizione e le dimensioni dell'oggetto (ad esempio una forma).<br/> Le impostazioni relative all'altezza delle righe e alla larghezza delle colonne non devono essere modificate durante l'accesso ottimizzato.|
| CELLS_DATA | Applicare l'ottimizzazione possibile per ottenere i valori delle celle.<br/>I dati Cells (dati e impostazioni di Cell, riga) non devono essere modificati durante<br/>l'accesso ottimizzato, non dovrebbero essere creati nuovi oggetti Cell/Row (come<br/> da [indicizzatore]).|
| CELL_DISPLAY | Applicare una possibile ottimizzazione per ottenere risultati correlati alla visualizzazione di<br/>celle ([`Cell.display_string_value`](/cells/python-net/it/aspose.cells/cell#display_string_value), [`Cell.get_style`](/cells/python-net/it/aspose.cells/cell/get_style), [`Cell.get_display_style`](/cells/python-net/it/aspose.cells/cell/get_display_style), ecc.).<br/>Cells i dati e gli oggetti correlati allo stile (Cell/stili di riga/colonna, larghezza della colonna, ecc.) non devono essere modificati<br/> durante l'accesso ottimizzato.|
| GET_FORMULA | Applicare l'ottimizzazione possibile per ottenere le formule.<br/>Tutti i dati e le impostazioni che possono influenzare l'espressione della formula (nome del foglio di lavoro, testo del nome,<br/> (la colonna della tabella, ecc.) non devono essere modificate durante l'accesso ottimizzato.|
| SET_FORMULA | Applicare l'ottimizzazione possibile per l'impostazione delle formule.<br/>Tutti i dati e le impostazioni che possono influenzare l'espressione della formula (nome del foglio di lavoro, testo del nome,<br/> (la colonna della tabella, ecc.) non devono essere modificate durante l'accesso ottimizzato.|
| CALCULATE_FORMULA | Applicare l'ottimizzazione possibile per il calcolo delle formule.<br/>I dati Cells non devono essere modificati durante l'accesso ottimizzato, nessun nuovo oggetto (Cell, riga, ecc.)<br/> dovrebbe essere creato (ad esempio da [indicizzatore]).|
| CONDITIONAL_FORMATTING | Applicare l'ottimizzazione possibile per ottenere il risultato di formattazione delle formattazioni condizionali.<br/>Tutti i dati e le impostazioni che possono influenzare il risultato delle formattazioni condizionali (impostazioni di<br/> formattazioni condizionali, valori di celle dipendenti, ecc.) non devono essere modificati durante l'accesso ottimizzato.|
| VALIDATION | Applicare l'ottimizzazione possibile per ottenere il risultato della convalida.<br/>Tutti i dati e le impostazioni che possono influenzare il risultato della convalida (impostazioni della convalida,<br/> valori delle celle dipendenti, ecc.) non devono essere modificati durante l'accesso ottimizzato.|



###  Osservazioni

Per alcune funzionalità, l'accesso a set di dati di grandi dimensioni richiede molte operazioni ripetute e complicate
come la ricerca, il calcolo, ecc. e tali operazioni richiederanno molto tempo extra.
Per situazioni comuni, tutti i dati dipendenti rimangono invariati durante l'accesso, quindi alcune cache possono essere create e utilizzate per
migliorare le prestazioni di accesso.
A questo scopo, forniamo questo API in modo che l'utente possa specificare quale tipo di accesso ai dati necessita
da ottimizzare tramite possibile meccanismo di memorizzazione nella cache.


Si prega di notare che, per opzioni diverse, potrebbe essere necessario che diversi set di dati siano di "sola lettura".
E le prestazioni di accesso ai dati dipendono da molti aspetti, dall'uso del meccanismo di memorizzazione nella cache
non garantisce che le prestazioni saranno migliorate. In alcune situazioni,
ad esempio, se il set di dati a cui accedere è piccolo, l'utilizzo della cache potrebbe richiedere ancora più tempo perché
Anche la memorizzazione nella cache stessa richiede un certo tempo extra.

###  Guarda anche
* modulo [`aspose.cells`](..)
