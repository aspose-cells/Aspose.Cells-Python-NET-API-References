---
title: Row classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 1230
url: /it/aspose.cells/row/
is_root: false
---
##  Row classe
Rappresenta una singola riga in un foglio di lavoro.



Il tipo Row espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [is_blank](/cells/python-net/it/aspose.cells/row/is_blank) | Indica se la riga contiene dati|
| [is_collapsed](/cells/python-net/it/aspose.cells/row/is_collapsed) | se la riga è compressa|
| [height](/cells/python-net/it/aspose.cells/row/height) | Ottiene e imposta l'altezza della riga in punti.|
| [is_hidden](/cells/python-net/it/aspose.cells/row/is_hidden) | Indica se la riga è nascosta.|
| [index](/cells/python-net/it/aspose.cells/row/index) | Ottiene l'indice di questa riga.|
| [group_level](/cells/python-net/it/aspose.cells/row/group_level) | Ottiene il livello di gruppo della riga.|
| [is_height_matched](/cells/python-net/it/aspose.cells/row/is_height_matched) | Indica se l'altezza della riga corrisponde all'impostazione predefinita del carattere della cartella di lavoro.<br/> Il fatto che questa proprietà sia vera indica anche che l'altezza della riga è "automatica" senza che l'utente imposti un valore di altezza personalizzato.|
| [has_custom_style](/cells/python-net/it/aspose.cells/row/has_custom_style) | Indica se questa riga ha impostazioni di stile personalizzate (diverse da quelle predefinite ereditate dalla cartella di lavoro).|
| [first_cell](/cells/python-net/it/aspose.cells/row/first_cell) | Ottiene il primo oggetto cella nella riga.|
| [first_data_cell](/cells/python-net/it/aspose.cells/row/first_data_cell) |Ottiene la prima cella non vuota nella riga.|
| [last_cell](/cells/python-net/it/aspose.cells/row/last_cell) | Ottiene l'ultimo oggetto cella nella riga.|
| [last_data_cell](/cells/python-net/it/aspose.cells/row/last_data_cell) | Ottiene l'ultima cella non vuota nella riga.|



Ottiene la cella.
###  Indicizzatore
| Nome| Descrizione|
| :- | :- |
| [index] | L'indice della colonna|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`get_cell_by_index(self, index)`](/cells/python-net/it/aspose.cells/row/get_cell_by_index/#int) | Ottieni la cella tramite l'indice specifico nella raccolta di celle di questa riga.|
| [`get_enumerator(self, reversed, sync)`](/cells/python-net/it/aspose.cells/row/get_enumerator/#bool-bool) | Ottiene un enumeratore che scorre le celle attraverso questa riga.|
| [`get_cell_or_null(self, column)`](/cells/python-net/it/aspose.cells/row/get_cell_or_null/#int) | Ottiene la cella o null nell'indice specifico.|
| [`get_style(self)`](/cells/python-net/it/aspose.cells/row/get_style/#) | Ottiene lo stile di questa riga.|
| [`set_style(self, style)`](/cells/python-net/it/aspose.cells/row/set_style/#aspose.cells.style) | Imposta lo stile di questa riga.|
| [`copy_settings(self, source, check_style)`](/cells/python-net/it/aspose.cells/row/copy_settings/#aspose.cells.row-bool) | Copia le impostazioni della riga, come stile, altezza, visibilità, ecc.|
| [`apply_style(self, style, flag)`](/cells/python-net/it/aspose.cells/row/apply_style/#aspose.cells.style-aspose.cells.styleflag) | Applica i formati per un'intera riga.|
| [`equals(self, row)`](/cells/python-net/it/aspose.cells/row/equals/#aspose.cells.row) | Controlla se questo oggetto fa riferimento alla stessa riga di un altro oggetto riga.|



###  Esempio

```python
from aspose.cells import BackgroundType, StyleFlag, Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the first worksheet
worksheet = workbook.worksheets[0]
style = workbook.create_style()
# Setting the background color to Blue
style.background_color = Color.blue
# Setting the foreground color to Red
style.foreground_color = Color.red
# setting Background Pattern
style.pattern = BackgroundType.DIAGONAL_STRIPE
# New Style Flag
styleFlag = StyleFlag()
# Set All Styles
styleFlag.all = True
# Get first row
row = worksheet.cells.rows[0]
# Apply Style to first row
row.apply_style(style, styleFlag)
# Saving the Excel file
workbook.save("book1.xls")

```

###  Guarda anche
* modulo [`aspose.cells`](..)
