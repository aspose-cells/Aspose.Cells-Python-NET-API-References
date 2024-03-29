---
title: TxtSaveOptions classe
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 1590
url: /it/aspose.cells/txtsaveoptions/
is_root: false
---
##  TxtSaveOptions classe
Rappresenta le opzioni di salvataggio per CSV/delimitato da tabulazioni/altro formato di testo.



**Eredità:** [`TxtSaveOptions`](/cells/python-net/aspose.cells/txtsaveoptions) → 
[`SaveOptions`](/cells/python-net/it/aspose.cells/saveoptions)



Il tipo TxtSaveOptions espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [__init__](/cells/python-net/it/aspose.cells/txtsaveoptions/__init__/#) | Crea opzioni di salvataggio del file di testo.|
| [__init__](/cells/python-net/it/aspose.cells/txtsaveoptions/__init__/#aspose.cells.SaveFormat) | Crea opzioni di salvataggio del file di testo.|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [save_format](/cells/python-net/it/aspose.cells/txtsaveoptions/save_format) | Ottiene il formato del file di salvataggio.|
| [clear_data](/cells/python-net/it/aspose.cells/txtsaveoptions/clear_data) | Rendi vuota la cartella di lavoro dopo aver salvato il file.|
| [cached_file_folder](/cells/python-net/it/aspose.cells/txtsaveoptions/cached_file_folder) | La cartella dei file memorizzati nella cache viene utilizzata per archiviare alcuni dati di grandi dimensioni.|
| [validate_merged_areas](/cells/python-net/it/aspose.cells/txtsaveoptions/validate_merged_areas) | Indica se convalidare le celle unite prima di salvare il file.|
| [merge_areas](/cells/python-net/it/aspose.cells/txtsaveoptions/merge_areas) | Indica se unire le aree di formattazione condizionale e di validazione prima di salvare il file.|
| [create_directory](/cells/python-net/it/aspose.cells/txtsaveoptions/create_directory) | Se vero e la directory non esiste, la directory verrà creata automaticamente prima di salvare il file.|
| [sort_names](/cells/python-net/it/aspose.cells/txtsaveoptions/sort_names) | Indica se ordinare i nomi definiti prima di salvare il file.|
| [sort_external_names](/cells/python-net/it/aspose.cells/txtsaveoptions/sort_external_names) | Indica se ordinare i nomi definiti esterni prima di salvare il file.|
| [refresh_chart_cache](/cells/python-net/it/aspose.cells/txtsaveoptions/refresh_chart_cache) | Indica se aggiornare i dati della cache del grafico|
| [warning_callback](/cells/python-net/it/aspose.cells/txtsaveoptions/warning_callback) | Ottiene o imposta la richiamata di avviso.|
| [update_smart_art](/cells/python-net/it/aspose.cells/txtsaveoptions/update_smart_art) | Indica se aggiornare l'impostazione della grafica intelligente.<br/> Il valore predefinito è falso.|
| [separator](/cells/python-net/it/aspose.cells/txtsaveoptions/separator) | Ottiene e imposta char Delimitatore del file di testo.|
| [separator_string](/cells/python-net/it/aspose.cells/txtsaveoptions/separator_string) | Ottiene e imposta un valore stringa come separatore.|
| [encoding](/cells/python-net/it/aspose.cells/txtsaveoptions/encoding) | Ottiene e imposta la codifica predefinita.|
| [always_quoted](/cells/python-net/it/aspose.cells/txtsaveoptions/always_quoted) | Indica se aggiungere sempre '"' per ciascun campo.<br/>Se vero allora tutti i valori verranno racchiusi tra virgolette;<br/>Se falso, i valori verranno citati solo quando necessario (ad esempio,<br/>quando i valori contengono caratteri speciali come '"', '\n' o caratteri separatori).<br/> L'impostazione predefinita è falsa.|
| [quote_type](/cells/python-net/it/aspose.cells/txtsaveoptions/quote_type) | Ottiene o imposta la modalità di virgolette dei valori nel file di testo esportato.|
| [format_strategy](/cells/python-net/it/aspose.cells/txtsaveoptions/format_strategy) | Ottiene e imposta la strategia di formato durante l'esportazione del valore della cella come stringa.|
| [light_cells_data_provider](/cells/python-net/it/aspose.cells/txtsaveoptions/light_cells_data_provider) | Il fornitore di dati per il salvataggio della cartella di lavoro in modalità Light.|
| [trim_leading_blank_row_and_column](/cells/python-net/it/aspose.cells/txtsaveoptions/trim_leading_blank_row_and_column) | Indica se le righe e le colonne vuote iniziali devono essere tagliate come fa MS Excel.<br/> L'impostazione predefinita è vera.|
| [trim_tailing_blank_cells](/cells/python-net/it/aspose.cells/txtsaveoptions/trim_tailing_blank_cells) | Indica se le celle vuote in coda in una riga devono essere tagliate. L'impostazione predefinita è falsa.|
| [keep_separators_for_blank_row](/cells/python-net/it/aspose.cells/txtsaveoptions/keep_separators_for_blank_row) |Indica se devono essere visualizzati i separatori per la riga vuota.<br/> Il valore predefinito è false, quindi per impostazione predefinita il contenuto della riga vuota sarà vuoto.|
| [export_area](/cells/python-net/it/aspose.cells/txtsaveoptions/export_area) | L'intervallo di celle da esportare.|
| [export_quote_prefix](/cells/python-net/it/aspose.cells/txtsaveoptions/export_quote_prefix) | Indica se il segno di virgoletta singola deve essere esportato come parte del valore di una cella<br/> quando [`Style.quote_prefix`](/cells/python-net/it/aspose.cells/style#quote_prefix) è vero per questo. L'impostazione predefinita è falsa.|
| [export_all_sheets](/cells/python-net/it/aspose.cells/txtsaveoptions/export_all_sheets) | Indica se esportare tutti i fogli nel file di testo.<br/> Se è falso, esporta solo il foglio attivo, proprio come MS Excel.|



###  Guarda anche
* modulo [`aspose.cells`](..)
* classe [`SaveOptions`](/cells/python-net/it/aspose.cells/saveoptions)
* classe [`TxtSaveOptions`](/cells/python-net/it/aspose.cells/txtsaveoptions)
