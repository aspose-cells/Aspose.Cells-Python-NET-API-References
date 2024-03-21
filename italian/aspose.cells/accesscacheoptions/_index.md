---
title: Enumerazione AccessCacheOptions
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 1810
url: /it/aspose.cells/accesscacheoptions/
is_root: false
---
##  Enumerazione AccessCacheOptions
Opzioni della cache per l'accesso ai dati. Può essere combinato con | operatore per più opzioni insieme.



Il tipo AccessCacheOptions espone i seguenti membri:

###  Campi
| Campo| Descrizione|
| :- | :- |
| NONE | Nessuna cache per l'accesso ai dati.|
| ALL | Applicare tutte le possibili ottimizzazioni per tutti i tipi di accesso ai dati nella cartella di lavoro.<br/> Tutte le impostazioni e i dati non devono essere modificati durante l'accesso ottimizzato.|
| POSITION_AND_SIZE |Applicare la possibile ottimizzazione per ottenere la posizione e le dimensioni dell'oggetto (come Shape).<br/> Le impostazioni dell'altezza della riga e della larghezza della colonna non devono essere modificate durante l'accesso ottimizzato.|
| CELLS_DATA | Applicare la possibile ottimizzazione per ottenere i valori delle celle.<br/>I dati Cells (dati e impostazioni di Cell, Riga) non devono essere modificati durante<br/>l'accesso ottimizzato, non dovrebbero essere creati nemmeno nuovi oggetti Cell/Riga (come<br/> da [indicizzatore]).|
| CELL_DISPLAY | Applicare la possibile ottimizzazione per ottenere risultati relativi alla visualizzazione di<br/>celle([`Cell.display_string_value`](/cells/python-net/it/aspose.cells/cell#display_string_value), [`Cell.get_style`](/cells/python-net/it/aspose.cells/cell/get_style), [`Cell.get_display_style`](/cells/python-net/it/aspose.cells/cell/get_display_style), ecc.).<br/>Cells i dati e gli oggetti relativi allo stile (Cell/Stili riga/colonna, larghezza colonna, ecc.) non devono essere modificati<br/> durante l'accesso ottimizzato.|
| GET_FORMULA | Applicare la possibile ottimizzazione per ottenere le formule.<br/>Tutti i dati e le impostazioni che possono influenzare l'espressione della formula (nome del foglio di lavoro, testo del nome,<br/> colonna della tabella, ecc.) non deve essere modificata durante l'accesso ottimizzato.|
| SET_FORMULA |Applicare la possibile ottimizzazione per l'impostazione delle formule.<br/>Tutti i dati e le impostazioni che possono influenzare l'espressione della formula (nome del foglio di lavoro, testo del nome,<br/> colonna della tabella, ecc.) non deve essere modificata durante l'accesso ottimizzato.|
| CALCULATE_FORMULA | Applicare la possibile ottimizzazione per il calcolo delle formule.<br/>I dati Cells non devono essere modificati durante l'accesso ottimizzato, nessun nuovo oggetto (Cell, Riga, ecc.)<br/> dovrebbe essere creato (ad esempio da [indicizzatore]).|
| CONDITIONAL_FORMATTING | Applicare la possibile ottimizzazione per ottenere il risultato della formattazione delle formattazioni condizionali.<br/>Tutti i dati e le impostazioni che possono influenzare il risultato delle formattazioni condizionali (impostazioni di<br/> formattazioni condizionali, valori di cella dipendenti, ecc.) non devono essere modificati durante l'accesso ottimizzato.|
| VALIDATION | Applicare la possibile ottimizzazione per ottenere il risultato della convalida.<br/>Tutti i dati e le impostazioni che possono influenzare il risultato della validazione (impostazioni della validazione,<br/> valori delle celle dipendenti, ecc.) non devono essere modificati durante l'accesso ottimizzato.|



###  Osservazioni

Per alcune funzionalità, l'accesso a set di dati di grandi dimensioni richiede molte operazioni ripetute e complicate
come ricerca, calcolo, ecc. e queste operazioni richiederanno molto tempo extra.
Per le situazioni comuni, tutti i dati dipendenti rimangono invariati durante l'accesso, quindi è possibile creare e utilizzare alcune cache
migliorare le prestazioni di accesso.
A questo scopo forniamo questo API in modo che l'utente possa specificare quale tipo di accesso ai dati necessita
da ottimizzare mediante un possibile meccanismo di caching.


Tieni presente che, per opzioni diverse, potrebbe essere necessario che set di dati diversi siano "di sola lettura".
E le prestazioni di accesso ai dati dipendono da molti aspetti, dall'uso del meccanismo di memorizzazione nella cache
non garantisce il miglioramento delle prestazioni. Per alcune situazioni,
poiché il set di dati a cui accedere è piccolo, l'utilizzo della cache può richiedere ancora più tempo perché
anche la memorizzazione nella cache richiede un certo tempo aggiuntivo.

###  Guarda anche
* modulo [`aspose.cells`](..)
