---
title: Column classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 240
url: /it/aspose.cells/column/
is_root: false
---
##  Column classe
Rappresenta una singola colonna in un foglio di lavoro.



Il tipo Column espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [index](/cells/python-net/it/aspose.cells/column/index) | Ottiene l'indice di questa colonna.|
| [width](/cells/python-net/it/aspose.cells/column/width) | Ottiene e imposta la larghezza della colonna in unità di caratteri.|
| [group_level](/cells/python-net/it/aspose.cells/column/group_level) | Ottiene il livello di gruppo della colonna.|
| [is_hidden](/cells/python-net/it/aspose.cells/column/is_hidden) | Indica se la colonna è nascosta.|
| [has_custom_style](/cells/python-net/it/aspose.cells/column/has_custom_style) | Indica se questa colonna ha impostazioni di stile personalizzate (diverse da quelle predefinite ereditate dalla cartella di lavoro).|
| [style](/cells/python-net/it/aspose.cells/column/style) | Ottiene lo stile di questa colonna.|
| [is_collapsed](/cells/python-net/it/aspose.cells/column/is_collapsed) | se la colonna è compressa|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`apply_style(self, style, flag)`](/cells/python-net/it/aspose.cells/column/apply_style/#aspose.cells.style-aspose.cells.styleflag) | Applica i formati per un'intera colonna.|
| [`get_style(self)`](/cells/python-net/it/aspose.cells/column/get_style/#) | Ottiene lo stile di questa colonna.|
| [`set_style(self, style)`](/cells/python-net/it/aspose.cells/column/set_style/#aspose.cells.style) | Imposta lo stile di questa colonna.|



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
# Get first Column
column = worksheet.cells.columns[0]
# Apply Style to first Column
column.apply_style(style, styleFlag)
# Saving the Excel file
workbook.save("book1.xls")

```

###  Guarda anche
* modulo [`aspose.cells`](..)
