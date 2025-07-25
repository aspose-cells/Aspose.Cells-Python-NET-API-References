---
title: ListObject klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 30
url: /sv/aspose.cells.tables/listobject/
is_root: false
---
##  ListObject klass
Representerar ett listobjekt i ett kalkylblad.
 Objektet ListObject är medlem i ListObjects-samlingen.
ListObjects-samlingen innehåller alla listobjekt i ett kalkylblad.



Typen ListObject avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [start_row](/cells/python-net/sv/aspose.cells.tables/listobject/start_row) | Hämtar startraden i intervallet.|
| [start_column](/cells/python-net/sv/aspose.cells.tables/listobject/start_column) | Hämtar startkolumnen för intervallet.|
| [end_row](/cells/python-net/sv/aspose.cells.tables/listobject/end_row) | Hämtar den sista raden i intervallet.|
| [end_column](/cells/python-net/sv/aspose.cells.tables/listobject/end_column) | Hämtar intervallets slutkolumn.|
| [list_columns](/cells/python-net/sv/aspose.cells.tables/listobject/list_columns) | Hämtar ListColumns från ListObject.|
| [show_header_row](/cells/python-net/sv/aspose.cells.tables/listobject/show_header_row) | Hämtar och anger om detta ListObject ska visa rubrikraden.|
| [show_totals](/cells/python-net/sv/aspose.cells.tables/listobject/show_totals) | Hämtar och anger om detta ListObject visar en total rad.|
| [data_range](/cells/python-net/sv/aspose.cells.tables/listobject/data_range) | Hämtar dataområdet för ListObject.|
| [query_table](/cells/python-net/sv/aspose.cells.tables/listobject/query_table) | Hämtar den länkade frågetabellen.|
| [data_source_type](/cells/python-net/sv/aspose.cells.tables/listobject/data_source_type) |Hämtar datakälltypen för tabellen.|
| [auto_filter](/cells/python-net/sv/aspose.cells.tables/listobject/auto_filter) | Hämtar automatiskt filter.|
| [display_name](/cells/python-net/sv/aspose.cells.tables/listobject/display_name) | Hämtar och anger visningsnamnet.|
| [comment](/cells/python-net/sv/aspose.cells.tables/listobject/comment) | Hämtar och anger tabellens kommentar.|
| [show_table_style_first_column](/cells/python-net/sv/aspose.cells.tables/listobject/show_table_style_first_column) | Anger om den första kolumnen i tabellen ska ha stilen tillämpad.|
| [show_table_style_last_column](/cells/python-net/sv/aspose.cells.tables/listobject/show_table_style_last_column) | Anger om den sista kolumnen i tabellen ska ha stilen tillämpad.|
| [show_table_style_row_stripes](/cells/python-net/sv/aspose.cells.tables/listobject/show_table_style_row_stripes) | Anger om radrandformatering tillämpas.|
| [show_table_style_column_stripes](/cells/python-net/sv/aspose.cells.tables/listobject/show_table_style_column_stripes) | Anger om formatering för kolumnrand tillämpas.|
| [table_style_type](/cells/python-net/sv/aspose.cells.tables/listobject/table_style_type) | Gets och den inbyggda tabellstilen.|
| [table_style_name](/cells/python-net/sv/aspose.cells.tables/listobject/table_style_name) | Hämtar och anger tabellstilens namn.|
| [xml_map](/cells/python-net/sv/aspose.cells.tables/listobject/xml_map) | Får en [`ListObject.xml_map`](/cells/python-net/sv/aspose.cells.tables/listobject#xml_map) som används för den här listan.|
| [alternative_text](/cells/python-net/sv/aspose.cells.tables/listobject/alternative_text) | Hämtar och ställer in alternativ text.|
| [alternative_description](/cells/python-net/sv/aspose.cells.tables/listobject/alternative_description) | Hämtar och anger den alternativa beskrivningen.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`put_cell_value(self, row_offset, column_offset, value)`](/cells/python-net/sv/aspose.cells.tables/listobject/put_cell_value/#int-int-any) | Sätt in värdet i cellen.|
| [`put_cell_value(self, row_offset, column_offset, value, is_totals_row_label)`](/cells/python-net/sv/aspose.cells.tables/listobject/put_cell_value/#int-int-any-bool) | Sätt in värdet i cellen.|
| [`put_cell_formula(self, row_offset, column_offset, formula)`](/cells/python-net/sv/aspose.cells.tables/listobject/put_cell_formula/#int-int-str) | Sätt in formeln i cellen i tabellen.|
| [`put_cell_formula(self, row_offset, column_offset, formula, is_totals_row_formula)`](/cells/python-net/sv/aspose.cells.tables/listobject/put_cell_formula/#int-int-str-bool) | Sätt in formeln i cellen i tabellen.|
| [`convert_to_range(self)`](/cells/python-net/sv/aspose.cells.tables/listobject/convert_to_range/#) | Konvertera tabellen till ett intervall.|
| [`convert_to_range(self, options)`](/cells/python-net/sv/aspose.cells.tables/listobject/convert_to_range/#aspose.cells.tables.tabletorangeoptions) | Konvertera tabellen till ett intervall.|
| [`resize(self, start_row, start_column, end_row, end_column, has_headers)`](/cells/python-net/sv/aspose.cells.tables/listobject/resize/#int-int-int-int-bool) | Ändra storlek på listobjektets område.|
| [`update_column_name(self)`](/cells/python-net/sv/aspose.cells.tables/listobject/update_column_name/#) | Uppdaterar alla listkolumners namn från kalkylbladet.|
| [`filter(self)`](/cells/python-net/sv/aspose.cells.tables/listobject/filter/#) | Filtrera tabellen.|
| [`apply_style_to_range(self)`](/cells/python-net/sv/aspose.cells.tables/listobject/apply_style_to_range/#) | Tillämpa tabellformatet på intervallet.|



###  Exempel

```python
from aspose.cells import CellsHelper, Workbook
from aspose.cells.tables import TotalsCalculation

workbook = Workbook()
cells = workbook.worksheets[0].cells
for i in range(5):
    cells.get(0, i).put_value(CellsHelper.column_index_to_name(i))
for row in range(1, 10):
    for column in range(5):
        cells.get(row, column).put_value(row * column)
tables = workbook.worksheets[0].list_objects
index = tables.add(0, 0, 9, 4, True)
table = tables[0]
table.show_totals = True
table.list_columns[4].totals_calculation = TotalsCalculation.SUM
workbook.save(r"Book1.xlsx")

```

###  Se även
* modul [`aspose.cells.tables`](..)
