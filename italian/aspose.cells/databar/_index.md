---
title: DataBar classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 390
url: /it/aspose.cells/databar/
is_root: false
---
##  DataBar classe
 Descrivere la regola di formattazione condizionale DataBar.
Questa regola di formattazione condizionale visualizza una graduazione
barra dati nell'intervallo di celle.



Il tipo DataBar espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [axis_color](/cells/python-net/it/aspose.cells/databar/axis_color) | Ottiene il colore dell'asse per le celle con formattazione condizionale come barre dati.|
| [axis_position](/cells/python-net/it/aspose.cells/databar/axis_position) | Ottiene o imposta la posizione dell'asse delle barre dati specificate da una regola di formattazione condizionale.|
| [bar_fill_type](/cells/python-net/it/aspose.cells/databar/bar_fill_type) | Ottiene o imposta il modo in cui una barra dati viene riempita con il colore.|
| [direction](/cells/python-net/it/aspose.cells/databar/direction) | Ottiene o imposta la direzione in cui viene visualizzata la barra dei dati.|
| [bar_border](/cells/python-net/it/aspose.cells/databar/bar_border) | Ottiene un oggetto che specifica il bordo di una barra dati.|
| [negative_bar_format](/cells/python-net/it/aspose.cells/databar/negative_bar_format) | Ottiene l'oggetto NegativeBarFormat associato a una regola di formattazione condizionale della barra dati.|
| [min_cfvo](/cells/python-net/it/aspose.cells/databar/min_cfvo) | Ottieni o imposta il valore minimo di questo oggetto DataBar.<br/> Non è possibile impostare null o CFValueObject con tipo FormatConditionValueType.Max.|
| [max_cfvo](/cells/python-net/it/aspose.cells/databar/max_cfvo) | Ottieni o imposta il valore massimo di questo oggetto DataBar.<br/> Non è possibile impostare null o CFValueObject con tipo FormatConditionValueType.Min.|
| [color](/cells/python-net/it/aspose.cells/databar/color) | Ottieni o imposta il colore di questo DataBar.|
| [min_length](/cells/python-net/it/aspose.cells/databar/min_length) | Rappresenta la lunghezza minima della barra dati.|
| [max_length](/cells/python-net/it/aspose.cells/databar/max_length) | Rappresenta la lunghezza massima della barra dati.|
| [show_value](/cells/python-net/it/aspose.cells/databar/show_value) |Ottieni o imposta il flag che indica se visualizzare i valori delle celle a cui è applicata questa barra dati.<br/> Il valore predefinito è vero.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`to_image(self, cell, img_opts)`](/cells/python-net/it/aspose.cells/databar/to_image/#aspose.cells.cell-aspose.cells.rendering.imageorprintoptions) | Trasforma la barra dati nella cella in un array di byte dell'immagine.|



###  Esempio

```python
from aspose.cells import CellArea, DataBarAxisPosition, DataBarBorderType, DataBarFillType, DataBarNegativeColorType, FormatConditionType, FormatConditionValueType, Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
sheet = workbook.worksheets[0]
# Adds an empty conditional formatting
index = sheet.conditional_formattings.add()
fcs = sheet.conditional_formattings[index]
# Sets the conditional format range.
ca = CellArea()
ca.start_row = 0
ca.end_row = 2
ca.start_column = 0
ca.end_column = 0
fcs.add_area(ca)
# Adds condition.
idx = fcs.add_condition(FormatConditionType.DATA_BAR)
fcs.add_area(ca)
cond = fcs[idx]
# Get Databar
dataBar = cond.data_bar
dataBar.color = Color.orange
# Set Databar properties
dataBar.min_cfvo.type = FormatConditionValueType.PERCENTILE
dataBar.min_cfvo.value = 30
dataBar.show_value = False
dataBar.bar_border.type = DataBarBorderType.SOLID
dataBar.bar_border.color = Color.plum
dataBar.bar_fill_type = DataBarFillType.SOLID
dataBar.axis_color = Color.red
dataBar.axis_position = DataBarAxisPosition.MIDPOINT
dataBar.negative_bar_format.color_type = DataBarNegativeColorType.COLOR
dataBar.negative_bar_format.color = Color.white
dataBar.negative_bar_format.border_color_type = DataBarNegativeColorType.COLOR
dataBar.negative_bar_format.border_color = Color.yellow
# Put Cell Values
cell1 = sheet.cells.get("A1")
cell1.put_value(10)
cell2 = sheet.cells.get("A2")
cell2.put_value(120)
cell3 = sheet.cells.get("A3")
cell3.put_value(260)
# Saving the Excel file
workbook.save("book1.xlsx")

```

###  Guarda anche
* modulo [`aspose.cells`](..)
