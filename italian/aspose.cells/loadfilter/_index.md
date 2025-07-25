---
title: LoadFilter classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 940
url: /it/aspose.cells/loadfilter/
is_root: false
---
##  LoadFilter classe
Rappresenta il filtro che fornisce opzioni per il caricamento dei dati durante il caricamento della cartella di lavoro dal modello.



Il tipo LoadFilter espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [`__init__(self)`](/cells/python-net/it/aspose.cells/loadfilter/__init__/#) | Costruisce un LoadFilter con opzioni di filtro predefinite LoadDataFilterOptions.All.|
| [`__init__(self, opts)`](/cells/python-net/it/aspose.cells/loadfilter/__init__/#aspose.cells.loaddatafilteroptions) | Costruisce un LoadFilter con le opzioni di filtro specificate.|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [load_data_filter_options](/cells/python-net/it/aspose.cells/loadfilter/load_data_filter_options) |Opzioni di filtro per indicare quali dati devono essere caricati.|
| [sheets_in_loading_order](/cells/python-net/it/aspose.cells/loadfilter/sheets_in_loading_order) | Specifica i fogli (indici) e l'ordine da caricare.<br/>Il valore predefinito è null, che indica di caricare tutti i fogli nell'ordine predefinito nel file modello.<br/> Se non è null e l'indice di un foglio non è presente nell'array restituito, il foglio non verrà caricato.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`start_sheet(self, sheet)`](/cells/python-net/it/aspose.cells/loadfilter/start_sheet/#aspose.cells.worksheet) | Prepara le opzioni del filtro prima di caricare il foglio di lavoro specificato.<br/>L'implementazione di LoadFilter da parte dell'utente può modificare LoadDataFilterOptions qui<br/> per indicare come caricare i dati per questo foglio di lavoro.|



###  Osservazioni

L'utente può specificare le opzioni del filtro o implementarne uno proprio LoadFilter per specificare come caricare i dati.

###  Guarda anche
* modulo [`aspose.cells`](..)
