---
title: FormatCondition classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 700
url: /it/aspose.cells/formatcondition/
is_root: false
---
##  FormatCondition classe
Rappresenta la condizione di formattazione condizionale.



Il tipo FormatCondition espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [formula1](/cells/python-net/it/aspose.cells/formatcondition/formula1) | Ottiene e imposta il valore o l'espressione associata alla formattazione condizionale.|
| [formula2](/cells/python-net/it/aspose.cells/formatcondition/formula2) | Ottiene e imposta il valore o l'espressione associata alla formattazione condizionale.|
| [operator](/cells/python-net/it/aspose.cells/formatcondition/operator) | Ottiene e imposta il tipo di operatore di formato condizionale.|
| [stop_if_true](/cells/python-net/it/aspose.cells/formatcondition/stop_if_true) |Vero, nessuna regola con priorità inferiore può essere applicata a questa regola, quando questa regola viene valutata come vera.<br/> Si applica solo a Excel 2007;|
| [priority](/cells/python-net/it/aspose.cells/formatcondition/priority) | La priorità di questa regola di formattazione condizionale. Questo valore viene utilizzato per determinare quale<br/>il formato dovrebbe essere valutato e reso. I valori numerici più bassi hanno una priorità maggiore rispetto a<br/> valori numerici più elevati, dove '1' rappresenta la priorità più alta.|
| [style](/cells/python-net/it/aspose.cells/formatcondition/style) | Ottiene o imposta lo stile degli intervalli di celle formattate in modo condizionale.|
| [type](/cells/python-net/it/aspose.cells/formatcondition/type) | Ottiene e imposta se il formato condizionale è Type.|
| [icon_set](/cells/python-net/it/aspose.cells/formatcondition/icon_set) | Ottieni l'istanza "IconSet" della formattazione condizionale.<br/>L'IconSetType dell'istanza predefinita è TrafficLights31.<br/> Valido solo per il tipo = IconSet.|
| [data_bar](/cells/python-net/it/aspose.cells/formatcondition/data_bar) | Ottieni l'istanza "DataBar" della formattazione condizionale.<br/>Il colore predefinito dell'istanza è blu.<br/> Valido solo per il tipo DataBar.|
| [color_scale](/cells/python-net/it/aspose.cells/formatcondition/color_scale) | Ottieni l'istanza "ColorScale" della formattazione condizionale.<br/>L'istanza predefinita è 3ColorScale "verde-giallo-rosso".<br/> Valido solo per tipo = ColorScale.|
| [top10](/cells/python-net/it/aspose.cells/formatcondition/top10) | Ottieni l'istanza "Top10" della formattazione condizionale.<br/>La regola dell'istanza predefinita evidenzia le celle la cui<br/>i valori rientrano nella fascia dei primi 10.<br/> Valido solo per il tipo Top10.|
| [above_average](/cells/python-net/it/aspose.cells/formatcondition/above_average) |Ottieni l'istanza "AboveAverage" della formattazione condizionale.<br/> La regola dell'istanza predefinita evidenzia le celle che sono<br/>al di sopra della media di tutti i valori nell'intervallo.<br/> Valido solo per tipo = AboveAverage.|
| [text](/cells/python-net/it/aspose.cells/formatcondition/text) | Valore di testo in una regola di formattazione condizionale "testo contiene".<br/>Valido solo per i tipi = containsText, notContainsText, beginsWith e endsWith.<br/> Il valore predefinito è null.|
| [time_period](/cells/python-net/it/aspose.cells/formatcondition/time_period) | Periodo di tempo applicabile in una regola di formattazione condizionale "data di ricorrenza...".<br/>Valido solo per tipo = timePeriod.<br/> Il valore predefinito è TimePeriodType.Today.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`get_formula1(self, is_r1c1, is_local)`](/cells/python-net/it/aspose.cells/formatcondition/get_formula1/#bool-bool) | Ottiene il valore o l'espressione associata a questa condizione di formato.|
| [`get_formula1(self, is_r1c1, is_local, row, column)`](/cells/python-net/it/aspose.cells/formatcondition/get_formula1/#bool-bool-int-int) | Ottiene il valore o l'espressione della formattazione condizionale della cella.|
| [`get_formula1(self, row, column)`](/cells/python-net/it/aspose.cells/formatcondition/get_formula1/#int-int) | Ottiene la formula della formattazione condizionale della cella.|
| [`get_formula2(self, is_r1c1, is_local)`](/cells/python-net/it/aspose.cells/formatcondition/get_formula2/#bool-bool) | Ottiene il valore o l'espressione associata a questa condizione di formato.|
| [`get_formula2(self, is_r1c1, is_local, row, column)`](/cells/python-net/it/aspose.cells/formatcondition/get_formula2/#bool-bool-int-int) | Ottiene il valore o l'espressione della formattazione condizionale della cella.|
| [`get_formula2(self, row, column)`](/cells/python-net/it/aspose.cells/formatcondition/get_formula2/#int-int) | Ottiene la formula della formattazione condizionale della cella.|
| [`set_formulas(self, formula1, formula2, is_r1c1, is_local)`](/cells/python-net/it/aspose.cells/formatcondition/set_formulas/#str-str-bool-bool) | Imposta il valore o l'espressione associata a questa condizione di formato.|
| [`set_formula1(self, formula, is_r1c1, is_local)`](/cells/python-net/it/aspose.cells/formatcondition/set_formula1/#str-bool-bool) | Imposta il valore o l'espressione associata a questa condizione di formato.|
| [`set_formula2(self, formula, is_r1c1, is_local)`](/cells/python-net/it/aspose.cells/formatcondition/set_formula2/#str-bool-bool) | Imposta il valore o l'espressione associata a questa condizione di formato.|



###  Esempio

```python
from aspose.cells import CellArea, FormatConditionType, OperatorType, Workbook
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
ca.end_row = 0
ca.start_column = 0
ca.end_column = 0
fcs.add_area(ca)
ca = CellArea()
ca.start_row = 1
ca.end_row = 1
ca.start_column = 1
ca.end_column = 1
fcs.add_area(ca)
# Adds condition.
conditionIndex = fcs.add_condition(FormatConditionType.CELL_VALUE, OperatorType.BETWEEN, "=A2", "100")
# Adds condition.
conditionIndex2 = fcs.add_condition(FormatConditionType.CELL_VALUE, OperatorType.BETWEEN, "50", "100")
# Sets the background color.
fc = fcs[conditionIndex]
fc.style.background_color = Color.red
# Saving the Excel file
workbook.save("output.xls")

```

###  Guarda anche
* modulo [`aspose.cells`](..)
