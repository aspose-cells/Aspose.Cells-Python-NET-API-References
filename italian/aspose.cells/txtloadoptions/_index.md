---
title: TxtLoadOptions classe
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 1580
url: /it/aspose.cells/txtloadoptions/
is_root: false
---
##  TxtLoadOptions classe
Rappresenta le opzioni per caricare il file di testo.



**Eredità:** [`TxtLoadOptions`](/cells/python-net/aspose.cells/txtloadoptions) → 
[`AbstractTextLoadOptions`](/cells/python-net/aspose.cells/abstracttextloadoptions) → 
[`LoadOptions`](/cells/python-net/it/aspose.cells/loadoptions)



Il tipo TxtLoadOptions espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [__init__](/cells/python-net/it/aspose.cells/txtloadoptions/__init__/#) | Crea le opzioni per caricare il file di testo.|
| [__init__](/cells/python-net/it/aspose.cells/txtloadoptions/__init__/#aspose.cells.LoadFormat) | Crea le opzioni per caricare il file di testo.|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [load_format](/cells/python-net/it/aspose.cells/txtloadoptions/load_format) | Ottiene il formato di caricamento.|
| [password](/cells/python-net/it/aspose.cells/txtloadoptions/password) | Ottiene e imposta la password della cartella di lavoro.|
| [parsing_formula_on_open](/cells/python-net/it/aspose.cells/txtloadoptions/parsing_formula_on_open) | Indica se si sta analizzando la formula durante la lettura del file.|
| [parsing_pivot_cached_records](/cells/python-net/it/aspose.cells/txtloadoptions/parsing_pivot_cached_records) | Indica se analizzare i record memorizzati nella cache pivot durante il caricamento del file.<br/> Il valore predefinito è falso.|
| [language_code](/cells/python-net/it/aspose.cells/txtloadoptions/language_code) | Ottiene o imposta la lingua dell'interfaccia utente della versione Workbook in base al CountryCode che ha salvato il file.|
| [region](/cells/python-net/it/aspose.cells/txtloadoptions/region) |Ottiene o imposta le impostazioni internazionali del sistema in base al CountryCode al momento del caricamento del file.|
| [default_style_settings](/cells/python-net/it/aspose.cells/txtloadoptions/default_style_settings) | Ottiene le impostazioni di stile predefinite per l'inizializzazione degli stili della cartella di lavoro|
| [standard_font](/cells/python-net/it/aspose.cells/txtloadoptions/standard_font) | Imposta il nome del carattere standard predefinito|
| [standard_font_size](/cells/python-net/it/aspose.cells/txtloadoptions/standard_font_size) | Imposta la dimensione del carattere standard predefinita.|
| [interrupt_monitor](/cells/python-net/it/aspose.cells/txtloadoptions/interrupt_monitor) | Ottiene e imposta il monitoraggio delle interruzioni.|
| [ignore_not_printed](/cells/python-net/it/aspose.cells/txtloadoptions/ignore_not_printed) | Ignorare i dati che non vengono stampati se si stampa direttamente il file|
| [check_data_valid](/cells/python-net/it/aspose.cells/txtloadoptions/check_data_valid) | Controlla se i dati sono validi nel file modello.|
| [check_excel_restriction](/cells/python-net/it/aspose.cells/txtloadoptions/check_excel_restriction) | Se controllare la restrizione del file Excel quando l'utente modifica gli oggetti correlati alle celle.<br/>Ad esempio, Excel non consente l'immissione di valori di stringa più lunghi di 32K.<br/>Quando inserisci un valore più lungo di 32 KB, ad esempio Cell.PutValue(string), se questa proprietà è vera, otterrai un'eccezione.<br/>Se questa proprietà è falsa, accetteremo il valore della stringa di input come valore della cella in modo che venga visualizzato in seguito<br/>è possibile restituire il valore stringa completo per altri formati di file come CSV.<br/>Tuttavia, se hai impostato un tipo di valore non valido per il formato file Excel,<br/> non dovresti salvare la cartella di lavoro come formato di file Excel in un secondo momento. Altrimenti potrebbe esserci un errore imprevisto per il file Excel generato.|
| [keep_unparsed_data](/cells/python-net/it/aspose.cells/txtloadoptions/keep_unparsed_data) | Indica se mantenere i dati non analizzati in memoria per la cartella di lavoro quando viene caricata dal file modello. L'impostazione predefinita è vera.|
| [load_filter](/cells/python-net/it/aspose.cells/txtloadoptions/load_filter) | Il filtro per indicare come caricare i dati.|
| [light_cells_data_handler](/cells/python-net/it/aspose.cells/txtloadoptions/light_cells_data_handler) | Il gestore dati per l'elaborazione dei dati delle celle durante la lettura del file modello.|
| [memory_setting](/cells/python-net/it/aspose.cells/txtloadoptions/memory_setting) | Ottiene o imposta le opzioni di utilizzo della memoria.|
| [warning_callback](/cells/python-net/it/aspose.cells/txtloadoptions/warning_callback) | Ottiene o imposta la richiamata di avviso.|
| [auto_fitter_options](/cells/python-net/it/aspose.cells/txtloadoptions/auto_fitter_options) | Ottiene e imposta le opzioni di adattamento automatico|
| [auto_filter](/cells/python-net/it/aspose.cells/txtloadoptions/auto_filter) | Indica se filtrare automaticamente i dati durante il caricamento dei file.|
| [font_configs](/cells/python-net/it/aspose.cells/txtloadoptions/font_configs) | Ottiene e imposta configurazioni di caratteri individuali.<br/> Funziona solo per lo [`Workbook`](/cells/python-net/it/aspose.cells/workbook) che utilizza questo [`LoadOptions`](/cells/python-net/it/aspose.cells/loadoptions) per caricare.|
| [ignore_useless_shapes](/cells/python-net/it/aspose.cells/txtloadoptions/ignore_useless_shapes) | Indica se ignorare le forme inutili.|
| [preserve_padding_spaces_in_formula](/cells/python-net/it/aspose.cells/txtloadoptions/preserve_padding_spaces_in_formula) | Indica se preservare gli spazi e le interruzioni di riga riempiti tra i token della formula<br/>durante l'acquisizione e l'impostazione delle formule.<br/> Il valore predefinito è falso.|
| [encoding](/cells/python-net/it/aspose.cells/txtloadoptions/encoding) |Ottiene e imposta la codifica predefinita. Si applica solo al file CSV.|
| [load_style_strategy](/cells/python-net/it/aspose.cells/txtloadoptions/load_style_strategy) | Indica la strategia per applicare lo stile per i valori analizzati durante la conversione del valore stringa in numero o data/ora.|
| [convert_numeric_data](/cells/python-net/it/aspose.cells/txtloadoptions/convert_numeric_data) | Ottiene o imposta un valore che indica se la stringa nel file di testo viene convertita in dati numerici.|
| [convert_date_time_data](/cells/python-net/it/aspose.cells/txtloadoptions/convert_date_time_data) | Ottiene o imposta un valore che indica se la stringa nel file di testo viene convertita in dati di data.|
| [keep_precision](/cells/python-net/it/aspose.cells/txtloadoptions/keep_precision) | Indica se non analizzare un valore stringa se la lunghezza è 15.|
| [separator](/cells/python-net/it/aspose.cells/txtloadoptions/separator) | Ottiene e imposta il separatore di caratteri del file di testo.|
| [separator_string](/cells/python-net/it/aspose.cells/txtloadoptions/separator_string) | Ottiene e imposta un valore stringa come separatore.|
| [is_multi_encoded](/cells/python-net/it/aspose.cells/txtloadoptions/is_multi_encoded) |Vero significa che il file contiene diverse codifiche.|
| [preferred_parsers](/cells/python-net/it/aspose.cells/txtloadoptions/preferred_parsers) | Ottiene e imposta i parser dei valori preferiti per il caricamento del file di testo.|
| [has_formula](/cells/python-net/it/aspose.cells/txtloadoptions/has_formula) | Indica se il testo è una formula se inizia con "=".|
| [has_text_qualifier](/cells/python-net/it/aspose.cells/txtloadoptions/has_text_qualifier) | Se è presente un qualificatore di testo per il valore della cella. L'impostazione predefinita è vera.|
| [text_qualifier](/cells/python-net/it/aspose.cells/txtloadoptions/text_qualifier) | Specifica il qualificatore di testo per i valori delle celle. Il qualificatore predefinito è '"'.|
| [treat_consecutive_delimiters_as_one](/cells/python-net/it/aspose.cells/txtloadoptions/treat_consecutive_delimiters_as_one) | Indica se i delimitatori consecutivi devono essere trattati come uno solo.|
| [treat_quote_prefix_as_value](/cells/python-net/it/aspose.cells/txtloadoptions/treat_quote_prefix_as_value) | Indica se il segno della virgoletta singola iniziale deve essere considerato come parte del valore di una cella.<br/>L'impostazione predefinita è vera. Se è falso, la virgoletta singola iniziale verrà rimossa dal valore della cella corrispondente<br/> e [`Style.quote_prefix`](/cells/python-net/it/aspose.cells/style#quote_prefix) verrà impostato come vero per la cella.|
| [extend_to_next_sheet](/cells/python-net/it/aspose.cells/txtloadoptions/extend_to_next_sheet) | Indica se estende i dati al foglio successivo quando le righe o le colonne di dati superano il limite.<br/> L'impostazione predefinita è falsa.|
| [header_rows_count](/cells/python-net/it/aspose.cells/txtloadoptions/header_rows_count) | Il conteggio delle righe di intestazione da ripetere per i fogli estesi.|
| [header_columns_count](/cells/python-net/it/aspose.cells/txtloadoptions/header_columns_count) | Il conteggio delle colonne di intestazione da ripetere per i fogli estesi.|
| [max_row_count](/cells/python-net/it/aspose.cells/txtloadoptions/max_row_count) | Il numero massimo di righe da importare per un foglio.|
| [max_column_count](/cells/python-net/it/aspose.cells/txtloadoptions/max_column_count) | Il numero massimo di colonne da importare per un foglio.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [set_paper_size](/cells/python-net/it/aspose.cells/txtloadoptions/set_paper_size/#aspose.cells.PaperSizeType) | Imposta il formato carta di stampa predefinito dalle impostazioni predefinite della stampante.|



###  Guarda anche
* modulo [`aspose.cells`](..)
* classe [`AbstractTextLoadOptions`](/cells/python-net/it/aspose.cells/abstracttextloadoptions)
* classe [`LoadOptions`](/cells/python-net/it/aspose.cells/loadoptions)
* classe [`TxtLoadOptions`](/cells/python-net/it/aspose.cells/txtloadoptions)
* classe [`Workbook`](/cells/python-net/it/aspose.cells/workbook)
