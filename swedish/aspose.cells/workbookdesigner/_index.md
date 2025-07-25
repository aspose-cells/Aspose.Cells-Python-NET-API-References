---
title: WorkbookDesigner klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1580
url: /sv/aspose.cells/workbookdesigner/
is_root: false
---
##  WorkbookDesigner klass
Inkapslar objektet som representerar ett Designer-kalkylblad.



Typen WorkbookDesigner avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [`__init__(self)`](/cells/python-net/sv/aspose.cells/workbookdesigner/__init__/#) | Initierar en ny instans av klassen [`WorkbookDesigner`](/cells/python-net/sv/aspose.cells/workbookdesigner).|
| [`__init__(self, workbook)`](/cells/python-net/sv/aspose.cells/workbookdesigner/__init__/#aspose.cells.workbook) | Initierar en ny instans av klassen [`WorkbookDesigner`](/cells/python-net/sv/aspose.cells/workbookdesigner).|


###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [workbook](/cells/python-net/sv/aspose.cells/workbookdesigner/workbook) | Hämtar och anger [`WorkbookDesigner.workbook`](/cells/python-net/sv/aspose.cells/workbookdesigner#workbook)-objektet.|
| [repeat_formulas_with_subtotal](/cells/python-net/sv/aspose.cells/workbookdesigner/repeat_formulas_with_subtotal) | Anger om upprepade formler med delsummarad är obligatoriska.|
| [update_empty_string_as_null](/cells/python-net/sv/aspose.cells/workbookdesigner/update_empty_string_as_null) |Om TRUE, infogas Null om värdet är "";|
| [update_reference](/cells/python-net/sv/aspose.cells/workbookdesigner/update_reference) | Anger om referenser i andra arbetsblad kommer att uppdateras.|
| [calculate_formula](/cells/python-net/sv/aspose.cells/workbookdesigner/calculate_formula) | Anger om formler ska beräknas.|
| [line_by_line](/cells/python-net/sv/aspose.cells/workbookdesigner/line_by_line) | Anger om den smarta markören bearbetas rad för rad.|
| [contains_variables](/cells/python-net/sv/aspose.cells/workbookdesigner/contains_variables) | Anger om det första kalkylbladet innehåller anpassade variabler.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`set_data_source(self, data_source, cells_data_table)`](/cells/python-net/sv/aspose.cells/workbookdesigner/set_data_source/#str-icellsdatatable) |  |
| [`set_data_source(self, variable, data)`](/cells/python-net/sv/aspose.cells/workbookdesigner/set_data_source/#str-any) | Ställer in databindning till en variabel.|
| [`process(self, range, is_preserved)`](/cells/python-net/sv/aspose.cells/workbookdesigner/process/#aspose.cells.range-bool) | Bearbetar de smarta markörerna och fyller i datakällans värden.|
| [`process(self)`](/cells/python-net/sv/aspose.cells/workbookdesigner/process/#) | Bearbetar de smarta markörerna och fyller i datakällans värden.|
| [`process(self, is_preserved)`](/cells/python-net/sv/aspose.cells/workbookdesigner/process/#bool) | Bearbetar de smarta markörerna och fyller i datakällans värden.|
| [`process(self, sheet_index, is_preserved)`](/cells/python-net/sv/aspose.cells/workbookdesigner/process/#int-bool) | Bearbetar de smarta markörerna och fyller i datakällans värden.|
| [`clear_data_source(self)`](/cells/python-net/sv/aspose.cells/workbookdesigner/clear_data_source/#) | Rensar alla datakällor.|
| [`set_json_data_source(self, variable, data)`](/cells/python-net/sv/aspose.cells/workbookdesigner/set_json_data_source/#str-str) |  |
| [`get_smart_markers(self)`](/cells/python-net/sv/aspose.cells/workbookdesigner/get_smart_markers/#) | Returnerar en samling smarta markörer i ett kalkylblad.|



###  Exempel

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

###  Se även
* modul [`aspose.cells`](..)
* klass [`WorkbookDesigner`](/cells/python-net/sv/aspose.cells/workbookdesigner)
