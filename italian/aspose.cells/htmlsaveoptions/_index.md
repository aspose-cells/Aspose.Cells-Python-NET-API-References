---
title: HtmlSaveOptions classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 790
url: /it/aspose.cells/htmlsaveoptions/
is_root: false
---
##  HtmlSaveOptions classe
Rappresenta le opzioni per salvare il file HTML.



**Eredità:** [`HtmlSaveOptions`](/cells/python-net/aspose.cells/htmlsaveoptions) → 
[`SaveOptions`](/cells/python-net/it/aspose.cells/saveoptions)



Il tipo HtmlSaveOptions espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [`__init__(self)`](/cells/python-net/it/aspose.cells/htmlsaveoptions/__init__/#) | Crea opzioni per salvare il file HTML.|
| [`__init__(self, save_format)`](/cells/python-net/it/aspose.cells/htmlsaveoptions/__init__/#aspose.cells.saveformat) | Crea opzioni per salvare il file htm.|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [save_format](/cells/python-net/it/aspose.cells/htmlsaveoptions/save_format) | Ottiene il formato del file di salvataggio.|
| [clear_data](/cells/python-net/it/aspose.cells/htmlsaveoptions/clear_data) | Dopo aver salvato il file, svuotare la cartella di lavoro.|
| [cached_file_folder](/cells/python-net/it/aspose.cells/htmlsaveoptions/cached_file_folder) | Cartella per i file temporanei che possono essere utilizzati come cache di dati.|
| [validate_merged_areas](/cells/python-net/it/aspose.cells/htmlsaveoptions/validate_merged_areas) | Indica se convalidare le celle unite prima di salvare il file.|
| [merge_areas](/cells/python-net/it/aspose.cells/htmlsaveoptions/merge_areas) | Indica se unire le aree di formattazione condizionale e convalida prima di salvare il file.|
| [create_directory](/cells/python-net/it/aspose.cells/htmlsaveoptions/create_directory) | Se è vero e la directory non esiste, la directory verrà creata automaticamente prima di salvare il file.|
| [sort_names](/cells/python-net/it/aspose.cells/htmlsaveoptions/sort_names) |Indica se ordinare i nomi definiti prima di salvare il file.|
| [sort_external_names](/cells/python-net/it/aspose.cells/htmlsaveoptions/sort_external_names) | Indica se ordinare i nomi definiti esternamente prima di salvare il file.|
| [refresh_chart_cache](/cells/python-net/it/aspose.cells/htmlsaveoptions/refresh_chart_cache) | Indica se aggiornare i dati della cache del grafico|
| [check_excel_restriction](/cells/python-net/it/aspose.cells/htmlsaveoptions/check_excel_restriction) | Se verificare la restrizione del file Excel quando l'utente modifica celle con oggetti correlati.<br/>Ad esempio, Excel non consente di immettere valori stringa più lunghi di 32K.<br/> Se si immette un valore più lungo di 32K, questo verrà troncato.|
| [update_smart_art](/cells/python-net/it/aspose.cells/htmlsaveoptions/update_smart_art) | Indica se aggiornare l'impostazione SmartArt.<br/> Il valore predefinito è falso.|
| [encrypt_document_properties](/cells/python-net/it/aspose.cells/htmlsaveoptions/encrypt_document_properties) | Indica se crittografare le proprietà del documento quando si salva come file .xls.<br/> Il valore predefinito è vero.|
| [ignore_invisible_shapes](/cells/python-net/it/aspose.cells/htmlsaveoptions/ignore_invisible_shapes) | Indicare se esportare le forme non visibili|
| [page_title](/cells/python-net/it/aspose.cells/htmlsaveoptions/page_title) | Il titolo della pagina HTML.<br/> Solo per il salvataggio nel flusso HTML.|
| [attached_files_directory](/cells/python-net/it/aspose.cells/htmlsaveoptions/attached_files_directory) | La directory in cui verranno salvati i file allegati.<br/> Solo per il salvataggio nel flusso HTML.|
| [attached_files_url_prefix](/cells/python-net/it/aspose.cells/htmlsaveoptions/attached_files_url_prefix) | Specificare il prefisso URL dei file allegati, ad esempio l'immagine nel file HTML.<br/> Solo per il salvataggio nel flusso HTML.|
| [default_font_name](/cells/python-net/it/aspose.cells/htmlsaveoptions/default_font_name) | Specificare il nome del font predefinito per l'esportazione HTML, il font predefinito verrà utilizzato quando il font dello stile non esiste,<br/>Se questa proprietà è null, Aspose.Cells utilizzerà un font universale che ha la stessa famiglia del font originale,<br/> il valore predefinito è null.|
| [add_generic_font](/cells/python-net/it/aspose.cells/htmlsaveoptions/add_generic_font) |Indica se aggiungere un font generico a CSS font-family.<br/> Il valore predefinito è vero|
| [worksheet_scalable](/cells/python-net/it/aspose.cells/htmlsaveoptions/worksheet_scalable) | Indica se si desidera ingrandire o ridurre l'HTML tramite il livello di zoom del foglio di lavoro quando si salva il file in HTML; il valore predefinito è falso.|
| [is_export_comments](/cells/python-net/it/aspose.cells/htmlsaveoptions/is_export_comments) | Indica se esportare i commenti durante il salvataggio del file in HTML; il valore predefinito è falso.|
| [export_comments_type](/cells/python-net/it/aspose.cells/htmlsaveoptions/export_comments_type) | Rappresenta il tipo di esportazione dei commenti nei file HTML.|
| [disable_downlevel_revealed_comments](/cells/python-net/it/aspose.cells/htmlsaveoptions/disable_downlevel_revealed_comments) | Indica se disabilitare i commenti condizionali rivelati di livello inferiore durante l'esportazione del file in HTML; il valore predefinito è falso.|
| [is_exp_image_to_temp_dir](/cells/python-net/it/aspose.cells/htmlsaveoptions/is_exp_image_to_temp_dir) | Indica se esportare i file immagine nella directory temporanea.<br/> Solo per il salvataggio nel flusso HTML.|
| [image_scalable](/cells/python-net/it/aspose.cells/htmlsaveoptions/image_scalable) | Indica se utilizzare un'unità scalabile per descrivere la larghezza dell'immagine<br/>quando si utilizza un'unità scalabile per descrivere la larghezza della colonna.<br/> Il valore predefinito è vero.|
| [width_scalable](/cells/python-net/it/aspose.cells/htmlsaveoptions/width_scalable) | Indica se esportare la larghezza della colonna in unità di scala in HTML.<br/> Il valore predefinito è falso.|
| [export_single_tab](/cells/python-net/it/aspose.cells/htmlsaveoptions/export_single_tab) | Indica se esportare la singola scheda quando il file ha un solo foglio di lavoro.<br/> Il valore predefinito è falso.|
| [export_images_as_base64](/cells/python-net/it/aspose.cells/htmlsaveoptions/export_images_as_base64) | Specifica se le immagini vengono salvate nel formato Base64 HTML, MHTML o EPUB.|
| [export_active_worksheet_only](/cells/python-net/it/aspose.cells/htmlsaveoptions/export_active_worksheet_only) | Indica se si desidera esportare solo il foglio di lavoro attivo nel file HTML.<br/>Se è vero, solo il foglio di lavoro attivo verrà esportato nel file HTML;<br/>Se falso, l'intera cartella di lavoro verrà esportata nel file HTML.<br/> Il valore predefinito è falso.|
| [export_print_area_only](/cells/python-net/it/aspose.cells/htmlsaveoptions/export_print_area_only) |Indica se si desidera esportare solo l'area di stampa in un file HTML. Il valore predefinito è "false".|
| [export_area](/cells/python-net/it/aspose.cells/htmlsaveoptions/export_area) | Ottiene o imposta la CellArea di esportazione del foglio di lavoro attivo corrente.<br/>Se si imposta questo attributo, l'area di stampa del foglio di lavoro attivo corrente verrà omessa.<br/> Quando si salva il file in formato HTML, verrà esportata solo l'area specificata.|
| [parse_html_tag_in_cell](/cells/python-net/it/aspose.cells/htmlsaveoptions/parse_html_tag_in_cell) | Indica se il tag HTML (ad esempio `<div></div>`) nella cella deve essere analizzato come valore della cella o mantenuto così com'è.<br/> Il valore predefinito è vero.|
| [html_cross_string_type](/cells/python-net/it/aspose.cells/htmlsaveoptions/html_cross_string_type) | Indica se una stringa tra celle verrà visualizzata nello stesso modo di MS Excel quando si salva un file Excel in formato HTML.<br/>Per impostazione predefinita il valore è Predefinito, quindi, per le stringhe tra celle, c'è poca differenza tra i file HTML creati da Aspose.Cells e MS Excel.<br/> Tuttavia, le prestazioni nella creazione di file HTML di grandi dimensioni, impostando il valore su Cross, sarebbero molto più veloci rispetto all'impostazione su Default o Fit2Cell.|
| [hidden_col_display_type](/cells/python-net/it/aspose.cells/htmlsaveoptions/hidden_col_display_type) | Colonna nascosta (la larghezza di questa colonna è 0) in Excel, prima di salvarla in formato HTML,<br/>se HtmlHiddenColDisplayType è "Rimuovi", la colonna nascosta non verrà visualizzata,<br/> se il valore è "Nascosto", la colonna verrebbe visualizzata ma nascosta, il valore predefinito è "Nascosto"|
| [hidden_row_display_type](/cells/python-net/it/aspose.cells/htmlsaveoptions/hidden_row_display_type) | Riga nascosta (l'altezza di questa riga è 0) in Excel, prima di salvarla in formato HTML,<br/>se HtmlHiddenRowDisplayType è "Rimuovi", la riga nascosta non verrà visualizzata,<br/>se il valore è "Nascosto", la riga verrebbe visualizzata, ma nascosta, il valore predefinito è "Nascosto"|
| [encoding](/cells/python-net/it/aspose.cells/htmlsaveoptions/encoding) | Se non impostato, utilizzare Encoding.UTF8 come tipo di codifica predefinito.|
| [image_options](/cells/python-net/it/aspose.cells/htmlsaveoptions/image_options) | Ottieni l'oggetto ImageOrPrintOptions prima di esportare|
| [save_as_single_file](/cells/python-net/it/aspose.cells/htmlsaveoptions/save_as_single_file) | Indica se salvare l'html come file singolo.<br/> Il valore predefinito è falso.|
| [show_all_sheets](/cells/python-net/it/aspose.cells/htmlsaveoptions/show_all_sheets) | Indica se visualizzare tutti i fogli quando si salva come un singolo file HTML.|
| [export_page_headers](/cells/python-net/it/aspose.cells/htmlsaveoptions/export_page_headers) | Indica se esportare le intestazioni di pagina.|
| [export_page_footers](/cells/python-net/it/aspose.cells/htmlsaveoptions/export_page_footers) | Indica se esportare le intestazioni di pagina.|
| [export_hidden_worksheet](/cells/python-net/it/aspose.cells/htmlsaveoptions/export_hidden_worksheet) | Indica se esportare il contenuto nascosto del foglio di lavoro. Il valore predefinito è true.|
| [presentation_preference](/cells/python-net/it/aspose.cells/htmlsaveoptions/presentation_preference) | Indica se è preferibile la presentazione tramite file html o mht.<br/>Il valore predefinito è falso.<br/> Se vuoi ottenere una presentazione più gradevole, imposta il valore su true.|
| [cell_css_prefix](/cells/python-net/it/aspose.cells/htmlsaveoptions/cell_css_prefix) | Ottiene e imposta il prefisso del nome css, il valore predefinito è "".|
| [table_css_id](/cells/python-net/it/aspose.cells/htmlsaveoptions/table_css_id) | Ottiene e imposta il prefisso del nome css del tipo come tr, col, td e così via, sono contenuti nell'elemento tabella<br/> che ha l'attributo specifico TableCssId. Il valore predefinito è "".|
| [is_full_path_link](/cells/python-net/it/aspose.cells/htmlsaveoptions/is_full_path_link) |Indica se utilizzare un collegamento al percorso completo in sheet00x.htm, filelist.xml e tabstrip.htm.<br/> Il valore predefinito è falso.|
| [export_worksheet_css_separately](/cells/python-net/it/aspose.cells/htmlsaveoptions/export_worksheet_css_separately) | Indica se esportare separatamente il css del foglio di lavoro. Il valore predefinito è false.|
| [export_similar_border_style](/cells/python-net/it/aspose.cells/htmlsaveoptions/export_similar_border_style) | Indica se esportare uno stile di bordo simile quando lo stile del bordo non è supportato dai browser.<br/>Se vuoi importare il file html o mht in excel, mantieni il valore predefinito.<br/> Il valore predefinito è falso.|
| [merge_empty_td_forcely](/cells/python-net/it/aspose.cells/htmlsaveoptions/merge_empty_td_forcely) | Indica se unire forzatamente l'elemento TD vuoto durante l'esportazione del file in HTML.<br/> La dimensione del file HTML verrà ridotta significativamente impostando il valore su true. Il valore predefinito è false.<br/> Se si desidera importare il file HTML in Excel o esportare linee di griglia perfette durante il salvataggio del file in HTML,<br/> si prega di mantenere il valore predefinito.|
| [merge_empty_td_type](/cells/python-net/it/aspose.cells/htmlsaveoptions/merge_empty_td_type) | L'opzione per unire celle vuote contigue (elementi td vuoti)<br/> Il valore predefinito è MergeEmptyTdType.Default.|
| [export_cell_coordinate](/cells/python-net/it/aspose.cells/htmlsaveoptions/export_cell_coordinate) | Indica se esportare le coordinate Excel delle celle non vuote durante il salvataggio del file in HTML. Il valore predefinito è "false".<br/> Se si desidera importare l'output HTML in Excel, mantenere il valore predefinito.|
| [export_extra_headings](/cells/python-net/it/aspose.cells/htmlsaveoptions/export_extra_headings) | Indica se esportare intestazioni extra quando la lunghezza del testo è maggiore della colonna visualizzata massima.<br/> Il valore predefinito è "false". Se si desidera importare il file HTML in Excel, mantenere il valore predefinito.|
| [export_headings](/cells/python-net/it/aspose.cells/htmlsaveoptions/export_headings) |Indica se esportare le intestazioni di riga e di colonna del foglio quando si salva nei file HTML.|
| [export_row_column_headings](/cells/python-net/it/aspose.cells/htmlsaveoptions/export_row_column_headings) |Indica se esportare le intestazioni di riga e di colonna del foglio quando si salva nei file HTML.|
| [export_formula](/cells/python-net/it/aspose.cells/htmlsaveoptions/export_formula) | Indica se esportare la formula quando si salva il file in formato HTML. Il valore predefinito è "true".<br/> Se si desidera importare l'output HTML in Excel, mantenere il valore predefinito.|
| [add_tooltip_text](/cells/python-net/it/aspose.cells/htmlsaveoptions/add_tooltip_text) | Indica se aggiungere testo di suggerimento quando i dati non possono essere visualizzati completamente.<br/> Il valore predefinito è falso.|
| [export_grid_lines](/cells/python-net/it/aspose.cells/htmlsaveoptions/export_grid_lines) | Indica se esportare le linee della griglia. Il valore predefinito è false.|
| [export_bogus_row_data](/cells/python-net/it/aspose.cells/htmlsaveoptions/export_bogus_row_data) | Indica se esportare dati falsi nella riga inferiore. Il valore predefinito è true. Se si desidera importare il file HTML o MHT.<br/> per eccellere, mantieni il valore predefinito.|
| [exclude_unused_styles](/cells/python-net/it/aspose.cells/htmlsaveoptions/exclude_unused_styles) | Indica se escludere gli stili non utilizzati.<br/>Per i file HTML generati, l'esclusione degli stili non utilizzati può ridurre le dimensioni del file<br/>senza influenzare gli effetti visivi. Quindi il valore predefinito di questa proprietà è true.<br/>Se l'utente ha bisogno di mantenere tutti gli stili nella cartella di lavoro per l'HTML generato (come nello scenario in cui l'utente<br/> (se in seguito è necessario ripristinare la cartella di lavoro dal codice HTML generato), impostare questa proprietà su false.|
| [export_document_properties](/cells/python-net/it/aspose.cells/htmlsaveoptions/export_document_properties) | Indica se esportare le proprietà del documento. Il valore predefinito è true. Se si desidera importare<br/> il file html o mht in excel, mantieni il valore predefinito.|
| [export_worksheet_properties](/cells/python-net/it/aspose.cells/htmlsaveoptions/export_worksheet_properties) | Indica se esportare le proprietà del foglio di lavoro. Il valore predefinito è true. Se si desidera importare<br/> il file html o mht in excel, mantieni il valore predefinito.|
| [export_workbook_properties](/cells/python-net/it/aspose.cells/htmlsaveoptions/export_workbook_properties) |Indica se esportare le proprietà della cartella di lavoro. Il valore predefinito è true. Se si desidera importare<br/> il file html o mht in excel, mantieni il valore predefinito.|
| [export_frame_scripts_and_properties](/cells/python-net/it/aspose.cells/htmlsaveoptions/export_frame_scripts_and_properties) | Indica se esportare gli script dei frame e le proprietà del documento. Il valore predefinito è true. Se si desidera importare il file HTML o MHT.<br/> per eccellere, mantieni il valore predefinito.|
| [export_data_options](/cells/python-net/it/aspose.cells/htmlsaveoptions/export_data_options) | Indica la regola per l'esportazione dei dati del file HTML. Il valore predefinito è Tutto.|
| [link_target_type](/cells/python-net/it/aspose.cells/htmlsaveoptions/link_target_type) | Indica il tipo di attributo di destinazione nel collegamento `<a>`. Il valore predefinito è HtmlLinkTargetType.Parent.|
| [is_ie_compatible](/cells/python-net/it/aspose.cells/htmlsaveoptions/is_ie_compatible) | Indica se l'output HTML è compatibile con il browser IE.<br/> Il valore predefinito è falso|
| [format_data_ignore_column_width](/cells/python-net/it/aspose.cells/htmlsaveoptions/format_data_ignore_column_width) | Indica se visualizzare tutti i dati formattati della cella quando la colonna è in overflow.<br/>Se è vero, ignora la larghezza della colonna e verranno esportati tutti i dati della cella.<br/>Se falso, i dati verranno esportati come Excel.<br/> Il valore predefinito è falso.|
| [calculate_formula](/cells/python-net/it/aspose.cells/htmlsaveoptions/calculate_formula) | Indica se calcolare le formule prima di salvare il file HTML.|
| [is_js_browser_compatible](/cells/python-net/it/aspose.cells/htmlsaveoptions/is_js_browser_compatible) | Indica se JavaScript è compatibile con i browser che non supportano JavaScript.<br/> Il valore predefinito è vero.|
| [is_mobile_compatible](/cells/python-net/it/aspose.cells/htmlsaveoptions/is_mobile_compatible) | Indica se l'output HTML è compatibile con i dispositivi mobili.<br/> Il valore predefinito è falso.|
| [css_styles](/cells/python-net/it/aspose.cells/htmlsaveoptions/css_styles) | Ottiene o imposta gli stili CSS aggiuntivi per il formattatore.<br/>Funziona solo se [`HtmlSaveOptions.save_as_single_file`](/cells/python-net/it/aspose.cells/htmlsaveoptions#save_as_single_file) è Vero.<br/><br/> CssStyles="corpo { imbottitura: 5px }";|
| [hide_overflow_wrapped_text](/cells/python-net/it/aspose.cells/htmlsaveoptions/hide_overflow_wrapped_text) |Indica se nascondere il testo in eccesso quando il formato della cella è impostato su testo a capo.<br/> Il valore predefinito è falso|
| [is_border_collapsed](/cells/python-net/it/aspose.cells/htmlsaveoptions/is_border_collapsed) | Indica se i bordi della tabella sono compressi.<br/> Il valore predefinito è vero.|
| [encode_entity_as_code](/cells/python-net/it/aspose.cells/htmlsaveoptions/encode_entity_as_code) | Indica se le entità carattere HTML vengono sostituite con codice decimale.<br/>(ad esempio "&nbsp;" viene sostituito con "&#160;").<br/> Il valore predefinito è falso.|
| [office_math_output_mode](/cells/python-net/it/aspose.cells/htmlsaveoptions/office_math_output_mode) | Indica come esportare gli oggetti OfficeMath in HTML. Il valore predefinito è Immagine.|
| [cell_name_attribute](/cells/python-net/it/aspose.cells/htmlsaveoptions/cell_name_attribute) | Specifica l'attributo che indica il CellName da scrivere.<br/>(ad esempio se il valore è "id", per la cella "A1", l'output sarà:<td id='A1'>).<br/> Il valore predefinito è null.|
| [disable_css](/cells/python-net/it/aspose.cells/htmlsaveoptions/disable_css) | Indica se vengono applicati solo gli stili in linea, senza basarsi su CSS.<br/> Il valore predefinito è falso.|
| [enable_css_custom_properties](/cells/python-net/it/aspose.cells/htmlsaveoptions/enable_css_custom_properties) | Ottimizza l'output HTML utilizzando le proprietà CSS personalizzate. Ad esempio, nel caso in cui un'immagine base64 presenti più occorrenze, con le proprietà personalizzate i dati dell'immagine devono essere salvati una sola volta, migliorando così le prestazioni del codice HTML risultante.<br/> Il valore predefinito è falso.|
| [html_version](/cells/python-net/it/aspose.cells/htmlsaveoptions/html_version) | Specifica la versione dello standard HTML da utilizzare quando si salva il formato HTML.<br/> Il valore predefinito è HtmlVersion.Default.|
| [sheet_set](/cells/python-net/it/aspose.cells/htmlsaveoptions/sheet_set) | Ottiene o imposta i fogli da visualizzare. L'impostazione predefinita è tutti i fogli visibili nella cartella di lavoro: [`SheetSet.visible`](/cells/python-net/it/aspose.cells.rendering/sheetset#visible).|



###  Guarda anche
* modulo [`aspose.cells`](..)
* classe [`HtmlSaveOptions`](/cells/python-net/it/aspose.cells/htmlsaveoptions)
* classe [`SaveOptions`](/cells/python-net/it/aspose.cells/saveoptions)
