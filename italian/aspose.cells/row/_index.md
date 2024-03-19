---
title: Row classe
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 1340
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
| [height](/cells/python-net/it/aspose.cells/row/height) | Ottiene e imposta l'altezza della riga in unità di punti.|
| [is_hidden](/cells/python-net/it/aspose.cells/row/is_hidden) | Indica se la riga è nascosta.|
| [index](/cells/python-net/it/aspose.cells/row/index) | Ottiene l'indice di questa riga.|
| [group_level](/cells/python-net/it/aspose.cells/row/group_level) | Ottiene il livello di gruppo della riga.|
| [is_height_matched](/cells/python-net/it/aspose.cells/row/is_height_matched) | Indica se l'altezza della riga corrisponde all'impostazione corrente del carattere predefinito della cartella di lavoro.<br/>True di questa proprietà indica anche che l'altezza della riga è "automatica" senza un valore di altezza personalizzato impostato dall'utente.|
| [has_custom_style](/cells/python-net/it/aspose.cells/row/has_custom_style) | Indica se questa riga ha impostazioni di stile personalizzate (diverse da quella predefinita ereditata dalla cartella di lavoro).|
| [first_cell](/cells/python-net/it/aspose.cells/row/first_cell) | Ottiene il primo oggetto cella nella riga.|
| [first_data_cell](/cells/python-net/it/aspose.cells/row/first_data_cell) | Ottiene la prima cella non vuota della riga.|
| [last_cell](/cells/python-net/it/aspose.cells/row/last_cell) | Ottiene l'ultimo oggetto cella nella riga.|
| [last_data_cell](/cells/python-net/it/aspose.cells/row/last_data_cell) | Ottiene l'ultima cella non vuota della riga.|



Ottiene la cella.
###  Indicizzatore
| Nome| Descrizione|
| :- | :- |
| [index] | L'indice della colonna|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [get_cell_by_index](/cells/python-net/it/aspose.cells/row/get_cell_by_index/#int) | Ottieni la cella in base all'indice specifico nella raccolta di celle di questa riga.|
| [get_enumerator](/cells/python-net/it/aspose.cells/row/get_enumerator/#bool-bool) | Ottiene un enumeratore che scorre le celle attraverso questa riga.|
| [get_cell_or_null](/cells/python-net/it/aspose.cells/row/get_cell_or_null/#int) | Ottiene la cella o il valore null nell'indice specifico.|
| [get_style](/cells/python-net/it/aspose.cells/row/get_style/#) | Ottiene lo stile di questa riga.|
| [set_style](/cells/python-net/it/aspose.cells/row/set_style/#aspose.cells.Style) | Imposta lo stile di questa riga.|
| [copy_settings](/cells/python-net/it/aspose.cells/row/copy_settings/#aspose.cells.Row-bool) | Copia le impostazioni della riga, come stile, altezza, visibilità, ... ecc.|
| [apply_style](/cells/python-net/it/aspose.cells/row/apply_style/#aspose.cells.Style-aspose.cells.StyleFlag) | Applica i formati per un'intera riga.|
| [equals](/cells/python-net/it/aspose.cells/row/equals/#aspose.cells.Row) | Controlla se questo oggetto fa riferimento alla stessa riga con un altro oggetto riga.|



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
