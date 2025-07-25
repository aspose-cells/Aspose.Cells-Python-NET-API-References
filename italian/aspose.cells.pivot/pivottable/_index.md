---
title: PivotTable classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 230
url: /it/aspose.cells.pivot/pivottable/
is_root: false
---
##  PivotTable classe
Descrizione riassuntiva per PivotTable.



Il tipo PivotTable espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [is_excel_2003_compatible](/cells/python-net/it/aspose.cells.pivot/pivottable/is_excel_2003_compatible) | Specifica se la tabella pivot è compatibile con Excel2003 quando si aggiorna la tabella pivot,<br/>se vero, una stringa deve essere minore o uguale a 255 caratteri, quindi se la stringa è maggiore di 255 caratteri,<br/>verrà troncato. Se è falso, una stringa non avrà la suddetta restrizione.<br/> Il valore predefinito è vero.|
| [refreshed_by_who](/cells/python-net/it/aspose.cells.pivot/pivottable/refreshed_by_who) | Ottiene il nome dell'ultimo utente che ha aggiornato questa tabella pivot|
| [refresh_date](/cells/python-net/it/aspose.cells.pivot/pivottable/refresh_date) | Ottiene l'ultima data e ora in cui la tabella pivot è stata aggiornata.|
| [pivot_table_style_name](/cells/python-net/it/aspose.cells.pivot/pivottable/pivot_table_style_name) | Ottiene e imposta il nome dello stile della tabella pivot.|
| [pivot_table_style_type](/cells/python-net/it/aspose.cells.pivot/pivottable/pivot_table_style_type) | Ottiene e imposta lo stile della tabella pivot incorporato.|
| [column_fields](/cells/python-net/it/aspose.cells.pivot/pivottable/column_fields) | Restituisce un oggetto PivotFields attualmente visualizzato come campi di colonna.|
| [row_fields](/cells/python-net/it/aspose.cells.pivot/pivottable/row_fields) | Restituisce un oggetto PivotFields attualmente visualizzato come campi di riga.|
| [page_fields](/cells/python-net/it/aspose.cells.pivot/pivottable/page_fields) | Restituisce un oggetto PivotFields attualmente visualizzato come campi di pagina.|
| [data_fields](/cells/python-net/it/aspose.cells.pivot/pivottable/data_fields) | Ottiene un oggetto PivotField che rappresenta tutti i campi dati in una tabella pivot.<br/>Di sola lettura. Verrebbe inizializzato solo se ci sono due o più campi dati in DataPiovtFiels.<br/> Serve solo per aggiungere DataPivotField all'area riga/colonna della tabella pivot. L'impostazione predefinita è nell'area riga.|
| [data_field](/cells/python-net/it/aspose.cells.pivot/pivottable/data_field) |Ottiene un oggetto [`PivotField`](/cells/python-net/it/aspose.cells.pivot/pivotfield) che rappresenta tutti i campi dati in una tabella pivot.<br/>Di sola lettura.<br/>Verrà creato solo se nell'area Dati sono presenti due o più campi dati.<br/> Di default, si trova nell'area di riga. È possibile trascinarlo nell'area di riga/colonna con il metodo PivotTable.AddFieldToArea().|
| [base_fields](/cells/python-net/it/aspose.cells.pivot/pivottable/base_fields) | Restituisce tutti i campi pivot di base nella tabella pivot.|
| [pivot_filters](/cells/python-net/it/aspose.cells.pivot/pivottable/pivot_filters) | Restituisce tutti i filtri dei campi pivot nella tabella pivot.|
| [column_range](/cells/python-net/it/aspose.cells.pivot/pivottable/column_range) | Restituisce un oggetto CellArea che rappresenta l'intervallo<br/> che contiene l'area delle colonne nel rapporto di tabella pivot. Di sola lettura.|
| [row_range](/cells/python-net/it/aspose.cells.pivot/pivottable/row_range) | Restituisce un oggetto CellArea che rappresenta l'intervallo<br/> che contiene l'area delle righe nel report della tabella pivot. Di sola lettura.|
| [data_body_range](/cells/python-net/it/aspose.cells.pivot/pivottable/data_body_range) | Restituisce un oggetto [`CellArea`](/cells/python-net/it/aspose.cells/cellarea) che rappresenta l'intervallo che contiene l'area dati<br/> nell'elenco tra la riga di intestazione e la riga di inserimento. Di sola lettura.|
| [table_range1](/cells/python-net/it/aspose.cells.pivot/pivottable/table_range1) | Restituisce un oggetto CellArea che rappresenta l'intervallo contenente l'intero report di tabella pivot,<br/> ma non include i campi pagina. Di sola lettura.|
| [table_range2](/cells/python-net/it/aspose.cells.pivot/pivottable/table_range2) | Restituisce un oggetto CellArea che rappresenta l'intervallo contenente l'intero report di tabella pivot,<br/> include campi di pagina. Sola lettura.|
| [is_grid_drop_zones](/cells/python-net/it/aspose.cells.pivot/pivottable/is_grid_drop_zones) | Indica se il report della tabella pivot visualizza il layout classico della tabella pivot.<br/> (consente di trascinare i campi nella griglia)|
| [show_column_grand_totals](/cells/python-net/it/aspose.cells.pivot/pivottable/show_column_grand_totals) |Indica se visualizzare i totali generali per le colonne di questa tabella pivot.|
| [show_row_grand_totals](/cells/python-net/it/aspose.cells.pivot/pivottable/show_row_grand_totals) | Indica se visualizzare i totali generali per le righe della tabella pivot.|
| [column_grand](/cells/python-net/it/aspose.cells.pivot/pivottable/column_grand) | Indica se il report della tabella pivot mostra i totali generali per le colonne.|
| [row_grand](/cells/python-net/it/aspose.cells.pivot/pivottable/row_grand) | Indica se visualizzare i totali generali per le righe di questa tabella pivot.|
| [display_null_string](/cells/python-net/it/aspose.cells.pivot/pivottable/display_null_string) | Indica se il report della tabella pivot visualizza una stringa personalizzata se il valore è null.|
| [null_string](/cells/python-net/it/aspose.cells.pivot/pivottable/null_string) | Ottiene la stringa visualizzata nelle celle che contengono valori nulli<br/> quando la proprietà DisplayNullString è true. Il valore predefinito è una stringa vuota.|
| [display_error_string](/cells/python-net/it/aspose.cells.pivot/pivottable/display_error_string) | Indica se il report della tabella pivot visualizza una stringa personalizzata nelle celle che contengono errori.|
| [data_field_header_name](/cells/python-net/it/aspose.cells.pivot/pivottable/data_field_header_name) | Ottiene e imposta il nome dell'intestazione del campo dell'area valore nella tabella pivot.|
| [error_string](/cells/python-net/it/aspose.cells.pivot/pivottable/error_string) | Ottiene la stringa visualizzata nelle celle che contengono errori<br/> quando la proprietà DisplayErrorString è true. Il valore predefinito è una stringa vuota.|
| [is_auto_format](/cells/python-net/it/aspose.cells.pivot/pivottable/is_auto_format) | Indica se il report della tabella pivot viene formattato automaticamente.<br/>Casella di controllo "formattazione automatica tabella" presente nell'opzione tabella pivot per Excel 2003|
| [autofit_column_width_on_update](/cells/python-net/it/aspose.cells.pivot/pivottable/autofit_column_width_on_update) | Indica se adattare automaticamente la larghezza della colonna durante l'aggiornamento|
| [auto_format_type](/cells/python-net/it/aspose.cells.pivot/pivottable/auto_format_type) | Ottiene e imposta il tipo di formattazione automatica della tabella pivot.|
| [has_blank_rows](/cells/python-net/it/aspose.cells.pivot/pivottable/has_blank_rows) | Indica se aggiungere righe vuote.<br/> Questa proprietà si applica solo ai tipi di formattazione automatica delle tabelle pivot che necessitano di aggiungere righe vuote.|
| [merge_labels](/cells/python-net/it/aspose.cells.pivot/pivottable/merge_labels) | Vero se le etichette dell'elemento della riga esterna, dell'elemento della colonna, del subtotale e del totale complessivo del report della tabella pivot specificata utilizzano celle unite.|
| [preserve_formatting](/cells/python-net/it/aspose.cells.pivot/pivottable/preserve_formatting) | Indica se la formattazione viene mantenuta quando la tabella pivot viene aggiornata o ricalcolata.|
| [show_drill](/cells/python-net/it/aspose.cells.pivot/pivottable/show_drill) | Ottiene e imposta se visualizzare i pulsanti espandi/contrai.|
| [enable_drilldown](/cells/python-net/it/aspose.cells.pivot/pivottable/enable_drilldown) | Indica se il drilldown è abilitato.|
| [enable_field_dialog](/cells/python-net/it/aspose.cells.pivot/pivottable/enable_field_dialog) | Indica se la finestra di dialogo Campo tabella pivot è disponibile<br/> quando l'utente fa doppio clic sul campo della tabella pivot.|
| [enable_field_list](/cells/python-net/it/aspose.cells.pivot/pivottable/enable_field_list) | Indica se l'elenco dei campi per la tabella pivot è disponibile nella visualizzazione di Excel.|
| [enable_wizard](/cells/python-net/it/aspose.cells.pivot/pivottable/enable_wizard) | Indica se la Creazione guidata tabella pivot è disponibile.|
| [subtotal_hidden_page_items](/cells/python-net/it/aspose.cells.pivot/pivottable/subtotal_hidden_page_items) |Indica se gli elementi del campo pagina sono nascosti nel report della tabella pivot<br/>sono inclusi nei subtotali di riga e di colonna, nei totali di blocco e nei totali generali.<br/> Il valore predefinito è False.|
| [grand_total_name](/cells/python-net/it/aspose.cells.pivot/pivottable/grand_total_name) | Restituisce l'etichetta visualizzata nell'intestazione di riga o di colonna del totale generale.<br/> Il valore predefinito è la stringa "Totale complessivo".|
| [manual_update](/cells/python-net/it/aspose.cells.pivot/pivottable/manual_update) | Indica se il report della tabella pivot viene ricalcolato solo su richiesta dell'utente.|
| [is_multiple_field_filters](/cells/python-net/it/aspose.cells.pivot/pivottable/is_multiple_field_filters) | Specifica un valore booleano che indica se è possibile impostare più filtri sui campi di una tabella pivot.|
| [allow_multiple_filters_per_field](/cells/python-net/it/aspose.cells.pivot/pivottable/allow_multiple_filters_per_field) | Specifica un valore booleano che indica se è possibile impostare più filtri sui campi di una tabella pivot.|
| [missing_items_limit](/cells/python-net/it/aspose.cells.pivot/pivottable/missing_items_limit) | Specifica un valore booleano che indica se è possibile impostare più filtri sui campi di una tabella pivot.|
| [enable_data_value_editing](/cells/python-net/it/aspose.cells.pivot/pivottable/enable_data_value_editing) | Specifica un valore booleano che indica se all'utente è consentito modificare le celle nell'area dati della tabella pivot.<br/> Abilita la modifica delle celle nell'area valori|
| [show_data_tips](/cells/python-net/it/aspose.cells.pivot/pivottable/show_data_tips) | Specifica un valore booleano che indica se visualizzare i suggerimenti per le celle di dati della tabella pivot.|
| [show_member_property_tips](/cells/python-net/it/aspose.cells.pivot/pivottable/show_member_property_tips) | Specifica un valore booleano che indica se le informazioni sulle proprietà dei membri devono essere omesse dalle descrizioni comandi della tabella pivot.|
| [show_values_row](/cells/python-net/it/aspose.cells.pivot/pivottable/show_values_row) | Indica se visualizzare la riga dei valori.|
| [show_empty_col](/cells/python-net/it/aspose.cells.pivot/pivottable/show_empty_col) | Indica se includere colonne vuote nella tabella|
| [show_empty_row](/cells/python-net/it/aspose.cells.pivot/pivottable/show_empty_row) |Indica se includere righe vuote nella tabella.|
| [field_list_sort_ascending](/cells/python-net/it/aspose.cells.pivot/pivottable/field_list_sort_ascending) | Indica se i campi nella tabella pivot sono ordinati in un ordine non predefinito nell'elenco dei campi.|
| [print_drill](/cells/python-net/it/aspose.cells.pivot/pivottable/print_drill) | Specifica un valore booleano che indica se gli indicatori di drill devono essere stampati.<br/> stampa i pulsanti espandi/contrai quando vengono visualizzati sulla tabella pivot.|
| [alt_text_title](/cells/python-net/it/aspose.cells.pivot/pivottable/alt_text_title) | Ottiene e imposta il titolo del testo alternativo.|
| [alt_text_description](/cells/python-net/it/aspose.cells.pivot/pivottable/alt_text_description) | Ottiene la descrizione del testo alternativo.|
| [name](/cells/python-net/it/aspose.cells.pivot/pivottable/name) | Ottiene il nome della tabella pivot|
| [column_header_caption](/cells/python-net/it/aspose.cells.pivot/pivottable/column_header_caption) | Ottiene la didascalia dell'intestazione di colonna della tabella pivot.|
| [indent](/cells/python-net/it/aspose.cells.pivot/pivottable/indent) | Specifica l'incremento di rientro per l'asse compatto e può essere utilizzato per impostare il layout del report su Formato compatto.|
| [row_header_caption](/cells/python-net/it/aspose.cells.pivot/pivottable/row_header_caption) | Ottiene la didascalia dell'intestazione di riga della tabella pivot.|
| [show_row_header_caption](/cells/python-net/it/aspose.cells.pivot/pivottable/show_row_header_caption) | Indica se la didascalia dell'intestazione di riga viene visualizzata nel report della tabella pivot<br/> Indica se visualizzare le didascalie dei campi e i menu a discesa dei filtri|
| [custom_list_sort](/cells/python-net/it/aspose.cells.pivot/pivottable/custom_list_sort) | Indica se considerare l'elenco personalizzato incorporato quando si ordinano i dati|
| [pivot_format_conditions](/cells/python-net/it/aspose.cells.pivot/pivottable/pivot_format_conditions) | Ottiene le condizioni di formato della tabella pivot.|
| [conditional_formats](/cells/python-net/it/aspose.cells.pivot/pivottable/conditional_formats) | Ottiene i formati condizionali della tabella pivot.|
| [page_field_order](/cells/python-net/it/aspose.cells.pivot/pivottable/page_field_order) |Ottiene e imposta l'ordine in cui i campi della pagina vengono aggiunti al layout del report della tabella pivot.|
| [page_field_wrap_count](/cells/python-net/it/aspose.cells.pivot/pivottable/page_field_wrap_count) | Ottiene il numero di campi di pagina in ogni colonna o riga nel report della tabella pivot.|
| [tag](/cells/python-net/it/aspose.cells.pivot/pivottable/tag) | Ottiene una stringa salvata con il report della tabella pivot.|
| [save_data](/cells/python-net/it/aspose.cells.pivot/pivottable/save_data) | Indica se i dati per il report di tabella pivot vengono salvati con la cartella di lavoro.|
| [refresh_data_on_opening_file](/cells/python-net/it/aspose.cells.pivot/pivottable/refresh_data_on_opening_file) | Indica se aggiornare i dati all'apertura del file.|
| [refresh_data_flag](/cells/python-net/it/aspose.cells.pivot/pivottable/refresh_data_flag) | Indica se i dati vengono aggiornati o meno.|
| [source_type](/cells/python-net/it/aspose.cells.pivot/pivottable/source_type) | Ottiene il tipo di origine dati della tabella pivot.|
| [external_connection_data_source](/cells/python-net/it/aspose.cells.pivot/pivottable/external_connection_data_source) | Ottiene l'origine dati della connessione esterna.|
| [data_source](/cells/python-net/it/aspose.cells.pivot/pivottable/data_source) | Ottiene e imposta l'origine dati della tabella pivot.|
| [pivot_formats](/cells/python-net/it/aspose.cells.pivot/pivottable/pivot_formats) | Ottiene la raccolta di formati applicati alla tabella pivot.|
| [item_print_titles](/cells/python-net/it/aspose.cells.pivot/pivottable/item_print_titles) | Indica se i nomi PivotItem devono essere ripetuti nella parte superiore di ogni pagina stampata.|
| [repeat_items_on_each_printed_page](/cells/python-net/it/aspose.cells.pivot/pivottable/repeat_items_on_each_printed_page) | Indica se le didascalie degli elementi pivot nell'area della riga vengono ripetute su ogni pagina stampata per i campi pivot in formato tabellare.|
| [print_titles](/cells/python-net/it/aspose.cells.pivot/pivottable/print_titles) | Indica se i titoli di stampa per il foglio di lavoro sono impostati in base<br/> nel report della tabella pivot. Il valore predefinito è falso.|
| [display_immediate_items](/cells/python-net/it/aspose.cells.pivot/pivottable/display_immediate_items) |Indica se gli elementi nelle aree riga e colonna sono visibili<br/> Quando l'area dati della tabella pivot è vuota. Il valore predefinito è true.|
| [is_selected](/cells/python-net/it/aspose.cells.pivot/pivottable/is_selected) | Indica se questa tabella pivot è selezionata.|
| [show_pivot_style_row_header](/cells/python-net/it/aspose.cells.pivot/pivottable/show_pivot_style_row_header) | Indica se applicare lo stile all'intestazione di riga nella tabella pivot.|
| [show_pivot_style_column_header](/cells/python-net/it/aspose.cells.pivot/pivottable/show_pivot_style_column_header) | Indica se applicare lo stile all'intestazione di colonna nella tabella pivot.|
| [show_pivot_style_row_stripes](/cells/python-net/it/aspose.cells.pivot/pivottable/show_pivot_style_row_stripes) | Indica se viene applicata la formattazione a strisce di riga.|
| [show_pivot_style_column_stripes](/cells/python-net/it/aspose.cells.pivot/pivottable/show_pivot_style_column_stripes) | Indica se alla colonna viene applicata la formattazione a strisce.|
| [show_pivot_style_last_column](/cells/python-net/it/aspose.cells.pivot/pivottable/show_pivot_style_last_column) | Indica se viene applicata la formattazione della colonna.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`remove_field(self, field_type, field_name)`](/cells/python-net/it/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.pivotfieldtype-str) | Rimuove un campo da un'area specifica del campo|
| [`remove_field(self, field_type, base_field_index)`](/cells/python-net/it/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.pivotfieldtype-int) | Rimuove un campo da un'area specifica del campo|
| [`remove_field(self, field_type, pivot_field)`](/cells/python-net/it/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.pivotfieldtype-aspose.cells.pivot.pivotfield) | Rimuovi campo da un'area specifica del campo|
| [`add_field_to_area(self, field_type, field_name)`](/cells/python-net/it/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.pivotfieldtype-str) | Aggiunge il campo all'area specifica.|
| [`add_field_to_area(self, field_type, base_field_index)`](/cells/python-net/it/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.pivotfieldtype-int) | Aggiunge il campo all'area specifica.|
| [`add_field_to_area(self, field_type, pivot_field)`](/cells/python-net/it/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.pivotfieldtype-aspose.cells.pivot.pivotfield) | Aggiunge il campo all'area specifica.|
| [`add_calculated_field(self, name, formula, drag_to_data_area)`](/cells/python-net/it/aspose.cells.pivot/pivottable/add_calculated_field/#str-str-bool) | Aggiunge un campo calcolato al campo pivot.|
| [`add_calculated_field(self, name, formula)`](/cells/python-net/it/aspose.cells.pivot/pivottable/add_calculated_field/#str-str) | Aggiunge un campo calcolato al campo pivot e lo trascina nell'area dati.|
| [`move(self, row, column)`](/cells/python-net/it/aspose.cells.pivot/pivottable/move/#int-int) | Sposta la tabella pivot in una posizione diversa nel foglio di lavoro.|
| [`move(self, dest_cell_name)`](/cells/python-net/it/aspose.cells.pivot/pivottable/move/#str) | Sposta la tabella pivot in una posizione diversa nel foglio di lavoro.|
| [`move_to(self, row, column)`](/cells/python-net/it/aspose.cells.pivot/pivottable/move_to/#int-int) | Sposta la tabella pivot in una posizione diversa nel foglio di lavoro.|
| [`move_to(self, dest_cell_name)`](/cells/python-net/it/aspose.cells.pivot/pivottable/move_to/#str) | Sposta la tabella pivot in una posizione diversa nel foglio di lavoro.|
| [`get_source(self)`](/cells/python-net/it/aspose.cells.pivot/pivottable/get_source/#) | Ottieni i dati sorgente della tabella pivot.|
| [`get_source(self, is_original)`](/cells/python-net/it/aspose.cells.pivot/pivottable/get_source/#bool) | Ottieni i dati sorgente della tabella pivot.|
| [`refresh_data(self)`](/cells/python-net/it/aspose.cells.pivot/pivottable/refresh_data/#) |Aggiorna i dati e le impostazioni della tabella pivot dalla sua origine dati.|
| [`refresh_data(self, option)`](/cells/python-net/it/aspose.cells.pivot/pivottable/refresh_data/#aspose.cells.pivot.pivottablerefreshoption) | Aggiorna i dati e le impostazioni della tabella pivot dalla sua sorgente dati con opzioni.|
| [`calculate_data(self)`](/cells/python-net/it/aspose.cells.pivot/pivottable/calculate_data/#) | Calcola i dati della tabella pivot nelle celle.|
| [`calculate_data(self, option)`](/cells/python-net/it/aspose.cells.pivot/pivottable/calculate_data/#aspose.cells.pivot.pivottablecalculateoption) | Calcolo delle tabelle pivot con opzioni|
| [`format(self, pivot_area, style)`](/cells/python-net/it/aspose.cells.pivot/pivottable/format/#aspose.cells.pivot.pivotarea-aspose.cells.style) | Formatta l'area selezionata della tabella pivot.|
| [`format(self, ca, style)`](/cells/python-net/it/aspose.cells.pivot/pivottable/format/#aspose.cells.cellarea-aspose.cells.style) | Formatta l'area selezionata della tabella pivot.|
| [`format(self, row, column, style)`](/cells/python-net/it/aspose.cells.pivot/pivottable/format/#int-int-aspose.cells.style) | Formattare la cella nell'area della tabella pivot|
| [`set_auto_group_field(self, base_field_index)`](/cells/python-net/it/aspose.cells.pivot/pivottable/set_auto_group_field/#int) | Imposta il raggruppamento automatico dei campi tramite la tabella pivot.|
| [`set_auto_group_field(self, pivot_field)`](/cells/python-net/it/aspose.cells.pivot/pivottable/set_auto_group_field/#aspose.cells.pivot.pivotfield) | Imposta il raggruppamento automatico dei campi tramite la tabella pivot.|
| [`set_manual_group_field(self, base_field_index, start_val, end_val, group_by_list, interval_num)`](/cells/python-net/it/aspose.cells.pivot/pivottable/set_manual_group_field/#int-float-float-list-float) | Imposta il raggruppamento manuale dei campi tramite la tabella pivot.|
| [`set_manual_group_field(self, pivot_field, start_val, end_val, group_by_list, interval_num)`](/cells/python-net/it/aspose.cells.pivot/pivottable/set_manual_group_field/#aspose.cells.pivot.pivotfield-float-float-list-float) | Imposta il raggruppamento manuale dei campi tramite la tabella pivot.|
| [`set_manual_group_field(self, base_field_index, start_val, end_val, group_by_list, interval_num)`](/cells/python-net/it/aspose.cells.pivot/pivottable/set_manual_group_field/#int-datetime-datetime-list-int) | Imposta il raggruppamento manuale dei campi tramite la tabella pivot.|
| [`set_manual_group_field(self, pivot_field, start_val, end_val, group_by_list, interval_num)`](/cells/python-net/it/aspose.cells.pivot/pivottable/set_manual_group_field/#aspose.cells.pivot.pivotfield-datetime-datetime-list-int) | Imposta il raggruppamento manuale dei campi tramite la tabella pivot.|
| [`set_ungroup(self, base_field_index)`](/cells/python-net/it/aspose.cells.pivot/pivottable/set_ungroup/#int) | Imposta la separazione tramite la tabella pivot|
| [`set_ungroup(self, pivot_field)`](/cells/python-net/it/aspose.cells.pivot/pivottable/set_ungroup/#aspose.cells.pivot.pivotfield) | Imposta la separazione tramite la tabella pivot|
| [`copy_style(self, pivot_table)`](/cells/python-net/it/aspose.cells.pivot/pivottable/copy_style/#aspose.cells.pivot.pivottable) | Copia lo stile denominato da un'altra tabella pivot.|
| [`show_report_filter_page(self, page_field)`](/cells/python-net/it/aspose.cells.pivot/pivottable/show_report_filter_page/#aspose.cells.pivot.pivotfield) | Mostra tutte le pagine del filtro del report in base al PivotField; il PivotField deve trovarsi nei PageField.|
| [`show_report_filter_page_by_name(self, field_name)`](/cells/python-net/it/aspose.cells.pivot/pivottable/show_report_filter_page_by_name/#str) | Mostra tutte le pagine del filtro del report in base al nome del PivotField; il PivotField deve trovarsi nei PageFields.|
| [`show_report_filter_page_by_index(self, pos_index)`](/cells/python-net/it/aspose.cells.pivot/pivottable/show_report_filter_page_by_index/#int) | Mostra tutte le pagine del filtro del report in base all'indice di posizione nei PageFields|
| [`get_fields(self, field_type)`](/cells/python-net/it/aspose.cells.pivot/pivottable/get_fields/#aspose.cells.pivot.pivotfieldtype) | Ottiene l'elenco specifico dei campi pivot in base alla regione.|
| [`fields(self, field_type)`](/cells/python-net/it/aspose.cells.pivot/pivottable/fields/#aspose.cells.pivot.pivotfieldtype) | Ottiene i campi specifici in base al tipo di campo.|
| [`get_source_data_connections(self)`](/cells/python-net/it/aspose.cells.pivot/pivottable/get_source_data_connections/#) |Ottiene le origini dati delle connessioni esterne.|
| [`get_names_of_source_data_connections(self)`](/cells/python-net/it/aspose.cells.pivot/pivottable/get_names_of_source_data_connections/#) | Ottiene il nome delle connessioni dati di origine esterne.|
| [`change_data_source(self, source)`](/cells/python-net/it/aspose.cells.pivot/pivottable/change_data_source/#list) | Imposta i dati sorgente della tabella pivot.|
| [`clear_data(self)`](/cells/python-net/it/aspose.cells.pivot/pivottable/clear_data/#) | Cancella i dati e la formattazione della tabella pivot|
| [`calculate_range(self)`](/cells/python-net/it/aspose.cells.pivot/pivottable/calculate_range/#) | Calcola l'intervallo della tabella pivot.|
| [`format_all(self, style)`](/cells/python-net/it/aspose.cells.pivot/pivottable/format_all/#aspose.cells.style) | Formatta tutte le celle nell'area della tabella pivot|
| [`format_row(self, row, style)`](/cells/python-net/it/aspose.cells.pivot/pivottable/format_row/#int-aspose.cells.style) | Formattare i dati di riga nell'area della tabella pivot|
| [`select_area(self, ca)`](/cells/python-net/it/aspose.cells.pivot/pivottable/select_area/#aspose.cells.cellarea) | Seleziona un'area della vista tabella pivot.|
| [`show_detail(self, row_offset, column_offset, new_sheet, dest_row, dest_column)`](/cells/python-net/it/aspose.cells.pivot/pivottable/show_detail/#int-int-bool-int-int) | Mostra i dettagli di un elemento nell'area dati in una nuova tabella.|
| [`get_horizontal_page_breaks(self)`](/cells/python-net/it/aspose.cells.pivot/pivottable/get_horizontal_page_breaks/#) | Ottiene le interruzioni di pagina orizzontali di questa tabella pivot.|
| [`get_horizontal_breaks(self)`](/cells/python-net/it/aspose.cells.pivot/pivottable/get_horizontal_breaks/#) | Ottiene l'elenco degli indici delle righe della tabella pivot delle interruzioni di pagina orizzontali|
| [`show_in_compact_form(self)`](/cells/python-net/it/aspose.cells.pivot/pivottable/show_in_compact_form/#) | Imposta la tabella pivot in formato compatto.|
| [`show_in_outline_form(self)`](/cells/python-net/it/aspose.cells.pivot/pivottable/show_in_outline_form/#) | Imposta la tabella pivot in forma strutturata.|
| [`show_in_tabular_form(self)`](/cells/python-net/it/aspose.cells.pivot/pivottable/show_in_tabular_form/#) | Visualizza la tabella pivot in formato tabellare.|
| [`get_cell_by_display_name(self, display_name)`](/cells/python-net/it/aspose.cells.pivot/pivottable/get_cell_by_display_name/#str) | Ottiene l'oggetto [`Cell`](/cells/python-net/it/aspose.cells/cell) tramite il nome visualizzato di PivotField.|
| [`get_children(self)`](/cells/python-net/it/aspose.cells.pivot/pivottable/get_children/#) | Ottiene le tabelle pivot figlio che utilizzano i dati di questa tabella pivot come origine dati.|



###  Esempio

```python
from aspose.cells import FormatConditionType, OperatorType, Workbook
from aspose.cells.pivot import PivotFieldType, PivotFilterType, PivotTableStyleType
from aspose.pydrawing import Color

book = Workbook()
sheet = book.worksheets[0]
cells = sheet.cells
cells.get(0, 0).value = "fruit"
cells.get(1, 0).value = "grape"
cells.get(2, 0).value = "blueberry"
cells.get(3, 0).value = "kiwi"
cells.get(4, 0).value = "cherry"
cells.get(5, 0).value = "grape"
cells.get(6, 0).value = "blueberry"
cells.get(7, 0).value = "kiwi"
cells.get(8, 0).value = "cherry"
cells.get(0, 1).value = "year"
cells.get(1, 1).value = 2020
cells.get(2, 1).value = 2020
cells.get(3, 1).value = 2020
cells.get(4, 1).value = 2020
cells.get(5, 1).value = 2021
cells.get(6, 1).value = 2021
cells.get(7, 1).value = 2021
cells.get(8, 1).value = 2021
cells.get(0, 2).value = "amount"
cells.get(1, 2).value = 50
cells.get(2, 2).value = 60
cells.get(3, 2).value = 70
cells.get(4, 2).value = 80
cells.get(5, 2).value = 90
cells.get(6, 2).value = 100
cells.get(7, 2).value = 110
cells.get(8, 2).value = 120
pivots = sheet.pivot_tables
pivotIndex = pivots.add("=Sheet1!A1:C9", "A12", "TestPivotTable")
pivot = pivots[pivotIndex]
pivot.add_field_to_area(PivotFieldType.ROW, "fruit")
pivot.add_field_to_area(PivotFieldType.COLUMN, "year")
pivot.add_field_to_area(PivotFieldType.DATA, "amount")
pivot.pivot_table_style_type = PivotTableStyleType.PIVOT_TABLE_STYLE_MEDIUM10
# Change PivotField's attributes
rowField = pivot.row_fields[0]
rowField.display_name = "custom display name"
# Add PivotFilter
index = pivot.pivot_filters.add(0, PivotFilterType.COUNT)
filter = pivot.pivot_filters[index]
filter.auto_filter.filter_top10(0, False, False, 2)
# Add PivotFormatCondition
formatIndex = pivot.pivot_format_conditions.add()
pfc = pivot.pivot_format_conditions[formatIndex]
fcc = pfc.format_conditions
fcc.add_area(pivot.data_body_range)
idx = fcc.add_condition(FormatConditionType.CELL_VALUE)
fc = fcc[idx]
fc.formula1 = "100"
fc.operator = OperatorType.GREATER_OR_EQUAL
fc.style.background_color = Color.red
pivot.refresh_data()
pivot.calculate_data()
# do your business
book.save("out.xlsx")

```

###  Guarda anche
* modulo [`aspose.cells.pivot`](..)
* classe [`Cell`](/cells/python-net/it/aspose.cells/cell)
* classe [`CellArea`](/cells/python-net/it/aspose.cells/cellarea)
* classe [`PivotField`](/cells/python-net/it/aspose.cells.pivot/pivotfield)
