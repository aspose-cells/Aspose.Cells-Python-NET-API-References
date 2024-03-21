---
title: EbookSaveOptions classe
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 10
url: /it/aspose.cells.saving/ebooksaveoptions/
is_root: false
---
##  EbookSaveOptions classe
Rappresenta le opzioni per salvare il file ebook.



**Eredità:** [`EbookSaveOptions`](/cells/python-net/aspose.cells.saving/ebooksaveoptions) → 
[`HtmlSaveOptions`](/cells/python-net/aspose.cells/htmlsaveoptions) → 
[`SaveOptions`](/cells/python-net/it/aspose.cells/saveoptions)



Il tipo EbookSaveOptions espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [__init__](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/__init__/#) | Crea opzioni per salvare il file ebook.|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [save_format](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/save_format) | Ottiene il formato del file di salvataggio.|
| [clear_data](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/clear_data) | Rendi vuota la cartella di lavoro dopo aver salvato il file.|
| [cached_file_folder](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/cached_file_folder) | La cartella dei file memorizzati nella cache viene utilizzata per archiviare alcuni dati di grandi dimensioni.|
| [validate_merged_areas](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/validate_merged_areas) | Indica se convalidare le celle unite prima di salvare il file.|
| [merge_areas](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/merge_areas) | Indica se unire le aree di formattazione condizionale e di validazione prima di salvare il file.|
| [create_directory](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/create_directory) | Se vero e la directory non esiste, la directory verrà creata automaticamente prima di salvare il file.|
| [sort_names](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/sort_names) | Indica se ordinare i nomi definiti prima di salvare il file.|
| [sort_external_names](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/sort_external_names) | Indica se ordinare i nomi definiti esterni prima di salvare il file.|
| [refresh_chart_cache](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/refresh_chart_cache) | Indica se aggiornare i dati della cache del grafico|
| [warning_callback](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/warning_callback) | Ottiene o imposta la richiamata di avviso.|
| [update_smart_art](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/update_smart_art) | Indica se aggiornare l'impostazione della grafica intelligente.
| [ignore_invisible_shapes](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/ignore_invisible_shapes) | Indicare se esportare le forme non visibili|
| [page_title](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/page_title) | Il titolo della pagina html.
| [attached_files_directory](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/attached_files_directory) | La directory in cui verranno salvati i file allegati.
| [attached_files_url_prefix](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/attached_files_url_prefix) | Specificare il prefisso URL dei file allegati come l'immagine nel file html.
| [default_font_name](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/default_font_name) | Specificare il nome del carattere predefinito per l'esportazione dell'HTML, il carattere predefinito verrà utilizzato quando il carattere dello stile non esiste,
| [worksheet_scalable](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/worksheet_scalable) | Indica se si esegue lo zoom avanti o indietro dell'HTML tramite il livello di zoom del foglio di lavoro durante il salvataggio del file in HTML, il valore predefinito è false.|
| [is_export_comments](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/is_export_comments) |Indica se si esportano commenti durante il salvataggio del file in html, il valore predefinito è false.|
| [export_comments_type](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/export_comments_type) | Rappresenta il tipo di esportazione dei commenti nei file html.|
| [disable_downlevel_revealed_comments](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/disable_downlevel_revealed_comments) | Indica se disabilitare i commenti condizionali rivelati di livello inferiore durante l'esportazione del file in html, il valore predefinito è false.|
| [is_exp_image_to_temp_dir](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/is_exp_image_to_temp_dir) | Indica se esportare i file di immagine nella directory temporanea.
| [image_scalable](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/image_scalable) | Indica se si utilizza un'unità scalabile per descrivere la larghezza dell'immagine
| [width_scalable](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/width_scalable) | Indica se esportare la larghezza della colonna in unità di scala in html.
| [export_single_tab](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/export_single_tab) | Indica se esportare la singola scheda quando il file ha un solo foglio di lavoro.
| [export_images_as_base64](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/export_images_as_base64) | Specifica se le immagini vengono salvate in formato Base64 su HTML, MHTML o EPUB.|
| [export_active_worksheet_only](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/export_active_worksheet_only) | Indica se si sta esportando solo il foglio di lavoro attivo in un file html.
| [export_print_area_only](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/export_print_area_only) | Indica se si esporta solo l'area di stampa in un file html. Il valore predefinito è falso.|
| [export_area](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/export_area) | Ottiene o imposta la CellArea di esportazione del foglio di lavoro attivo corrente.
| [parse_html_tag_in_cell](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/parse_html_tag_in_cell) |Indica se il tag html (come `<div></div>`) nella cella deve essere analizzato come valore di cella o conservato così com'è.
| [html_cross_string_type](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/html_cross_string_type) | Indica se una stringa incrociata verrà visualizzata allo stesso modo di MS Excel quando si salva un file Excel in formato html.
| [hidden_col_display_type](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/hidden_col_display_type) | Colonna nascosta (la larghezza di questa colonna è 0) in Excel, prima di salvarla in formato html,
| [hidden_row_display_type](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/hidden_row_display_type) | Riga nascosta (l'altezza di questa riga è 0) in Excel, prima di salvarla in formato html,
| [encoding](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/encoding) | Se non impostato, utilizza Encoding.UTF8 come tipo di codifica predefinito.|
| [export_object_listener](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/export_object_listener) | Ottiene o imposta ExportObjectListener per l'esportazione di oggetti.|
| [file_path_provider](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/file_path_provider) |Ottiene o imposta IFilePathProvider per esportare separatamente il foglio di lavoro in HTML.|
| [stream_provider](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/stream_provider) | Ottiene o imposta IStreamProvider per l'esportazione di oggetti.|
| [image_options](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/image_options) | Ottieni l'oggetto ImageOrPrintOptions prima dell'esportazione|
| [save_as_single_file](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/save_as_single_file) | Indica se salvare l'html come file singolo.
| [show_all_sheets](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/show_all_sheets) | Indica se mostrare tutti i fogli durante il salvataggio come singolo file html.|
| [export_page_headers](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/export_page_headers) | Indica se esportare le intestazioni di pagina.|
| [export_page_footers](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/export_page_footers) | Indica se esportare le intestazioni di pagina.|
| [export_hidden_worksheet](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/export_hidden_worksheet) | Indica se si sta esportando il contenuto del foglio di lavoro nascosto. Il valore predefinito è true.|
| [presentation_preference](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/presentation_preference) | Indica se il file html o mht è la preferenza di presentazione.
| [cell_css_prefix](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/cell_css_prefix) | Ottiene e imposta il prefisso del nome CSS, il valore predefinito è "".|
| [table_css_id](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/table_css_id) | Ottiene e imposta il prefisso del tipo nome css come tr,col,td e così via, sono contenuti nell'elemento table
| [is_full_path_link](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/is_full_path_link) | Indica se si utilizza il collegamento al percorso completo in sheet00x.htm, filelist.xml e tabstrip.htm.
| [export_worksheet_css_separately](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/export_worksheet_css_separately) |Indica se esportare il foglio di lavoro CSS separatamente. Il valore predefinito è false.|
| [export_similar_border_style](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/export_similar_border_style) | Indica se esportare lo stile del bordo simile quando lo stile del bordo non è supportato dai browser.
| [merge_empty_td_forcely](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/merge_empty_td_forcely) | Indica se unire forzatamente l'elemento TD vuoto durante l'esportazione del file in html.
| [merge_empty_td_type](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/merge_empty_td_type) | Indica se l'elemento TD vuoto verrà unito allo stesso modo di MS Excel quando si salva un file Excel in formato html.
| [export_cell_coordinate](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/export_cell_coordinate) | Indica se esportare le coordinate Excel delle celle non vuote durante il salvataggio del file in html. Il valore predefinito è falso.
| [export_extra_headings](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/export_extra_headings) | Indica se esportare intestazioni aggiuntive quando la lunghezza del testo è maggiore della colonna massima di visualizzazione.
| [export_headings](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/export_headings) |Indica se esporta le intestazioni di riga e colonna del foglio durante il salvataggio nei file HTML.|
| [export_row_column_headings](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/export_row_column_headings) |Indica se esporta le intestazioni di riga e colonna del foglio durante il salvataggio nei file HTML.|
| [export_formula](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/export_formula) | Indica se esportare la formula durante il salvataggio del file in html. Il valore predefinito è vero.
| [add_tooltip_text](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/add_tooltip_text) | Indica se aggiungere testo di descrizione comando quando i dati non possono essere visualizzati completamente.
| [export_grid_lines](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/export_grid_lines) | Indica se esportare la griglia. Il valore predefinito è false.|
| [export_bogus_row_data](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/export_bogus_row_data) | Indica se si stanno esportando dati fasulli della riga inferiore. Il valore predefinito è true.Se desideri importare il file html o mht
| [exclude_unused_styles](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/exclude_unused_styles) | Indica se esclude gli stili non utilizzati.
| [export_document_properties](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/export_document_properties) | Indica se si stanno esportando le proprietà del documento. Il valore predefinito è true. Se si desidera importare
| [export_worksheet_properties](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/export_worksheet_properties) | Indica se si stanno esportando le proprietà del foglio di lavoro. Il valore predefinito è true. Se si desidera importare
| [export_workbook_properties](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/export_workbook_properties) |Indica se esportare le proprietà della cartella di lavoro. Il valore predefinito è true. Se si desidera importare
| [export_frame_scripts_and_properties](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/export_frame_scripts_and_properties) | Indica se esportare script di frame e proprietà del documento. Il valore predefinito è true.Se desideri importare il file html o mht
| [export_data_options](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/export_data_options) | Indica la regola di esportazione dei dati del file html. Il valore predefinito è Tutti.|
| [link_target_type](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/link_target_type) | Indicando il tipo di attributo target nel collegamento `<a>`. Il valore predefinito è HtmlLinkTargetType.Parent.|
| [is_ie_compatible](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/is_ie_compatible) | Indica se l'output HTML è compatibile con il browser IE.
| [format_data_ignore_column_width](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/format_data_ignore_column_width) | Indica se mostrare tutti i dati formattati della cella in caso di overflow della colonna.
| [calculate_formula](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/calculate_formula) | Indica se calcolare le formule prima di salvare il file html.|
| [is_js_browser_compatible](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/is_js_browser_compatible) | Indica se JavaScript è compatibile con i browser che non supportano JavaScript.
| [is_mobile_compatible](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/is_mobile_compatible) | Indica se l'uscita HTML è compatibile con i dispositivi mobili.
| [css_styles](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions/css_styles) | Ottiene o imposta gli stili CSS aggiuntivi per il formattatore.



###  Guarda anche
* modulo [`aspose.cells.saving`](..)
* classe [`EbookSaveOptions`](/cells/python-net/it/aspose.cells.saving/ebooksaveoptions)
* classe [`HtmlSaveOptions`](/cells/python-net/it/aspose.cells/htmlsaveoptions)
* classe [`SaveOptions`](/cells/python-net/it/aspose.cells/saveoptions)