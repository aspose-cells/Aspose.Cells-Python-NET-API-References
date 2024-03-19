---
title: OdsLoadOptions classe
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 1140
url: /it/aspose.cells/odsloadoptions/
is_root: false
---
##  OdsLoadOptions classe
Rappresenta le opzioni di caricamento del file ods.



**Eredità:** [`OdsLoadOptions`](/cells/python-net/aspose.cells/odsloadoptions) → 
[`LoadOptions`](/cells/python-net/it/aspose.cells/loadoptions)



Il tipo OdsLoadOptions espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [__init__](/cells/python-net/it/aspose.cells/odsloadoptions/__init__/#) | Rappresenta le opzioni di caricamento del file ods.|
| [__init__](/cells/python-net/it/aspose.cells/odsloadoptions/__init__/#aspose.cells.LoadFormat) | Rappresenta le opzioni di caricamento del file ods.|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [load_format](/cells/python-net/it/aspose.cells/odsloadoptions/load_format) | Ottiene il formato di caricamento.|
| [password](/cells/python-net/it/aspose.cells/odsloadoptions/password) | Ottiene e imposta la password della cartella di lavoro.|
| [parsing_formula_on_open](/cells/python-net/it/aspose.cells/odsloadoptions/parsing_formula_on_open) | Indica se si sta analizzando la formula durante la lettura del file.|
| [parsing_pivot_cached_records](/cells/python-net/it/aspose.cells/odsloadoptions/parsing_pivot_cached_records) | Indica se analizzare i record memorizzati nella cache pivot durante il caricamento del file.<br/> Il valore predefinito è falso.|
| [language_code](/cells/python-net/it/aspose.cells/odsloadoptions/language_code) | Ottiene o imposta la lingua dell'interfaccia utente della versione Workbook in base al CountryCode che ha salvato il file.|
| [region](/cells/python-net/it/aspose.cells/odsloadoptions/region) |Ottiene o imposta le impostazioni internazionali del sistema in base al CountryCode al momento del caricamento del file.|
| [default_style_settings](/cells/python-net/it/aspose.cells/odsloadoptions/default_style_settings) | Ottiene le impostazioni di stile predefinite per l'inizializzazione degli stili della cartella di lavoro|
| [standard_font](/cells/python-net/it/aspose.cells/odsloadoptions/standard_font) | Imposta il nome del carattere standard predefinito|
| [standard_font_size](/cells/python-net/it/aspose.cells/odsloadoptions/standard_font_size) | Imposta la dimensione del carattere standard predefinita.|
| [interrupt_monitor](/cells/python-net/it/aspose.cells/odsloadoptions/interrupt_monitor) | Ottiene e imposta il monitoraggio delle interruzioni.|
| [ignore_not_printed](/cells/python-net/it/aspose.cells/odsloadoptions/ignore_not_printed) | Ignorare i dati che non vengono stampati se si stampa direttamente il file|
| [check_data_valid](/cells/python-net/it/aspose.cells/odsloadoptions/check_data_valid) | Controlla se i dati sono validi nel file modello.|
| [check_excel_restriction](/cells/python-net/it/aspose.cells/odsloadoptions/check_excel_restriction) | Se controllare la restrizione del file Excel quando l'utente modifica gli oggetti correlati alle celle.<br/>Ad esempio, Excel non consente l'immissione di valori di stringa più lunghi di 32K.<br/>Quando inserisci un valore più lungo di 32 KB, ad esempio Cell.PutValue(string), se questa proprietà è vera, otterrai un'eccezione.<br/>Se questa proprietà è falsa, accetteremo il valore della stringa di input come valore della cella in modo che venga visualizzato in seguito<br/>è possibile restituire il valore stringa completo per altri formati di file come CSV.<br/>Tuttavia, se hai impostato un tipo di valore non valido per il formato file Excel,<br/> non dovresti salvare la cartella di lavoro come formato di file Excel in un secondo momento. Altrimenti potrebbe esserci un errore imprevisto per il file Excel generato.|
| [keep_unparsed_data](/cells/python-net/it/aspose.cells/odsloadoptions/keep_unparsed_data) | Indica se mantenere i dati non analizzati in memoria per la cartella di lavoro quando viene caricata dal file modello. L'impostazione predefinita è vera.|
| [load_filter](/cells/python-net/it/aspose.cells/odsloadoptions/load_filter) | Il filtro per indicare come caricare i dati.|
| [light_cells_data_handler](/cells/python-net/it/aspose.cells/odsloadoptions/light_cells_data_handler) | Il gestore dati per l'elaborazione dei dati delle celle durante la lettura del file modello.|
| [memory_setting](/cells/python-net/it/aspose.cells/odsloadoptions/memory_setting) | Ottiene o imposta le opzioni di utilizzo della memoria.|
| [warning_callback](/cells/python-net/it/aspose.cells/odsloadoptions/warning_callback) | Ottiene o imposta la richiamata di avviso.|
| [auto_fitter_options](/cells/python-net/it/aspose.cells/odsloadoptions/auto_fitter_options) | Ottiene e imposta le opzioni di adattamento automatico|
| [auto_filter](/cells/python-net/it/aspose.cells/odsloadoptions/auto_filter) | Indica se filtrare automaticamente i dati durante il caricamento dei file.|
| [font_configs](/cells/python-net/it/aspose.cells/odsloadoptions/font_configs) | Ottiene e imposta configurazioni di caratteri individuali.<br/> Funziona solo per lo [`Workbook`](/cells/python-net/it/aspose.cells/workbook) che utilizza questo [`LoadOptions`](/cells/python-net/it/aspose.cells/loadoptions) per caricare.|
| [ignore_useless_shapes](/cells/python-net/it/aspose.cells/odsloadoptions/ignore_useless_shapes) | Indica se ignorare le forme inutili.|
| [preserve_padding_spaces_in_formula](/cells/python-net/it/aspose.cells/odsloadoptions/preserve_padding_spaces_in_formula) | Indica se preservare gli spazi e le interruzioni di riga riempiti tra i token della formula<br/>durante l'acquisizione e l'impostazione delle formule.<br/> Il valore predefinito è falso.|
| [apply_excel_default_style_to_hyperlink](/cells/python-net/it/aspose.cells/odsloadoptions/apply_excel_default_style_to_hyperlink) | Indica se applicare lo stile predefinito di Excel al collegamento ipertestuale.|
| [refresh_pivot_tables](/cells/python-net/it/aspose.cells/odsloadoptions/refresh_pivot_tables) | Indica se aggiornare le tabelle pivot durante il caricamento del file.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [set_paper_size](/cells/python-net/it/aspose.cells/odsloadoptions/set_paper_size/#aspose.cells.PaperSizeType) | Imposta il formato carta di stampa predefinito dalle impostazioni predefinite della stampante.|



###  Guarda anche
* modulo [`aspose.cells`](..)
* classe [`LoadOptions`](/cells/python-net/it/aspose.cells/loadoptions)
* classe [`OdsLoadOptions`](/cells/python-net/it/aspose.cells/odsloadoptions)
* classe [`Workbook`](/cells/python-net/it/aspose.cells/workbook)
