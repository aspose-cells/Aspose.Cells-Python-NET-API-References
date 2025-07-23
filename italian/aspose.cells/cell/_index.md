---
title: Cell classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 110
url: /it/aspose.cells/cell/
is_root: false
---
##  Cell classe
Incapsula l'oggetto che rappresenta una singola cella della cartella di lavoro.



Il tipo Cell espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [worksheet](/cells/python-net/it/aspose.cells/cell/worksheet) | Ottiene il foglio di lavoro padre.|
| [date_time_value](/cells/python-net/it/aspose.cells/cell/date_time_value) | Ottiene il valore DateTime contenuto nella cella.|
| [row](/cells/python-net/it/aspose.cells/cell/row) | Ottiene il numero di riga (a partire da zero) della cella.|
| [column](/cells/python-net/it/aspose.cells/cell/column) | Ottiene il numero di colonna (a partire da zero) della cella.|
| [is_formula](/cells/python-net/it/aspose.cells/cell/is_formula) | Indica se la cella specificata contiene una formula.|
| [has_custom_function](/cells/python-net/it/aspose.cells/cell/has_custom_function) |Controlla se nella formula di questa cella è presente una funzione personalizzata (funzione non supportata).|
| [type](/cells/python-net/it/aspose.cells/cell/type) | Rappresenta il tipo di valore della cella.|
| [name](/cells/python-net/it/aspose.cells/cell/name) | Ottiene il nome della cella.|
| [is_error_value](/cells/python-net/it/aspose.cells/cell/is_error_value) | Controlla se il valore di questa cella è un errore.|
| [is_numeric_value](/cells/python-net/it/aspose.cells/cell/is_numeric_value) | Indica se il valore di questa cella è numerico (int, double e datetime)|
| [string_value](/cells/python-net/it/aspose.cells/cell/string_value) | Restituisce il valore stringa contenuto nella cella. Se il tipo di questa cella è stringa, restituisce il valore stringa stesso.<br/>Per altri tipi di cella, verrà restituito il valore stringa formattato (formattato con lo stile specificato per questa cella).<br/>Il valore della cella formattata è lo stesso che puoi ottenere da Excel quando copi una cella come testo (ad esempio<br/> copia della cella nell'editor di testo o esportazione in csv).|
| [string_value_without_format](/cells/python-net/it/aspose.cells/cell/string_value_without_format) | Ottiene il valore della cella come stringa senza alcun formato.|
| [number_category_type](/cells/python-net/it/aspose.cells/cell/number_category_type) | Rappresenta il tipo di categoria della formattazione numerica di questa cella.|
| [display_string_value](/cells/python-net/it/aspose.cells/cell/display_string_value) | Ottiene il valore stringa formattato di questa cella in base allo stile di visualizzazione della cella.|
| [int_value](/cells/python-net/it/aspose.cells/cell/int_value) | Ottiene il valore intero contenuto nella cella.|
| [double_value](/cells/python-net/it/aspose.cells/cell/double_value) | Ottiene il valore double contenuto nella cella.|
| [float_value](/cells/python-net/it/aspose.cells/cell/float_value) | Ottiene il valore float contenuto nella cella.|
| [bool_value](/cells/python-net/it/aspose.cells/cell/bool_value) | Ottiene il valore booleano contenuto nella cella.|
| [has_custom_style](/cells/python-net/it/aspose.cells/cell/has_custom_style) | Indica se questa cella ha impostazioni di stile personalizzate (diverse da quelle predefinite ereditate<br/>dalla riga, colonna o cartella di lavoro corrispondente).|
| [shared_style_index](/cells/python-net/it/aspose.cells/cell/shared_style_index) | Ottiene l'indice di stile condiviso della cella nel pool di stili.|
| [formula](/cells/python-net/it/aspose.cells/cell/formula) | Ottiene o imposta una formula di [`Cell`](/cells/python-net/it/aspose.cells/cell).|
| [formula_local](/cells/python-net/it/aspose.cells/cell/formula_local) | Ottieni la formula formattata localmente della cella.|
| [r1c1_formula](/cells/python-net/it/aspose.cells/cell/r1c1_formula) | Ottiene o imposta una formula R1C1 di [`Cell`](/cells/python-net/it/aspose.cells/cell).|
| [contains_external_link](/cells/python-net/it/aspose.cells/cell/contains_external_link) | Indica se questa cella contiene un collegamento esterno.<br/> Si applica solo quando la cella è una cella formula.|
| [is_array_header](/cells/python-net/it/aspose.cells/cell/is_array_header) | Indica che la formula della cella è una formula di matrice<br/> ed è la prima cella della matrice.|
| [is_dynamic_array_formula](/cells/python-net/it/aspose.cells/cell/is_dynamic_array_formula) | Indica se la formula della cella è una formula di matrice dinamica (true) o una formula di matrice legacy (false).|
| [is_array_formula](/cells/python-net/it/aspose.cells/cell/is_array_formula) | Indica se la formula della cella è una formula di matrice.|
| [is_in_array](/cells/python-net/it/aspose.cells/cell/is_in_array) | Indica se la formula della cella è una formula di matrice.|
| [is_shared_formula](/cells/python-net/it/aspose.cells/cell/is_shared_formula) | Indica se la formula della cella fa parte di una formula condivisa.|
| [is_table_formula](/cells/python-net/it/aspose.cells/cell/is_table_formula) | Indica se questa cella fa parte della formula della tabella.|
| [is_in_table](/cells/python-net/it/aspose.cells/cell/is_in_table) | Indica se questa cella fa parte della formula della tabella.|
| [value](/cells/python-net/it/aspose.cells/cell/value) | Ottiene/imposta il valore contenuto in questa cella.|
| [is_style_set](/cells/python-net/it/aspose.cells/cell/is_style_set) | Indica se lo stile della cella è impostato. Se restituisce "false", significa che questa cella ha un formato predefinito.|
| [is_merged](/cells/python-net/it/aspose.cells/cell/is_merged) | Controlla se una cella fa parte o meno di un intervallo unito.|
| [comment](/cells/python-net/it/aspose.cells/cell/comment) |Ottiene il commento di questa cella.|
| [html_string](/cells/python-net/it/aspose.cells/cell/html_string) | Ottiene e imposta la stringa HTML che contiene dati e alcuni formati in questa cella.|
| [is_check_box_style](/cells/python-net/it/aspose.cells/cell/is_check_box_style) | Indica se impostare questa cella come casella di controllo.|
| [embedded_image](/cells/python-net/it/aspose.cells/cell/embedded_image) | Ottiene e imposta l'immagine incorporata nella cella.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`put_value(self, bool_value)`](/cells/python-net/it/aspose.cells/cell/put_value/#bool) | Inserisce un valore booleano nella cella.|
| [`put_value(self, int_value)`](/cells/python-net/it/aspose.cells/cell/put_value/#int) | Inserisce un valore intero nella cella.|
| [`put_value(self, double_value)`](/cells/python-net/it/aspose.cells/cell/put_value/#float) | Inserisce un valore doppio nella cella.|
| [`put_value(self, string_value, is_converted, set_style)`](/cells/python-net/it/aspose.cells/cell/put_value/#str-bool-bool) | Inserisce un valore nella cella. Se appropriato, il valore verrà convertito in un altro tipo di dati e il formato numerico della cella verrà reimpostato.|
| [`put_value(self, string_value, is_converted)`](/cells/python-net/it/aspose.cells/cell/put_value/#str-bool) | Inserisce un valore stringa nella cella e, se appropriato, converte il valore in un altro tipo di dati.|
| [`put_value(self, string_value)`](/cells/python-net/it/aspose.cells/cell/put_value/#str) | Inserisce un valore stringa nella cella.|
| [`put_value(self, date_time)`](/cells/python-net/it/aspose.cells/cell/put_value/#datetime) | Inserisce un valore DateTime nella cella.|
| [`put_value(self, object_value)`](/cells/python-net/it/aspose.cells/cell/put_value/#any) | Inserisce un valore oggetto nella cella.|
| [`get_display_style(self)`](/cells/python-net/it/aspose.cells/cell/get_display_style/#) | Ottiene lo stile di visualizzazione di questa cella.|
| [`get_display_style(self, include_merged_borders)`](/cells/python-net/it/aspose.cells/cell/get_display_style/#bool) | Ottiene lo stile di visualizzazione di questa cella.|
| [`get_display_style(self, adjacent_borders)`](/cells/python-net/it/aspose.cells/cell/get_display_style/#aspose.cells.bordertype) | Ottiene lo stile di visualizzazione di questa cella.|
| [`get_style(self)`](/cells/python-net/it/aspose.cells/cell/get_style/#) | Ottiene lo stile della cella.|
| [`get_style(self, check_borders)`](/cells/python-net/it/aspose.cells/cell/get_style/#bool) | Se checkBorders è impostato su true, controlla se i bordi delle altre celle influenzeranno lo stile di questa cella.|
| [`set_style(self, style)`](/cells/python-net/it/aspose.cells/cell/set_style/#aspose.cells.style) | Imposta lo stile della cella.|
| [`set_style(self, style, explicit_flag)`](/cells/python-net/it/aspose.cells/cell/set_style/#aspose.cells.style-bool) | Applica la proprietà di stile modificata alla cella.|
| [`set_style(self, style, flag)`](/cells/python-net/it/aspose.cells/cell/set_style/#aspose.cells.style-aspose.cells.styleflag) |Applica lo stile della cella in base ai flag.|
| [`set_formula(self, formula, value)`](/cells/python-net/it/aspose.cells/cell/set_formula/#str-any) | Imposta la formula e il valore (risultato calcolato) della formula.|
| [`set_formula(self, formula, options)`](/cells/python-net/it/aspose.cells/cell/set_formula/#str-aspose.cells.formulaparseoptions) | Imposta la formula e il valore (risultato calcolato) della formula.|
| [`set_formula(self, formula, is_r1c1, is_local, value)`](/cells/python-net/it/aspose.cells/cell/set_formula/#str-bool-bool-any) | Imposta la formula e il valore della formula.|
| [`set_formula(self, formula, options, value)`](/cells/python-net/it/aspose.cells/cell/set_formula/#str-aspose.cells.formulaparseoptions-any) | Imposta la formula e il valore (risultato calcolato) della formula.|
| [`set_array_formula(self, array_formula, row_number, column_number, is_r1c1, is_local)`](/cells/python-net/it/aspose.cells/cell/set_array_formula/#str-int-int-bool-bool) | Imposta una formula di matrice su un intervallo di celle.|
| [`set_array_formula(self, array_formula, row_number, column_number)`](/cells/python-net/it/aspose.cells/cell/set_array_formula/#str-int-int) | Imposta una formula di matrice (formula di matrice legacy immessa tramite CTRL+MAIUSC+INVIO in MS Excel) su un intervallo di celle.|
| [`set_array_formula(self, array_formula, row_number, column_number, options)`](/cells/python-net/it/aspose.cells/cell/set_array_formula/#str-int-int-aspose.cells.formulaparseoptions) | Imposta una formula di matrice su un intervallo di celle.|
| [`set_array_formula(self, array_formula, row_number, column_number, options, values)`](/cells/python-net/it/aspose.cells/cell/set_array_formula/#str-int-int-aspose.cells.formulaparseoptions-list) | Imposta una formula di matrice su un intervallo di celle.|
| [`set_shared_formula(self, shared_formula, row_number, column_number, is_r1c1, is_local)`](/cells/python-net/it/aspose.cells/cell/set_shared_formula/#str-int-int-bool-bool) | Imposta una formula su un intervallo di celle.|
| [`set_shared_formula(self, shared_formula, row_number, column_number)`](/cells/python-net/it/aspose.cells/cell/set_shared_formula/#str-int-int) | Imposta le formule condivise su un intervallo di celle.|
| [`set_shared_formula(self, shared_formula, row_number, column_number, options)`](/cells/python-net/it/aspose.cells/cell/set_shared_formula/#str-int-int-aspose.cells.formulaparseoptions) | Imposta le formule condivise su un intervallo di celle.|
| [`set_shared_formula(self, shared_formula, row_number, column_number, options, values)`](/cells/python-net/it/aspose.cells/cell/set_shared_formula/#str-int-int-aspose.cells.formulaparseoptions-list) | Imposta le formule condivise su un intervallo di celle.|
| [`get_leafs(self)`](/cells/python-net/it/aspose.cells/cell/get_leafs/#) | Ottieni tutte le celle che fanno riferimento direttamente a questa cella e che devono essere aggiornate quando questa cella viene modificata.|
| [`get_leafs(self, recursive)`](/cells/python-net/it/aspose.cells/cell/get_leafs/#bool) | Ottieni tutte le celle che verranno aggiornate quando questa cella viene modificata.|
| [`set_dynamic_array_formula(self, array_formula, options, calculate_value)`](/cells/python-net/it/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.formulaparseoptions-bool) | Imposta una formula di matrice dinamica e, se possibile, fa sì che la formula si estenda alle celle adiacenti.|
| [`set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value)`](/cells/python-net/it/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.formulaparseoptions-list-bool-bool) | Imposta una formula di matrice dinamica e, se possibile, fa sì che la formula si estenda alle celle adiacenti.|
| [`set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value, copts)`](/cells/python-net/it/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.formulaparseoptions-list-bool-bool-aspose.cells.calculationoptions) | Imposta una formula di matrice dinamica e, se possibile, fa sì che la formula si estenda alle celle adiacenti.|
| [`set_table_formula(self, row_number, column_number, row_input_cell, column_input_cell, values)`](/cells/python-net/it/aspose.cells/cell/set_table_formula/#int-int-str-str-list) | Crea una tabella dati a due variabili per l'intervallo specificato a partire da questa cella.|
| [`set_table_formula(self, row_number, column_number, input_cell, is_row_input, values)`](/cells/python-net/it/aspose.cells/cell/set_table_formula/#int-int-str-bool-list) | Crea una tabella dati a una variabile per l'intervallo specificato a partire da questa cella.|
| [`set_table_formula(self, row_number, column_number, row_index_of_row_input_cell, column_index_of_row_input_cell, row_index_of_column_input_cell, column_index_of_column_input_cell, values)`](/cells/python-net/it/aspose.cells/cell/set_table_formula/#int-int-int-int-int-int-list) | Crea una tabella dati a due variabili per l'intervallo specificato a partire da questa cella.|
| [`set_table_formula(self, row_number, column_number, row_index_of_input_cell, column_index_of_input_cell, is_row_input, values)`](/cells/python-net/it/aspose.cells/cell/set_table_formula/#int-int-int-int-bool-list) | Crea una tabella dati a una variabile per l'intervallo specificato a partire da questa cella.|
| [`get_characters(self)`](/cells/python-net/it/aspose.cells/cell/get_characters/#) | Restituisce tutti gli oggetti Characters<br/> che rappresenta un intervallo di caratteri all'interno del testo della cella.|
| [`get_characters(self, flag)`](/cells/python-net/it/aspose.cells/cell/get_characters/#bool) | Restituisce tutti gli oggetti Characters<br/> che rappresenta un intervallo di caratteri all'interno del testo della cella.|
| [`calculate(self, options)`](/cells/python-net/it/aspose.cells/cell/calculate/#aspose.cells.calculationoptions) | Calcola la formula della cella.|
| [`get_string_value(self, format_strategy)`](/cells/python-net/it/aspose.cells/cell/get_string_value/#aspose.cells.cellvalueformatstrategy) |Ottiene il valore stringa tramite una strategia di formattazione specifica.|
| [`get_width_of_value(self)`](/cells/python-net/it/aspose.cells/cell/get_width_of_value/#) | Ottiene la larghezza del valore in unità di pixel.|
| [`get_height_of_value(self)`](/cells/python-net/it/aspose.cells/cell/get_height_of_value/#) | Ottiene l'altezza del valore in unità di pixel.|
| [`get_format_conditions(self)`](/cells/python-net/it/aspose.cells/cell/get_format_conditions/#) | Ottiene le condizioni di formato che si applicano a questa cella.|
| [`get_formula(self, is_r1c1, is_local)`](/cells/python-net/it/aspose.cells/cell/get_formula/#bool-bool) | Ottieni la formula di questa cella.|
| [`get_precedents(self)`](/cells/python-net/it/aspose.cells/cell/get_precedents/#) | Ottiene tutti i riferimenti presenti nella formula di questa cella.|
| [`get_dependents(self, is_all)`](/cells/python-net/it/aspose.cells/cell/get_dependents/#bool) | Ottieni tutte le celle la cui formula fa riferimento direttamente a questa cella.|
| [`get_precedents_in_calculation(self)`](/cells/python-net/it/aspose.cells/cell/get_precedents_in_calculation/#) | Ottiene tutti i precedenti (riferimenti alle celle nella cartella di lavoro corrente) utilizzati dalla formula di questa cella durante il calcolo.|
| [`get_dependents_in_calculation(self, recursive)`](/cells/python-net/it/aspose.cells/cell/get_dependents_in_calculation/#bool) | Ottiene tutte le celle il cui risultato calcolato dipende da questa cella.|
| [`get_array_range(self)`](/cells/python-net/it/aspose.cells/cell/get_array_range/#) | Ottiene l'intervallo della matrice se la formula della cella è una formula di matrice.|
| [`remove_array_formula(self, leave_normal_formula)`](/cells/python-net/it/aspose.cells/cell/remove_array_formula/#bool) | Rimuovi la formula matrice.|
| [`copy(self, cell)`](/cells/python-net/it/aspose.cells/cell/copy/#aspose.cells.cell) | Copia i dati da una cella sorgente.|
| [`characters(self, start_index, length)`](/cells/python-net/it/aspose.cells/cell/characters/#int-int) | Restituisce un oggetto Characters che rappresenta un intervallo di caratteri all'interno del testo della cella.|
| [`replace(self, place_holder, new_value, options)`](/cells/python-net/it/aspose.cells/cell/replace/#str-str-aspose.cells.replaceoptions) | Sostituisci il testo della cella con le opzioni.|
| [`insert_text(self, index, text)`](/cells/python-net/it/aspose.cells/cell/insert_text/#int-str) | Inserire alcuni caratteri nella cella.<br/> Se la cella è formattata in modo avanzato, questo metodo potrebbe mantenere la formattazione originale.|
| [`is_rich_text(self)`](/cells/python-net/it/aspose.cells/cell/is_rich_text/#) |Indica se il valore stringa di questa cella è un testo formattato.|
| [`set_characters(self, characters)`](/cells/python-net/it/aspose.cells/cell/set_characters/#list) | Imposta il formato RTF della cella.|
| [`get_merged_range(self)`](/cells/python-net/it/aspose.cells/cell/get_merged_range/#) | Restituisce un oggetto [`Range`](/cells/python-net/it/aspose.cells/range) che rappresenta un intervallo unito.|
| [`get_html_string(self, html5)`](/cells/python-net/it/aspose.cells/cell/get_html_string/#bool) | Ottiene la stringa HTML che contiene dati e alcuni formati in questa cella.|
| [`to_json(self)`](/cells/python-net/it/aspose.cells/cell/to_json/#) | Converti i dati della struttura [`Cell`](/cells/python-net/it/aspose.cells/cell) in JSON.|
| [`equals(self, cell)`](/cells/python-net/it/aspose.cells/cell/equals/#aspose.cells.cell) | Controlla se questo oggetto fa riferimento alla stessa cella con un altro oggetto cella.|
| [`get_conditional_formatting_result(self)`](/cells/python-net/it/aspose.cells/cell/get_conditional_formatting_result/#) | Ottieni il risultato della formattazione condizionale.|
| [`get_validation(self)`](/cells/python-net/it/aspose.cells/cell/get_validation/#) | Ottiene la convalida applicata a questa cella.|
| [`get_validation_value(self)`](/cells/python-net/it/aspose.cells/cell/get_validation_value/#) | Ottiene il valore di convalida applicato a questa cella.|
| [`get_table(self)`](/cells/python-net/it/aspose.cells/cell/get_table/#) | Ottiene la tabella che contiene questa cella.|
| [`get_rich_value(self)`](/cells/python-net/it/aspose.cells/cell/get_rich_value/#) | Ottiene il valore aggiunto della cella.|



###  Esempio

```python
from aspose.cells import TextAlignmentType, Workbook
from aspose.pydrawing import Color

excel = Workbook()
cells = excel.worksheets[0].cells
# Put a string into a cell
cell = cells.get(0, 0)
cell.put_value("Hello")
first = cell.string_value
# Put an integer into a cell
cell = cells.get("B1")
cell.put_value(12)
second = cell.int_value
# Put a double into a cell
cell = cells.get(0, 2)
cell.put_value(-1.234)
third = cell.double_value
# Put a formula into a cell
cell = cells.get("D1")
cell.formula = "=B1 + C1"
# Put a combined formula: "sum(average(b1,c1), b1)" to cell at b2
cell = cells.get("b2")
cell.formula = "=sum(average(b1,c1), b1)"
# Set style of a cell
style = cell.get_style()
# Set background color
style.background_color = Color.yellow
# Set format of a cell
style.font.name = "Courier New"
style.vertical_alignment = TextAlignmentType.TOP
cell.set_style(style)

```

###  Guarda anche
* modulo [`aspose.cells`](..)
* classe [`Cell`](/cells/python-net/it/aspose.cells/cell)
* classe [`Range`](/cells/python-net/it/aspose.cells/range)
