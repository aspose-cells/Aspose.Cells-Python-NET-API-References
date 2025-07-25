---
title: SettableGlobalizationSettings classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 1310
url: /it/aspose.cells/settableglobalizationsettings/
is_root: false
---
##  SettableGlobalizationSettings classe
Implementazione di GlobalizationSettings che supporta l'utente nell'impostazione/modifica di testi predefiniti.



**Eredità:** [`SettableGlobalizationSettings`](/cells/python-net/aspose.cells/settableglobalizationsettings) → 
[`GlobalizationSettings`](/cells/python-net/it/aspose.cells/globalizationsettings)



Il tipo SettableGlobalizationSettings espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [`__init__(self)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/__init__/#) | Crea una nuova istanza di SettableGlobalizationSettings|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [chart_settings](/cells/python-net/it/aspose.cells/settableglobalizationsettings/chart_settings) | Ottiene o imposta le impostazioni di globalizzazione per Chart.|
| [pivot_settings](/cells/python-net/it/aspose.cells/settableglobalizationsettings/pivot_settings) | Ottiene o imposta le impostazioni di globalizzazione per la tabella pivot.|
| [list_separator](/cells/python-net/it/aspose.cells/settableglobalizationsettings/list_separator) | Ottiene il separatore per l'elenco, i parametri della funzione, ecc.|
| [row_separator_of_formula_array](/cells/python-net/it/aspose.cells/settableglobalizationsettings/row_separator_of_formula_array) | Ottiene il separatore per le righe nei dati dell'array nella formula.|
| [column_separator_of_formula_array](/cells/python-net/it/aspose.cells/settableglobalizationsettings/column_separator_of_formula_array) |Ottiene il separatore per gli elementi nei dati di riga dell'array nella formula.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`get_pivot_total_name(self)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/get_pivot_total_name/#) | Ottiene il nome dell'etichetta "Totale" nella tabella pivot.<br/> È necessario sovrascrivere questo metodo quando la tabella pivot contiene due o più campi pivot nell'area dati.|
| [`get_pivot_grand_total_name(self)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/get_pivot_grand_total_name/#) | Ottiene il nome dell'etichetta "Totale complessivo" nella tabella pivot.|
| [`get_multiple_items_name(self)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/get_multiple_items_name/#) | Ottiene il nome dell'etichetta "(Più elementi)" nella tabella pivot.|
| [`get_all_name(self)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/get_all_name/#) | Ottiene il nome dell'etichetta "(Tutti)" nella tabella pivot.|
| [`get_protection_name_of_pivot_table(self)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/get_protection_name_of_pivot_table/#) | Ottiene il nome della protezione nella tabella pivot.|
| [`get_column_labels_of_pivot_table(self)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/get_column_labels_of_pivot_table/#) | Ottiene il nome dell'etichetta "Etichette colonne" nella tabella pivot.|
| [`get_row_labels_name_of_pivot_table(self)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/get_row_labels_name_of_pivot_table/#) | Ottiene il nome dell'etichetta "Etichette di riga" nella tabella pivot.|
| [`get_empty_data_name(self)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/get_empty_data_name/#) | Ottiene il nome dell'etichetta "(vuota)" nella tabella pivot.|
| [`get_data_field_header_name_of_pivot_table(self)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/get_data_field_header_name_of_pivot_table/#) | Ottiene il nome dell'intestazione del campo dell'area valore nella tabella pivot.|
| [`get_sub_total_name(self, sub_total_type)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/get_sub_total_name/#aspose.cells.pivot.pivotfieldsubtotaltype) | Ottiene il nome del tipo [`PivotFieldSubtotalType`](/cells/python-net/it/aspose.cells.pivot/pivotfieldsubtotaltype) nella tabella pivot.|
| [`get_total_name(self, function_type)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/get_total_name/#aspose.cells.consolidationfunction) | Ottiene il nome completo della funzione specifica.|
| [`get_grand_total_name(self, function_type)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/get_grand_total_name/#aspose.cells.consolidationfunction) | Ottiene il nome del totale complessivo della funzione.|
| [`get_default_sheet_name(self)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/get_default_sheet_name/#) |Ottiene il nome del foglio predefinito per l'aggiunta automatica del foglio di lavoro.<br/> L'impostazione predefinita è "Foglio".|
| [`get_table_row_type_of_headers(self)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/get_table_row_type_of_headers/#) | Ottiene il nome del tipo di righe della tabella che comprende l'intestazione della tabella.<br/> L'impostazione predefinita è "Intestazioni", quindi nella formula "#Intestazioni" rappresenta l'intestazione della tabella.|
| [`get_table_row_type_of_data(self)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/get_table_row_type_of_data/#) | Ottiene il nome del tipo di righe della tabella che costituiscono l'area dati della tabella referenziata.<br/> Il valore predefinito è "Dati", quindi nella formula "#Dati" rappresenta l'area dati della tabella.|
| [`get_table_row_type_of_all(self)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/get_table_row_type_of_all/#) | Ottiene il nome del tipo di righe della tabella che comprende tutte le righe nella tabella a cui si fa riferimento.|
| [`get_table_row_type_of_totals(self)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/get_table_row_type_of_totals/#) | Ottiene il nome del tipo di righe della tabella che costituisce il numero totale di righe della tabella a cui si fa riferimento.|
| [`get_table_row_type_of_current(self)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/get_table_row_type_of_current/#) |Ottiene il nome del tipo di righe della tabella che costituisce la riga corrente nella tabella a cui si fa riferimento.|
| [`get_error_value_string(self, err)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/get_error_value_string/#str) | Ottiene il valore della stringa visualizzata per il valore di errore della cella|
| [`get_boolean_value_string(self, bv)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/get_boolean_value_string/#bool) | Ottiene il valore della stringa visualizzata per il valore booleano della cella|
| [`get_local_function_name(self, standard_name)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/get_local_function_name/#str) | Ottiene il nome della funzione dipendente dalle impostazioni locali in base al nome della funzione standard specificato.|
| [`get_standard_function_name(self, local_name)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/get_standard_function_name/#str) | Ottiene il nome della funzione standard in base al nome della funzione dipendente dalle impostazioni locali specificate.|
| [`get_local_built_in_name(self, standard_name)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/get_local_built_in_name/#str) | Ottiene il testo dipendente dalle impostazioni locali per il nome incorporato in base al testo standard fornito.|
| [`get_standard_built_in_name(self, local_name)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/get_standard_built_in_name/#str) | Ottiene il testo standard del nome incorporato in base al testo dipendente dalle impostazioni locali specificate.|
| [`get_standard_header_footer_font_style_name(self, localfont_style_name)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/get_standard_header_footer_font_style_name/#str) | Ottiene il nome dello stile del carattere inglese standard (normale, grassetto, corsivo) per intestazione/piè di pagina in base al nome dello stile del carattere locale specificato.|
| [`get_comment_title_name(self, type)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/get_comment_title_name/#aspose.cells.rendering.commenttitletype) | Ottiene il nome del titolo del commento dipendente dalle impostazioni locali in base al tipo di titolo del commento.|
| [`compare(self, v1, v2, ignore_case)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/compare/#str-str-bool) | Confronta due valori stringa in base a determinate regole di confronto.|
| [`set_total_name(self, function_type, name)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/set_total_name/#aspose.cells.consolidationfunction-str) | Imposta il nome completo della funzione specifica.|
| [`set_grand_total_name(self, function_type, name)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/set_grand_total_name/#aspose.cells.consolidationfunction-str) | Imposta il nome del totale generale della funzione specifica.|
| [`set_table_row_type_of_headers(self, name)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/set_table_row_type_of_headers/#str) | Imposta il nome del tipo di righe della tabella che comprende l'intestazione della tabella.|
| [`set_table_row_type_of_data(self, name)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/set_table_row_type_of_data/#str) | Imposta il nome del tipo di righe della tabella che consistono nell'area dati della tabella a cui si fa riferimento.|
| [`set_table_row_type_of_all(self, name)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/set_table_row_type_of_all/#str) | Imposta il nome del tipo di righe della tabella che comprende tutte le righe nella tabella a cui si fa riferimento.|
| [`set_table_row_type_of_totals(self, name)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/set_table_row_type_of_totals/#str) | Imposta il nome del tipo di righe della tabella che consiste nel numero totale di righe della tabella a cui si fa riferimento.|
| [`set_table_row_type_of_current(self, name)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/set_table_row_type_of_current/#str) | Imposta il nome del tipo di righe della tabella che comprende la riga corrente nella tabella a cui si fa riferimento.|
| [`set_boolean_value_string(self, bv, name)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/set_boolean_value_string/#bool-str) | Imposta il valore della stringa visualizzata per il valore booleano della cella|
| [`set_local_function_name(self, standard_name, local_name, bidirectional)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/set_local_function_name/#str-str-bool) | Imposta il nome della funzione dipendente dalle impostazioni locali corrispondente al nome della funzione standard specificato.|
| [`set_standard_function_name(self, local_name, standard_name, bidirectional)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/set_standard_function_name/#str-str-bool) | Imposta il nome della funzione dipendente dalle impostazioni locali in base al nome della funzione standard specificato.|
| [`set_local_built_in_name(self, standard_name, local_name, bidirectional)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/set_local_built_in_name/#str-str-bool) | Imposta il testo dipendente dalle impostazioni locali per il nome incorporato con il testo del nome standard fornito.|
| [`set_standard_built_in_name(self, local_name, standard_name, bidirectional)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/set_standard_built_in_name/#str-str-bool) | Imposta il nome della funzione dipendente dalle impostazioni locali in base al nome della funzione standard specificato.|
| [`set_list_separator(self, c)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/set_list_separator/#char) |Imposta il separatore per l'elenco, i parametri della funzione, ecc.|
| [`set_row_separator_of_formula_array(self, c)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/set_row_separator_of_formula_array/#char) | Imposta il separatore per le righe nei dati dell'array nella formula.|
| [`set_column_separator_of_formula_array(self, c)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/set_column_separator_of_formula_array/#char) | Imposta il separatore per gli elementi nei dati di riga dell'array nella formula.|
| [`set_standard_header_footer_font_style_name(self, localfont_style_name, standard_name)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/set_standard_header_footer_font_style_name/#str-str) | Imposta il nome della funzione dipendente dalle impostazioni locali in base al nome della funzione standard specificato.|
| [`set_comment_title_name(self, type, name)`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/set_comment_title_name/#aspose.cells.rendering.commenttitletype-str) | Ottiene il nome del titolo del commento dipendente dalle impostazioni locali in base al tipo di titolo del commento.|



###  Guarda anche
* modulo [`aspose.cells`](..)
* classe [`GlobalizationSettings`](/cells/python-net/it/aspose.cells/globalizationsettings)
* classe [`PivotFieldSubtotalType`](/cells/python-net/it/aspose.cells.pivot/pivotfieldsubtotaltype)
* classe [`SettableGlobalizationSettings`](/cells/python-net/it/aspose.cells/settableglobalizationsettings)
