---
title: WorkbookDesigner classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 1580
url: /it/aspose.cells/workbookdesigner/
is_root: false
---
##  WorkbookDesigner classe
Incapsula l'oggetto che rappresenta un foglio di calcolo del progettista.



Il tipo WorkbookDesigner espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [`__init__(self)`](/cells/python-net/it/aspose.cells/workbookdesigner/__init__/#) | Inizializza una nuova istanza della classe [`WorkbookDesigner`](/cells/python-net/it/aspose.cells/workbookdesigner).|
| [`__init__(self, workbook)`](/cells/python-net/it/aspose.cells/workbookdesigner/__init__/#aspose.cells.workbook) | Inizializza una nuova istanza della classe [`WorkbookDesigner`](/cells/python-net/it/aspose.cells/workbookdesigner).|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [workbook](/cells/python-net/it/aspose.cells/workbookdesigner/workbook) | Ottiene e imposta l'oggetto [`WorkbookDesigner.workbook`](/cells/python-net/it/aspose.cells/workbookdesigner#workbook).|
| [repeat_formulas_with_subtotal](/cells/python-net/it/aspose.cells/workbookdesigner/repeat_formulas_with_subtotal) | Indica se ripetere le formule con la riga del subtotale.|
| [update_empty_string_as_null](/cells/python-net/it/aspose.cells/workbookdesigner/update_empty_string_as_null) |Se VERO, verrà inserito Null se il valore è "";|
| [update_reference](/cells/python-net/it/aspose.cells/workbookdesigner/update_reference) | Indica se i riferimenti negli altri fogli di lavoro verranno aggiornati.|
| [calculate_formula](/cells/python-net/it/aspose.cells/workbookdesigner/calculate_formula) | Indica se le formule devono essere calcolate.|
| [line_by_line](/cells/python-net/it/aspose.cells/workbookdesigner/line_by_line) | Indica se l'elaborazione del marcatore intelligente avviene riga per riga.|
| [contains_variables](/cells/python-net/it/aspose.cells/workbookdesigner/contains_variables) | Indica se il primo foglio di lavoro contiene variabili personalizzate.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`set_data_source(self, data_source, cells_data_table)`](/cells/python-net/it/aspose.cells/workbookdesigner/set_data_source/#str-icellsdatatable) |  |
| [`set_data_source(self, variable, data)`](/cells/python-net/it/aspose.cells/workbookdesigner/set_data_source/#str-any) | Imposta l'associazione dei dati a una variabile.|
| [`process(self, range, is_preserved)`](/cells/python-net/it/aspose.cells/workbookdesigner/process/#aspose.cells.range-bool) | Elabora i marcatori intelligenti e popola i valori della sorgente dati.|
| [`process(self)`](/cells/python-net/it/aspose.cells/workbookdesigner/process/#) | Elabora i marcatori intelligenti e popola i valori della sorgente dati.|
| [`process(self, is_preserved)`](/cells/python-net/it/aspose.cells/workbookdesigner/process/#bool) | Elabora i marcatori intelligenti e popola i valori della sorgente dati.|
| [`process(self, sheet_index, is_preserved)`](/cells/python-net/it/aspose.cells/workbookdesigner/process/#int-bool) | Elabora i marcatori intelligenti e popola i valori della sorgente dati.|
| [`clear_data_source(self)`](/cells/python-net/it/aspose.cells/workbookdesigner/clear_data_source/#) | Cancella tutte le origini dati.|
| [`set_json_data_source(self, variable, data)`](/cells/python-net/it/aspose.cells/workbookdesigner/set_json_data_source/#str-str) |  |
| [`get_smart_markers(self)`](/cells/python-net/it/aspose.cells/workbookdesigner/get_smart_markers/#) | Restituisce una raccolta di marcatori intelligenti in un foglio di calcolo.|



###  Esempio

```python
from aspose.cells import Workbook, WorkbookDesigner

# Create WorkbookDesigner object.
wd = WorkbookDesigner()
# Open the template file (which contains smart markers).
wd.workbook = Workbook("SmartMarker_Designer.xls")
# Initialize your data from data source
# DataSet ds = new DataSet();
# ...
# Set the datatable as the data source.
# wd.SetDataSource(dt);
# Process the smart markers to fill the data into the worksheets.
wd.process(True)
# Save the excel file.
wd.workbook.save("outSmartMarker_Designer.xls")

```

###  Guarda anche
* modulo [`aspose.cells`](..)
* classe [`WorkbookDesigner`](/cells/python-net/it/aspose.cells/workbookdesigner)
