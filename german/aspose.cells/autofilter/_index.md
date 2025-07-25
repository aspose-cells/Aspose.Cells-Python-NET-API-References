---
title: AutoFilter Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 40
url: /de/aspose.cells/autofilter/
is_root: false
---
##  AutoFilter Klasse
Stellt die automatische Filterung für das angegebene Arbeitsblatt dar.



Der Typ AutoFilter macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [sorter](/cells/python-net/de/aspose.cells/autofilter/sorter) | Ruft den Datensortierer ab.|
| [range](/cells/python-net/de/aspose.cells/autofilter/range) | Stellt den Bereich dar, auf den der angegebene AutoFilter angewendet wird.|
| [show_filter_button](/cells/python-net/de/aspose.cells/autofilter/show_filter_button) | Gibt an, ob die AutoFilter-Schaltfläche für diese Spalte sichtbar ist.|
| [filter_columns](/cells/python-net/de/aspose.cells/autofilter/filter_columns) | Ruft die Auflistung der Filterspalten ab.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`get_cell_area(self)`](/cells/python-net/de/aspose.cells/autofilter/get_cell_area/#) | Ruft die [`CellArea`](/cells/python-net/de/aspose.cells/cellarea) ab, auf die dieser AutoFilter zutrifft.|
| [`get_cell_area(self, refresh_applied_range)`](/cells/python-net/de/aspose.cells/autofilter/get_cell_area/#bool) | Ruft die [`CellArea`](/cells/python-net/de/aspose.cells/cellarea) ab, auf die der angegebene AutoFilter zutrifft.|
| [`remove_filter(self, field_index, criteria)`](/cells/python-net/de/aspose.cells/autofilter/remove_filter/#int-str) | Entfernt einen Filter für eine Filterspalte.|
| [`remove_filter(self, field_index)`](/cells/python-net/de/aspose.cells/autofilter/remove_filter/#int) | Entfernen Sie den spezifischen Filter.|
| [`custom(self, field_index, operator_type1, criteria1)`](/cells/python-net/de/aspose.cells/autofilter/custom/#int-aspose.cells.filteroperatortype-any) | Filtert eine Liste mit benutzerdefinierten Kriterien.|
| [`custom(self, field_index, operator_type1, criteria1, is_and, operator_type2, criteria2)`](/cells/python-net/de/aspose.cells/autofilter/custom/#int-aspose.cells.filteroperatortype-any-bool-aspose.cells.filteroperatortype-any) | Filtert eine Liste mit benutzerdefinierten Kriterien.|
| [`refresh(self)`](/cells/python-net/de/aspose.cells/autofilter/refresh/#) | Aktualisieren Sie die automatischen Filter, um die Zeilen auszublenden oder einzublenden.|
| [`refresh(self, hide_rows)`](/cells/python-net/de/aspose.cells/autofilter/refresh/#bool) | Ruft die Indizes aller ausgeblendeten Zeilen ab.|
| [`set_range(self, row, start_column, end_column)`](/cells/python-net/de/aspose.cells/autofilter/set_range/#int-int-int) | Legt den Bereich fest, auf den der angegebene AutoFilter angewendet wird.|
| [`add_filter(self, field_index, criteria)`](/cells/python-net/de/aspose.cells/autofilter/add_filter/#int-str) | Fügt einen Filter für eine Filterspalte hinzu.|
| [`add_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second)`](/cells/python-net/de/aspose.cells/autofilter/add_date_filter/#int-aspose.cells.datetimegroupingtype-int-int-int-int-int-int) | Fügt einen Datumsfilter hinzu.|
| [`remove_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second)`](/cells/python-net/de/aspose.cells/autofilter/remove_date_filter/#int-aspose.cells.datetimegroupingtype-int-int-int-int-int-int) |Entfernt einen Datumsfilter.|
| [`filter(self, field_index, criteria)`](/cells/python-net/de/aspose.cells/autofilter/filter/#int-str) | Filtert eine Liste mit angegebenen Kriterien.|
| [`filter_top10(self, field_index, is_top, is_percent, item_count)`](/cells/python-net/de/aspose.cells/autofilter/filter_top10/#int-bool-bool-int) | Filtern Sie die Top 10-Elemente in der Liste|
| [`dynamic_filter(self, field_index, dynamic_filter_type)`](/cells/python-net/de/aspose.cells/autofilter/dynamic_filter/#int-aspose.cells.dynamicfiltertype) | Fügt einen dynamischen Filter hinzu.|
| [`add_font_color_filter(self, field_index, color)`](/cells/python-net/de/aspose.cells/autofilter/add_font_color_filter/#int-aspose.cells.cellscolor) | Fügt einen Schriftfarbfilter hinzu.|
| [`add_fill_color_filter(self, field_index, pattern, foreground_color, background_color)`](/cells/python-net/de/aspose.cells/autofilter/add_fill_color_filter/#int-aspose.cells.backgroundtype-aspose.cells.cellscolor-aspose.cells.cellscolor) | Fügt einen Füllfarbfilter hinzu.|
| [`add_icon_filter(self, field_index, icon_set_type, icon_id)`](/cells/python-net/de/aspose.cells/autofilter/add_icon_filter/#int-aspose.cells.iconsettype-int) | Fügt einen Symbolfilter hinzu.|
| [`match_blanks(self, field_index)`](/cells/python-net/de/aspose.cells/autofilter/match_blanks/#int) | Alle leeren Zellen in der Liste abgleichen.|
| [`match_non_blanks(self, field_index)`](/cells/python-net/de/aspose.cells/autofilter/match_non_blanks/#int) | Alle nicht leeren Zellen in der Liste abgleichen.|
| [`show_all(self)`](/cells/python-net/de/aspose.cells/autofilter/show_all/#) | Alle Zeilen einblenden.|



###  Beispiel

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

###  Siehe auch
* Modul [`aspose.cells`](..)
* Klasse [`CellArea`](/cells/python-net/de/aspose.cells/cellarea)
