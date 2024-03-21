---
title: PptxSaveOptions classe
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 1230
url: /it/aspose.cells/pptxsaveoptions/
is_root: false
---
##  PptxSaveOptions classe
Rappresenta le opzioni di salvataggio pptx.



**Eredità:** [`PptxSaveOptions`](/cells/python-net/aspose.cells/pptxsaveoptions) → 
[`PaginatedSaveOptions`](/cells/python-net/aspose.cells/paginatedsaveoptions) → 
[`SaveOptions`](/cells/python-net/it/aspose.cells/saveoptions)



Il tipo PptxSaveOptions espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [__init__](/cells/python-net/it/aspose.cells/pptxsaveoptions/__init__/#) | Rappresenta le opzioni di salvataggio pptx.|
| [__init__](/cells/python-net/it/aspose.cells/pptxsaveoptions/__init__/#bool) | Rappresenta le opzioni di salvataggio del file .pptx.|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [save_format](/cells/python-net/it/aspose.cells/pptxsaveoptions/save_format) | Ottiene il formato del file di salvataggio.|
| [clear_data](/cells/python-net/it/aspose.cells/pptxsaveoptions/clear_data) | Rendi vuota la cartella di lavoro dopo aver salvato il file.|
| [cached_file_folder](/cells/python-net/it/aspose.cells/pptxsaveoptions/cached_file_folder) | La cartella dei file memorizzati nella cache viene utilizzata per archiviare alcuni dati di grandi dimensioni.|
| [validate_merged_areas](/cells/python-net/it/aspose.cells/pptxsaveoptions/validate_merged_areas) | Indica se convalidare le celle unite prima di salvare il file.|
| [merge_areas](/cells/python-net/it/aspose.cells/pptxsaveoptions/merge_areas) | Indica se unire le aree di formattazione condizionale e di validazione prima di salvare il file.|
| [create_directory](/cells/python-net/it/aspose.cells/pptxsaveoptions/create_directory) | Se vero e la directory non esiste, la directory verrà creata automaticamente prima di salvare il file.|
| [sort_names](/cells/python-net/it/aspose.cells/pptxsaveoptions/sort_names) | Indica se ordinare i nomi definiti prima di salvare il file.|
| [sort_external_names](/cells/python-net/it/aspose.cells/pptxsaveoptions/sort_external_names) | Indica se ordinare i nomi definiti esterni prima di salvare il file.|
| [refresh_chart_cache](/cells/python-net/it/aspose.cells/pptxsaveoptions/refresh_chart_cache) | Indica se aggiornare i dati della cache del grafico|
| [warning_callback](/cells/python-net/it/aspose.cells/pptxsaveoptions/warning_callback) | Ottiene o imposta la richiamata di avviso.|
| [update_smart_art](/cells/python-net/it/aspose.cells/pptxsaveoptions/update_smart_art) | Indica se aggiornare l'impostazione della grafica intelligente.<br/> Il valore predefinito è falso.|
| [default_font](/cells/python-net/it/aspose.cells/pptxsaveoptions/default_font) | Quando i caratteri in Excel sono Unicode e non sono impostati con il carattere corretto nello stile cella,<br/>Possono apparire come blocchi in pdf,immagine.<br/>Imposta il DefaultFont come MingLiu o MS Gothic per mostrare questi caratteri.<br/> Se questa proprietà non è impostata, Aspose.Cells utilizzerà il carattere predefinito del sistema per mostrare questi caratteri Unicode.|
| [check_workbook_default_font](/cells/python-net/it/aspose.cells/pptxsaveoptions/check_workbook_default_font) | Quando i caratteri in Excel sono Unicode e non sono impostati con il carattere corretto nello stile cella,<br/>Possono apparire come blocchi in pdf,immagine.<br/> Impostalo su true per provare a utilizzare il carattere predefinito della cartella di lavoro per mostrare prima questi caratteri.|
| [check_font_compatibility](/cells/python-net/it/aspose.cells/pptxsaveoptions/check_font_compatibility) | Indica se verificare la compatibilità dei caratteri per ogni carattere del testo.|
| [is_font_substitution_char_granularity](/cells/python-net/it/aspose.cells/pptxsaveoptions/is_font_substitution_char_granularity) |Indica se sostituire il carattere del carattere solo quando il carattere della cella non è compatibile con esso.|
| [one_page_per_sheet](/cells/python-net/it/aspose.cells/pptxsaveoptions/one_page_per_sheet) | Se OnePagePerSheet è true , tutto il contenuto di un foglio verrà visualizzato in una sola pagina come risultato.<br/> Il formato carta di pagesetup non sarà valido, così come le altre impostazioni di pagesetup<br/> avrà comunque effetto.|
| [all_columns_in_one_page_per_sheet](/cells/python-net/it/aspose.cells/pptxsaveoptions/all_columns_in_one_page_per_sheet) | Se AllColumnsInOnePagePerSheet è true , tutto il contenuto delle colonne di un foglio verrà visualizzato in una sola pagina come risultato.<br/> La larghezza del formato carta di pagesetup verrà ignorata e le altre impostazioni di pagesetup<br/> avrà comunque effetto.|
| [ignore_error](/cells/python-net/it/aspose.cells/pptxsaveoptions/ignore_error) | Indica se è necessario nascondere l'errore durante il rendering.<br/> L'errore può essere un errore nella forma, nell'immagine, nel rendering del grafico, ecc.|
| [output_blank_page_when_nothing_to_print](/cells/python-net/it/aspose.cells/pptxsaveoptions/output_blank_page_when_nothing_to_print) | Indica se stampare una pagina vuota quando non c'è nulla da stampare.|
| [page_index](/cells/python-net/it/aspose.cells/pptxsaveoptions/page_index) | Ottiene o imposta l'indice in base 0 della prima pagina da salvare.|
| [page_count](/cells/python-net/it/aspose.cells/pptxsaveoptions/page_count) | Ottiene o imposta il numero di pagine da salvare.|
| [printing_page_type](/cells/python-net/it/aspose.cells/pptxsaveoptions/printing_page_type) | Indica quali pagine non verranno stampate.|
| [gridline_type](/cells/python-net/it/aspose.cells/pptxsaveoptions/gridline_type) | Ottiene o imposta il tipo di linea della griglia.|
| [text_cross_type](/cells/python-net/it/aspose.cells/pptxsaveoptions/text_cross_type) | Ottiene o imposta la visualizzazione del tipo di testo quando la larghezza del testo è maggiore della larghezza della cella.|
| [default_edit_language](/cells/python-net/it/aspose.cells/pptxsaveoptions/default_edit_language) | Ottiene o imposta la lingua di modifica predefinita.|
| [sheet_set](/cells/python-net/it/aspose.cells/pptxsaveoptions/sheet_set) |Ottiene o imposta i fogli di cui eseguire il rendering. Per impostazione predefinita sono tutti i fogli visibili nella cartella di lavoro: [`SheetSet.visible`](/cells/python-net/it/aspose.cells.rendering/sheetset#visible).|
| [draw_object_event_handler](/cells/python-net/it/aspose.cells/pptxsaveoptions/draw_object_event_handler) | Implementa questa interfaccia per ottenere DrawObject e Bound durante il rendering.|
| [page_saving_callback](/cells/python-net/it/aspose.cells/pptxsaveoptions/page_saving_callback) | Controlla/indica l'avanzamento del processo di salvataggio della pagina.|
| [emf_render_setting](/cells/python-net/it/aspose.cells/pptxsaveoptions/emf_render_setting) | Impostazione per il rendering del metafile Emf.|
| [ignore_hidden_rows](/cells/python-net/it/aspose.cells/pptxsaveoptions/ignore_hidden_rows) | Indica se ignorare le righe nascoste durante la conversione di Excel in PowerPoint.|
| [adjust_font_size_for_row_type](/cells/python-net/it/aspose.cells/pptxsaveoptions/adjust_font_size_for_row_type) | Rappresenta il tipo di linea di cui è necessario regolare la dimensione del carattere se l'altezza della riga è piccola.|
| [export_view_type](/cells/python-net/it/aspose.cells/pptxsaveoptions/export_view_type) | Ottiene e imposta il tipo di visualizzazione durante l'esportazione su PowerPoint.<br/> Il tipo di esportazione predefinito funziona come stampa.|



###  Guarda anche
* modulo [`aspose.cells`](..)
* classe [`PaginatedSaveOptions`](/cells/python-net/it/aspose.cells/paginatedsaveoptions)
* classe [`PptxSaveOptions`](/cells/python-net/it/aspose.cells/pptxsaveoptions)
* classe [`SaveOptions`](/cells/python-net/it/aspose.cells/saveoptions)
