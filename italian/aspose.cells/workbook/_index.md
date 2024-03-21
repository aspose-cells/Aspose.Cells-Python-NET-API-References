---
title: Workbook classe
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 1660
url: /it/aspose.cells/workbook/
is_root: false
---
##  Workbook classe
Rappresenta un oggetto radice per creare un foglio di calcolo Excel.



Il tipo Workbook espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [__init__](/cells/python-net/it/aspose.cells/workbook/__init__/#) | Inizializza una nuova istanza della classe [`Workbook`](/cells/python-net/it/aspose.cells/workbook).|
| [__init__](/cells/python-net/it/aspose.cells/workbook/__init__/#aspose.cells.FileFormatType) | Inizializza una nuova istanza della classe [`Workbook`](/cells/python-net/it/aspose.cells/workbook).|
| [__init__](/cells/python-net/it/aspose.cells/workbook/__init__/#str) | Inizializza una nuova istanza della classe [`Workbook`](/cells/python-net/it/aspose.cells/workbook) e apre un file.|
| [__init__](/cells/python-net/it/aspose.cells/workbook/__init__/#io.RawIOBase) | Inizializza una nuova istanza della classe [`Workbook`](/cells/python-net/it/aspose.cells/workbook) e apre uno stream.|
| [__init__](/cells/python-net/it/aspose.cells/workbook/__init__/#str-aspose.cells.LoadOptions) | Inizializza una nuova istanza della classe [`Workbook`](/cells/python-net/it/aspose.cells/workbook) e apre un file.|
| [__init__](/cells/python-net/it/aspose.cells/workbook/__init__/#io.RawIOBase-aspose.cells.LoadOptions) | Inizializza una nuova istanza della classe [`Workbook`](/cells/python-net/it/aspose.cells/workbook) e del flusso aperto.|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [settings](/cells/python-net/it/aspose.cells/workbook/settings) | Rappresenta le impostazioni della cartella di lavoro.|
| [worksheets](/cells/python-net/it/aspose.cells/workbook/worksheets) | Ottiene la raccolta [`WorksheetCollection`](/cells/python-net/it/aspose.cells/worksheetcollection) nel foglio di calcolo.|
| [is_licensed](/cells/python-net/it/aspose.cells/workbook/is_licensed) | Indica se la licenza è impostata.|
| [colors](/cells/python-net/it/aspose.cells/workbook/colors) | Restituisce i colori nella tavolozza per il foglio di calcolo.|
| [count_of_styles_in_pool](/cells/python-net/it/aspose.cells/workbook/count_of_styles_in_pool) | Ottiene il numero di stili nel pool di stili.|
| [default_style](/cells/python-net/it/aspose.cells/workbook/default_style) |Ottiene o imposta l'oggetto predefinito [`Style`](/cells/python-net/it/aspose.cells/style) della cartella di lavoro.|
| [is_digitally_signed](/cells/python-net/it/aspose.cells/workbook/is_digitally_signed) | Indica se questo foglio di calcolo è firmato digitalmente.|
| [is_workbook_protected_with_password](/cells/python-net/it/aspose.cells/workbook/is_workbook_protected_with_password) | Indica se la struttura o la finestra è protetta con password.|
| [vba_project](/cells/python-net/it/aspose.cells/workbook/vba_project) | Ottiene lo [`Workbook.vba_project`](/cells/python-net/it/aspose.cells/workbook#vba_project) in un foglio di calcolo.|
| [has_macro](/cells/python-net/it/aspose.cells/workbook/has_macro) | Indica se questo foglio di calcolo contiene macro/VBA.|
| [has_revisions](/cells/python-net/it/aspose.cells/workbook/has_revisions) | Ottiene se nella cartella di lavoro sono presenti modifiche rilevate|
| [file_name](/cells/python-net/it/aspose.cells/workbook/file_name) | Ottiene e imposta il nome del file corrente.|
| [cells_data_table_factory](/cells/python-net/it/aspose.cells/workbook/cells_data_table_factory) | Ottiene la factory per la creazione di ICellsDataTable da oggetti personalizzati|
| [data_sorter](/cells/python-net/it/aspose.cells/workbook/data_sorter) | Ottiene un oggetto DataSorter per ordinare i dati.|
| [theme](/cells/python-net/it/aspose.cells/workbook/theme) | Ottiene il nome del tema.|
| [built_in_document_properties](/cells/python-net/it/aspose.cells/workbook/built_in_document_properties) | Restituisce una raccolta [`DocumentProperty`](/cells/python-net/it/aspose.cells.properties/documentproperty) che rappresenta tutte le proprietà del documento integrate nel foglio di calcolo.|
| [custom_document_properties](/cells/python-net/it/aspose.cells/workbook/custom_document_properties) | Restituisce una raccolta [`DocumentProperty`](/cells/python-net/it/aspose.cells.properties/documentproperty) che rappresenta tutte le proprietà del documento personalizzato del foglio di calcolo.|
| [file_format](/cells/python-net/it/aspose.cells/workbook/file_format) | Ottiene e imposta il formato del file.|
| [interrupt_monitor](/cells/python-net/it/aspose.cells/workbook/interrupt_monitor) | Ottiene e imposta il monitoraggio delle interruzioni.|
| [content_type_properties](/cells/python-net/it/aspose.cells/workbook/content_type_properties) | Ottiene l'elenco degli oggetti [`ContentTypeProperty`](/cells/python-net/it/aspose.cells.properties/contenttypeproperty) nella cartella di lavoro.|
| [custom_xml_parts](/cells/python-net/it/aspose.cells/workbook/custom_xml_parts) | Rappresenta una parte di archiviazione dati XML personalizzata (dati XML personalizzati all'interno di un pacchetto).|
| [data_mashup](/cells/python-net/it/aspose.cells/workbook/data_mashup) | Ottiene i dati del mashup.|
| [ribbon_xml](/cells/python-net/it/aspose.cells/workbook/ribbon_xml) |Ottiene e imposta il file XML che definisce l'interfaccia utente della barra multifunzione.|
| [absolute_path](/cells/python-net/it/aspose.cells/workbook/absolute_path) | Ottiene e imposta il percorso assoluto del file.|
| [data_connections](/cells/python-net/it/aspose.cells/workbook/data_connections) | Ottiene la raccolta [`ExternalConnection`](/cells/python-net/it/aspose.cells.externalconnections/externalconnection).|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [save](/cells/python-net/it/aspose.cells/workbook/save/#str-aspose.cells.SaveFormat) | Salva la cartella di lavoro sul disco.|
| [save](/cells/python-net/it/aspose.cells/workbook/save/#str) | Salvare la cartella di lavoro sul disco.|
| [save](/cells/python-net/it/aspose.cells/workbook/save/#str-aspose.cells.SaveOptions) | Salva la cartella di lavoro sul disco.|
| [save](/cells/python-net/it/aspose.cells/workbook/save/#io.RawIOBase-aspose.cells.SaveFormat) | Salva la cartella di lavoro nel flusso.|
| [save](/cells/python-net/it/aspose.cells/workbook/save/#io.RawIOBase-aspose.cells.SaveOptions) | Salva la cartella di lavoro nel flusso.|
| [replace](/cells/python-net/it/aspose.cells/workbook/replace/#str-str) | Sostituisce il valore di una cella con una nuova stringa.|
| [replace](/cells/python-net/it/aspose.cells/workbook/replace/#str-int) | Sostituisce il valore di una cella con un nuovo numero intero.|
| [replace](/cells/python-net/it/aspose.cells/workbook/replace/#str-float) | Sostituisce il valore di una cella con un nuovo double.|
| [replace](/cells/python-net/it/aspose.cells/workbook/replace/#str-list-bool) | Sostituisce il valore di una cella con una nuova matrice di stringhe.|
| [replace](/cells/python-net/it/aspose.cells/workbook/replace/#str-list-bool) | Sostituisce i valori delle celle con un array di numeri interi.|
| [replace](/cells/python-net/it/aspose.cells/workbook/replace/#str-list-bool) | Sostituisce i valori delle celle con un doppio array.|
| [replace](/cells/python-net/it/aspose.cells/workbook/replace/#bool-any) | Sostituisce i valori delle celle con nuovi dati.|
| [replace](/cells/python-net/it/aspose.cells/workbook/replace/#int-any) | Sostituisce i valori delle celle con nuovi dati.|
| [replace](/cells/python-net/it/aspose.cells/workbook/replace/#str-str-aspose.cells.ReplaceOptions) | Sostituisce il valore di una cella con una nuova stringa.|
| [copy](/cells/python-net/it/aspose.cells/workbook/copy/#aspose.cells.Workbook-aspose.cells.CopyOptions) | Copia un altro oggetto cartella di lavoro.|
| [copy](/cells/python-net/it/aspose.cells/workbook/copy/#aspose.cells.Workbook) | Copia i dati da un oggetto cartella di lavoro di origine.|
| [calculate_formula](/cells/python-net/it/aspose.cells/workbook/calculate_formula/#) | Calcola il risultato delle formule.|
| [calculate_formula](/cells/python-net/it/aspose.cells/workbook/calculate_formula/#bool) | Calcola il risultato delle formule.|
| [calculate_formula](/cells/python-net/it/aspose.cells/workbook/calculate_formula/#aspose.cells.CalculationOptions) | Calcolo delle formule in questa cartella di lavoro.|
| [refresh_dynamic_array_formulas](/cells/python-net/it/aspose.cells/workbook/refresh_dynamic_array_formulas/#bool) | Aggiorna le formule di matrice dinamica (distribuite in un nuovo intervallo di celle vicine in base ai dati correnti)<br/>Altre formule nella cartella di lavoro non verranno calcolate in modo ricorsivo anche se utilizzate da formule in matrice dinamica.|
| [refresh_dynamic_array_formulas](/cells/python-net/it/aspose.cells/workbook/refresh_dynamic_array_formulas/#bool-aspose.cells.CalculationOptions) | Aggiorna le formule di matrice dinamica (distribuite in un nuovo intervallo di celle vicine in base ai dati correnti)|
| [import_xml](/cells/python-net/it/aspose.cells/workbook/import_xml/#str-str-int-int) | Importa/aggiorna un file di dati XML nella cartella di lavoro.|
| [import_xml](/cells/python-net/it/aspose.cells/workbook/import_xml/#io.RawIOBase-str-int-int) | Importa/aggiorna un file di dati XML nella cartella di lavoro.|
| [export_xml](/cells/python-net/it/aspose.cells/workbook/export_xml/#str-str) | Esporta i dati XML collegati dalla mappa XML specificata.|
| [export_xml](/cells/python-net/it/aspose.cells/workbook/export_xml/#str-io.RawIOBase) | Esporta dati XML.|
| [parse_formulas](/cells/python-net/it/aspose.cells/workbook/parse_formulas/#bool) | Analizza tutte le formule che non sono state analizzate quando sono state caricate dal file modello o impostate in una cella.|
| [start_access_cache](/cells/python-net/it/aspose.cells/workbook/start_access_cache/#aspose.cells.AccessCacheOptions) | Avvia la sessione che utilizza le cache per accedere ai dati.|
| [close_access_cache](/cells/python-net/it/aspose.cells/workbook/close_access_cache/#aspose.cells.AccessCacheOptions) | Chiude la sessione che utilizza le cache per accedere ai dati.|
| [remove_unused_styles](/cells/python-net/it/aspose.cells/workbook/remove_unused_styles/#) | Rimuovi tutti gli stili inutilizzati.|
| [create_style](/cells/python-net/it/aspose.cells/workbook/create_style/#) | Crea un nuovo stile.|
| [create_builtin_style](/cells/python-net/it/aspose.cells/workbook/create_builtin_style/#aspose.cells.BuiltinStyleType) | Crea uno stile integrato in base al tipo specificato.|
| [create_cells_color](/cells/python-net/it/aspose.cells/workbook/create_cells_color/#) | Crea un oggetto [`CellsColor`](/cells/python-net/it/aspose.cells/cellscolor).|
| [combine](/cells/python-net/it/aspose.cells/workbook/combine/#aspose.cells.Workbook) | Combina un altro oggetto cartella di lavoro.|
| [get_style_in_pool](/cells/python-net/it/aspose.cells/workbook/get_style_in_pool/#int) | Ottiene lo stile nel pool di stili.<br/>Tutti gli stili nella cartella di lavoro verranno raccolti in un pool.<br/> Nelle celle è presente solo un semplice indice di riferimento.|
| [get_fonts](/cells/python-net/it/aspose.cells/workbook/get_fonts/#) | Ottiene tutti i caratteri nel pool di stili.|
| [get_named_style](/cells/python-net/it/aspose.cells/workbook/get_named_style/#str) | Ottiene lo stile denominato nel pool di stili.|
| [change_palette](/cells/python-net/it/aspose.cells/workbook/change_palette/#aspose.pydrawing.Color-int) |Modifica la tavolozza per il foglio di calcolo nell'indice specificato.|
| [is_color_in_palette](/cells/python-net/it/aspose.cells/workbook/is_color_in_palette/#aspose.pydrawing.Color) | Controlla se è presente un colore nella tavolozza del foglio di calcolo.|
| [get_matching_color](/cells/python-net/it/aspose.cells/workbook/get_matching_color/#aspose.pydrawing.Color) | Trova il colore più corrispondente nella tavolozza corrente.|
| [set_encryption_options](/cells/python-net/it/aspose.cells/workbook/set_encryption_options/#aspose.cells.EncryptionType-int) | Imposta le opzioni di crittografia.|
| [protect](/cells/python-net/it/aspose.cells/workbook/protect/#aspose.cells.ProtectionType-str) | Protegge una cartella di lavoro.|
| [protect_shared_workbook](/cells/python-net/it/aspose.cells/workbook/protect_shared_workbook/#str) | Protegge una cartella di lavoro condivisa.|
| [unprotect](/cells/python-net/it/aspose.cells/workbook/unprotect/#str) | Annulla la protezione di una cartella di lavoro.|
| [unprotect_shared_workbook](/cells/python-net/it/aspose.cells/workbook/unprotect_shared_workbook/#str) | Annulla la protezione di una cartella di lavoro condivisa.|
| [remove_macro](/cells/python-net/it/aspose.cells/workbook/remove_macro/#) | Rimuove VBA/macro da questo foglio di calcolo.|
| [remove_digital_signature](/cells/python-net/it/aspose.cells/workbook/remove_digital_signature/#) | Rimuove la firma digitale da questo foglio di calcolo.|
| [accept_all_revisions](/cells/python-net/it/aspose.cells/workbook/accept_all_revisions/#) | Accetta tutte le modifiche rilevate nella cartella di lavoro.|
| [remove_external_links](/cells/python-net/it/aspose.cells/workbook/remove_external_links/#) | Rimuove tutti i collegamenti esterni nella cartella di lavoro.|
| [get_theme_color](/cells/python-net/it/aspose.cells/workbook/get_theme_color/#aspose.cells.ThemeColorType) | Ottiene il colore del tema.|
| [set_theme_color](/cells/python-net/it/aspose.cells/workbook/set_theme_color/#aspose.cells.ThemeColorType-aspose.pydrawing.Color) | Imposta il colore del tema|
| [custom_theme](/cells/python-net/it/aspose.cells/workbook/custom_theme/#str-aspose.pydrawing.Color[]) | Il tema è la dogana.|
| [copy_theme](/cells/python-net/it/aspose.cells/workbook/copy_theme/#aspose.cells.Workbook) | Copia il tema da un'altra cartella di lavoro.|
| [has_exernal_links](/cells/python-net/it/aspose.cells/workbook/has_exernal_links/#) | Indica se questa cartella di lavoro contiene collegamenti esterni ad altre origini dati.|
| [update_custom_function_definition](/cells/python-net/it/aspose.cells/workbook/update_custom_function_definition/#aspose.cells.CustomFunctionDefinition) | Aggiorna la definizione delle funzioni personalizzate.|
| [update_linked_data_source](/cells/python-net/it/aspose.cells/workbook/update_linked_data_source/#list) | Se questa cartella di lavoro contiene collegamenti esterni ad altre origini dati,<br/> Aspose.Cells tenterà di recuperare i dati più recenti dalle fonti fornite.|
| [set_digital_signature](/cells/python-net/it/aspose.cells/workbook/set_digital_signature/#aspose.cells.digitalsignatures.DigitalSignatureCollection) |Imposta la firma digitale su un file di foglio di calcolo (Excel2007 e versioni successive).|
| [add_digital_signature](/cells/python-net/it/aspose.cells/workbook/add_digital_signature/#aspose.cells.digitalsignatures.DigitalSignatureCollection) | Aggiunge la firma digitale a un file di foglio di calcolo OOXML (Excel2007 e versioni successive).|
| [get_digital_signature](/cells/python-net/it/aspose.cells/workbook/get_digital_signature/#) | Ottiene la firma digitale dal file.|
| [remove_personal_information](/cells/python-net/it/aspose.cells/workbook/remove_personal_information/#) | Rimuove le informazioni personali.|



###  Osservazioni

La classe Workbook denota un foglio di calcolo Excel. Ogni foglio di calcolo può contenere più fogli di lavoro.
La caratteristica di base della classe è aprire e salvare file Excel nativi.
La classe dispone di alcune funzionalità avanzate come la copia di dati da altre cartelle di lavoro, la combinazione di due cartelle di lavoro, la conversione di Excel in PDF, il rendering di Excel in immagine e la protezione del foglio di calcolo Excel.

###  Esempio

L'esempio seguente carica Workbook da un file Excel denominato designer.xls e rende invisibili le barre di scorrimento orizzontale e verticale.
 Quindi sostituisce due valori stringa rispettivamente con un valore intero e un valore stringa all'interno del foglio di calcolo e infine salva la cartella di lavoro come file xlsx di Excel.

```python
from aspose.cells import Workbook

# Open a designer file
designerFile = "designer.xls"
workbook = Workbook(designerFile)
# Set scroll bars
workbook.settings.is_h_scroll_bar_visible = False
workbook.settings.is_v_scroll_bar_visible = False
# Replace the placeholder string with new values
newInt = 100
workbook.replace("OldInt", newInt)
newString = "Hello!"
workbook.replace("OldString", newString)
workbook.save("result.xlsx")

```

###  Guarda anche
* modulo [`aspose.cells`](..)
* classe [`CellsColor`](/cells/python-net/it/aspose.cells/cellscolor)
* classe [`ContentTypeProperty`](/cells/python-net/it/aspose.cells.properties/contenttypeproperty)
* classe [`DocumentProperty`](/cells/python-net/it/aspose.cells.properties/documentproperty)
* classe [`ExternalConnection`](/cells/python-net/it/aspose.cells.externalconnections/externalconnection)
* classe [`Style`](/cells/python-net/it/aspose.cells/style)
* classe [`Workbook`](/cells/python-net/it/aspose.cells/workbook)
* classe [`WorksheetCollection`](/cells/python-net/it/aspose.cells/worksheetcollection)
