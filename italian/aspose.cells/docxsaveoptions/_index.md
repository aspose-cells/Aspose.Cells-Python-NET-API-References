---
title: DocxSaveOptions classe
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 510
url: /it/aspose.cells/docxsaveoptions/
is_root: false
---
##  DocxSaveOptions classe
Rappresenta le opzioni di salvataggio del file .docx.



**Eredità:** [`DocxSaveOptions`](/cells/python-net/aspose.cells/docxsaveoptions) → 
[`PaginatedSaveOptions`](/cells/python-net/aspose.cells/paginatedsaveoptions) → 
[`SaveOptions`](/cells/python-net/it/aspose.cells/saveoptions)



Il tipo DocxSaveOptions espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [__init__](/cells/python-net/it/aspose.cells/docxsaveoptions/__init__/#) | Rappresenta le opzioni di salvataggio del file .docx.|
| [__init__](/cells/python-net/it/aspose.cells/docxsaveoptions/__init__/#bool) | Rappresenta le opzioni di salvataggio del file .docx.|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [save_format](/cells/python-net/it/aspose.cells/docxsaveoptions/save_format) | Ottiene il formato del file di salvataggio.|
| [clear_data](/cells/python-net/it/aspose.cells/docxsaveoptions/clear_data) | Rendi vuota la cartella di lavoro dopo aver salvato il file.|
| [cached_file_folder](/cells/python-net/it/aspose.cells/docxsaveoptions/cached_file_folder) | La cartella dei file memorizzati nella cache viene utilizzata per archiviare alcuni dati di grandi dimensioni.|
| [validate_merged_areas](/cells/python-net/it/aspose.cells/docxsaveoptions/validate_merged_areas) | Indica se convalidare le celle unite prima di salvare il file.|
| [merge_areas](/cells/python-net/it/aspose.cells/docxsaveoptions/merge_areas) | Indica se unire le aree di formattazione condizionale e di validazione prima di salvare il file.|
| [create_directory](/cells/python-net/it/aspose.cells/docxsaveoptions/create_directory) | Se vero e la directory non esiste, la directory verrà creata automaticamente prima di salvare il file.|
| [sort_names](/cells/python-net/it/aspose.cells/docxsaveoptions/sort_names) | Indica se ordinare i nomi definiti prima di salvare il file.|
| [sort_external_names](/cells/python-net/it/aspose.cells/docxsaveoptions/sort_external_names) | Indica se ordinare i nomi definiti esterni prima di salvare il file.|
| [refresh_chart_cache](/cells/python-net/it/aspose.cells/docxsaveoptions/refresh_chart_cache) | Indica se aggiornare i dati della cache del grafico|
| [warning_callback](/cells/python-net/it/aspose.cells/docxsaveoptions/warning_callback) | Ottiene o imposta la richiamata di avviso.|
| [update_smart_art](/cells/python-net/it/aspose.cells/docxsaveoptions/update_smart_art) | Indica se aggiornare l'impostazione della grafica intelligente.<br/> Il valore predefinito è falso.|
| [default_font](/cells/python-net/it/aspose.cells/docxsaveoptions/default_font) | Quando i caratteri in Excel sono Unicode e non sono impostati con il carattere corretto nello stile cella,<br/>Possono apparire come blocchi in pdf,immagine.<br/>Imposta il DefaultFont come MingLiu o MS Gothic per mostrare questi caratteri.<br/> Se questa proprietà non è impostata, Aspose.Cells utilizzerà il carattere predefinito del sistema per mostrare questi caratteri Unicode.|
| [check_workbook_default_font](/cells/python-net/it/aspose.cells/docxsaveoptions/check_workbook_default_font) | Quando i caratteri in Excel sono Unicode e non sono impostati con il carattere corretto nello stile cella,<br/>Possono apparire come blocchi in pdf,immagine.<br/> Impostalo su true per provare a utilizzare il carattere predefinito della cartella di lavoro per mostrare prima questi caratteri.|
| [check_font_compatibility](/cells/python-net/it/aspose.cells/docxsaveoptions/check_font_compatibility) | Indica se verificare la compatibilità dei caratteri per ogni carattere del testo.|
| [is_font_substitution_char_granularity](/cells/python-net/it/aspose.cells/docxsaveoptions/is_font_substitution_char_granularity) |Indica se sostituire il carattere del carattere solo quando il carattere della cella non è compatibile con esso.|
| [one_page_per_sheet](/cells/python-net/it/aspose.cells/docxsaveoptions/one_page_per_sheet) | Se OnePagePerSheet è true , tutto il contenuto di un foglio verrà visualizzato in una sola pagina come risultato.<br/> Il formato carta di pagesetup non sarà valido, così come le altre impostazioni di pagesetup<br/> avrà comunque effetto.|
| [all_columns_in_one_page_per_sheet](/cells/python-net/it/aspose.cells/docxsaveoptions/all_columns_in_one_page_per_sheet) | Se AllColumnsInOnePagePerSheet è true , tutto il contenuto delle colonne di un foglio verrà visualizzato in una sola pagina come risultato.<br/> La larghezza del formato carta di pagesetup verrà ignorata e le altre impostazioni di pagesetup<br/> avrà comunque effetto.|
| [ignore_error](/cells/python-net/it/aspose.cells/docxsaveoptions/ignore_error) | Indica se è necessario nascondere l'errore durante il rendering.<br/> L'errore può essere un errore nella forma, nell'immagine, nel rendering del grafico, ecc.|
| [output_blank_page_when_nothing_to_print](/cells/python-net/it/aspose.cells/docxsaveoptions/output_blank_page_when_nothing_to_print) | Indica se stampare una pagina vuota quando non c'è nulla da stampare.|
| [page_index](/cells/python-net/it/aspose.cells/docxsaveoptions/page_index) | Ottiene o imposta l'indice in base 0 della prima pagina da salvare.|
| [page_count](/cells/python-net/it/aspose.cells/docxsaveoptions/page_count) | Ottiene o imposta il numero di pagine da salvare.|
| [printing_page_type](/cells/python-net/it/aspose.cells/docxsaveoptions/printing_page_type) | Indica quali pagine non verranno stampate.|
| [gridline_type](/cells/python-net/it/aspose.cells/docxsaveoptions/gridline_type) | Ottiene o imposta il tipo di linea della griglia.|
| [text_cross_type](/cells/python-net/it/aspose.cells/docxsaveoptions/text_cross_type) | Ottiene o imposta la visualizzazione del tipo di testo quando la larghezza del testo è maggiore della larghezza della cella.|
| [default_edit_language](/cells/python-net/it/aspose.cells/docxsaveoptions/default_edit_language) | Ottiene o imposta la lingua di modifica predefinita.|
| [sheet_set](/cells/python-net/it/aspose.cells/docxsaveoptions/sheet_set) |Ottiene o imposta i fogli di cui eseguire il rendering. Per impostazione predefinita sono tutti i fogli visibili nella cartella di lavoro: [`SheetSet.visible`](/cells/python-net/it/aspose.cells.rendering/sheetset#visible).|
| [draw_object_event_handler](/cells/python-net/it/aspose.cells/docxsaveoptions/draw_object_event_handler) | Implementa questa interfaccia per ottenere DrawObject e Bound durante il rendering.|
| [page_saving_callback](/cells/python-net/it/aspose.cells/docxsaveoptions/page_saving_callback) | Controlla/indica l'avanzamento del processo di salvataggio della pagina.|
| [emf_render_setting](/cells/python-net/it/aspose.cells/docxsaveoptions/emf_render_setting) | Impostazione per il rendering del metafile Emf.|



###  Guarda anche
* modulo [`aspose.cells`](..)
* classe [`DocxSaveOptions`](/cells/python-net/it/aspose.cells/docxsaveoptions)
* classe [`PaginatedSaveOptions`](/cells/python-net/it/aspose.cells/paginatedsaveoptions)
* classe [`SaveOptions`](/cells/python-net/it/aspose.cells/saveoptions)
