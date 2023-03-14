---
title: WorkbookDesigner klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1600
url: /sv/aspose.cells/workbookdesigner/
is_root: false
---
##  WorkbookDesigner klass
Kapslar in objektet som representerar ett designerkalkylblad.



Typen WorkbookDesigner avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [WorkbookDesigner()](/cells/python-net/sv/aspose.cells/workbookdesigner/__init__/#) | Initierar en ny instans av klassen [WorkbookDesigner](/cells/python-net/sv/aspose.cells/workbookdesigner).|
| [WorkbookDesigner(workbook)](/cells/python-net/sv/aspose.cells/workbookdesigner/__init__/#Workbook) | Initierar en ny instans av klassen [WorkbookDesigner](/cells/python-net/sv/aspose.cells/workbookdesigner).|


###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [workbook](/cells/python-net/sv/aspose.cells/workbookdesigner/workbook) |Hämtar och ställer in objektet [WorkbookDesigner.workbook](/cells/python-net/sv/aspose.cells/workbookdesigner#workbook).|
| [repeat_formulas_with_subtotal](/cells/python-net/sv/aspose.cells/workbookdesigner/repeat_formulas_with_subtotal) | Anger om repeterande formler med delsumma rad.|
| [update_empty_string_as_null](/cells/python-net/sv/aspose.cells/workbookdesigner/update_empty_string_as_null) | Om TRUE, kommer Null att infogas om värdet är "";|
| [update_reference](/cells/python-net/sv/aspose.cells/workbookdesigner/update_reference) |Anger om referenser i andra arbetsblad kommer att uppdateras.|
| [calculate_formula](/cells/python-net/sv/aspose.cells/workbookdesigner/calculate_formula) | Anger om formler ska beräknas.|
| [call_back](/cells/python-net/sv/aspose.cells/workbookdesigner/call_back) | Hämtar och ställer in återuppringningsgränssnitt för bearbetning av smartmarker.|
| [line_by_line](/cells/python-net/sv/aspose.cells/workbookdesigner/line_by_line) | Indikerar om den smarta markören bearbetas rad för rad.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [set_data_source(data_source, cells_data_table)](/cells/python-net/sv/aspose.cells/workbookdesigner/set_data_source/#str-ICellsDataTable) | Ställer in datakälla för ett [ICellsDataTable](/cells/python-net/sv/aspose.cells/icellsdatatable)-objekt.|
| [set_data_source(variable, data)](/cells/python-net/sv/aspose.cells/workbookdesigner/set_data_source/#str-any) | Ställer in databindning till en variabel.|
| [process()](/cells/python-net/sv/aspose.cells/workbookdesigner/process/#) | Bearbetar de smarta markörerna och fyller i datakällans värden.|
| [process(is_preserved)](/cells/python-net/sv/aspose.cells/workbookdesigner/process/#bool) | Bearbetar de smarta markörerna och fyller i datakällans värden.|
| [process(sheet_index, is_preserved)](/cells/python-net/sv/aspose.cells/workbookdesigner/process/#int-bool) | Bearbetar de smarta markörerna och fyller i datakällans värden.|
| [clear_data_source()](/cells/python-net/sv/aspose.cells/workbookdesigner/clear_data_source/#) | Rensar alla datakällor.|
| [get_smart_markers()](/cells/python-net/sv/aspose.cells/workbookdesigner/get_smart_markers/#) | Returnerar en samling smarta markörer i ett kalkylblad.|



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
* modul [aspose.cells](..)
* klass [ICellsDataTable](/cells/python-net/sv/aspose.cells/icellsdatatable)
* klass [WorkbookDesigner](/cells/python-net/sv/aspose.cells/workbookdesigner)
