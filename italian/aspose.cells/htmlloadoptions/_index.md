---
title: HtmlLoadOptions classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 780
url: /it/aspose.cells/htmlloadoptions/
is_root: false
---
##  HtmlLoadOptions classe
Rappresenta le opzioni durante l'importazione di un file HTML.



**Eredità:** [`HtmlLoadOptions`](/cells/python-net/aspose.cells/htmlloadoptions) → 
[`AbstractTextLoadOptions`](/cells/python-net/aspose.cells/abstracttextloadoptions) → 
[`LoadOptions`](/cells/python-net/it/aspose.cells/loadoptions)



Il tipo HtmlLoadOptions espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [`__init__(self)`](/cells/python-net/it/aspose.cells/htmlloadoptions/__init__/#) | Crea un'opzione per il caricamento del file.|
| [`__init__(self, load_format)`](/cells/python-net/it/aspose.cells/htmlloadoptions/__init__/#aspose.cells.loadformat) | Crea un'opzione per il caricamento del file.|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [load_format](/cells/python-net/it/aspose.cells/htmlloadoptions/load_format) | Ottiene il formato di caricamento.|
| [password](/cells/python-net/it/aspose.cells/htmlloadoptions/password) | Ottiene e imposta la password della cartella di lavoro.|
| [parsing_formula_on_open](/cells/python-net/it/aspose.cells/htmlloadoptions/parsing_formula_on_open) | Indica se analizzare la formula durante la lettura del file.|
| [parsing_pivot_cached_records](/cells/python-net/it/aspose.cells/htmlloadoptions/parsing_pivot_cached_records) | Indica se analizzare i record memorizzati nella cache del pivot durante il caricamento del file.<br/> Il valore predefinito è falso.|
| [language_code](/cells/python-net/it/aspose.cells/htmlloadoptions/language_code) | Ottiene o imposta la lingua dell'interfaccia utente della versione della cartella di lavoro in base al CountryCode in cui è stato salvato il file.|
| [region](/cells/python-net/it/aspose.cells/htmlloadoptions/region) | Ottiene o imposta le impostazioni regionali utilizzate per la cartella di lavoro che verrà caricata.|
| [default_style_settings](/cells/python-net/it/aspose.cells/htmlloadoptions/default_style_settings) | Ottiene le impostazioni di stile predefinite per l'inizializzazione degli stili della cartella di lavoro|
| [standard_font](/cells/python-net/it/aspose.cells/htmlloadoptions/standard_font) | Imposta il nome del font standard predefinito|
| [standard_font_size](/cells/python-net/it/aspose.cells/htmlloadoptions/standard_font_size) | Imposta la dimensione standard predefinita del carattere.|
| [ignore_not_printed](/cells/python-net/it/aspose.cells/htmlloadoptions/ignore_not_printed) | Ignora i dati che non vengono stampati se si stampa direttamente il file|
| [check_data_valid](/cells/python-net/it/aspose.cells/htmlloadoptions/check_data_valid) | Controllare se i dati nel file modello sono validi.|
| [check_excel_restriction](/cells/python-net/it/aspose.cells/htmlloadoptions/check_excel_restriction) | Se verificare la restrizione del file Excel quando l'utente modifica celle con oggetti correlati.<br/>Ad esempio, Excel non consente di immettere valori stringa più lunghi di 32K.<br/>Quando si immette un valore più lungo di 32K, ad esempio Cell.PutValue(string), se questa proprietà è vera, si otterrà un'eccezione.<br/>Se questa proprietà è falsa, accetteremo il valore della stringa di input come valore della cella in modo che in seguito<br/>è possibile restituire il valore stringa completo per altri formati di file, ad esempio CSV.<br/>Tuttavia, se hai impostato un valore di questo tipo che non è valido per il formato di file Excel,<br/>Non salvare la cartella di lavoro in formato Excel in un secondo momento. In caso contrario, potrebbe verificarsi un errore imprevisto nel file Excel generato.|
| [keep_unparsed_data](/cells/python-net/it/aspose.cells/htmlloadoptions/keep_unparsed_data) | Mantenere in memoria i dati non analizzati per la cartella di lavoro quando viene caricata dal file modello. Il valore predefinito è true.|
| [load_filter](/cells/python-net/it/aspose.cells/htmlloadoptions/load_filter) | Il filtro per indicare come caricare i dati.|
| [memory_setting](/cells/python-net/it/aspose.cells/htmlloadoptions/memory_setting) | Ottiene o imposta la modalità di memoria per la cartella di lavoro caricata.|
| [auto_fitter_options](/cells/python-net/it/aspose.cells/htmlloadoptions/auto_fitter_options) | Ottiene e imposta le opzioni di adattamento automatico|
| [auto_filter](/cells/python-net/it/aspose.cells/htmlloadoptions/auto_filter) | Indica se filtrare automaticamente i dati durante il caricamento dei file.|
| [font_configs](/cells/python-net/it/aspose.cells/htmlloadoptions/font_configs) | Ottiene e imposta le singole configurazioni dei font.<br/> Funziona solo per [`Workbook`](/cells/python-net/it/aspose.cells/workbook) che utilizza questo [`LoadOptions`](/cells/python-net/it/aspose.cells/loadoptions) per caricare.|
| [ignore_useless_shapes](/cells/python-net/it/aspose.cells/htmlloadoptions/ignore_useless_shapes) | Indica se ignorare le forme inutili.|
| [preserve_padding_spaces_in_formula](/cells/python-net/it/aspose.cells/htmlloadoptions/preserve_padding_spaces_in_formula) | Indica se conservare gli spazi e le interruzioni di riga che vengono aggiunti tra i token della formula<br/>durante l'ottenimento e l'impostazione delle formule.<br/> Il valore predefinito è falso.|
| [encoding](/cells/python-net/it/aspose.cells/htmlloadoptions/encoding) | Ottiene e imposta la codifica predefinita. Si applica solo ai file CSV.|
| [load_style_strategy](/cells/python-net/it/aspose.cells/htmlloadoptions/load_style_strategy) | Indica la strategia da applicare allo stile per i valori analizzati durante la conversione del valore stringa in numero o data e ora.|
| [convert_numeric_data](/cells/python-net/it/aspose.cells/htmlloadoptions/convert_numeric_data) |Ottiene o imposta un valore che indica se la stringa nel file di testo viene convertita in dati numerici.|
| [convert_date_time_data](/cells/python-net/it/aspose.cells/htmlloadoptions/convert_date_time_data) | Ottiene o imposta un valore che indica se la stringa nel file di testo viene convertita in dati di data.|
| [keep_precision](/cells/python-net/it/aspose.cells/htmlloadoptions/keep_precision) | Indica se non analizzare un valore stringa se la lunghezza è 15.|
| [attached_files_directory](/cells/python-net/it/aspose.cells/htmlloadoptions/attached_files_directory) | La directory in cui verranno salvati i file allegati.|
| [load_formulas](/cells/python-net/it/aspose.cells/htmlloadoptions/load_formulas) | Indica se importare formule se il file html originale contiene formule|
| [support_div_tag](/cells/python-net/it/aspose.cells/htmlloadoptions/support_div_tag) | Indica se supportare il layout del tag `<div>` quando il file HTML lo contiene.<br/> Il valore predefinito è falso.|
| [delete_redundant_spaces](/cells/python-net/it/aspose.cells/htmlloadoptions/delete_redundant_spaces) | Indica se eliminare gli spazi ridondanti quando il testo va a capo utilizzando il tag `<br>`.<br/> Il valore predefinito è falso.|
| [auto_fit_cols_and_rows](/cells/python-net/it/aspose.cells/htmlloadoptions/auto_fit_cols_and_rows) | Indica se adattare automaticamente colonne e righe. Il valore predefinito è "false".|
| [convert_formulas_data](/cells/python-net/it/aspose.cells/htmlloadoptions/convert_formulas_data) |se vero, converte la stringa in formula quando il valore della stringa inizia con il carattere '='; il valore predefinito è falso.|
| [has_formula](/cells/python-net/it/aspose.cells/htmlloadoptions/has_formula) | Indica se il testo è una formula se inizia con "=".|
| [prog_id](/cells/python-net/it/aspose.cells/htmlloadoptions/prog_id) | Ottiene l'ID del programma che ha creato il file.<br/> Solo per i file MHT.|
| [table_load_options](/cells/python-net/it/aspose.cells/htmlloadoptions/table_load_options) | Ottieni l'istanza di HtmlTableLoadOptionCollection|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`set_paper_size(self, type)`](/cells/python-net/it/aspose.cells/htmlloadoptions/set_paper_size/#aspose.cells.papersizetype) | Imposta il formato carta di stampa predefinito in base alle impostazioni predefinite della stampante.|



###  Guarda anche
* modulo [`aspose.cells`](..)
* classe [`AbstractTextLoadOptions`](/cells/python-net/it/aspose.cells/abstracttextloadoptions)
* classe [`HtmlLoadOptions`](/cells/python-net/it/aspose.cells/htmlloadoptions)
* classe [`LoadOptions`](/cells/python-net/it/aspose.cells/loadoptions)
* classe [`Workbook`](/cells/python-net/it/aspose.cells/workbook)
