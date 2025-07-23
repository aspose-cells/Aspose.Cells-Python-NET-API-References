---
title: TxtSaveOptions classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 1500
url: /it/aspose.cells/txtsaveoptions/
is_root: false
---
##  TxtSaveOptions classe
Rappresenta le opzioni di salvataggio per i formati di testo csv/delimitati da tabulazioni/altri.



**Eredità:** [`TxtSaveOptions`](/cells/python-net/aspose.cells/txtsaveoptions) → 
[`SaveOptions`](/cells/python-net/it/aspose.cells/saveoptions)



Il tipo TxtSaveOptions espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [`__init__(self)`](/cells/python-net/it/aspose.cells/txtsaveoptions/__init__/#) | Crea opzioni di salvataggio del file di testo.|
| [`__init__(self, save_format)`](/cells/python-net/it/aspose.cells/txtsaveoptions/__init__/#aspose.cells.saveformat) | Crea opzioni di salvataggio del file di testo.|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [save_format](/cells/python-net/it/aspose.cells/txtsaveoptions/save_format) | Ottiene il formato del file di salvataggio.|
| [clear_data](/cells/python-net/it/aspose.cells/txtsaveoptions/clear_data) | Dopo aver salvato il file, svuotare la cartella di lavoro.|
| [cached_file_folder](/cells/python-net/it/aspose.cells/txtsaveoptions/cached_file_folder) | Cartella per i file temporanei che possono essere utilizzati come cache di dati.|
| [validate_merged_areas](/cells/python-net/it/aspose.cells/txtsaveoptions/validate_merged_areas) | Indica se convalidare le celle unite prima di salvare il file.|
| [merge_areas](/cells/python-net/it/aspose.cells/txtsaveoptions/merge_areas) | Indica se unire le aree di formattazione condizionale e convalida prima di salvare il file.|
| [create_directory](/cells/python-net/it/aspose.cells/txtsaveoptions/create_directory) | Se è vero e la directory non esiste, la directory verrà creata automaticamente prima di salvare il file.|
| [sort_names](/cells/python-net/it/aspose.cells/txtsaveoptions/sort_names) |Indica se ordinare i nomi definiti prima di salvare il file.|
| [sort_external_names](/cells/python-net/it/aspose.cells/txtsaveoptions/sort_external_names) | Indica se ordinare i nomi definiti esternamente prima di salvare il file.|
| [refresh_chart_cache](/cells/python-net/it/aspose.cells/txtsaveoptions/refresh_chart_cache) | Indica se aggiornare i dati della cache del grafico|
| [check_excel_restriction](/cells/python-net/it/aspose.cells/txtsaveoptions/check_excel_restriction) | Se verificare la restrizione del file Excel quando l'utente modifica celle con oggetti correlati.<br/>Ad esempio, Excel non consente di immettere valori stringa più lunghi di 32K.<br/> Se si immette un valore più lungo di 32K, questo verrà troncato.|
| [update_smart_art](/cells/python-net/it/aspose.cells/txtsaveoptions/update_smart_art) | Indica se aggiornare l'impostazione SmartArt.<br/> Il valore predefinito è falso.|
| [encrypt_document_properties](/cells/python-net/it/aspose.cells/txtsaveoptions/encrypt_document_properties) | Indica se crittografare le proprietà del documento quando si salva come file .xls.<br/> Il valore predefinito è vero.|
| [separator](/cells/python-net/it/aspose.cells/txtsaveoptions/separator) | Ottiene e imposta il delimitatore di caratteri del file di testo.|
| [separator_string](/cells/python-net/it/aspose.cells/txtsaveoptions/separator_string) | Ottiene e imposta un valore stringa come separatore.|
| [encoding](/cells/python-net/it/aspose.cells/txtsaveoptions/encoding) | Ottiene e imposta la codifica predefinita.|
| [always_quoted](/cells/python-net/it/aspose.cells/txtsaveoptions/always_quoted) | Indica se aggiungere sempre '"' per ogni campo.<br/>Se è vero, tutti i valori saranno tra virgolette;<br/>Se falso, i valori verranno citati solo quando necessario (ad esempio,<br/>quando i valori contengono caratteri speciali come '"', '\n' o carattere separatore).<br/> Il valore predefinito è falso.|
| [quote_type](/cells/python-net/it/aspose.cells/txtsaveoptions/quote_type) |Ottiene o imposta come racchiudere i valori tra virgolette nel file di testo esportato.|
| [format_strategy](/cells/python-net/it/aspose.cells/txtsaveoptions/format_strategy) | Ottiene e imposta la strategia di formato durante l'esportazione del valore della cella come stringa.|
| [trim_leading_blank_row_and_column](/cells/python-net/it/aspose.cells/txtsaveoptions/trim_leading_blank_row_and_column) | Indica se le righe e le colonne vuote iniziali devono essere tagliate, come fa Microsoft Excel.<br/> L'impostazione predefinita è vero.|
| [trim_tailing_blank_cells](/cells/python-net/it/aspose.cells/txtsaveoptions/trim_tailing_blank_cells) | Indica se le celle vuote in coda in una riga devono essere eliminate. Il valore predefinito è "false".|
| [keep_separators_for_blank_row](/cells/python-net/it/aspose.cells/txtsaveoptions/keep_separators_for_blank_row) | Indica se devono essere visualizzati i separatori per le righe vuote.<br/> Il valore predefinito è false, quindi per impostazione predefinita il contenuto della riga vuota sarà vuoto.|
| [export_area](/cells/python-net/it/aspose.cells/txtsaveoptions/export_area) | Intervallo di celle da esportare.|
| [export_quote_prefix](/cells/python-net/it/aspose.cells/txtsaveoptions/export_quote_prefix) | Indica se il simbolo di virgoletta singola deve essere esportato come parte del valore di una cella<br/> Quando [`Style.quote_prefix`](/cells/python-net/it/aspose.cells/style#quote_prefix) è vero per esso. Il valore predefinito è falso.|
| [export_all_sheets](/cells/python-net/it/aspose.cells/txtsaveoptions/export_all_sheets) | Indica se esportare tutti i fogli nel file di testo.<br/> Se è falso, esporta solo il foglio attivo, proprio come MS Excel.|



###  Guarda anche
* modulo [`aspose.cells`](..)
* classe [`SaveOptions`](/cells/python-net/it/aspose.cells/saveoptions)
* classe [`TxtSaveOptions`](/cells/python-net/it/aspose.cells/txtsaveoptions)
