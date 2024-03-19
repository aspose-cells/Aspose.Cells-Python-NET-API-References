---
title: LightCellsDataHandler classe
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 1030
url: /it/aspose.cells/lightcellsdatahandler/
is_root: false
---
##  LightCellsDataHandler classe
Rappresenta il gestore dati delle celle per la lettura di file di fogli di calcolo di grandi dimensioni in modalità leggera.



Il tipo LightCellsDataHandler espone i seguenti membri:

###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [start_sheet](/cells/python-net/it/aspose.cells/lightcellsdatahandler/start_sheet/#aspose.cells.Worksheet) | Inizia a elaborare un foglio di lavoro.|
| [start_row](/cells/python-net/it/aspose.cells/lightcellsdatahandler/start_row/#int) | Prepara l'elaborazione di una riga.|
| [process_row](/cells/python-net/it/aspose.cells/lightcellsdatahandler/process_row/#aspose.cells.Row) | Inizia a elaborare una riga.|
| [start_cell](/cells/python-net/it/aspose.cells/lightcellsdatahandler/start_cell/#int) | Si prepara a elaborare una cellula.|
| [process_cell](/cells/python-net/it/aspose.cells/lightcellsdatahandler/process_cell/#aspose.cells.Cell) | Inizia a elaborare una cella.|



###  Osservazioni

Quando si legge una cartella di lavoro in questa modalità, [`LightCellsDataHandler.start_sheet`](/cells/python-net/it/aspose.cells/lightcellsdatahandler/start_sheet) verrà controllato durante la lettura di ogni foglio di lavoro nella cartella di lavoro.
Per un foglio, se [`LightCellsDataHandler.start_sheet`](/cells/python-net/it/aspose.cells/lightcellsdatahandler/start_sheet) restituisce vero, verranno controllati tutti i dati e le proprietà delle righe/celle di questo foglio
ed elaborato dall'implementazione di questa interfaccia. Per ogni riga verrà chiamato lo [`LightCellsDataHandler.start_row`](/cells/python-net/it/aspose.cells/lightcellsdatahandler/start_row) per verificare se è necessario elaborarla.
Se è necessario elaborare una riga, le proprietà di questa riga verranno lette per prime e l'utente potrà accedere alle sue proprietà tramite [`LightCellsDataHandler.process_row`](/cells/python-net/it/aspose.cells/lightcellsdatahandler/process_row).
se anche le celle della riga devono essere elaborate, allora [`LightCellsDataHandler.process_row`](/cells/python-net/it/aspose.cells/lightcellsdatahandler/process_row) dovrebbe restituire vero e quindi [`LightCellsDataHandler.start_cell`](/cells/python-net/it/aspose.cells/lightcellsdatahandler/start_cell) sarà
chiamato per ogni cella esistente in questa riga per verificare se una cella deve essere elaborata. Se è necessario elaborare una cella,
quindi verrà chiamato [`LightCellsDataHandler.process_cell`](/cells/python-net/it/aspose.cells/lightcellsdatahandler/process_cell) per elaborare la cella mediante l'implementazione di questa interfaccia.


Tieni presente che l'utente deve operare solo sui valori e sulle proprietà dell'oggetto Row/Cell corrente fornito dal metodo corrispondente.
Poiché i dati delle celle vengono letti dal file modello in modalità streaming, la maggior parte degli altri oggetti potrebbe essere reimpostata/aggiornata in seguito
dopo che i dati delle celle sono stati caricati. Pertanto, quando l'utente utilizza altri oggetti in questa implementazione,
tali operazioni potrebbero non essere in grado di influenzare gli oggetti esistenti nella cartella di lavoro. O peggio ancora, quelle operazioni potrebbero farlo
causare dati incoerenti nella cartella di lavoro e quindi causare problemi o eccezioni imprevisti in un secondo momento.
Quindi, per tutti gli altri oggetti come forme, larghezza e stili di colonna, formattazioni condizionali, ... ecc.,
si prega di non utilizzarli in alcun metodo di questa implementazione.
Gestirli invece dopo che la cartella di lavoro è stata costruita.

###  Guarda anche
* modulo [`aspose.cells`](..)
