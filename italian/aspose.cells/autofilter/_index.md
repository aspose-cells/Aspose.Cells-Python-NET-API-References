---
title: AutoFilter classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 40
url: /it/aspose.cells/autofilter/
is_root: false
---
##  AutoFilter classe
Rappresenta il filtraggio automatico per il foglio di lavoro specificato.



Il tipo AutoFilter espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [sorter](/cells/python-net/it/aspose.cells/autofilter/sorter) | Ottiene l'ordinatore dei dati.|
| [range](/cells/python-net/it/aspose.cells/autofilter/range) | Rappresenta l'intervallo a cui si applica il filtro automatico specificato.|
| [show_filter_button](/cells/python-net/it/aspose.cells/autofilter/show_filter_button) | Indica se il pulsante Filtro automatico per questa colonna è visibile.|
| [filter_columns](/cells/python-net/it/aspose.cells/autofilter/filter_columns) | Ottiene la raccolta delle colonne filtro.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`get_cell_area(self)`](/cells/python-net/it/aspose.cells/autofilter/get_cell_area/#) | Ottiene [`CellArea`](/cells/python-net/it/aspose.cells/cellarea) a cui si applica questo filtro automatico.|
| [`get_cell_area(self, refresh_applied_range)`](/cells/python-net/it/aspose.cells/autofilter/get_cell_area/#bool) | Ottiene [`CellArea`](/cells/python-net/it/aspose.cells/cellarea) a cui si applica l'AutoFilter specificato.|
| [`remove_filter(self, field_index, criteria)`](/cells/python-net/it/aspose.cells/autofilter/remove_filter/#int-str) | Rimuove un filtro per una colonna filtro.|
| [`remove_filter(self, field_index)`](/cells/python-net/it/aspose.cells/autofilter/remove_filter/#int) | Rimuovere il filtro specifico.|
| [`custom(self, field_index, operator_type1, criteria1)`](/cells/python-net/it/aspose.cells/autofilter/custom/#int-aspose.cells.filteroperatortype-any) | Filtra un elenco con criteri personalizzati.|
| [`custom(self, field_index, operator_type1, criteria1, is_and, operator_type2, criteria2)`](/cells/python-net/it/aspose.cells/autofilter/custom/#int-aspose.cells.filteroperatortype-any-bool-aspose.cells.filteroperatortype-any) | Filtra un elenco con criteri personalizzati.|
| [`refresh(self)`](/cells/python-net/it/aspose.cells/autofilter/refresh/#) | Aggiorna i filtri automatici per nascondere o visualizzare le righe.|
| [`refresh(self, hide_rows)`](/cells/python-net/it/aspose.cells/autofilter/refresh/#bool) | Ottiene tutti gli indici delle righe nascoste.|
| [`set_range(self, row, start_column, end_column)`](/cells/python-net/it/aspose.cells/autofilter/set_range/#int-int-int) | Imposta l'intervallo a cui si applica il filtro automatico specificato.|
| [`add_filter(self, field_index, criteria)`](/cells/python-net/it/aspose.cells/autofilter/add_filter/#int-str) | Aggiunge un filtro per una colonna filtro.|
| [`add_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second)`](/cells/python-net/it/aspose.cells/autofilter/add_date_filter/#int-aspose.cells.datetimegroupingtype-int-int-int-int-int-int) | Aggiunge un filtro data.|
| [`remove_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second)`](/cells/python-net/it/aspose.cells/autofilter/remove_date_filter/#int-aspose.cells.datetimegroupingtype-int-int-int-int-int-int) |Rimuove un filtro data.|
| [`filter(self, field_index, criteria)`](/cells/python-net/it/aspose.cells/autofilter/filter/#int-str) | Filtra un elenco in base a criteri specificati.|
| [`filter_top10(self, field_index, is_top, is_percent, item_count)`](/cells/python-net/it/aspose.cells/autofilter/filter_top10/#int-bool-bool-int) | Filtra i primi 10 elementi nell'elenco|
| [`dynamic_filter(self, field_index, dynamic_filter_type)`](/cells/python-net/it/aspose.cells/autofilter/dynamic_filter/#int-aspose.cells.dynamicfiltertype) | Aggiunge un filtro dinamico.|
| [`add_font_color_filter(self, field_index, color)`](/cells/python-net/it/aspose.cells/autofilter/add_font_color_filter/#int-aspose.cells.cellscolor) | Aggiunge un filtro colore del carattere.|
| [`add_fill_color_filter(self, field_index, pattern, foreground_color, background_color)`](/cells/python-net/it/aspose.cells/autofilter/add_fill_color_filter/#int-aspose.cells.backgroundtype-aspose.cells.cellscolor-aspose.cells.cellscolor) | Aggiunge un filtro colore di riempimento.|
| [`add_icon_filter(self, field_index, icon_set_type, icon_id)`](/cells/python-net/it/aspose.cells/autofilter/add_icon_filter/#int-aspose.cells.iconsettype-int) | Aggiunge un filtro icona.|
| [`match_blanks(self, field_index)`](/cells/python-net/it/aspose.cells/autofilter/match_blanks/#int) | Abbina tutte le celle vuote nell'elenco.|
| [`match_non_blanks(self, field_index)`](/cells/python-net/it/aspose.cells/autofilter/match_non_blanks/#int) | Abbina tutte le celle non vuote nell'elenco.|
| [`show_all(self)`](/cells/python-net/it/aspose.cells/autofilter/show_all/#) | Visualizza tutte le righe.|



###  Esempio

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

###  Guarda anche
* modulo [`aspose.cells`](..)
* classe [`CellArea`](/cells/python-net/it/aspose.cells/cellarea)
