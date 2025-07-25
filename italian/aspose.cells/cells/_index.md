---
title: Cells classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 160
url: /it/aspose.cells/cells/
is_root: false
---
##  Cells classe
Incapsula una raccolta di oggetti rilevanti per la cella, come [`Cell`](/cells/python-net/it/aspose.cells/cell), [`Row`](/cells/python-net/it/aspose.cells/row), ecc.



Il tipo Cells espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [ods_cell_fields](/cells/python-net/it/aspose.cells/cells/ods_cell_fields) | Ottiene l'elenco dei campi di ods.|
| [count](/cells/python-net/it/aspose.cells/cells/count) | Ottiene il conteggio totale degli oggetti Cell istanziati.|
| [count_large](/cells/python-net/it/aspose.cells/cells/count_large) | Ottiene il conteggio totale degli oggetti Cell istanziati.|
| [rows](/cells/python-net/it/aspose.cells/cells/rows) | Ottiene la raccolta di [`Row`](/cells/python-net/it/aspose.cells/row) oggetti che rappresentano le singole righe in questo foglio di lavoro.|
| [merged_cells](/cells/python-net/it/aspose.cells/cells/merged_cells) | Ottiene la raccolta di celle unite.|
| [multi_thread_reading](/cells/python-net/it/aspose.cells/cells/multi_thread_reading) | Ottiene o imposta se il modello di dati delle celle deve supportare la lettura multi-thread.<br/> Il valore predefinito di questa proprietà è false.|
| [memory_setting](/cells/python-net/it/aspose.cells/cells/memory_setting) | Ottiene o imposta l'opzione di utilizzo della memoria per queste celle.|
| [style](/cells/python-net/it/aspose.cells/cells/style) | Ottiene e imposta lo stile predefinito del foglio di lavoro.|
| [is_default_column_hidden](/cells/python-net/it/aspose.cells/cells/is_default_column_hidden) |  |
| [standard_width_inch](/cells/python-net/it/aspose.cells/cells/standard_width_inch) | Ottiene o imposta la larghezza predefinita della colonna nel foglio di lavoro, in pollici.|
| [standard_width_pixels](/cells/python-net/it/aspose.cells/cells/standard_width_pixels) |Ottiene o imposta la larghezza predefinita della colonna nel foglio di lavoro, in pixel.|
| [standard_width](/cells/python-net/it/aspose.cells/cells/standard_width) | Ottiene o imposta la larghezza predefinita della colonna nel foglio di lavoro, in unità di caratteri.|
| [standard_height](/cells/python-net/it/aspose.cells/cells/standard_height) | Ottiene o imposta l'altezza predefinita della riga in questo foglio di lavoro, in unità di punti.|
| [standard_height_pixels](/cells/python-net/it/aspose.cells/cells/standard_height_pixels) | Ottiene o imposta l'altezza predefinita della riga in questo foglio di lavoro, in pixel.|
| [standard_height_inch](/cells/python-net/it/aspose.cells/cells/standard_height_inch) | Ottiene o imposta l'altezza predefinita della riga in questo foglio di lavoro, in pollici.|
| [preserve_string](/cells/python-net/it/aspose.cells/cells/preserve_string) | Ottiene o imposta un valore che indica se tutti i valori del foglio di lavoro vengono conservati come stringhe.<br/> Il valore predefinito è falso.|
| [min_row](/cells/python-net/it/aspose.cells/cells/min_row) | Indice minimo di riga della cella che contiene dati o stile.|
| [max_row](/cells/python-net/it/aspose.cells/cells/max_row) | Indice massimo di riga della cella che contiene dati o stile.|
| [min_column](/cells/python-net/it/aspose.cells/cells/min_column) | Indice minimo di colonna delle celle che sono state istanziate nella raccolta (non include la colonna<br/> dove lo stile è definito per l'intera colonna ma non è stata istanziata alcuna cella in essa).|
| [max_column](/cells/python-net/it/aspose.cells/cells/max_column) | Indice massimo della colonna delle celle che sono state istanziate nella raccolta (non include la colonna<br/> dove lo stile è definito per l'intera colonna ma non è stata istanziata alcuna cella in essa).|
| [min_data_row](/cells/python-net/it/aspose.cells/cells/min_data_row) |Indice minimo di riga della cella che contiene dati.|
| [max_data_row](/cells/python-net/it/aspose.cells/cells/max_data_row) | Indice massimo di riga della cella contenente dati.|
| [min_data_column](/cells/python-net/it/aspose.cells/cells/min_data_column) | Indice minimo di colonna della cella che contiene dati.|
| [max_data_column](/cells/python-net/it/aspose.cells/cells/max_data_column) | Indice massimo della colonna della cella che contiene dati.|
| [is_default_row_height_matched](/cells/python-net/it/aspose.cells/cells/is_default_row_height_matched) | Indica che l'altezza della riga e l'altezza del carattere predefinito corrispondono|
| [is_default_row_hidden](/cells/python-net/it/aspose.cells/cells/is_default_row_hidden) | Indica se la riga è nascosta per impostazione predefinita.|
| [columns](/cells/python-net/it/aspose.cells/cells/columns) | Ottiene la raccolta di [`Column`](/cells/python-net/it/aspose.cells/column) oggetti che rappresentano le singole colonne in questo foglio di lavoro.|
| [ranges](/cells/python-net/it/aspose.cells/cells/ranges) | Ottiene la raccolta di [`Range`](/cells/python-net/it/aspose.cells/range) oggetti creati in fase di esecuzione.|
| [last_cell](/cells/python-net/it/aspose.cells/cells/last_cell) | Ottiene l'ultima cella in questo foglio di lavoro.|
| [max_display_range](/cells/python-net/it/aspose.cells/cells/max_display_range) | Ottiene l'intervallo massimo che include dati, celle unite e forme.|
| [first_cell](/cells/python-net/it/aspose.cells/cells/first_cell) | Ottiene la prima cella in questo foglio di lavoro.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`create_range(self, upper_left_cell, lower_right_cell)`](/cells/python-net/it/aspose.cells/cells/create_range/#str-str) | Crea un oggetto [`Range`](/cells/python-net/it/aspose.cells/range) da un intervallo di celle.|
| [`create_range(self, first_row, first_column, total_rows, total_columns)`](/cells/python-net/it/aspose.cells/cells/create_range/#int-int-int-int) | Crea un oggetto [`Range`](/cells/python-net/it/aspose.cells/range) da un intervallo di celle.|
| [`create_range(self, address)`](/cells/python-net/it/aspose.cells/cells/create_range/#str) | Crea un oggetto [`Range`](/cells/python-net/it/aspose.cells/range) da un indirizzo compreso nell'intervallo.|
| [`create_range(self, first_index, number, is_vertical)`](/cells/python-net/it/aspose.cells/cells/create_range/#int-int-bool) | Crea un oggetto [`Range`](/cells/python-net/it/aspose.cells/range) da righe di celle o colonne di celle.|
| [`get(self, row, column)`](/cells/python-net/it/aspose.cells/cells/get/#int-int) | Aggiungi API for Python tramite .Net. poiché questo [int riga, int colonna] non è supportato|
| [`get(self, cell_name)`](/cells/python-net/it/aspose.cells/cells/get/#str) |Aggiungi API for Python tramite .Net poiché questo [string cellName] non è supportato|
| [`import_object_array(self, obj_array, first_row, first_column, is_vertical)`](/cells/python-net/it/aspose.cells/cells/import_object_array/#list-int-int-bool) | Importa una matrice di dati in un foglio di lavoro.|
| [`import_object_array(self, obj_array, first_row, first_column, is_vertical, skip)`](/cells/python-net/it/aspose.cells/cells/import_object_array/#list-int-int-bool-int) | Importa una matrice di dati in un foglio di lavoro.|
| [`import_array(self, string_array, first_row, first_column, is_vertical)`](/cells/python-net/it/aspose.cells/cells/import_array/#list-int-int-bool) | Importa un array di stringhe in un foglio di lavoro.|
| [`import_array(self, int_array, first_row, first_column, is_vertical)`](/cells/python-net/it/aspose.cells/cells/import_array/#list-int-int-bool) | Importa un array di numeri interi in un foglio di lavoro.|
| [`import_array(self, double_array, first_row, first_column, is_vertical)`](/cells/python-net/it/aspose.cells/cells/import_array/#list-int-int-bool) | Importa un array di double in un foglio di lavoro.|
| [`import_csv(self, file_name, splitter, convert_numeric_data, first_row, first_column)`](/cells/python-net/it/aspose.cells/cells/import_csv/#str-str-bool-int-int) | Importare un file CSV nelle celle.|
| [`import_csv(self, stream, splitter, convert_numeric_data, first_row, first_column)`](/cells/python-net/it/aspose.cells/cells/import_csv/#io.rawiobase-str-bool-int-int) | Importare un file CSV nelle celle.|
| [`import_csv(self, file_name, options, first_row, first_column)`](/cells/python-net/it/aspose.cells/cells/import_csv/#str-aspose.cells.txtloadoptions-int-int) | Importare un file CSV nelle celle.|
| [`import_csv(self, stream, options, first_row, first_column)`](/cells/python-net/it/aspose.cells/cells/import_csv/#io.rawiobase-aspose.cells.txtloadoptions-int-int) | Importare un file CSV nelle celle.|
| [`merge(self, first_row, first_column, total_rows, total_columns)`](/cells/python-net/it/aspose.cells/cells/merge/#int-int-int-int) | Unisce un intervallo di celle specificato in un'unica cella.|
| [`merge(self, first_row, first_column, total_rows, total_columns, merge_conflict)`](/cells/python-net/it/aspose.cells/cells/merge/#int-int-int-int-bool) | Unisce un intervallo di celle specificato in un'unica cella.|
| [`merge(self, first_row, first_column, total_rows, total_columns, check_conflict, merge_conflict)`](/cells/python-net/it/aspose.cells/cells/merge/#int-int-int-int-bool-bool) | Unisce un intervallo di celle specificato in un'unica cella.|
| [`get_row_height(self, row, is_original, unit_type)`](/cells/python-net/it/aspose.cells/cells/get_row_height/#int-bool-aspose.cells.cellsunittype) | Ottiene l'altezza della riga.|
| [`get_row_height(self, row)`](/cells/python-net/it/aspose.cells/cells/get_row_height/#int) | Ottiene l'altezza di una riga specificata, in unità di punti.|
| [`get_column_width(self, column, is_original, unit_type)`](/cells/python-net/it/aspose.cells/cells/get_column_width/#int-bool-aspose.cells.cellsunittype) | Ottiene la larghezza della colonna.|
| [`get_column_width(self, column)`](/cells/python-net/it/aspose.cells/cells/get_column_width/#int) | Ottiene la larghezza (in unità di caratteri) della colonna specificata nella visualizzazione normale|
| [`get_column_width_pixel(self, column)`](/cells/python-net/it/aspose.cells/cells/get_column_width_pixel/#int) | Ottiene la larghezza della colonna specificata nella visualizzazione normale, in unità di pixel.|
| [`get_column_width_pixel(self, column, original)`](/cells/python-net/it/aspose.cells/cells/get_column_width_pixel/#int-bool) | Ottiene la larghezza della colonna specificata nella visualizzazione normale, in unità di pixel.|
| [`copy_columns(self, source_cells0, source_column_index, destination_column_index, column_number, paste_options)`](/cells/python-net/it/aspose.cells/cells/copy_columns/#aspose.cells.cells-int-int-int-aspose.cells.pasteoptions) | Copia i dati e i formati di un'intera colonna.|
| [`copy_columns(self, source_cells0, source_column_index, destination_column_index, column_number)`](/cells/python-net/it/aspose.cells/cells/copy_columns/#aspose.cells.cells-int-int-int) | Copia i dati e i formati di un'intera colonna.|
| [`copy_columns(self, source_cells, source_column_index, source_total_columns, destination_column_index, destination_total_columns)`](/cells/python-net/it/aspose.cells/cells/copy_columns/#aspose.cells.cells-int-int-int-int) | Copia i dati e i formati di tutte le colonne.|
| [`copy_rows(self, source_cells, source_row_index, destination_row_index, row_number)`](/cells/python-net/it/aspose.cells/cells/copy_rows/#aspose.cells.cells-int-int-int) | Copia i dati e i formati di alcune righe intere.|
| [`copy_rows(self, source_cells0, source_row_index, destination_row_index, row_number, copy_options)`](/cells/python-net/it/aspose.cells/cells/copy_rows/#aspose.cells.cells-int-int-int-aspose.cells.copyoptions) | Copia i dati e i formati di alcune righe intere.|
| [`copy_rows(self, source_cells0, source_row_index, destination_row_index, row_number, copy_options, paste_options)`](/cells/python-net/it/aspose.cells/cells/copy_rows/#aspose.cells.cells-int-int-int-aspose.cells.copyoptions-aspose.cells.pasteoptions) | Copia i dati e i formati di alcune righe intere.|
| [`group_columns(self, first_index, last_index)`](/cells/python-net/it/aspose.cells/cells/group_columns/#int-int) | Colonne dei gruppi.|
| [`group_columns(self, first_index, last_index, is_hidden)`](/cells/python-net/it/aspose.cells/cells/group_columns/#int-int-bool) | Colonne dei gruppi.|
| [`ungroup_rows(self, first_index, last_index, is_all)`](/cells/python-net/it/aspose.cells/cells/ungroup_rows/#int-int-bool) | Separa le righe.|
| [`ungroup_rows(self, first_index, last_index)`](/cells/python-net/it/aspose.cells/cells/ungroup_rows/#int-int) | Separa le righe.|
| [`group_rows(self, first_index, last_index, is_hidden)`](/cells/python-net/it/aspose.cells/cells/group_rows/#int-int-bool) | Raggruppa le righe.|
| [`group_rows(self, first_index, last_index)`](/cells/python-net/it/aspose.cells/cells/group_rows/#int-int) | Raggruppa le righe.|
| [`delete_column(self, column_index, update_reference)`](/cells/python-net/it/aspose.cells/cells/delete_column/#int-bool) | Elimina una colonna.|
| [`delete_column(self, column_index)`](/cells/python-net/it/aspose.cells/cells/delete_column/#int) | Elimina una colonna.|
| [`delete_columns(self, column_index, total_columns, update_reference)`](/cells/python-net/it/aspose.cells/cells/delete_columns/#int-int-bool) | Elimina diverse colonne.|
| [`delete_columns(self, column_index, total_columns, options)`](/cells/python-net/it/aspose.cells/cells/delete_columns/#int-int-aspose.cells.deleteoptions) | Elimina diverse colonne.|
| [`delete_row(self, row_index)`](/cells/python-net/it/aspose.cells/cells/delete_row/#int) | Elimina una riga.|
| [`delete_row(self, row_index, update_reference)`](/cells/python-net/it/aspose.cells/cells/delete_row/#int-bool) | Elimina una riga.|
| [`delete_rows(self, row_index, total_rows)`](/cells/python-net/it/aspose.cells/cells/delete_rows/#int-int) |Elimina più righe.|
| [`delete_rows(self, row_index, total_rows, update_reference)`](/cells/python-net/it/aspose.cells/cells/delete_rows/#int-int-bool) | Elimina più righe nel foglio di lavoro.|
| [`delete_rows(self, row_index, total_rows, options)`](/cells/python-net/it/aspose.cells/cells/delete_rows/#int-int-aspose.cells.deleteoptions) | Elimina più righe nel foglio di lavoro.|
| [`delete_blank_columns(self)`](/cells/python-net/it/aspose.cells/cells/delete_blank_columns/#) | Elimina tutte le colonne vuote che non contengono dati.|
| [`delete_blank_columns(self, options)`](/cells/python-net/it/aspose.cells/cells/delete_blank_columns/#aspose.cells.deleteoptions) | Elimina tutte le colonne vuote che non contengono dati.|
| [`delete_blank_rows(self)`](/cells/python-net/it/aspose.cells/cells/delete_blank_rows/#) | Elimina tutte le righe vuote che non contengono dati o altri oggetti.|
| [`delete_blank_rows(self, options)`](/cells/python-net/it/aspose.cells/cells/delete_blank_rows/#aspose.cells.deleteoptions) | Elimina tutte le righe vuote che non contengono dati o oggetti speciali, come commenti visibili e tabelle pivot.|
| [`insert_columns(self, column_index, total_columns)`](/cells/python-net/it/aspose.cells/cells/insert_columns/#int-int) | Inserisce alcune colonne nel foglio di lavoro.|
| [`insert_columns(self, column_index, total_columns, update_reference)`](/cells/python-net/it/aspose.cells/cells/insert_columns/#int-int-bool) | Inserisce alcune colonne nel foglio di lavoro.|
| [`insert_columns(self, column_index, total_columns, options)`](/cells/python-net/it/aspose.cells/cells/insert_columns/#int-int-aspose.cells.insertoptions) | Inserisce alcune colonne nel foglio di lavoro.|
| [`insert_column(self, column_index, update_reference)`](/cells/python-net/it/aspose.cells/cells/insert_column/#int-bool) | Inserisce una nuova colonna nel foglio di lavoro.|
| [`insert_column(self, column_index)`](/cells/python-net/it/aspose.cells/cells/insert_column/#int) | Inserisce una nuova colonna nel foglio di lavoro.|
| [`insert_rows(self, row_index, total_rows, update_reference)`](/cells/python-net/it/aspose.cells/cells/insert_rows/#int-int-bool) | Inserisce più righe nel foglio di lavoro.|
| [`insert_rows(self, row_index, total_rows, options)`](/cells/python-net/it/aspose.cells/cells/insert_rows/#int-int-aspose.cells.insertoptions) | Inserisce più righe nel foglio di lavoro.|
| [`insert_rows(self, row_index, total_rows)`](/cells/python-net/it/aspose.cells/cells/insert_rows/#int-int) | Inserisce più righe nel foglio di lavoro.|
| [`clear_range(self, range)`](/cells/python-net/it/aspose.cells/cells/clear_range/#aspose.cells.cellarea) | Cancella il contenuto e la formattazione di un intervallo.|
| [`clear_range(self, start_row, start_column, end_row, end_column)`](/cells/python-net/it/aspose.cells/cells/clear_range/#int-int-int-int) | Cancella il contenuto e la formattazione di un intervallo.|
| [`clear_contents(self, range)`](/cells/python-net/it/aspose.cells/cells/clear_contents/#aspose.cells.cellarea) | Cancella il contenuto di un intervallo.|
| [`clear_contents(self, start_row, start_column, end_row, end_column)`](/cells/python-net/it/aspose.cells/cells/clear_contents/#int-int-int-int) | Cancella il contenuto di un intervallo.|
| [`clear_formats(self, range)`](/cells/python-net/it/aspose.cells/cells/clear_formats/#aspose.cells.cellarea) | Cancella la formattazione di un intervallo.|
| [`clear_formats(self, start_row, start_column, end_row, end_column)`](/cells/python-net/it/aspose.cells/cells/clear_formats/#int-int-int-int) | Cancella la formattazione di un intervallo.|
| [`find(self, what, previous_cell)`](/cells/python-net/it/aspose.cells/cells/find/#any-aspose.cells.cell) | Trova la cella contenente l'oggetto di input.|
| [`find(self, what, previous_cell, find_options)`](/cells/python-net/it/aspose.cells/cells/find/#any-aspose.cells.cell-aspose.cells.findoptions) | Trova la cella contenente l'oggetto di input.|
| [`end_cell_in_row(self, row_index)`](/cells/python-net/it/aspose.cells/cells/end_cell_in_row/#int) | Ottiene l'ultima cella in questa riga.|
| [`end_cell_in_row(self, start_row, end_row, start_column, end_column)`](/cells/python-net/it/aspose.cells/cells/end_cell_in_row/#int-int-int-int) | Ottiene l'ultima cella con l'indice di riga massimo in questo intervallo.|
| [`end_cell_in_column(self, column_index)`](/cells/python-net/it/aspose.cells/cells/end_cell_in_column/#int) | Ottiene l'ultima cella in questa colonna.|
| [`end_cell_in_column(self, start_row, end_row, start_column, end_column)`](/cells/python-net/it/aspose.cells/cells/end_cell_in_column/#int-int-int-int) | Ottiene l'ultima cella con l'indice di colonna massimo in questo intervallo.|
| [`insert_range(self, area, shift_number, shift_type, update_reference)`](/cells/python-net/it/aspose.cells/cells/insert_range/#aspose.cells.cellarea-int-aspose.cells.shifttype-bool) | Inserisce un intervallo di celle e sposta le celle in base all'opzione Sposta.|
| [`insert_range(self, area, shift_type)`](/cells/python-net/it/aspose.cells/cells/insert_range/#aspose.cells.cellarea-aspose.cells.shifttype) | Inserisce un intervallo di celle e sposta le celle in base all'opzione Sposta.|
| [`insert_range(self, area, shift_number, shift_type)`](/cells/python-net/it/aspose.cells/cells/insert_range/#aspose.cells.cellarea-int-aspose.cells.shifttype) | Inserisce un intervallo di celle e sposta le celle in base all'opzione Sposta.|
| [`subtotal(self, ca, group_by, function, total_list)`](/cells/python-net/it/aspose.cells/cells/subtotal/#aspose.cells.cellarea-int-aspose.cells.consolidationfunction-list) | Crea subtotali per l'intervallo.|
| [`subtotal(self, ca, group_by, function, total_list, replace, page_breaks, summary_below_data)`](/cells/python-net/it/aspose.cells/cells/subtotal/#aspose.cells.cellarea-int-aspose.cells.consolidationfunction-list-bool-bool-bool) | Crea subtotali per l'intervallo.|
| [`remove_duplicates(self)`](/cells/python-net/it/aspose.cells/cells/remove_duplicates/#) |Rimuove le righe duplicate nel foglio.|
| [`remove_duplicates(self, start_row, start_column, end_row, end_column)`](/cells/python-net/it/aspose.cells/cells/remove_duplicates/#int-int-int-int) | Rimuove i valori duplicati nell'intervallo.|
| [`remove_duplicates(self, start_row, start_column, end_row, end_column, has_headers, column_offsets)`](/cells/python-net/it/aspose.cells/cells/remove_duplicates/#int-int-int-int-bool-list) | Rimuove i dati duplicati dell'intervallo.|
| [`get_cell_display_style(self, row, column)`](/cells/python-net/it/aspose.cells/cells/get_cell_display_style/#int-int) | Ottieni lo stile di visualizzazione della cella specificata.|
| [`get_cell_display_style(self, row, column, adjacent_borders)`](/cells/python-net/it/aspose.cells/cells/get_cell_display_style/#int-int-aspose.cells.bordertype) | Ottieni lo stile di visualizzazione della cella specificata.|
| [`get_row_enumerator(self)`](/cells/python-net/it/aspose.cells/cells/get_row_enumerator/#) | Ottiene l'enumeratore delle righe.|
| [`get_merged_areas(self)`](/cells/python-net/it/aspose.cells/cells/get_merged_areas/#) | Ottiene tutte le celle unite.|
| [`get_cell(self, row, column)`](/cells/python-net/it/aspose.cells/cells/get_cell/#int-int) | Ottiene l'elemento [`Cell`](/cells/python-net/it/aspose.cells/cell) o null all'indice di riga della cella e all'indice di colonna specificati.|
| [`get_row(self, row)`](/cells/python-net/it/aspose.cells/cells/get_row/#int) | Ottiene l'elemento [`Row`](/cells/python-net/it/aspose.cells/row) all'indice della riga della cella specificata.|
| [`check_cell(self, row, column)`](/cells/python-net/it/aspose.cells/cells/check_cell/#int-int) | Ottiene l'elemento [`Cell`](/cells/python-net/it/aspose.cells/cell) o null all'indice di riga della cella e all'indice di colonna specificati.|
| [`check_row(self, row)`](/cells/python-net/it/aspose.cells/cells/check_row/#int) | Ottiene l'elemento [`Row`](/cells/python-net/it/aspose.cells/row) o null nell'indice della riga della cella specificata.|
| [`check_column(self, column_index)`](/cells/python-net/it/aspose.cells/cells/check_column/#int) | Ottiene l'elemento [`Column`](/cells/python-net/it/aspose.cells/column) o null nell'indice di colonna specificato.|
| [`is_row_hidden(self, row_index)`](/cells/python-net/it/aspose.cells/cells/is_row_hidden/#int) | Controlla se una riga all'indice specificato è nascosta.|
| [`is_column_hidden(self, column_index)`](/cells/python-net/it/aspose.cells/cells/is_column_hidden/#int) | Controlla se una colonna all'indice specificato è nascosta.|
| [`add_range(self, range_object)`](/cells/python-net/it/aspose.cells/cells/add_range/#aspose.cells.range) | Aggiunge un riferimento all'oggetto intervallo alle celle|
| [`clear(self)`](/cells/python-net/it/aspose.cells/cells/clear/#) | Cancella tutti i dati del foglio di lavoro.|
| [`import_array_list(self, array_list, first_row, first_column, is_vertical)`](/cells/python-net/it/aspose.cells/cells/import_array_list/#list-int-int-bool) | Importa un arraylist di dati in un foglio di lavoro.|
| [`import_formula_array(self, string_array, first_row, first_column, is_vertical)`](/cells/python-net/it/aspose.cells/cells/import_formula_array/#list-int-int-bool) | Importa una matrice di formule in un foglio di lavoro.|
| [`text_to_columns(self, row, column, total_rows, options)`](/cells/python-net/it/aspose.cells/cells/text_to_columns/#int-int-int-aspose.cells.txtloadoptions) | Divide il contenuto della colonna specificata in più colonne.|
| [`un_merge(self, first_row, first_column, total_rows, total_columns)`](/cells/python-net/it/aspose.cells/cells/un_merge/#int-int-int-int) | Separa un intervallo specificato di celle unite.|
| [`clear_merged_cells(self)`](/cells/python-net/it/aspose.cells/cells/clear_merged_cells/#) | Cancella tutti gli intervalli uniti.|
| [`hide_row(self, row)`](/cells/python-net/it/aspose.cells/cells/hide_row/#int) |Nasconde una riga.|
| [`unhide_row(self, row, height)`](/cells/python-net/it/aspose.cells/cells/unhide_row/#int-float) | Visualizza una riga.|
| [`hide_rows(self, row, total_rows)`](/cells/python-net/it/aspose.cells/cells/hide_rows/#int-int) | Nasconde più righe.|
| [`unhide_rows(self, row, total_rows, height)`](/cells/python-net/it/aspose.cells/cells/unhide_rows/#int-int-float) | Visualizza le righe nascoste.|
| [`set_row_height_pixel(self, row, pixels)`](/cells/python-net/it/aspose.cells/cells/set_row_height_pixel/#int-int) | Imposta l'altezza della riga in pixel.|
| [`set_row_height_inch(self, row, inches)`](/cells/python-net/it/aspose.cells/cells/set_row_height_inch/#int-float) | Imposta l'altezza della riga in pollici.|
| [`set_row_height(self, row, height)`](/cells/python-net/it/aspose.cells/cells/set_row_height/#int-float) | Imposta l'altezza della riga specificata.|
| [`get_row_original_height_point(self, row)`](/cells/python-net/it/aspose.cells/cells/get_row_original_height_point/#int) | Ottiene l'altezza della riga originale in unità di punti se la riga è nascosta|
| [`get_column_original_width_point(self, column)`](/cells/python-net/it/aspose.cells/cells/get_column_original_width_point/#int) | Ottiene l'altezza della colonna originale in unità di punti se la colonna è nascosta|
| [`hide_column(self, column)`](/cells/python-net/it/aspose.cells/cells/hide_column/#int) | Nasconde una colonna.|
| [`unhide_column(self, column, width)`](/cells/python-net/it/aspose.cells/cells/unhide_column/#int-float) | Mostra una colonna|
| [`hide_columns(self, column, total_columns)`](/cells/python-net/it/aspose.cells/cells/hide_columns/#int-int) | Nascondi più colonne.|
| [`unhide_columns(self, column, total_columns, width)`](/cells/python-net/it/aspose.cells/cells/unhide_columns/#int-int-float) | Visualizza più colonne.|
| [`get_view_row_height(self, row)`](/cells/python-net/it/aspose.cells/cells/get_view_row_height/#int) | Ottiene l'altezza di una riga specificata.|
| [`get_row_height_inch(self, row)`](/cells/python-net/it/aspose.cells/cells/get_row_height_inch/#int) | Ottiene l'altezza di una riga specificata in pollici.|
| [`get_view_row_height_inch(self, row)`](/cells/python-net/it/aspose.cells/cells/get_view_row_height_inch/#int) | Ottiene l'altezza di una riga specificata in pollici.|
| [`get_row_height_pixel(self, row)`](/cells/python-net/it/aspose.cells/cells/get_row_height_pixel/#int) | Ottiene l'altezza di una riga specificata in pixel.|
| [`set_column_width_pixel(self, column, pixels)`](/cells/python-net/it/aspose.cells/cells/set_column_width_pixel/#int-int) | Imposta la larghezza della colonna in pixel nella visualizzazione normale.|
| [`set_column_width_inch(self, column, inches)`](/cells/python-net/it/aspose.cells/cells/set_column_width_inch/#int-float) | Imposta la larghezza della colonna in pollici nella visualizzazione normale.|
| [`set_column_width(self, column, width)`](/cells/python-net/it/aspose.cells/cells/set_column_width/#int-float) | Imposta la larghezza della colonna specificata nella visualizzazione normale.|
| [`get_column_width_inch(self, column)`](/cells/python-net/it/aspose.cells/cells/get_column_width_inch/#int) | Ottiene la larghezza della colonna specificata nella visualizzazione normale, in unità di pollici.|
| [`get_view_column_width_pixel(self, column)`](/cells/python-net/it/aspose.cells/cells/get_view_column_width_pixel/#int) | Ottieni la larghezza in diversi tipi di visualizzazione.|
| [`set_view_column_width_pixel(self, column, pixels)`](/cells/python-net/it/aspose.cells/cells/set_view_column_width_pixel/#int-int) |Imposta la larghezza della colonna in diverse viste.|
| [`get_last_data_row(self, column)`](/cells/python-net/it/aspose.cells/cells/get_last_data_row/#int) | Ottiene l'indice dell'ultima riga della cella che contiene dati nella colonna specificata.|
| [`get_first_data_row(self, column)`](/cells/python-net/it/aspose.cells/cells/get_first_data_row/#int) | Ottiene l'indice della prima riga della cella che contiene dati nella colonna specificata.|
| [`apply_column_style(self, column, style, flag)`](/cells/python-net/it/aspose.cells/cells/apply_column_style/#int-aspose.cells.style-aspose.cells.styleflag) | Applica i formati per un'intera colonna.|
| [`apply_row_style(self, row, style, flag)`](/cells/python-net/it/aspose.cells/cells/apply_row_style/#int-aspose.cells.style-aspose.cells.styleflag) | Applica i formati per un'intera riga.|
| [`apply_style(self, style, flag)`](/cells/python-net/it/aspose.cells/cells/apply_style/#aspose.cells.style-aspose.cells.styleflag) | Applica i formati per un intero foglio di lavoro.|
| [`copy_column(self, source_cells, source_column_index, destination_column_index)`](/cells/python-net/it/aspose.cells/cells/copy_column/#aspose.cells.cells-int-int) | Copia i dati e i formati di un'intera colonna.|
| [`copy_row(self, source_cells, source_row_index, destination_row_index)`](/cells/python-net/it/aspose.cells/cells/copy_row/#aspose.cells.cells-int-int) | Copia i dati e i formati di un'intera riga.|
| [`get_grouped_row_outline_level(self, row_index)`](/cells/python-net/it/aspose.cells/cells/get_grouped_row_outline_level/#int) | Ottiene il livello di struttura (a partire da zero) della riga.|
| [`get_grouped_column_outline_level(self, column_index)`](/cells/python-net/it/aspose.cells/cells/get_grouped_column_outline_level/#int) | Ottiene il livello di struttura (a partire da zero) della colonna.|
| [`get_max_grouped_column_outline_level(self)`](/cells/python-net/it/aspose.cells/cells/get_max_grouped_column_outline_level/#) | Ottiene il livello massimo di struttura delle colonne raggruppate (a partire da zero).|
| [`get_max_grouped_row_outline_level(self)`](/cells/python-net/it/aspose.cells/cells/get_max_grouped_row_outline_level/#) | Ottiene il livello massimo di struttura delle righe raggruppate (a partire da zero).|
| [`show_group_detail(self, is_vertical, index)`](/cells/python-net/it/aspose.cells/cells/show_group_detail/#bool-int) | Espande le righe/colonne raggruppate.|
| [`hide_group_detail(self, is_vertical, index)`](/cells/python-net/it/aspose.cells/cells/hide_group_detail/#bool-int) | Comprime le righe/colonne raggruppate.|
| [`ungroup_columns(self, first_index, last_index)`](/cells/python-net/it/aspose.cells/cells/ungroup_columns/#int-int) | Separa le colonne.|
| [`is_deleting_range_enabled(self, start_row, start_column, total_rows, total_columns)`](/cells/python-net/it/aspose.cells/cells/is_deleting_range_enabled/#int-int-int-int) | Controllare se l'intervallo può essere eliminato.|
| [`is_blank_column(self, column_index)`](/cells/python-net/it/aspose.cells/cells/is_blank_column/#int) | Controlla se la colonna specificata è vuota (non contiene dati).|
| [`insert_row(self, row_index)`](/cells/python-net/it/aspose.cells/cells/insert_row/#int) | Inserisce una nuova riga nel foglio di lavoro.|
| [`link_to_xml_map(self, map_name, row, column, path)`](/cells/python-net/it/aspose.cells/cells/link_to_xml_map/#str-int-int-str) | Collegamento a una mappa xml.|
| [`move_range(self, source_area, dest_row, dest_column)`](/cells/python-net/it/aspose.cells/cells/move_range/#aspose.cells.cellarea-int-int) | Sposta l'intervallo.|
| [`insert_cut_cells(self, cut_range, row, column, shift_type)`](/cells/python-net/it/aspose.cells/cells/insert_cut_cells/#aspose.cells.range-int-int-aspose.cells.shifttype) | Inserire intervallo di taglio.|
| [`delete_range(self, start_row, start_column, end_row, end_column, shift_type)`](/cells/python-net/it/aspose.cells/cells/delete_range/#int-int-int-int-aspose.cells.shifttype) |Elimina un intervallo di celle e sposta le celle in base all'opzione Sposta.|
| [`retrieve_subtotal_setting(self, ca)`](/cells/python-net/it/aspose.cells/cells/retrieve_subtotal_setting/#aspose.cells.cellarea) | Recupera l'impostazione dei subtotali dell'intervallo.|
| [`remove_formulas(self)`](/cells/python-net/it/aspose.cells/cells/remove_formulas/#) | Rimuove tutte le formule e le sostituisce con il valore della formula.|
| [`convert_string_to_numeric_value(self)`](/cells/python-net/it/aspose.cells/cells/convert_string_to_numeric_value/#) | Se possibile, converte tutti i dati stringa nel foglio di lavoro in valori numerici.|
| [`get_dependents(self, is_all, row, column)`](/cells/python-net/it/aspose.cells/cells/get_dependents/#bool-int-int) | Ottieni tutte le celle che fanno riferimento alla cella specifica.|
| [`get_dependents_in_calculation(self, row, column, recursive)`](/cells/python-net/it/aspose.cells/cells/get_dependents_in_calculation/#int-int-bool) | Ottiene tutte le celle il cui risultato calcolato dipende da una cella specifica.|
| [`get_cells_with_place_in_cell_picture(self)`](/cells/python-net/it/aspose.cells/cells/get_cells_with_place_in_cell_picture/#) | Ottiene tutte le celle che contengono un'immagine incorporata.|
| [`get_cell_style(self, row, column)`](/cells/python-net/it/aspose.cells/cells/get_cell_style/#int-int) | Ottieni lo stile della cella specificata.|



###  Osservazioni



###  Guarda anche
* modulo [`aspose.cells`](..)
* classe [`Cell`](/cells/python-net/it/aspose.cells/cell)
* classe [`Column`](/cells/python-net/it/aspose.cells/column)
* classe [`Range`](/cells/python-net/it/aspose.cells/range)
* classe [`Row`](/cells/python-net/it/aspose.cells/row)
