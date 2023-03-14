---
title: classe NumbersLoadOptions
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 10
url: /it/aspose.cells.numbers/numbersloadoptions/
is_root: false
---
##  classe NumbersLoadOptions
Rappresenta le opzioni di caricamento dei file Apple Numbers.



**Eredità:** [NumbersLoadOptions](/cells/python-net/aspose.cells.numbers/numbersloadoptions) → 
[LoadOptions](/cells/python-net/it/aspose.cells/loadoptions)



Il tipo NumbersLoadOptions espone i membri seguenti:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [NumbersLoadOptions()](/cells/python-net/it/aspose.cells.numbers/numbersloadoptions/__init__/#) | Costruttore.|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [load_format](/cells/python-net/it/aspose.cells.numbers/numbersloadoptions/load_format) | Ottiene il formato di caricamento.|
| [password](/cells/python-net/it/aspose.cells.numbers/numbersloadoptions/password) | Ottiene e imposta la password della cartella di lavoro.|
| [parsing_formula_on_open](/cells/python-net/it/aspose.cells.numbers/numbersloadoptions/parsing_formula_on_open) | Indica se analizzare la formula durante la lettura del file.|
| [parsing_pivot_cached_records](/cells/python-net/it/aspose.cells.numbers/numbersloadoptions/parsing_pivot_cached_records) | Indica se l'analisi dei record memorizzati nella cache pivot durante il caricamento del file.<br/> Il valore predefinito è falso.|
| [language_code](/cells/python-net/it/aspose.cells.numbers/numbersloadoptions/language_code) | Ottiene o imposta la lingua dell'interfaccia utente della versione della cartella di lavoro basata su CountryCode che ha salvato il file.|
| [region](/cells/python-net/it/aspose.cells.numbers/numbersloadoptions/region) | Ottiene o imposta le impostazioni internazionali del sistema in base a CountryCode al momento del caricamento del file.|
| [default_style_settings](/cells/python-net/it/aspose.cells.numbers/numbersloadoptions/default_style_settings) | Ottiene le impostazioni di stile predefinite per l'inizializzazione degli stili della cartella di lavoro|
| [standard_font](/cells/python-net/it/aspose.cells.numbers/numbersloadoptions/standard_font) | Imposta il nome del carattere standard predefinito|
| [standard_font_size](/cells/python-net/it/aspose.cells.numbers/numbersloadoptions/standard_font_size) | Imposta la dimensione del carattere standard predefinita.|
| [interrupt_monitor](/cells/python-net/it/aspose.cells.numbers/numbersloadoptions/interrupt_monitor) | Ottiene e imposta il monitor di interrupt.|
| [ignore_not_printed](/cells/python-net/it/aspose.cells.numbers/numbersloadoptions/ignore_not_printed) | Ignora i dati che non vengono stampati se stampi direttamente il file|
| [check_data_valid](/cells/python-net/it/aspose.cells.numbers/numbersloadoptions/check_data_valid) |Verificare se i dati sono validi nel file modello.|
| [check_excel_restriction](/cells/python-net/it/aspose.cells.numbers/numbersloadoptions/check_excel_restriction) | Se controllare la restrizione del file excel quando l'utente modifica gli oggetti relativi alle celle.<br/>Ad esempio, Excel non consente di inserire un valore di stringa più lungo di 32K.<br/>Quando inserisci un valore più lungo di 32K, ad esempio Cell.PutValue(string), se questa proprietà è true, otterrai un'eccezione.<br/>Se questa proprietà è falsa, accetteremo il valore della stringa di input come valore della cella in modo che in seguito<br/>puoi emettere il valore di stringa completo per altri formati di file come CSV.<br/>Tuttavia, se hai impostato un tipo di valore non valido per il formato di file excel,<br/> non dovresti salvare la cartella di lavoro come formato di file excel in un secondo momento. Altrimenti potrebbe esserci un errore imprevisto per il file excel generato.|
| [keep_unparsed_data](/cells/python-net/it/aspose.cells.numbers/numbersloadoptions/keep_unparsed_data) | Se conservare i dati non analizzati in memoria per la cartella di lavoro quando viene caricata dal file modello. L'impostazione predefinita è true.|
| [load_filter](/cells/python-net/it/aspose.cells.numbers/numbersloadoptions/load_filter) | Il filtro per indicare come caricare i dati.|
| [light_cells_data_handler](/cells/python-net/it/aspose.cells.numbers/numbersloadoptions/light_cells_data_handler) | Il gestore dati per l'elaborazione dei dati delle celle durante la lettura del file modello.|
| [memory_setting](/cells/python-net/it/aspose.cells.numbers/numbersloadoptions/memory_setting) | Ottiene o imposta le opzioni di utilizzo della memoria.|
| [warning_callback](/cells/python-net/it/aspose.cells.numbers/numbersloadoptions/warning_callback) | Ottiene o imposta la richiamata di avviso.|
| [auto_fitter_options](/cells/python-net/it/aspose.cells.numbers/numbersloadoptions/auto_fitter_options) | Ottiene e imposta le opzioni di installazione automatica|
| [auto_filter](/cells/python-net/it/aspose.cells.numbers/numbersloadoptions/auto_filter) | Indica se filtrare automaticamente i dati durante il caricamento dei file.|
| [font_configs](/cells/python-net/it/aspose.cells.numbers/numbersloadoptions/font_configs) | Ottiene e imposta le singole configurazioni dei caratteri.<br/> Funziona solo per [Workbook](/cells/python-net/it/aspose.cells/workbook) che utilizza questo [LoadOptions](/cells/python-net/it/aspose.cells/loadoptions) per caricare.|
| [load_table_type](/cells/python-net/it/aspose.cells.numbers/numbersloadoptions/load_table_type) | Ottiene e imposta il tipo di caricamento di più tabelle in un foglio di lavoro.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [set_paper_size(type)](/cells/python-net/it/aspose.cells.numbers/numbersloadoptions/set_paper_size/#PaperSizeType) | Imposta il formato carta di stampa predefinito dall'impostazione predefinita della stampante.|



###  Guarda anche
* modulo [aspose.cells.numbers](..)
* classe [LoadOptions](/cells/python-net/it/aspose.cells/loadoptions)
* classe [NumbersLoadOptions](/cells/python-net/it/aspose.cells.numbers/numbersloadoptions)
* classe [Workbook](/cells/python-net/it/aspose.cells/workbook)
