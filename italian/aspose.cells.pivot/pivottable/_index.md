---
title: PivotTable classe
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 180
url: /it/aspose.cells.pivot/pivottable/
is_root: false
---
##  PivotTable classe
Descrizione riassuntiva per PivotTable.



Il tipo PivotTable espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [is_excel_2003_compatible](/cells/python-net/it/aspose.cells.pivot/pivottable/is_excel_2003_compatible) | Specifica se la tabella pivot è compatibile con Excel2003 durante l'aggiornamento della tabella pivot,<br/>se vero, una stringa deve essere inferiore o uguale a 255 caratteri, quindi se la stringa è maggiore di 255 caratteri,<br/>verrà troncato. se false, una stringa non avrà la suddetta restrizione.<br/> Il valore predefinito è vero.|
| [refreshed_by_who](/cells/python-net/it/aspose.cells.pivot/pivottable/refreshed_by_who) | Ottiene il nome dell'utente che ha aggiornato per ultimo la tabella pivot|
| [refresh_date](/cells/python-net/it/aspose.cells.pivot/pivottable/refresh_date) | Ottiene la data dell'ultimo aggiornamento della tabella pivot.|
| [pivot_table_style_name](/cells/python-net/it/aspose.cells.pivot/pivottable/pivot_table_style_name) | Ottiene e imposta il nome dello stile pivottabile.|
| [pivot_table_style_type](/cells/python-net/it/aspose.cells.pivot/pivottable/pivot_table_style_type) | Ottiene e imposta lo stile della tabella pivot integrato.|
| [column_fields](/cells/python-net/it/aspose.cells.pivot/pivottable/column_fields) | Restituisce un oggetto PivotFields attualmente visualizzato come campi colonna.|
| [row_fields](/cells/python-net/it/aspose.cells.pivot/pivottable/row_fields) | Restituisce un oggetto PivotFields attualmente visualizzato come campi riga.|
| [page_fields](/cells/python-net/it/aspose.cells.pivot/pivottable/page_fields) | Restituisce un oggetto PivotFields attualmente visualizzato come campi di pagina.|
| [data_fields](/cells/python-net/it/aspose.cells.pivot/pivottable/data_fields) | Ottiene un oggetto PivotField che rappresenta tutti i campi dati in una tabella pivot.<br/>Di sola lettura. Sarebbe init solo quando ci sono due o più campi dati in DataPiovtFiels.<br/> Viene utilizzato solo per aggiungere DataPivotField all'area di riga/colonna della tabella pivot. L'impostazione predefinita è nell'area della riga.|
| [data_field](/cells/python-net/it/aspose.cells.pivot/pivottable/data_field) | Ottiene un oggetto PivotField che rappresenta tutti i campi dati in una tabella pivot.<br/>Di sola lettura. Sarebbe init solo quando ci sono due o più campi dati in DataPiovtFiels.<br/> Viene utilizzato solo per aggiungere DataPivotField all'area di riga/colonna della tabella pivot. L'impostazione predefinita è nell'area della riga.|
| [base_fields](/cells/python-net/it/aspose.cells.pivot/pivottable/base_fields) | Restituisce un oggetto PivotFields che include tutti i campi nel rapporto di tabella pivot|
| [pivot_filters](/cells/python-net/it/aspose.cells.pivot/pivottable/pivot_filters) | Restituisce un oggetto PivotFilterCollection.|
| [column_range](/cells/python-net/it/aspose.cells.pivot/pivottable/column_range) |Restituisce un oggetto CellArea che rappresenta l'intervallo<br/> che contiene l'area della colonna nel rapporto di tabella pivot. Sola lettura.|
| [row_range](/cells/python-net/it/aspose.cells.pivot/pivottable/row_range) |Restituisce un oggetto CellArea che rappresenta l'intervallo<br/> che contiene l'area della riga nel rapporto di tabella pivot. Sola lettura.|
| [data_body_range](/cells/python-net/it/aspose.cells.pivot/pivottable/data_body_range) | Restituisce un oggetto CellArea che rappresenta l'intervallo che contiene l'area dati<br/> nell'elenco tra la riga di intestazione e la riga di inserimento. Sola lettura.|
| [table_range1](/cells/python-net/it/aspose.cells.pivot/pivottable/table_range1) | Restituisce un oggetto CellArea che rappresenta l'intervallo contenente l'intero rapporto di tabella pivot,<br/> ma non include i campi della pagina. Sola lettura.|
| [table_range2](/cells/python-net/it/aspose.cells.pivot/pivottable/table_range2) | Restituisce un oggetto CellArea che rappresenta l'intervallo contenente l'intero rapporto di tabella pivot,<br/> include i campi della pagina. Sola lettura.|
| [column_grand](/cells/python-net/it/aspose.cells.pivot/pivottable/column_grand) | Indica se il rapporto di tabella pivot mostra i totali generali per le colonne.|
| [is_grid_drop_zones](/cells/python-net/it/aspose.cells.pivot/pivottable/is_grid_drop_zones) | Indica se nel rapporto di tabella pivot viene visualizzato il layout di tabella pivot classico.<br/> (abilita il trascinamento dei campi nella griglia)|
| [row_grand](/cells/python-net/it/aspose.cells.pivot/pivottable/row_grand) | Indica se il rapporto di tabella pivot mostra i totali generali per le righe.|
| [display_null_string](/cells/python-net/it/aspose.cells.pivot/pivottable/display_null_string) | Indica se nel rapporto di tabella pivot viene visualizzata una stringa personalizzata<br/> nelle celle che contengono valori nulli.|
| [null_string](/cells/python-net/it/aspose.cells.pivot/pivottable/null_string) | Ottiene la stringa visualizzata nelle celle che contengono valori Null<br/>quando la proprietà DisplayNullString è true. Il valore predefinito è una stringa vuota.|
| [display_error_string](/cells/python-net/it/aspose.cells.pivot/pivottable/display_error_string) | Indica se il rapporto di tabella pivot visualizza una stringa personalizzata nelle celle che contengono errori.|
| [data_field_header_name](/cells/python-net/it/aspose.cells.pivot/pivottable/data_field_header_name) | Ottiene e imposta il nome dell'intestazione del campo dell'area valori nella tabella pivot.|
| [error_string](/cells/python-net/it/aspose.cells.pivot/pivottable/error_string) | Ottiene la stringa visualizzata nelle celle che contengono errori<br/> quando la proprietà DisplayErrorString è true. Il valore predefinito è una stringa vuota.|
| [is_auto_format](/cells/python-net/it/aspose.cells.pivot/pivottable/is_auto_format) | Indica se il rapporto di tabella pivot viene formattato automaticamente.<br/> Casella di controllo "tabella di formattazione automatica" che è nell'opzione pivot per Excel 2003|
| [autofit_column_width_on_update](/cells/python-net/it/aspose.cells.pivot/pivottable/autofit_column_width_on_update) | Indica se adattare automaticamente la larghezza della colonna durante l'aggiornamento|
| [auto_format_type](/cells/python-net/it/aspose.cells.pivot/pivottable/auto_format_type) | Ottiene il tipo di formato automatico della tabella pivot.|
| [has_blank_rows](/cells/python-net/it/aspose.cells.pivot/pivottable/has_blank_rows) | Indica se aggiungere righe vuote.<br/> Questa proprietà si applica solo ai tipi di formato automatico della tabella pivot che devono aggiungere righe vuote.|
| [merge_labels](/cells/python-net/it/aspose.cells.pivot/pivottable/merge_labels) | Indica se l'elemento riga esterna, l'elemento colonna, il totale parziale o il totale parziale del rapporto di tabella pivot specificato<br/> e le etichette del totale complessivo utilizzano celle unite.|
| [preserve_formatting](/cells/python-net/it/aspose.cells.pivot/pivottable/preserve_formatting) |Indica se la formattazione viene mantenuta quando la tabella pivot viene aggiornata o ricalcolata.|
| [show_drill](/cells/python-net/it/aspose.cells.pivot/pivottable/show_drill) | Indica se vengono visualizzati i pulsanti di espansione/compressione.|
| [enable_drilldown](/cells/python-net/it/aspose.cells.pivot/pivottable/enable_drilldown) | Ottiene se il drilldown è abilitato.|
| [enable_field_dialog](/cells/python-net/it/aspose.cells.pivot/pivottable/enable_field_dialog) | Indica se la finestra di dialogo Campo tabella pivot è disponibile<br/> quando l'utente fa doppio clic sul campo della tabella pivot.|
| [enable_field_list](/cells/python-net/it/aspose.cells.pivot/pivottable/enable_field_list) | Ottiene se abilitare l'elenco dei campi per la tabella pivot.|
| [enable_wizard](/cells/python-net/it/aspose.cells.pivot/pivottable/enable_wizard) | Indica se la Creazione guidata tabella pivot è disponibile.|
| [subtotal_hidden_page_items](/cells/python-net/it/aspose.cells.pivot/pivottable/subtotal_hidden_page_items) | Indica se gli elementi dei campi della pagina sono nascosti nel rapporto di tabella pivot<br/>sono inclusi nei totali parziali di riga e colonna, nei totali di blocco e nei totali generali.<br/> Il valore predefinito è falso.|
| [grand_total_name](/cells/python-net/it/aspose.cells.pivot/pivottable/grand_total_name) | Restituisce l'etichetta della stringa di testo visualizzata nell'intestazione della colonna o della riga del totale generale.<br/> Il valore predefinito è la stringa "Totale generale".|
| [manual_update](/cells/python-net/it/aspose.cells.pivot/pivottable/manual_update) | Indica se il rapporto di tabella pivot viene ricalcolato solo su richiesta dell'utente.|
| [is_multiple_field_filters](/cells/python-net/it/aspose.cells.pivot/pivottable/is_multiple_field_filters) | Specifica un valore booleano che indica se sui campi di una tabella pivot possono essere impostati più filtri.|
| [missing_items_limit](/cells/python-net/it/aspose.cells.pivot/pivottable/missing_items_limit) | Specifica un valore booleano che indica se sui campi di una tabella pivot possono essere impostati più filtri.|
| [enable_data_value_editing](/cells/python-net/it/aspose.cells.pivot/pivottable/enable_data_value_editing) |Specifica un valore booleano che indica se all'utente è consentito modificare le celle nell'area dati della tabella pivot.<br/> Abilita la modifica della cella nell'area dei valori|
| [show_data_tips](/cells/python-net/it/aspose.cells.pivot/pivottable/show_data_tips) | Specifica un valore booleano che indica se le descrizioni comandi devono essere visualizzate per le celle di dati della tabella pivot.|
| [show_member_property_tips](/cells/python-net/it/aspose.cells.pivot/pivottable/show_member_property_tips) | Specifica un valore booleano che indica se le informazioni sulle proprietà dei membri devono essere omesse dalle descrizioni comandi della tabella pivot.|
| [show_values_row](/cells/python-net/it/aspose.cells.pivot/pivottable/show_values_row) | Specifica un valore booleano che indica se mostrare la riga dei valori.<br/> mostra la riga dei valori|
| [show_empty_col](/cells/python-net/it/aspose.cells.pivot/pivottable/show_empty_col) | Specifica un valore booleano che indica se includere colonne vuote nella tabella|
| [show_empty_row](/cells/python-net/it/aspose.cells.pivot/pivottable/show_empty_row) | Specifica un valore booleano che indica se includere righe vuote nella tabella.|
| [field_list_sort_ascending](/cells/python-net/it/aspose.cells.pivot/pivottable/field_list_sort_ascending) | Specifica un valore booleano che indica se i campi nella tabella pivot sono ordinati in un ordine non predefinito nell'elenco dei campi.|
| [print_drill](/cells/python-net/it/aspose.cells.pivot/pivottable/print_drill) | Specifica un valore booleano che indica se gli indicatori di drill devono essere stampati.<br/> stampare i pulsanti di espansione/compressione quando visualizzati su pivottable.|
| [alt_text_title](/cells/python-net/it/aspose.cells.pivot/pivottable/alt_text_title) |Ottiene il titolo dell'altertext|
| [alt_text_description](/cells/python-net/it/aspose.cells.pivot/pivottable/alt_text_description) | Ottiene la descrizione del testo alternativo|
| [name](/cells/python-net/it/aspose.cells.pivot/pivottable/name) | Ottiene il nome della tabella pivot|
| [column_header_caption](/cells/python-net/it/aspose.cells.pivot/pivottable/column_header_caption) | Ottiene la didascalia dell'intestazione di colonna della tabella pivot.|
| [indent](/cells/python-net/it/aspose.cells.pivot/pivottable/indent) | Specifica l'incremento del rientro per l'asse compatto e può essere utilizzato per impostare il layout del report su Formato compatto.|
| [row_header_caption](/cells/python-net/it/aspose.cells.pivot/pivottable/row_header_caption) | Ottiene la didascalia dell'intestazione di riga della tabella pivot.|
| [show_row_header_caption](/cells/python-net/it/aspose.cells.pivot/pivottable/show_row_header_caption) | Indica se la didascalia dell'intestazione della riga viene visualizzata nel rapporto di tabella pivot<br/> Indica se visualizzare le didascalie dei campi e i filtri a discesa|
| [custom_list_sort](/cells/python-net/it/aspose.cells.pivot/pivottable/custom_list_sort) | Indica se considerare l'elenco personalizzato integrato durante l'ordinamento dei dati|
| [pivot_format_conditions](/cells/python-net/it/aspose.cells.pivot/pivottable/pivot_format_conditions) | Ottiene le condizioni di formato della tabella pivot.|
| [page_field_order](/cells/python-net/it/aspose.cells.pivot/pivottable/page_field_order) | Ottiene l'ordine in cui i campi della pagina vengono aggiunti al layout del rapporto di tabella pivot.|
| [page_field_wrap_count](/cells/python-net/it/aspose.cells.pivot/pivottable/page_field_wrap_count) | Ottiene il numero di campi pagina in ogni colonna o riga nel rapporto di tabella pivot.|
| [tag](/cells/python-net/it/aspose.cells.pivot/pivottable/tag) | Ottiene una stringa salvata con il rapporto di tabella pivot.|
| [save_data](/cells/python-net/it/aspose.cells.pivot/pivottable/save_data) | Indica se i dati per il rapporto di tabella pivot vengono salvati con la cartella di lavoro.|
| [refresh_data_on_opening_file](/cells/python-net/it/aspose.cells.pivot/pivottable/refresh_data_on_opening_file) | Indica se aggiornare i dati all'apertura del file.|
| [refresh_data_flag](/cells/python-net/it/aspose.cells.pivot/pivottable/refresh_data_flag) |Indica se si stanno aggiornando i dati o meno.|
| [external_connection_data_source](/cells/python-net/it/aspose.cells.pivot/pivottable/external_connection_data_source) | Ottiene l'origine dati della connessione esterna.|
| [data_source](/cells/python-net/it/aspose.cells.pivot/pivottable/data_source) | Ottiene e imposta l'origine dati della tabella pivot.|
| [pivot_formats](/cells/python-net/it/aspose.cells.pivot/pivottable/pivot_formats) | Ottiene la raccolta di formati applicati alla tabella pivot.|
| [item_print_titles](/cells/python-net/it/aspose.cells.pivot/pivottable/item_print_titles) | Un bit che specifica se ruotare le didascalie degli elementi sull'asse di riga<br/> vengono ripetuti su ogni pagina stampata per i campi pivot in forma tabellare.|
| [print_titles](/cells/python-net/it/aspose.cells.pivot/pivottable/print_titles) | Indica se i titoli di stampa per il foglio di lavoro sono basati su set<br/> nel rapporto di tabella pivot. Il valore predefinito è falso.|
| [display_immediate_items](/cells/python-net/it/aspose.cells.pivot/pivottable/display_immediate_items) | Indica se gli elementi nelle aree delle righe e delle colonne sono visibili<br/> quando l'area dati della tabella pivot è vuota. Il valore predefinito è vero.|
| [is_selected](/cells/python-net/it/aspose.cells.pivot/pivottable/is_selected) | Indica se la tabella pivot è selezionata.|
| [show_pivot_style_row_header](/cells/python-net/it/aspose.cells.pivot/pivottable/show_pivot_style_row_header) | Indica se all'intestazione della riga nella tabella pivot deve essere applicato lo stile.|
| [show_pivot_style_column_header](/cells/python-net/it/aspose.cells.pivot/pivottable/show_pivot_style_column_header) | Indica se all'intestazione della colonna nella tabella pivot deve essere applicato lo stile.|
| [show_pivot_style_row_stripes](/cells/python-net/it/aspose.cells.pivot/pivottable/show_pivot_style_row_stripes) | Indica se viene applicata la formattazione della striscia di riga.|
| [show_pivot_style_column_stripes](/cells/python-net/it/aspose.cells.pivot/pivottable/show_pivot_style_column_stripes) | Indica se viene applicata la formattazione della striscia di colonna.|
| [show_pivot_style_last_column](/cells/python-net/it/aspose.cells.pivot/pivottable/show_pivot_style_last_column) | Indica se viene applicata la formattazione della striscia di colonna.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [remove_field](/cells/python-net/it/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.PivotFieldType-str) |Rimuove un campo da un'area specifica|
| [remove_field](/cells/python-net/it/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.PivotFieldType-int) |Rimuove un campo da un'area specifica|
| [remove_field](/cells/python-net/it/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.PivotFieldType-aspose.cells.pivot.PivotField) | Rimuovi il campo dall'area specifica del campo|
| [add_field_to_area](/cells/python-net/it/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.PivotFieldType-str) | Aggiunge il campo all'area specifica.|
| [add_field_to_area](/cells/python-net/it/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.PivotFieldType-int) | Aggiunge il campo all'area specifica.|
| [add_field_to_area](/cells/python-net/it/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.PivotFieldType-aspose.cells.pivot.PivotField) | Aggiunge il campo all'area specifica.|
| [add_calculated_field](/cells/python-net/it/aspose.cells.pivot/pivottable/add_calculated_field/#str-str-bool) | Aggiunge un campo calcolato al campo pivot.|
| [add_calculated_field](/cells/python-net/it/aspose.cells.pivot/pivottable/add_calculated_field/#str-str) | Aggiunge un campo calcolato al campo pivot e trascinalo nell'area dati.|
| [move](/cells/python-net/it/aspose.cells.pivot/pivottable/move/#int-int) | Sposta la tabella pivot in una posizione diversa nel foglio di lavoro.|
| [move](/cells/python-net/it/aspose.cells.pivot/pivottable/move/#str) | Sposta la tabella pivot in una posizione diversa nel foglio di lavoro.|
| [format](/cells/python-net/it/aspose.cells.pivot/pivottable/format/#aspose.cells.pivot.PivotArea-aspose.cells.Style) | Formatta l'area selezionata della tabella pivot.|
| [format](/cells/python-net/it/aspose.cells.pivot/pivottable/format/#int-int-aspose.cells.Style) | Formattare la cella nell'area pivottabile|
| [set_auto_group_field](/cells/python-net/it/aspose.cells.pivot/pivottable/set_auto_group_field/#int) | Imposta il gruppo di campi automatici in base alla tabella pivot.|
| [set_auto_group_field](/cells/python-net/it/aspose.cells.pivot/pivottable/set_auto_group_field/#aspose.cells.pivot.PivotField) | Imposta il gruppo di campi automatici in base alla tabella pivot.|
| [set_manual_group_field](/cells/python-net/it/aspose.cells.pivot/pivottable/set_manual_group_field/#int-float-float-list-float) | Imposta il gruppo di campi manuale in base alla tabella pivot.|
| [set_manual_group_field](/cells/python-net/it/aspose.cells.pivot/pivottable/set_manual_group_field/#aspose.cells.pivot.PivotField-float-float-list-float) | Imposta il gruppo di campi manuale in base alla tabella pivot.|
| [set_manual_group_field](/cells/python-net/it/aspose.cells.pivot/pivottable/set_manual_group_field/#int-DateTime-DateTime-list-int) | Imposta il gruppo di campi manuale in base alla tabella pivot.|
| [set_manual_group_field](/cells/python-net/it/aspose.cells.pivot/pivottable/set_manual_group_field/#aspose.cells.pivot.PivotField-DateTime-DateTime-list-int) | Imposta il gruppo di campi manuale in base alla tabella pivot.|
| [set_ungroup](/cells/python-net/it/aspose.cells.pivot/pivottable/set_ungroup/#int) | Imposta la separazione in base alla tabella pivot|
| [set_ungroup](/cells/python-net/it/aspose.cells.pivot/pivottable/set_ungroup/#aspose.cells.pivot.PivotField) | Imposta la separazione in base alla tabella pivot|
| [copy_style](/cells/python-net/it/aspose.cells.pivot/pivottable/copy_style/#aspose.cells.pivot.PivotTable) | Copia lo stile denominato da un'altra tabella pivot.|
| [show_report_filter_page](/cells/python-net/it/aspose.cells.pivot/pivottable/show_report_filter_page/#aspose.cells.pivot.PivotField) | Mostra tutte le pagine del filtro del report in base a PivotField, il PivotField deve essere posizionato nei PageField.|
| [show_report_filter_page_by_name](/cells/python-net/it/aspose.cells.pivot/pivottable/show_report_filter_page_by_name/#str) | Mostra tutte le pagine del filtro del report in base al nome del PivotField, il PivotField deve trovarsi nei PageField.|
| [show_report_filter_page_by_index](/cells/python-net/it/aspose.cells.pivot/pivottable/show_report_filter_page_by_index/#int) | Mostra tutte le pagine del filtro del report in base all'indice di posizione nei PageFields|
| [fields](/cells/python-net/it/aspose.cells.pivot/pivottable/fields/#aspose.cells.pivot.PivotFieldType) | Ottiene i campi specifici in base al tipo di campo.|
| [change_data_source](/cells/python-net/it/aspose.cells.pivot/pivottable/change_data_source/#list) |Imposta i dati di origine della tabella pivot.<br/> Foglio1!$A$1:$C$3|
| [get_source](/cells/python-net/it/aspose.cells.pivot/pivottable/get_source/#) | Ottieni i dati di origine di Pivotable.|
| [refresh_data](/cells/python-net/it/aspose.cells.pivot/pivottable/refresh_data/#) | Aggiorna i dati e le impostazioni della tabella pivot dalla sua origine dati.|
| [calculate_data](/cells/python-net/it/aspose.cells.pivot/pivottable/calculate_data/#) | Calcola i dati della tabella pivot nelle celle.|
| [clear_data](/cells/python-net/it/aspose.cells.pivot/pivottable/clear_data/#) | Cancella i dati e la formattazione della tabella pivot|
| [calculate_range](/cells/python-net/it/aspose.cells.pivot/pivottable/calculate_range/#) | Calcola l'intervallo del pivottabile.|
| [format_all](/cells/python-net/it/aspose.cells.pivot/pivottable/format_all/#aspose.cells.Style) | Formatta tutta la cella nell'area pivottabile|
| [format_row](/cells/python-net/it/aspose.cells.pivot/pivottable/format_row/#int-aspose.cells.Style) | Formattare i dati della riga nell'area pivottabile|
| [get_horizontal_breaks](/cells/python-net/it/aspose.cells.pivot/pivottable/get_horizontal_breaks/#) | ottieni l'elenco degli indici delle righe della tabella pivot delle interruzioni di pagina orizzontali|
| [show_in_compact_form](/cells/python-net/it/aspose.cells.pivot/pivottable/show_in_compact_form/#) | Presenta la tabella pivot in formato compatto.|
| [show_in_outline_form](/cells/python-net/it/aspose.cells.pivot/pivottable/show_in_outline_form/#) | Presenta la tabella pivot sotto forma di struttura.|
| [show_in_tabular_form](/cells/python-net/it/aspose.cells.pivot/pivottable/show_in_tabular_form/#) | Presenta la tabella pivot in formato tabellare.|
| [get_cell_by_display_name](/cells/python-net/it/aspose.cells.pivot/pivottable/get_cell_by_display_name/#str) | Ottiene l'oggetto [`Cell`](/cells/python-net/it/aspose.cells/cell) con il nome visualizzato di PivotField.|
| [get_children](/cells/python-net/it/aspose.cells.pivot/pivottable/get_children/#) | Ottiene le tabelle pivot secondarie che utilizzano i dati di questa tabella pivot come origine dati.|



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
