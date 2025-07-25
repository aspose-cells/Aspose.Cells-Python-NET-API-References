---
title: DbfLoadOptions classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 10
url: /it/aspose.cells.loading/dbfloadoptions/
is_root: false
---
##  DbfLoadOptions classe
Rappresenta le opzioni di caricamento del file .dbf.



**Eredità:** [`DbfLoadOptions`](/cells/python-net/aspose.cells.loading/dbfloadoptions) → 
[`LoadOptions`](/cells/python-net/it/aspose.cells/loadoptions)



Il tipo DbfLoadOptions espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [`__init__(self)`](/cells/python-net/it/aspose.cells.loading/dbfloadoptions/__init__/#) | Le opzioni.|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [load_format](/cells/python-net/it/aspose.cells.loading/dbfloadoptions/load_format) | Ottiene il formato di caricamento.|
| [password](/cells/python-net/it/aspose.cells.loading/dbfloadoptions/password) | Ottiene e imposta la password della cartella di lavoro.|
| [parsing_formula_on_open](/cells/python-net/it/aspose.cells.loading/dbfloadoptions/parsing_formula_on_open) | Indica se analizzare la formula durante la lettura del file.|
| [parsing_pivot_cached_records](/cells/python-net/it/aspose.cells.loading/dbfloadoptions/parsing_pivot_cached_records) | Indica se analizzare i record memorizzati nella cache del pivot durante il caricamento del file.<br/> Il valore predefinito è falso.|
| [language_code](/cells/python-net/it/aspose.cells.loading/dbfloadoptions/language_code) | Ottiene o imposta la lingua dell'interfaccia utente della versione della cartella di lavoro in base al CountryCode in cui è stato salvato il file.|
| [region](/cells/python-net/it/aspose.cells.loading/dbfloadoptions/region) | Ottiene o imposta le impostazioni regionali utilizzate per la cartella di lavoro che verrà caricata.|
| [default_style_settings](/cells/python-net/it/aspose.cells.loading/dbfloadoptions/default_style_settings) | Ottiene le impostazioni di stile predefinite per l'inizializzazione degli stili della cartella di lavoro|
| [standard_font](/cells/python-net/it/aspose.cells.loading/dbfloadoptions/standard_font) | Imposta il nome del font standard predefinito|
| [standard_font_size](/cells/python-net/it/aspose.cells.loading/dbfloadoptions/standard_font_size) | Imposta la dimensione standard predefinita del carattere.|
| [ignore_not_printed](/cells/python-net/it/aspose.cells.loading/dbfloadoptions/ignore_not_printed) | Ignora i dati che non vengono stampati se si stampa direttamente il file|
| [check_data_valid](/cells/python-net/it/aspose.cells.loading/dbfloadoptions/check_data_valid) | Controllare se i dati nel file modello sono validi.|
| [check_excel_restriction](/cells/python-net/it/aspose.cells.loading/dbfloadoptions/check_excel_restriction) | Se verificare la restrizione del file Excel quando l'utente modifica celle con oggetti correlati.<br/>Ad esempio, Excel non consente di immettere valori stringa più lunghi di 32K.<br/>Quando si immette un valore più lungo di 32K, ad esempio Cell.PutValue(string), se questa proprietà è vera, si otterrà un'eccezione.<br/>Se questa proprietà è falsa, accetteremo il valore della stringa di input come valore della cella in modo che in seguito<br/>è possibile restituire il valore stringa completo per altri formati di file, ad esempio CSV.<br/>Tuttavia, se hai impostato un valore di questo tipo che non è valido per il formato di file Excel,<br/>Non salvare la cartella di lavoro in formato Excel in un secondo momento. In caso contrario, potrebbe verificarsi un errore imprevisto nel file Excel generato.|
| [keep_unparsed_data](/cells/python-net/it/aspose.cells.loading/dbfloadoptions/keep_unparsed_data) | Mantenere in memoria i dati non analizzati per la cartella di lavoro quando viene caricata dal file modello. Il valore predefinito è true.|
| [load_filter](/cells/python-net/it/aspose.cells.loading/dbfloadoptions/load_filter) | Il filtro per indicare come caricare i dati.|
| [memory_setting](/cells/python-net/it/aspose.cells.loading/dbfloadoptions/memory_setting) | Ottiene o imposta la modalità di memoria per la cartella di lavoro caricata.|
| [auto_fitter_options](/cells/python-net/it/aspose.cells.loading/dbfloadoptions/auto_fitter_options) | Ottiene e imposta le opzioni di adattamento automatico|
| [auto_filter](/cells/python-net/it/aspose.cells.loading/dbfloadoptions/auto_filter) | Indica se filtrare automaticamente i dati durante il caricamento dei file.|
| [font_configs](/cells/python-net/it/aspose.cells.loading/dbfloadoptions/font_configs) | Ottiene e imposta le singole configurazioni dei font.<br/> Funziona solo per [`Workbook`](/cells/python-net/it/aspose.cells/workbook) che utilizza questo [`LoadOptions`](/cells/python-net/it/aspose.cells/loadoptions) per caricare.|
| [ignore_useless_shapes](/cells/python-net/it/aspose.cells.loading/dbfloadoptions/ignore_useless_shapes) | Indica se ignorare le forme inutili.|
| [preserve_padding_spaces_in_formula](/cells/python-net/it/aspose.cells.loading/dbfloadoptions/preserve_padding_spaces_in_formula) | Indica se conservare gli spazi e le interruzioni di riga che vengono aggiunti tra i token della formula<br/>durante l'ottenimento e l'impostazione delle formule.<br/> Il valore predefinito è falso.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`set_paper_size(self, type)`](/cells/python-net/it/aspose.cells.loading/dbfloadoptions/set_paper_size/#aspose.cells.papersizetype) | Imposta il formato carta di stampa predefinito in base alle impostazioni predefinite della stampante.|



###  Guarda anche
* modulo [`aspose.cells.loading`](..)
* classe [`DbfLoadOptions`](/cells/python-net/it/aspose.cells.loading/dbfloadoptions)
* classe [`LoadOptions`](/cells/python-net/it/aspose.cells/loadoptions)
* classe [`Workbook`](/cells/python-net/it/aspose.cells/workbook)
