---
title: CellsHelper classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 210
url: /it/aspose.cells/cellshelper/
is_root: false
---
##  CellsHelper classe
Fornisce funzioni di supporto.



Il tipo CellsHelper espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [significant_digits](/cells/python-net/it/aspose.cells/cellshelper/significant_digits) | Ottiene e imposta il numero di cifre significative.<br/> Il valore predefinito è 17.|
| [dpi](/cells/python-net/it/aspose.cells/cellshelper/dpi) | Ottiene i DPI della macchina.|
| [startup_path](/cells/python-net/it/aspose.cells/cellshelper/startup_path) | Ottiene o imposta il percorso di avvio, a cui fanno riferimento alcuni riferimenti a formule esterne.|
| [alt_start_path](/cells/python-net/it/aspose.cells/cellshelper/alt_start_path) | Ottiene o imposta il percorso di avvio alternativo, a cui fanno riferimento alcuni riferimenti a formule esterne.|
| [library_path](/cells/python-net/it/aspose.cells/cellshelper/library_path) |Ottiene o imposta il percorso della libreria a cui fanno riferimento alcuni riferimenti a formule esterne.|
| [custom_implementation_factory](/cells/python-net/it/aspose.cells/cellshelper/custom_implementation_factory) | Ottiene o imposta la factory per la creazione di istanze con implementazione speciale.|
| [is_cloud_platform](/cells/python-net/it/aspose.cells/cellshelper/is_cloud_platform) | Impostare questa proprietà su True quando si esegue su una piattaforma cloud, come: Azure, AWSLambda, ecc.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`create_safe_sheet_name(, name_proposal)`](/cells/python-net/it/aspose.cells/cellshelper/create_safe_sheet_name/#str) | Controlla il nome del foglio specificato e ne crea uno valido quando necessario.<br/>Se il nome del foglio specificato è conforme alle regole del nome del foglio Excel, allora restituiscilo.<br/>Altrimenti la stringa verrà troncata se la lunghezza supera il limite<br/> e i caratteri non validi verranno sostituiti con ' ', quindi verrà restituito il valore stringa ricostruito.|
| [`create_safe_sheet_name(, name_proposal, replace_char)`](/cells/python-net/it/aspose.cells/cellshelper/create_safe_sheet_name/#str-char) | Controlla il nome del foglio specificato e ne crea uno valido quando necessario.<br/>Se il nome del foglio specificato è conforme alle regole del nome del foglio Excel, allora restituiscilo.<br/>Altrimenti la stringa verrà troncata se la lunghezza supera il limite<br/> e i caratteri non validi verranno sostituiti con il carattere specificato, quindi verrà restituito il valore stringa ricostruito.|
| [`get_text_width(, text, font, scaling)`](/cells/python-net/it/aspose.cells/cellshelper/get_text_width/#str-aspose.cells.font-float) | Ottieni la larghezza del testo in unità di punti.|
| [`get_version()`](/cells/python-net/it/aspose.cells/cellshelper/get_version/#) | Ottieni la versione definitiva.|
| [`cell_name_to_index(, cell_name, row, column)`](/cells/python-net/it/aspose.cells/cellshelper/cell_name_to_index/#str-any-any) | Ottiene gli indici di riga e colonna della cella in base al suo nome.|
| [`cell_index_to_name(, row, column)`](/cells/python-net/it/aspose.cells/cellshelper/cell_index_to_name/#int-int) | Ottiene il nome della cella in base ai suoi indici di riga e di colonna.|
| [`column_index_to_name(, column)`](/cells/python-net/it/aspose.cells/cellshelper/column_index_to_name/#int) | Ottiene il nome della colonna in base all'indice della colonna.|
| [`column_name_to_index(, column_name)`](/cells/python-net/it/aspose.cells/cellshelper/column_name_to_index/#str) | Ottiene l'indice della colonna in base al nome della colonna.|
| [`row_index_to_name(, row)`](/cells/python-net/it/aspose.cells/cellshelper/row_index_to_name/#int) | Ottiene il nome della riga in base all'indice della riga.|
| [`row_name_to_index(, row_name)`](/cells/python-net/it/aspose.cells/cellshelper/row_name_to_index/#str) | Ottiene l'indice di riga in base al nome della riga.|
| [`convert_r1c1_formula_to_a1(, r_1c1_formula, row, column)`](/cells/python-net/it/aspose.cells/cellshelper/convert_r1c1_formula_to_a1/#str-int-int) | Converte la formula r1c1 della cella nella formula A1.|
| [`convert_a1_formula_to_r1c1(, formula, row, column)`](/cells/python-net/it/aspose.cells/cellshelper/convert_a1_formula_to_r1c1/#str-int-int) |Converte la formula A1 della cella nella formula r1c1.|
| [`get_date_time_from_double(, double_value, date1904)`](/cells/python-net/it/aspose.cells/cellshelper/get_date_time_from_double/#float-bool) | Converti il valore double nel valore date time.|
| [`get_double_from_date_time(, date_time, date1904)`](/cells/python-net/it/aspose.cells/cellshelper/get_double_from_date_time/#datetime-bool) | Converti la data e l'ora in un valore doppio.|
| [`get_used_colors(, workbook)`](/cells/python-net/it/aspose.cells/cellshelper/get_used_colors/#aspose.cells.workbook) | Ottiene tutti i colori utilizzati nella cartella di lavoro.|
| [`add_add_in_function(, function, min_count_of_parameters, max_count_of_parameters, paramers_type, function_value_type)`](/cells/python-net/it/aspose.cells/cellshelper/add_add_in_function/#str-int-int-list-aspose.cells.parametertype) | Aggiungere funzione aggiuntiva.|
| [`merge_files(, files, cached_file, dest_file)`](/cells/python-net/it/aspose.cells/cellshelper/merge_files/#list-str-str) | Unisce alcuni file xls di grandi dimensioni in un unico file xls.|
| [`get_cache_folder()`](/cells/python-net/it/aspose.cells/cellshelper/get_cache_folder/#) | Ottiene la cartella per i file temporanei che possono essere utilizzati come cache dati.|
| [`set_cache_folder(, cache)`](/cells/python-net/it/aspose.cells/cellshelper/set_cache_folder/#str) | Imposta la cartella per i file temporanei che possono essere utilizzati come cache dati.|
| [`need_quote_in_formula(, sheet_name)`](/cells/python-net/it/aspose.cells/cellshelper/need_quote_in_formula/#str) | Indica se il nome del foglio deve essere racchiuso tra virgolette singole|
| [`init_for_dot_net_core()`](/cells/python-net/it/aspose.cells/cellshelper/init_for_dot_net_core/#) | Eseguire l'inizializzazione per il programma .NetCore.<br/> Ti consigliamo di chiamare prima questo metodo per tutte le inizializzazioni .NetCore.<br/>Per esempio:<br/>CellsHelper.InitForDotNetCore();<br/> Cartella di lavoro wb = nuova cartella di lavoro();|



###  Guarda anche
* modulo [`aspose.cells`](..)
