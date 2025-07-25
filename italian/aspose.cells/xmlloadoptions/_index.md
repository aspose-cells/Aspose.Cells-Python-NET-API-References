---
title: XmlLoadOptions classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 1660
url: /it/aspose.cells/xmlloadoptions/
is_root: false
---
##  XmlLoadOptions classe
Rappresenta le opzioni di caricamento xml.



**Eredità:** [`XmlLoadOptions`](/cells/python-net/aspose.cells/xmlloadoptions) → 
[`LoadOptions`](/cells/python-net/it/aspose.cells/loadoptions)



Il tipo XmlLoadOptions espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [`__init__(self)`](/cells/python-net/it/aspose.cells/xmlloadoptions/__init__/#) | Rappresenta le opzioni di caricamento del file xml.|
| [`__init__(self, type)`](/cells/python-net/it/aspose.cells/xmlloadoptions/__init__/#aspose.cells.loadformat) | Rappresenta le opzioni di caricamento del file xml.|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [load_format](/cells/python-net/it/aspose.cells/xmlloadoptions/load_format) | Ottiene il formato di caricamento.|
| [password](/cells/python-net/it/aspose.cells/xmlloadoptions/password) | Ottiene e imposta la password della cartella di lavoro.|
| [parsing_formula_on_open](/cells/python-net/it/aspose.cells/xmlloadoptions/parsing_formula_on_open) | Indica se analizzare la formula durante la lettura del file.|
| [parsing_pivot_cached_records](/cells/python-net/it/aspose.cells/xmlloadoptions/parsing_pivot_cached_records) | Indica se analizzare i record memorizzati nella cache del pivot durante il caricamento del file.<br/> Il valore predefinito è falso.|
| [language_code](/cells/python-net/it/aspose.cells/xmlloadoptions/language_code) | Ottiene o imposta la lingua dell'interfaccia utente della versione della cartella di lavoro in base al CountryCode in cui è stato salvato il file.|
| [region](/cells/python-net/it/aspose.cells/xmlloadoptions/region) | Ottiene o imposta le impostazioni regionali utilizzate per la cartella di lavoro che verrà caricata.|
| [default_style_settings](/cells/python-net/it/aspose.cells/xmlloadoptions/default_style_settings) | Ottiene le impostazioni di stile predefinite per l'inizializzazione degli stili della cartella di lavoro|
| [standard_font](/cells/python-net/it/aspose.cells/xmlloadoptions/standard_font) | Imposta il nome del font standard predefinito|
| [standard_font_size](/cells/python-net/it/aspose.cells/xmlloadoptions/standard_font_size) | Imposta la dimensione standard predefinita del carattere.|
| [ignore_not_printed](/cells/python-net/it/aspose.cells/xmlloadoptions/ignore_not_printed) | Ignora i dati che non vengono stampati se si stampa direttamente il file|
| [check_data_valid](/cells/python-net/it/aspose.cells/xmlloadoptions/check_data_valid) | Controllare se i dati nel file modello sono validi.|
| [check_excel_restriction](/cells/python-net/it/aspose.cells/xmlloadoptions/check_excel_restriction) | Se verificare la restrizione del file Excel quando l'utente modifica celle con oggetti correlati.<br/>Ad esempio, Excel non consente di immettere valori stringa più lunghi di 32K.<br/>Quando si immette un valore più lungo di 32K, ad esempio Cell.PutValue(string), se questa proprietà è vera, si otterrà un'eccezione.<br/>Se questa proprietà è falsa, accetteremo il valore della stringa di input come valore della cella in modo che in seguito<br/>è possibile restituire il valore stringa completo per altri formati di file, ad esempio CSV.<br/>Tuttavia, se hai impostato un valore di questo tipo che non è valido per il formato di file Excel,<br/>Non salvare la cartella di lavoro in formato Excel in un secondo momento. In caso contrario, potrebbe verificarsi un errore imprevisto nel file Excel generato.|
| [keep_unparsed_data](/cells/python-net/it/aspose.cells/xmlloadoptions/keep_unparsed_data) | Mantenere in memoria i dati non analizzati per la cartella di lavoro quando viene caricata dal file modello. Il valore predefinito è true.|
| [load_filter](/cells/python-net/it/aspose.cells/xmlloadoptions/load_filter) | Il filtro per indicare come caricare i dati.|
| [memory_setting](/cells/python-net/it/aspose.cells/xmlloadoptions/memory_setting) | Ottiene o imposta la modalità di memoria per la cartella di lavoro caricata.|
| [auto_fitter_options](/cells/python-net/it/aspose.cells/xmlloadoptions/auto_fitter_options) | Ottiene e imposta le opzioni di adattamento automatico|
| [auto_filter](/cells/python-net/it/aspose.cells/xmlloadoptions/auto_filter) | Indica se filtrare automaticamente i dati durante il caricamento dei file.|
| [font_configs](/cells/python-net/it/aspose.cells/xmlloadoptions/font_configs) | Ottiene e imposta le singole configurazioni dei font.<br/> Funziona solo per [`Workbook`](/cells/python-net/it/aspose.cells/workbook) che utilizza questo [`LoadOptions`](/cells/python-net/it/aspose.cells/loadoptions) per caricare.|
| [ignore_useless_shapes](/cells/python-net/it/aspose.cells/xmlloadoptions/ignore_useless_shapes) | Indica se ignorare le forme inutili.|
| [preserve_padding_spaces_in_formula](/cells/python-net/it/aspose.cells/xmlloadoptions/preserve_padding_spaces_in_formula) | Indica se conservare gli spazi e le interruzioni di riga che vengono aggiunti tra i token della formula<br/>durante l'ottenimento e l'impostazione delle formule.<br/> Il valore predefinito è falso.|
| [start_cell](/cells/python-net/it/aspose.cells/xmlloadoptions/start_cell) | Ottiene e imposta la cella iniziale.|
| [is_xml_map](/cells/python-net/it/aspose.cells/xmlloadoptions/is_xml_map) | Indica se si desidera mappare XML in Excel.<br/> Il valore predefinito è falso.|
| [contains_multiple_worksheets](/cells/python-net/it/aspose.cells/xmlloadoptions/contains_multiple_worksheets) | Indica se importare XML come più fogli di lavoro.|
| [convert_numeric_or_date](/cells/python-net/it/aspose.cells/xmlloadoptions/convert_numeric_or_date) | Indica se convertire il valore nel file xml in numerico o in data.|
| [number_format](/cells/python-net/it/aspose.cells/xmlloadoptions/number_format) | Ottiene e imposta il formato del valore numerico.|
| [date_format](/cells/python-net/it/aspose.cells/xmlloadoptions/date_format) | Ottiene e imposta il formato del valore della data.|
| [ignore_root_attributes](/cells/python-net/it/aspose.cells/xmlloadoptions/ignore_root_attributes) | Indica se ignorare gli attributi dell'elemento radice.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`set_paper_size(self, type)`](/cells/python-net/it/aspose.cells/xmlloadoptions/set_paper_size/#aspose.cells.papersizetype) | Imposta il formato carta di stampa predefinito in base alle impostazioni predefinite della stampante.|



###  Guarda anche
* modulo [`aspose.cells`](..)
* classe [`LoadOptions`](/cells/python-net/it/aspose.cells/loadoptions)
* classe [`Workbook`](/cells/python-net/it/aspose.cells/workbook)
* classe [`XmlLoadOptions`](/cells/python-net/it/aspose.cells/xmlloadoptions)
