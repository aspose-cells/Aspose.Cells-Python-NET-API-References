---
title: WorkbookDesigner classe
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 1670
url: /it/aspose.cells/workbookdesigner/
is_root: false
---
##  WorkbookDesigner classe
Incapsula l'oggetto che rappresenta un foglio di calcolo della finestra di progettazione.



Il tipo WorkbookDesigner espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [__init__](/cells/python-net/it/aspose.cells/workbookdesigner/__init__/#) | Inizializza una nuova istanza della classe [`WorkbookDesigner`](/cells/python-net/it/aspose.cells/workbookdesigner).|
| [__init__](/cells/python-net/it/aspose.cells/workbookdesigner/__init__/#aspose.cells.Workbook) | Inizializza una nuova istanza della classe [`WorkbookDesigner`](/cells/python-net/it/aspose.cells/workbookdesigner).|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [workbook](/cells/python-net/it/aspose.cells/workbookdesigner/workbook) | Ottiene e imposta l'oggetto [`WorkbookDesigner.workbook`](/cells/python-net/it/aspose.cells/workbookdesigner#workbook).|
| [repeat_formulas_with_subtotal](/cells/python-net/it/aspose.cells/workbookdesigner/repeat_formulas_with_subtotal) | Indica se ripetere le formule con la riga del totale parziale.|
| [update_empty_string_as_null](/cells/python-net/it/aspose.cells/workbookdesigner/update_empty_string_as_null) | Se TRUE, verrà inserito Null se il valore è "";|
| [update_reference](/cells/python-net/it/aspose.cells/workbookdesigner/update_reference) | Indica se i riferimenti in altri fogli di lavoro verranno aggiornati.|
| [calculate_formula](/cells/python-net/it/aspose.cells/workbookdesigner/calculate_formula) | Indica se le formule devono essere calcolate.|
| [call_back](/cells/python-net/it/aspose.cells/workbookdesigner/call_back) | Ottiene e imposta l'interfaccia di callback per l'elaborazione dello smartmarker.|
| [line_by_line](/cells/python-net/it/aspose.cells/workbookdesigner/line_by_line) | Indica se elaborare lo smart marker riga per riga.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [set_data_source](/cells/python-net/it/aspose.cells/workbookdesigner/set_data_source/#str-aspose.cells.ICellsDataTable) | Imposta l'origine dati di un oggetto [`ICellsDataTable`](/cells/python-net/it/aspose.cells/icellsdatatable).|
| [set_data_source](/cells/python-net/it/aspose.cells/workbookdesigner/set_data_source/#str-any) | Imposta l'associazione dati a una variabile.|
| [process](/cells/python-net/it/aspose.cells/workbookdesigner/process/#) |Elabora gli indicatori intelligenti e popola i valori dell'origine dati.|
| [process](/cells/python-net/it/aspose.cells/workbookdesigner/process/#bool) |Elabora gli indicatori intelligenti e popola i valori dell'origine dati.|
| [process](/cells/python-net/it/aspose.cells/workbookdesigner/process/#int-bool) |Elabora gli indicatori intelligenti e popola i valori dell'origine dati.|
| [clear_data_source](/cells/python-net/it/aspose.cells/workbookdesigner/clear_data_source/#) | Cancella tutte le origini dati.|
| [set_json_data_source](/cells/python-net/it/aspose.cells/workbookdesigner/set_json_data_source/#str-str) |  |
| [get_smart_markers](/cells/python-net/it/aspose.cells/workbookdesigner/get_smart_markers/#) | Restituisce una raccolta di indicatori intelligenti in un foglio di calcolo.|



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
* classe [`ICellsDataTable`](/cells/python-net/it/aspose.cells/icellsdatatable)
* classe [`WorkbookDesigner`](/cells/python-net/it/aspose.cells/workbookdesigner)
