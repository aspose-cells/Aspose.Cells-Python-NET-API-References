---
title: Style classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 1350
url: /it/aspose.cells/style/
is_root: false
---
##  Style classe
Rappresenta lo stile di visualizzazione del documento Excel, ad esempio carattere, colore, allineamento, bordo, ecc.
L'oggetto Style contiene tutti gli attributi di stile (carattere, formato numero, allineamento e così via) come proprietà.



Il tipo Style espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [`__init__(self)`](/cells/python-net/it/aspose.cells/style/__init__/#) | Inizializza una nuova istanza della classe [`Style`](/cells/python-net/it/aspose.cells/style).|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [background_theme_color](/cells/python-net/it/aspose.cells/style/background_theme_color) | Ottiene e imposta il colore del tema di sfondo.|
| [foreground_theme_color](/cells/python-net/it/aspose.cells/style/foreground_theme_color) | Ottiene e imposta il colore del tema in primo piano.|
| [name](/cells/python-net/it/aspose.cells/style/name) | Ottiene o imposta il nome dello stile.|
| [pattern](/cells/python-net/it/aspose.cells/style/pattern) | Ottiene o imposta il tipo di pattern di sfondo della cella.|
| [borders](/cells/python-net/it/aspose.cells/style/borders) | Ottiene lo [`BorderCollection`](/cells/python-net/it/aspose.cells/bordercollection) dello stile.|
| [background_color](/cells/python-net/it/aspose.cells/style/background_color) | Ottiene o imposta il colore di sfondo di uno stile.|
| [background_argb_color](/cells/python-net/it/aspose.cells/style/background_argb_color) | Ottiene e imposta il colore di sfondo con un valore ARGB a 32 bit.|
| [foreground_color](/cells/python-net/it/aspose.cells/style/foreground_color) | Ottiene o imposta il colore di primo piano di uno stile.|
| [foreground_argb_color](/cells/python-net/it/aspose.cells/style/foreground_argb_color) | Ottiene e imposta il colore di primo piano con un valore ARGB a 32 bit.|
| [has_borders](/cells/python-net/it/aspose.cells/style/has_borders) | Controlla se sono stati impostati dei bordi per lo stile.|
| [parent_style](/cells/python-net/it/aspose.cells/style/parent_style) | Ottiene lo stile padre di questo stile.|
| [is_number_format_applied](/cells/python-net/it/aspose.cells/style/is_number_format_applied) | Indica se deve essere applicata la formattazione dei numeri.|
| [is_font_applied](/cells/python-net/it/aspose.cells/style/is_font_applied) |Indica se deve essere applicata la formattazione del carattere.|
| [is_alignment_applied](/cells/python-net/it/aspose.cells/style/is_alignment_applied) | Indica se deve essere applicata la formattazione dell'allineamento.|
| [is_border_applied](/cells/python-net/it/aspose.cells/style/is_border_applied) | Indica se deve essere applicata la formattazione del bordo.|
| [is_fill_applied](/cells/python-net/it/aspose.cells/style/is_fill_applied) | Indica se deve essere applicata la formattazione di riempimento.|
| [is_protection_applied](/cells/python-net/it/aspose.cells/style/is_protection_applied) | Indica se deve essere applicata la formattazione di protezione.|
| [indent_level](/cells/python-net/it/aspose.cells/style/indent_level) | Rappresenta il livello di rientro per la cella o l'intervallo. Può essere un numero intero compreso tra 0 e 250.|
| [font](/cells/python-net/it/aspose.cells/style/font) | Ottiene un oggetto [`Style.font`](/cells/python-net/it/aspose.cells/style#font).|
| [rotation_angle](/cells/python-net/it/aspose.cells/style/rotation_angle) | Rappresenta l'angolo di rotazione del testo.|
| [horizontal_alignment](/cells/python-net/it/aspose.cells/style/horizontal_alignment) | Ottiene o imposta il tipo di allineamento orizzontale del testo in una cella.|
| [vertical_alignment](/cells/python-net/it/aspose.cells/style/vertical_alignment) | Ottiene o imposta il tipo di allineamento verticale del testo in una cella.|
| [is_text_wrapped](/cells/python-net/it/aspose.cells/style/is_text_wrapped) | Ottiene o imposta un valore che indica se il testo all'interno di una cella è suddiviso in righe.|
| [number](/cells/python-net/it/aspose.cells/style/number) | Ottiene o imposta il formato di visualizzazione di numeri e date. I modelli di formattazione sono diversi per le diverse regioni.|
| [is_locked](/cells/python-net/it/aspose.cells/style/is_locked) | Ottiene o imposta un valore che indica se una cella può essere modificata o meno.|
| [custom](/cells/python-net/it/aspose.cells/style/custom) | Rappresenta la stringa di formato numerico personalizzata di questo oggetto stile.<br/>Se il formato numerico personalizzato non è impostato (ad esempio, se il formato numerico è incorporato), verrà restituito "".|
| [culture_custom](/cells/python-net/it/aspose.cells/style/culture_custom) | Ottiene e imposta la stringa modello dipendente dalla cultura per il formato numerico.<br/>Se non è stato impostato alcun formato numerico per questo oggetto, verrà restituito null.<br/> Se il formato numerico è incorporato, verrà restituita la stringa modello corrispondente al numero incorporato.|
| [invariant_custom](/cells/python-net/it/aspose.cells/style/invariant_custom) | Ottiene la stringa modello indipendente dalla cultura per il formato numerico.<br/>Se non è stato impostato alcun formato numerico per questo oggetto, verrà restituito null.<br/> Se il formato numerico è incorporato, verrà restituita la stringa modello corrispondente al numero incorporato.|
| [is_formula_hidden](/cells/python-net/it/aspose.cells/style/is_formula_hidden) | Indica se la formula verrà nascosta quando il foglio di lavoro è protetto.|
| [shrink_to_fit](/cells/python-net/it/aspose.cells/style/shrink_to_fit) | Indica se il testo si riduce automaticamente per adattarsi alla larghezza disponibile della colonna.|
| [text_direction](/cells/python-net/it/aspose.cells/style/text_direction) | Rappresenta l'ordine di lettura del testo.|
| [is_justify_distributed](/cells/python-net/it/aspose.cells/style/is_justify_distributed) | Indica se nell'ultima riga di testo deve essere utilizzato l'allineamento giustificato o distribuito.|
| [quote_prefix](/cells/python-net/it/aspose.cells/style/quote_prefix) | Indica se il valore della cella inizia con un apice singolo.|
| [is_gradient](/cells/python-net/it/aspose.cells/style/is_gradient) | Indica se l'ombreggiatura della cella è un motivo sfumato.|
| [is_percent](/cells/python-net/it/aspose.cells/style/is_percent) | Indica se il formato del numero è un formato percentuale.|
| [is_date_time](/cells/python-net/it/aspose.cells/style/is_date_time) | Indica se il formato numerico è un formato data.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`set_border(self, border_type, border_style, border_color)`](/cells/python-net/it/aspose.cells/style/set_border/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.pydrawing.color) | Imposta i bordi dello stile.|
| [`set_border(self, border_type, border_style, border_color)`](/cells/python-net/it/aspose.cells/style/set_border/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.cells.cellscolor) | Imposta i bordi dello stile.|
| [`set_pattern_color(self, pattern, color1, color2)`](/cells/python-net/it/aspose.cells/style/set_pattern_color/#aspose.cells.backgroundtype-aspose.pydrawing.color-aspose.pydrawing.color) |Imposta il colore di sfondo.|
| [`copy(self, style)`](/cells/python-net/it/aspose.cells/style/copy/#aspose.cells.style) | Copia i dati da un altro oggetto di stile|
| [`update(self)`](/cells/python-net/it/aspose.cells/style/update/#) | Applica lo stile denominato agli stili delle celle che utilizzano tale stile denominato.<br/>Funziona come se si cliccasse sul pulsante "ok" dopo aver terminato di modificare lo stile.<br/> Si applica solo allo stile denominato.|
| [`is_modified(self, modify_flag)`](/cells/python-net/it/aspose.cells/style/is_modified/#aspose.cells.stylemodifyflag) | Controlla se le proprietà specificate dello stile sono state modificate.<br/> Utilizzato per lo stile delle formattazioni condizionali per verificare se le proprietà specificate di questo stile devono essere utilizzate quando si applicano le formattazioni condizionali a una cella.|
| [`set_custom(self, custom, builtin_preference)`](/cells/python-net/it/aspose.cells/style/set_custom/#str-bool) | Imposta la stringa del formato numerico personalizzato di una cella.|
| [`set_two_color_gradient(self, color1, color2, gradient_style_type, variant)`](/cells/python-net/it/aspose.cells/style/set_two_color_gradient/#aspose.pydrawing.color-aspose.pydrawing.color-aspose.cells.drawing.gradientstyletype-int) | Imposta il riempimento specificato su un gradiente a due colori.|
| [`get_two_color_gradient(self, color1, color2, gradient_style_type, variant)`](/cells/python-net/it/aspose.cells/style/get_two_color_gradient/#aspose.pydrawing.color&-aspose.pydrawing.color&-any-any) | Ottieni l'impostazione del gradiente a due colori.|
| [`get_two_color_gradient_setting(self)`](/cells/python-net/it/aspose.cells/style/get_two_color_gradient_setting/#) | Ottieni l'impostazione del gradiente a due colori.|
| [`to_json(self)`](/cells/python-net/it/aspose.cells/style/to_json/#) | Converti i dati della struttura [`Style`](/cells/python-net/it/aspose.cells/style) in JSON.|



###  Esempio

```python
from aspose.cells import Workbook
from aspose.pydrawing import Color

workbook = Workbook()
sheets = workbook.worksheets
cell = sheets[0].cells.get("A1")
style = cell.get_style()
style.font.name = "Times New Roman"
style.font.color = Color.blue
cell.set_style(style)

```

###  Guarda anche
* modulo [`aspose.cells`](..)
* classe [`BorderCollection`](/cells/python-net/it/aspose.cells/bordercollection)
* classe [`Style`](/cells/python-net/it/aspose.cells/style)
