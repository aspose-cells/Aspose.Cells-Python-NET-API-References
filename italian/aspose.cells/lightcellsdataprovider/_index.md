---
title: LightCellsDataProvider classe
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 1040
url: /it/aspose.cells/lightcellsdataprovider/
is_root: false
---
##  LightCellsDataProvider classe
Rappresenta il fornitore di dati per il salvataggio di file di fogli di calcolo di grandi dimensioni in modalità leggera.



Il tipo LightCellsDataProvider espone i seguenti membri:

###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [start_sheet](/cells/python-net/it/aspose.cells/lightcellsdataprovider/start_sheet/#int) | Inizia a salvare un foglio di lavoro.|
| [next_row](/cells/python-net/it/aspose.cells/lightcellsdataprovider/next_row/#) | Ottiene la riga successiva da salvare.|
| [start_row](/cells/python-net/it/aspose.cells/lightcellsdataprovider/start_row/#aspose.cells.Row) | Inizia a salvare i dati di una riga.|
| [next_cell](/cells/python-net/it/aspose.cells/lightcellsdataprovider/next_cell/#) | Ottiene la cella successiva da salvare.|
| [start_cell](/cells/python-net/it/aspose.cells/lightcellsdataprovider/start_cell/#aspose.cells.Cell) | Inizia a salvare i dati di una cella.|
| [is_gather_string](/cells/python-net/it/aspose.cells/lightcellsdataprovider/is_gather_string/#) |Controlla se il valore stringa corrente della cella deve essere raccolto in un pool globale.|



###  Osservazioni

Quando si salva una cartella di lavoro in questa modalità, [`LightCellsDataProvider.start_sheet`](/cells/python-net/it/aspose.cells/lightcellsdataprovider/start_sheet) verrà controllato quando si salva ogni foglio di lavoro nella cartella di lavoro.
Per un foglio, se [`LightCellsDataProvider.start_sheet`](/cells/python-net/it/aspose.cells/lightcellsdataprovider/start_sheet) è vero, tutti i dati e le proprietà verranno salvati per le righe/celle di questo foglio
sarà fornito dall'implementazione di questa interfaccia.
In primo luogo verrà chiamato [`LightCellsDataProvider.next_row`](/cells/python-net/it/aspose.cells/lightcellsdataprovider/next_row) per ottenere l'indice della riga successiva da salvare.
Se viene restituito un indice di riga valido (l'indice di riga deve essere in ordine crescente affinché le righe vengano salvate),
quindi un oggetto Row che rappresenta questa riga verrà fornito da [`LightCellsDataProvider.start_row`](/cells/python-net/it/aspose.cells/lightcellsdataprovider/start_row) affinché l'implementazione ne imposti le proprietà.
Per una riga, verrà controllato per primo [`LightCellsDataProvider.next_cell`](/cells/python-net/it/aspose.cells/lightcellsdataprovider/next_cell).
Se viene restituito un indice di colonna valido (l'indice di colonna deve essere in ordine crescente per tutte le celle della riga corrente),
quindi un oggetto Cell che rappresenta questa cella verrà fornito da [`LightCellsDataProvider.start_cell`](/cells/python-net/it/aspose.cells/lightcellsdataprovider/start_cell) per l'implementazione per impostarne i dati e le proprietà.
Dopo [`LightCellsDataProvider.start_cell`](/cells/python-net/it/aspose.cells/lightcellsdataprovider/start_cell) la cella verrà salvata direttamente nel file del foglio di calcolo risultante.
Quindi la cella successiva verrà controllata ed elaborata.


Tieni presente che l'utente deve aggiornare solo i valori e le proprietà per l'oggetto Row/Cell corrente fornito dal metodo corrispondente.
Poiché i dati delle celle vengono scritti nel file risultante in modalità flusso, è possibile che sia stata scritta la maggior parte degli altri oggetti
al file risultante, o sono stati raccolti e scritti alcuni dati globali per essi. Pertanto, quando l'utente aggiorna altri oggetti
durante il salvataggio dei dati delle celle, tali operazioni potrebbero non essere in grado di influenzare i dati salvati. O peggio ancora, quelle operazioni potrebbero farlo
causare il salvataggio di dati incoerenti nel file risultante e infine rendere il file danneggiato.
Quindi, per tutti gli altri oggetti come forme, larghezza e stili di colonna, formattazioni condizionali, ... ecc.,
si prega di non utilizzarli in alcun metodo di questa implementazione.
Gestiscili invece e adattali allo stato finale prima di chiamare il metodo "Salva" della cartella di lavoro.

###  Guarda anche
* modulo [`aspose.cells`](..)
