---
title: OdsLoadOptions classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 1030
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
| [`__init__(self)`](/cells/python-net/it/aspose.cells/odsloadoptions/__init__/#) | Rappresenta le opzioni di caricamento del file ods.|
| [`__init__(self, type)`](/cells/python-net/it/aspose.cells/odsloadoptions/__init__/#aspose.cells.loadformat) | Rappresenta le opzioni di caricamento del file ods.|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [load_format](/cells/python-net/it/aspose.cells/odsloadoptions/load_format) | Ottiene il formato di caricamento.|
| [password](/cells/python-net/it/aspose.cells/odsloadoptions/password) | Ottiene e imposta la password della cartella di lavoro.|
| [parsing_formula_on_open](/cells/python-net/it/aspose.cells/odsloadoptions/parsing_formula_on_open) | Indica se analizzare la formula durante la lettura del file.|
| [parsing_pivot_cached_records](/cells/python-net/it/aspose.cells/odsloadoptions/parsing_pivot_cached_records) | Indica se analizzare i record memorizzati nella cache del pivot durante il caricamento del file.<br/> Il valore predefinito è falso.|
| [language_code](/cells/python-net/it/aspose.cells/odsloadoptions/language_code) | Ottiene o imposta la lingua dell'interfaccia utente della versione della cartella di lavoro in base al CountryCode in cui è stato salvato il file.|
| [region](/cells/python-net/it/aspose.cells/odsloadoptions/region) | Ottiene o imposta le impostazioni regionali utilizzate per la cartella di lavoro che verrà caricata.|
| [default_style_settings](/cells/python-net/it/aspose.cells/odsloadoptions/default_style_settings) | Ottiene le impostazioni di stile predefinite per l'inizializzazione degli stili della cartella di lavoro|
| [standard_font](/cells/python-net/it/aspose.cells/odsloadoptions/standard_font) | Imposta il nome del font standard predefinito|
| [standard_font_size](/cells/python-net/it/aspose.cells/odsloadoptions/standard_font_size) | Imposta la dimensione standard predefinita del carattere.|
| [ignore_not_printed](/cells/python-net/it/aspose.cells/odsloadoptions/ignore_not_printed) | Ignora i dati che non vengono stampati se si stampa direttamente il file|
| [check_data_valid](/cells/python-net/it/aspose.cells/odsloadoptions/check_data_valid) | Controllare se i dati nel file modello sono validi.|
| [check_excel_restriction](/cells/python-net/it/aspose.cells/odsloadoptions/check_excel_restriction) | Se verificare la restrizione del file Excel quando l'utente modifica celle con oggetti correlati.<br/>Ad esempio, Excel non consente di immettere valori stringa più lunghi di 32K.<br/>Quando si immette un valore più lungo di 32K, ad esempio Cell.PutValue(string), se questa proprietà è vera, si otterrà un'eccezione.<br/>Se questa proprietà è falsa, accetteremo il valore della stringa di input come valore della cella in modo che in seguito<br/>è possibile restituire il valore stringa completo per altri formati di file, ad esempio CSV.<br/>Tuttavia, se hai impostato un valore di questo tipo che non è valido per il formato di file Excel,<br/>Non salvare la cartella di lavoro in formato Excel in un secondo momento. In caso contrario, potrebbe verificarsi un errore imprevisto nel file Excel generato.|
| [keep_unparsed_data](/cells/python-net/it/aspose.cells/odsloadoptions/keep_unparsed_data) | Mantenere in memoria i dati non analizzati per la cartella di lavoro quando viene caricata dal file modello. Il valore predefinito è true.|
| [load_filter](/cells/python-net/it/aspose.cells/odsloadoptions/load_filter) | Il filtro per indicare come caricare i dati.|
| [memory_setting](/cells/python-net/it/aspose.cells/odsloadoptions/memory_setting) | Ottiene o imposta la modalità di memoria per la cartella di lavoro caricata.|
| [auto_fitter_options](/cells/python-net/it/aspose.cells/odsloadoptions/auto_fitter_options) | Ottiene e imposta le opzioni di adattamento automatico|
| [auto_filter](/cells/python-net/it/aspose.cells/odsloadoptions/auto_filter) | Indica se filtrare automaticamente i dati durante il caricamento dei file.|
| [font_configs](/cells/python-net/it/aspose.cells/odsloadoptions/font_configs) | Ottiene e imposta le singole configurazioni dei font.<br/> Funziona solo per [`Workbook`](/cells/python-net/it/aspose.cells/workbook) che utilizza questo [`LoadOptions`](/cells/python-net/it/aspose.cells/loadoptions) per caricare.|
| [ignore_useless_shapes](/cells/python-net/it/aspose.cells/odsloadoptions/ignore_useless_shapes) | Indica se ignorare le forme inutili.|
| [preserve_padding_spaces_in_formula](/cells/python-net/it/aspose.cells/odsloadoptions/preserve_padding_spaces_in_formula) | Indica se conservare gli spazi e le interruzioni di riga che vengono aggiunti tra i token della formula<br/>durante l'ottenimento e l'impostazione delle formule.<br/> Il valore predefinito è falso.|
| [apply_excel_default_style_to_hyperlink](/cells/python-net/it/aspose.cells/odsloadoptions/apply_excel_default_style_to_hyperlink) | Indica se applicare lo stile predefinito di Excel al collegamento ipertestuale.|
| [refresh_pivot_tables](/cells/python-net/it/aspose.cells/odsloadoptions/refresh_pivot_tables) | Indica se aggiornare le tabelle pivot durante il caricamento del file.|
| [is_classic_pivot_table](/cells/python-net/it/aspose.cells/odsloadoptions/is_classic_pivot_table) | Indica se la tabella pivot è classica.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`set_paper_size(self, type)`](/cells/python-net/it/aspose.cells/odsloadoptions/set_paper_size/#aspose.cells.papersizetype) | Imposta il formato carta di stampa predefinito in base alle impostazioni predefinite della stampante.|



###  Guarda anche
* modulo [`aspose.cells`](..)
* classe [`LoadOptions`](/cells/python-net/it/aspose.cells/loadoptions)
* classe [`OdsLoadOptions`](/cells/python-net/it/aspose.cells/odsloadoptions)
* classe [`Workbook`](/cells/python-net/it/aspose.cells/workbook)
