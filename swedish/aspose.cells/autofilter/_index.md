---
title: AutoFilter klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 40
url: /sv/aspose.cells/autofilter/
is_root: false
---
##  AutoFilter klass
Representerar autofiltrering för det angivna kalkylbladet.



Typen AutoFilter avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [sorter](/cells/python-net/sv/aspose.cells/autofilter/sorter) | Hämtar datasorteraren.|
| [range](/cells/python-net/sv/aspose.cells/autofilter/range) | Representerar det område som det angivna autofiltret gäller för.|
| [show_filter_button](/cells/python-net/sv/aspose.cells/autofilter/show_filter_button) | Anger om knappen Autofilter för den här kolumnen är synlig.|
| [filter_columns](/cells/python-net/sv/aspose.cells/autofilter/filter_columns) | Hämtar samlingen av filterkolumnerna.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`get_cell_area(self)`](/cells/python-net/sv/aspose.cells/autofilter/get_cell_area/#) | Hämtar [`CellArea`](/cells/python-net/sv/aspose.cells/cellarea) där detta autofilter gäller.|
| [`get_cell_area(self, refresh_applied_range)`](/cells/python-net/sv/aspose.cells/autofilter/get_cell_area/#bool) | Hämtar [`CellArea`](/cells/python-net/sv/aspose.cells/cellarea) där det angivna autofiltret gäller för.|
| [`remove_filter(self, field_index, criteria)`](/cells/python-net/sv/aspose.cells/autofilter/remove_filter/#int-str) | Tar bort ett filter för en filterkolumn.|
| [`remove_filter(self, field_index)`](/cells/python-net/sv/aspose.cells/autofilter/remove_filter/#int) | Ta bort det specifika filtret.|
| [`custom(self, field_index, operator_type1, criteria1)`](/cells/python-net/sv/aspose.cells/autofilter/custom/#int-aspose.cells.filteroperatortype-any) | Filtrerar en lista med anpassade kriterier.|
| [`custom(self, field_index, operator_type1, criteria1, is_and, operator_type2, criteria2)`](/cells/python-net/sv/aspose.cells/autofilter/custom/#int-aspose.cells.filteroperatortype-any-bool-aspose.cells.filteroperatortype-any) | Filtrerar en lista med anpassade kriterier.|
| [`refresh(self)`](/cells/python-net/sv/aspose.cells/autofilter/refresh/#) | Uppdatera autofilter för att dölja eller visa raderna.|
| [`refresh(self, hide_rows)`](/cells/python-net/sv/aspose.cells/autofilter/refresh/#bool) | Hämtar alla index för dolda rader.|
| [`set_range(self, row, start_column, end_column)`](/cells/python-net/sv/aspose.cells/autofilter/set_range/#int-int-int) | Anger det område som det angivna autofiltret gäller för.|
| [`add_filter(self, field_index, criteria)`](/cells/python-net/sv/aspose.cells/autofilter/add_filter/#int-str) | Lägger till ett filter för en filterkolumn.|
| [`add_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second)`](/cells/python-net/sv/aspose.cells/autofilter/add_date_filter/#int-aspose.cells.datetimegroupingtype-int-int-int-int-int-int) | Lägger till ett datumfilter.|
| [`remove_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second)`](/cells/python-net/sv/aspose.cells/autofilter/remove_date_filter/#int-aspose.cells.datetimegroupingtype-int-int-int-int-int-int) |Tar bort ett datumfilter.|
| [`filter(self, field_index, criteria)`](/cells/python-net/sv/aspose.cells/autofilter/filter/#int-str) | Filtrerar en lista med angivna kriterier.|
| [`filter_top10(self, field_index, is_top, is_percent, item_count)`](/cells/python-net/sv/aspose.cells/autofilter/filter_top10/#int-bool-bool-int) | Filtrera de 10 främsta objekten i listan|
| [`dynamic_filter(self, field_index, dynamic_filter_type)`](/cells/python-net/sv/aspose.cells/autofilter/dynamic_filter/#int-aspose.cells.dynamicfiltertype) | Lägger till ett dynamiskt filter.|
| [`add_font_color_filter(self, field_index, color)`](/cells/python-net/sv/aspose.cells/autofilter/add_font_color_filter/#int-aspose.cells.cellscolor) | Lägger till ett filter för teckensnittsfärg.|
| [`add_fill_color_filter(self, field_index, pattern, foreground_color, background_color)`](/cells/python-net/sv/aspose.cells/autofilter/add_fill_color_filter/#int-aspose.cells.backgroundtype-aspose.cells.cellscolor-aspose.cells.cellscolor) | Lägger till ett fyllningsfärgsfilter.|
| [`add_icon_filter(self, field_index, icon_set_type, icon_id)`](/cells/python-net/sv/aspose.cells/autofilter/add_icon_filter/#int-aspose.cells.iconsettype-int) | Lägger till ett ikonfilter.|
| [`match_blanks(self, field_index)`](/cells/python-net/sv/aspose.cells/autofilter/match_blanks/#int) | Matcha alla tomma celler i listan.|
| [`match_non_blanks(self, field_index)`](/cells/python-net/sv/aspose.cells/autofilter/match_non_blanks/#int) | Matcha alla celler i listan som inte är tomma.|
| [`show_all(self)`](/cells/python-net/sv/aspose.cells/autofilter/show_all/#) | Visa alla rader.|



###  Exempel

```python
from aspose.cells import Workbook

# Creating a file stream containing the Excel file to be opened
# Instantiating a Workbook object
workbook = Workbook("template.xlsx")
# Accessing the first worksheet in the Excel file
worksheet = workbook.worksheets[0]
# Creating AutoFilter by giving the cells range of the heading row
worksheet.auto_filter.range = "A1:B1"
# Filtering columns with specified values
worksheet.auto_filter.filter(1, "Bananas")
# Saving the modified Excel file.
workbook.save("output.xls")

```

###  Se även
* modul [`aspose.cells`](..)
* klass [`CellArea`](/cells/python-net/sv/aspose.cells/cellarea)
