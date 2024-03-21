---
title: LoadFilter classe
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 1050
url: /it/aspose.cells/loadfilter/
is_root: false
---
##  LoadFilter classe
Rappresenta il filtro che fornisce opzioni per il caricamento dei dati durante il caricamento della cartella di lavoro dal modello.



Il tipo LoadFilter espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [__init__](/cells/python-net/it/aspose.cells/loadfilter/__init__/#) | Costruisce un LoadFilter con le opzioni di filtro predefinite LoadDataFilterOptions.All.|
| [__init__](/cells/python-net/it/aspose.cells/loadfilter/__init__/#aspose.cells.LoadDataFilterOptions) | Costruisce un LoadFilter con le opzioni di filtro specificate.|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [load_data_filter_options](/cells/python-net/it/aspose.cells/loadfilter/load_data_filter_options) | Le opzioni di filtro per indicare quali dati devono essere caricati.|
| [sheets_in_loading_order](/cells/python-net/it/aspose.cells/loadfilter/sheets_in_loading_order) | Specifica i fogli (indici) e l'ordine da caricare.<br/>L'impostazione predefinita è null, che indica di caricare tutti i fogli nell'ordine predefinito nel file modello.<br/> Se non è null e l'indice di alcuni fogli non è presente nell'array restituito, il foglio non verrà caricato.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [start_sheet](/cells/python-net/it/aspose.cells/loadfilter/start_sheet/#aspose.cells.Worksheet) | Prepara le opzioni di filtro prima di caricare un determinato foglio di lavoro.<br/>L'implementazione di LoadFilter da parte dell'utente può modificare LoadDataFilterOptions qui<br/> per indicare come caricare i dati per questo foglio di lavoro.|



###  Osservazioni

L'utente può specificare le opzioni del filtro o implementare il proprio LoadFilter per specificare come caricare i dati.

###  Guarda anche
* modulo [`aspose.cells`](..)
