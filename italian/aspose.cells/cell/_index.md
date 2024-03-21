---
title: Cell classe
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 140
url: /it/aspose.cells/cell/
is_root: false
---
##  Cell classe
Incapsula l'oggetto che rappresenta una singola cella della cartella di lavoro.



Il tipo Cell espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [worksheet](/cells/python-net/it/aspose.cells/cell/worksheet) |Ottiene il foglio di lavoro padre.|
| [date_time_value](/cells/python-net/it/aspose.cells/cell/date_time_value) | Ottiene il valore DateTime contenuto nella cella.|
| [row](/cells/python-net/it/aspose.cells/cell/row) | Ottiene il numero di riga (in base zero) della cella.|
| [column](/cells/python-net/it/aspose.cells/cell/column) | Ottiene il numero di colonna (in base zero) della cella.|
| [is_formula](/cells/python-net/it/aspose.cells/cell/is_formula) | Rappresenta se la cella specificata contiene una formula.|
| [type](/cells/python-net/it/aspose.cells/cell/type) | Rappresenta il tipo di valore della cella.|
| [name](/cells/python-net/it/aspose.cells/cell/name) | Ottiene il nome della cella.|
| [is_error_value](/cells/python-net/it/aspose.cells/cell/is_error_value) | Controlla se il valore di questa cella è un errore.|
| [is_numeric_value](/cells/python-net/it/aspose.cells/cell/is_numeric_value) | Indica se il valore di questa cella è numerico (int, double e datetime)|
| [string_value](/cells/python-net/it/aspose.cells/cell/string_value) | Ottiene il valore stringa contenuto nella cella. Se il tipo di questa cella è stringa, restituisce il valore stringa stesso.<br/>Per gli altri tipi di cella, verrà restituito il valore stringa formattato (formattato con lo stile specificato di questa cella).<br/>Il valore della cella formattata è lo stesso di quello che puoi ottenere da Excel quando copi una cella come testo (come<br/> copiare la cella nell'editor di testo o esportarla in CSV).|
| [string_value_without_format](/cells/python-net/it/aspose.cells/cell/string_value_without_format) | Ottiene il valore della cella come stringa senza alcun formato.|
| [number_category_type](/cells/python-net/it/aspose.cells/cell/number_category_type) | Rappresenta il tipo di categoria della formattazione numerica di questa cella.|
| [display_string_value](/cells/python-net/it/aspose.cells/cell/display_string_value) | Ottiene il valore della stringa formattata di questa cella in base allo stile di visualizzazione della cella.|
| [int_value](/cells/python-net/it/aspose.cells/cell/int_value) | Ottiene il valore intero contenuto nella cella.|
| [double_value](/cells/python-net/it/aspose.cells/cell/double_value) | Ottiene il valore double contenuto nella cella.|
| [float_value](/cells/python-net/it/aspose.cells/cell/float_value) | Ottiene il valore float contenuto nella cella.|
| [bool_value](/cells/python-net/it/aspose.cells/cell/bool_value) |Ottiene il valore booleano contenuto nella cella.|
| [has_custom_style](/cells/python-net/it/aspose.cells/cell/has_custom_style) | Indica se questa cella ha impostazioni di stile personalizzate (diverse da quella predefinita ereditata<br/> dalla riga, colonna o cartella di lavoro corrispondente).|
| [shared_style_index](/cells/python-net/it/aspose.cells/cell/shared_style_index) | Ottiene l'indice di stile condiviso della cella nel pool di stili.|
| [formula](/cells/python-net/it/aspose.cells/cell/formula) | Ottiene o imposta una formula pari a [`Cell`](/cells/python-net/it/aspose.cells/cell).|
| [formula_local](/cells/python-net/it/aspose.cells/cell/formula_local) | Ottieni la formula formattata in base alle impostazioni locali della cella.|
| [r1c1_formula](/cells/python-net/it/aspose.cells/cell/r1c1_formula) | Ottiene o imposta una formula R1C1 di [`Cell`](/cells/python-net/it/aspose.cells/cell).|
| [contains_external_link](/cells/python-net/it/aspose.cells/cell/contains_external_link) | Indica se questa cella contiene un collegamento esterno.<br/> Si applica solo quando la cella è una cella formula.|
| [is_array_header](/cells/python-net/it/aspose.cells/cell/is_array_header) | Indica che la formula della cella è una formula di matrice<br/> ed è la prima cella dell'array.|
| [is_dynamic_array_formula](/cells/python-net/it/aspose.cells/cell/is_dynamic_array_formula) | Indica se la formula della cella è una formula in matrice dinamica (true) o una formula in matrice legacy (false).|
| [is_array_formula](/cells/python-net/it/aspose.cells/cell/is_array_formula) | Indica se la formula della cella è una formula di matrice.|
| [is_in_array](/cells/python-net/it/aspose.cells/cell/is_in_array) | Indica se la formula della cella è una formula di matrice.|
| [is_shared_formula](/cells/python-net/it/aspose.cells/cell/is_shared_formula) | Indica se la formula della cella fa parte di una formula condivisa.|
| [is_table_formula](/cells/python-net/it/aspose.cells/cell/is_table_formula) | Indica se questa cella fa parte della formula della tabella.|
| [is_in_table](/cells/python-net/it/aspose.cells/cell/is_in_table) | Indica se questa cella fa parte della formula della tabella.|
| [value](/cells/python-net/it/aspose.cells/cell/value) | Ottiene/imposta il valore contenuto in questa cella.|
| [is_style_set](/cells/python-net/it/aspose.cells/cell/is_style_set) |Indica se lo stile della cella è impostato. Se restituisce false, significa che questa cella ha un formato di cella predefinito.|
| [is_merged](/cells/python-net/it/aspose.cells/cell/is_merged) | Controlla se una cella fa parte di un intervallo unito o meno.|
| [comment](/cells/python-net/it/aspose.cells/cell/comment) | Ottiene il commento di questa cella.|
| [html_string](/cells/python-net/it/aspose.cells/cell/html_string) | Ottiene e imposta la stringa html che contiene dati e alcuni formati in questa cella.|
| [embedded_image](/cells/python-net/it/aspose.cells/cell/embedded_image) | Ottiene e imposta l'immagine incorporata nella cella.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [put_value](/cells/python-net/it/aspose.cells/cell/put_value/#bool) | Inserisce un valore booleano nella cella.|
| [put_value](/cells/python-net/it/aspose.cells/cell/put_value/#int) | Inserisce un valore intero nella cella.|
| [put_value](/cells/python-net/it/aspose.cells/cell/put_value/#float) | Inserisce un valore doppio nella cella.|
| [put_value](/cells/python-net/it/aspose.cells/cell/put_value/#str-bool-bool) | Inserisce un valore nella cella, se appropriato il valore verrà convertito in un altro tipo di dati e il formato numerico della cella verrà ripristinato.|
| [put_value](/cells/python-net/it/aspose.cells/cell/put_value/#str-bool) | Inserisce un valore stringa nella cella e, se appropriato, converte il valore in un altro tipo di dati.|
| [put_value](/cells/python-net/it/aspose.cells/cell/put_value/#str) | Inserisce un valore stringa nella cella.|
| [put_value](/cells/python-net/it/aspose.cells/cell/put_value/#DateTime) | Inserisce un valore DateTime nella cella.|
| [put_value](/cells/python-net/it/aspose.cells/cell/put_value/#any) | Inserisce un valore oggetto nella cella.|
| [get_display_style](/cells/python-net/it/aspose.cells/cell/get_display_style/#) | Ottiene lo stile di visualizzazione della cella.<br/>Se questa cella è influenzata anche da altre impostazioni come formattazione condizionale, elenco oggetti, ecc.,<br/>quindi lo stile di visualizzazione potrebbe essere diverso da cell.GetStyle().|
| [get_display_style](/cells/python-net/it/aspose.cells/cell/get_display_style/#bool) | Ottiene lo stile di visualizzazione della cella.<br/> Se la cella è formattata in modo condizionale, lo stile di visualizzazione non è lo stesso di cell.GetStyle().|
| [get_style](/cells/python-net/it/aspose.cells/cell/get_style/#) | Ottiene lo stile della cella.|
| [get_style](/cells/python-net/it/aspose.cells/cell/get_style/#bool) | Se checkBorders è vero, controlla se i bordi di altre celle influenzeranno lo stile di questa cella.|
| [set_style](/cells/python-net/it/aspose.cells/cell/set_style/#aspose.cells.Style) | Imposta lo stile della cella.|
| [set_style](/cells/python-net/it/aspose.cells/cell/set_style/#aspose.cells.Style-bool) | Applica la proprietà modificata di style alla cella.|
| [set_style](/cells/python-net/it/aspose.cells/cell/set_style/#aspose.cells.Style-aspose.cells.StyleFlag) | Applica lo stile della cella in base ai flag.|
| [set_formula](/cells/python-net/it/aspose.cells/cell/set_formula/#str-any) | Imposta la formula e il valore (risultato calcolato) della formula.|
| [set_formula](/cells/python-net/it/aspose.cells/cell/set_formula/#str-bool-bool-any) | Imposta la formula e il valore della formula.|
| [set_formula](/cells/python-net/it/aspose.cells/cell/set_formula/#str-aspose.cells.FormulaParseOptions-any) | Imposta la formula e il valore (risultato calcolato) della formula.|
| [set_array_formula](/cells/python-net/it/aspose.cells/cell/set_array_formula/#str-int-int-bool-bool) | Imposta una formula di matrice su un intervallo di celle.|
| [set_array_formula](/cells/python-net/it/aspose.cells/cell/set_array_formula/#str-int-int) | Imposta una formula di matrice (formula di matrice legacy inserita tramite CTRL+MAIUSC+INVIO in ms Excel) su un intervallo di celle.|
| [set_array_formula](/cells/python-net/it/aspose.cells/cell/set_array_formula/#str-int-int-aspose.cells.FormulaParseOptions) | Imposta una formula di matrice su un intervallo di celle.|
| [set_array_formula](/cells/python-net/it/aspose.cells/cell/set_array_formula/#str-int-int-aspose.cells.FormulaParseOptions-list) | Imposta una formula di matrice su un intervallo di celle.|
| [set_shared_formula](/cells/python-net/it/aspose.cells/cell/set_shared_formula/#str-int-int-bool-bool) | Imposta una formula su un intervallo di celle.|
| [set_shared_formula](/cells/python-net/it/aspose.cells/cell/set_shared_formula/#str-int-int) | Imposta le formule condivise su un intervallo di celle.|
| [set_shared_formula](/cells/python-net/it/aspose.cells/cell/set_shared_formula/#str-int-int-aspose.cells.FormulaParseOptions) | Imposta le formule condivise su un intervallo di celle.|
| [set_shared_formula](/cells/python-net/it/aspose.cells/cell/set_shared_formula/#str-int-int-aspose.cells.FormulaParseOptions-list) | Imposta le formule condivise su un intervallo di celle.|
| [get_leafs](/cells/python-net/it/aspose.cells/cell/get_leafs/#) | Ottieni tutte le celle che fanno riferimento direttamente a questa cella e devono essere aggiornate quando questa cella viene modificata.|
| [get_leafs](/cells/python-net/it/aspose.cells/cell/get_leafs/#bool) | Ottieni tutte le celle che verranno aggiornate quando questa cella viene modificata.|
| [set_dynamic_array_formula](/cells/python-net/it/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.FormulaParseOptions-bool) |Imposta la formula di matrice dinamica e, se possibile, fa in modo che la formula si diffonda nelle celle vicine.|
| [set_dynamic_array_formula](/cells/python-net/it/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.FormulaParseOptions-list-bool-bool) |Imposta la formula di matrice dinamica e, se possibile, fa in modo che la formula si diffonda nelle celle vicine.|
| [set_dynamic_array_formula](/cells/python-net/it/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.FormulaParseOptions-list-bool-bool-aspose.cells.CalculationOptions) |Imposta la formula di matrice dinamica e, se possibile, fa in modo che la formula si diffonda nelle celle vicine.|
| [set_table_formula](/cells/python-net/it/aspose.cells/cell/set_table_formula/#int-int-str-str-list) | Crea una tabella dati a due variabili per un determinato intervallo a partire da questa cella.|
| [set_table_formula](/cells/python-net/it/aspose.cells/cell/set_table_formula/#int-int-str-bool-list) | Crea una tabella dati a una variabile per un determinato intervallo a partire da questa cella.|
| [set_table_formula](/cells/python-net/it/aspose.cells/cell/set_table_formula/#int-int-int-int-int-int-list) | Crea una tabella dati a due variabili per un determinato intervallo a partire da questa cella.|
| [set_table_formula](/cells/python-net/it/aspose.cells/cell/set_table_formula/#int-int-int-int-bool-list) | Crea una tabella dati a una variabile per un determinato intervallo a partire da questa cella.|
| [get_characters](/cells/python-net/it/aspose.cells/cell/get_characters/#) | Restituisce tutti gli oggetti Characters<br/> che rappresenta un intervallo di caratteri all'interno del testo della cella.|
| [get_characters](/cells/python-net/it/aspose.cells/cell/get_characters/#bool) | Restituisce tutti gli oggetti Characters<br/> che rappresenta un intervallo di caratteri all'interno del testo della cella.|
| [calculate](/cells/python-net/it/aspose.cells/cell/calculate/#aspose.cells.CalculationOptions) | Calcola la formula della cella.|
| [get_string_value](/cells/python-net/it/aspose.cells/cell/get_string_value/#aspose.cells.CellValueFormatStrategy) | Ottiene il valore della stringa in base a una strategia formattata specifica.|
| [get_width_of_value](/cells/python-net/it/aspose.cells/cell/get_width_of_value/#) | Ottiene la larghezza del valore in unità di pixel.|
| [get_height_of_value](/cells/python-net/it/aspose.cells/cell/get_height_of_value/#) | Ottiene l'altezza del valore in unità di pixel.|
| [get_format_conditions](/cells/python-net/it/aspose.cells/cell/get_format_conditions/#) | Ottiene le condizioni di formato che si applicano a questa cella.|
| [get_formula](/cells/python-net/it/aspose.cells/cell/get_formula/#bool-bool) | Ottieni la formula di questa cella.|
| [get_precedents](/cells/python-net/it/aspose.cells/cell/get_precedents/#) | Ottiene tutti i riferimenti visualizzati nella formula di questa cella.|
| [get_dependents](/cells/python-net/it/aspose.cells/cell/get_dependents/#bool) | Ottieni tutte le celle la cui formula fa riferimento direttamente a questa cella.|
| [get_precedents_in_calculation](/cells/python-net/it/aspose.cells/cell/get_precedents_in_calculation/#) | Ottiene tutti i precedenti (riferimento alle celle nella cartella di lavoro corrente) utilizzati dalla formula di questa cella durante il calcolo.|
| [get_dependents_in_calculation](/cells/python-net/it/aspose.cells/cell/get_dependents_in_calculation/#bool) | Ottiene tutte le celle il cui risultato calcolato dipende da questa cella.|
| [get_array_range](/cells/python-net/it/aspose.cells/cell/get_array_range/#) |Ottiene l'intervallo di matrice se la formula della cella è una formula di matrice.|
| [remove_array_formula](/cells/python-net/it/aspose.cells/cell/remove_array_formula/#bool) | Rimuovi la formula di matrice.|
| [copy](/cells/python-net/it/aspose.cells/cell/copy/#aspose.cells.Cell) | Copia i dati da una cella di origine.|
| [characters](/cells/python-net/it/aspose.cells/cell/characters/#int-int) | Restituisce un oggetto Characters che rappresenta un intervallo di caratteri all'interno del testo della cella.|
| [replace](/cells/python-net/it/aspose.cells/cell/replace/#str-str-aspose.cells.ReplaceOptions) | Sostituisci il testo della cella con le opzioni.|
| [insert_text](/cells/python-net/it/aspose.cells/cell/insert_text/#int-str) | Inserisci alcuni caratteri nella cella.<br/> Se la cella è in formato RTF, questo metodo potrebbe mantenere la formattazione originale.|
| [is_rich_text](/cells/python-net/it/aspose.cells/cell/is_rich_text/#) | Indica se il valore stringa di questa cella è un testo in formato RTF.|
| [set_characters](/cells/python-net/it/aspose.cells/cell/set_characters/#list) | Imposta il formato RTF della cella.|
| [get_merged_range](/cells/python-net/it/aspose.cells/cell/get_merged_range/#) | Restituisce un oggetto [`Range`](/cells/python-net/it/aspose.cells/range) che rappresenta un intervallo unito.|
| [get_html_string](/cells/python-net/it/aspose.cells/cell/get_html_string/#bool) | Ottiene la stringa html che contiene i dati e alcuni formati in questa cella.|
| [to_json](/cells/python-net/it/aspose.cells/cell/to_json/#) | Converti i dati della struttura da [`Cell`](/cells/python-net/it/aspose.cells/cell) a JSON.|
| [equals](/cells/python-net/it/aspose.cells/cell/equals/#aspose.cells.Cell) | Controlla se questo oggetto si riferisce alla stessa cella con un altro oggetto cella.|
| [get_conditional_formatting_result](/cells/python-net/it/aspose.cells/cell/get_conditional_formatting_result/#) | Ottieni il risultato della formattazione condizionale.|
| [get_validation](/cells/python-net/it/aspose.cells/cell/get_validation/#) | Ottiene la convalida applicata a questa cella.|
| [get_validation_value](/cells/python-net/it/aspose.cells/cell/get_validation_value/#) | Ottiene il valore di convalida applicato a questa cella.|
| [get_table](/cells/python-net/it/aspose.cells/cell/get_table/#) |Ottiene la tabella che contiene questa cella.|



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
