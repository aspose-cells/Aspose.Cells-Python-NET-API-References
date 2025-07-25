---
title: Cells klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 160
url: /sv/aspose.cells/cells/
is_root: false
---
##  Cells klass
Inkapslar en samling cellrelevanta objekt, såsom [`Cell`](/cells/python-net/sv/aspose.cells/cell), [`Row`](/cells/python-net/sv/aspose.cells/row), ...etc.



Typen Cells avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [ods_cell_fields](/cells/python-net/sv/aspose.cells/cells/ods_cell_fields) | Hämtar listan över fält för ods.|
| [count](/cells/python-net/sv/aspose.cells/cells/count) | Hämtar det totala antalet instansierade Cell objekt.|
| [count_large](/cells/python-net/sv/aspose.cells/cells/count_large) | Hämtar det totala antalet instansierade Cell objekt.|
| [rows](/cells/python-net/sv/aspose.cells/cells/rows) | Hämtar samlingen av [`Row`](/cells/python-net/sv/aspose.cells/row)-objekt som representerar de enskilda raderna i detta kalkylblad.|
| [merged_cells](/cells/python-net/sv/aspose.cells/cells/merged_cells) | Hämtar samlingen av sammanslagna celler.|
| [multi_thread_reading](/cells/python-net/sv/aspose.cells/cells/multi_thread_reading) | Hämtar eller anger om cellernas datamodell ska stödja flertrådsläsning.<br/> Standardvärdet för den här egenskapen är falskt.|
| [memory_setting](/cells/python-net/sv/aspose.cells/cells/memory_setting) | Hämtar eller ställer in minnesanvändningsalternativet för dessa celler.|
| [style](/cells/python-net/sv/aspose.cells/cells/style) | Hämtar och anger standardformatet för kalkylbladet.|
| [is_default_column_hidden](/cells/python-net/sv/aspose.cells/cells/is_default_column_hidden) |  |
| [standard_width_inch](/cells/python-net/sv/aspose.cells/cells/standard_width_inch) | Hämtar eller anger standardkolumnbredden i kalkylbladet, i enheten tum.|
| [standard_width_pixels](/cells/python-net/sv/aspose.cells/cells/standard_width_pixels) |Hämtar eller anger standardkolumnbredden i kalkylbladet, i pixlar.|
| [standard_width](/cells/python-net/sv/aspose.cells/cells/standard_width) | Hämtar eller anger standardkolumnbredden i kalkylbladet, i teckenenhet.|
| [standard_height](/cells/python-net/sv/aspose.cells/cells/standard_height) | Hämtar eller ställer in standardradhöjden i detta kalkylblad, i enheten punkter.|
| [standard_height_pixels](/cells/python-net/sv/aspose.cells/cells/standard_height_pixels) | Hämtar eller anger standardradhöjden i detta kalkylblad, i pixlar.|
| [standard_height_inch](/cells/python-net/sv/aspose.cells/cells/standard_height_inch) | Hämtar eller anger standardradhöjden i detta kalkylblad, i enheten tum.|
| [preserve_string](/cells/python-net/sv/aspose.cells/cells/preserve_string) | Hämtar eller anger ett värde som anger om alla kalkylbladsvärden bevaras som strängar.<br/> Standardvärdet är falskt.|
| [min_row](/cells/python-net/sv/aspose.cells/cells/min_row) | Minsta radindex för cell som innehåller data eller format.|
| [max_row](/cells/python-net/sv/aspose.cells/cells/max_row) | Maximalt radindex för cell som innehåller data eller format.|
| [min_column](/cells/python-net/sv/aspose.cells/cells/min_column) | Minsta kolumnindex för de celler som har instansierats i samlingen (inkluderar inte kolumnen<br/> där stilen är definierad för hela kolumnen men ingen cell har instansierats i den).|
| [max_column](/cells/python-net/sv/aspose.cells/cells/max_column) | Maximalt kolumnindex för de celler som har instansierats i samlingen (inkluderar inte kolumnen<br/> där stilen är definierad för hela kolumnen men ingen cell har instansierats i den).|
| [min_data_row](/cells/python-net/sv/aspose.cells/cells/min_data_row) |Minsta radindex för cell som innehåller data.|
| [max_data_row](/cells/python-net/sv/aspose.cells/cells/max_data_row) | Maximalt radindex för cell som innehåller data.|
| [min_data_column](/cells/python-net/sv/aspose.cells/cells/min_data_column) | Minsta kolumnindex för cell som innehåller data.|
| [max_data_column](/cells/python-net/sv/aspose.cells/cells/max_data_column) | Maximalt kolumnindex för cell som innehåller data.|
| [is_default_row_height_matched](/cells/python-net/sv/aspose.cells/cells/is_default_row_height_matched) | Indikerar att radhöjden och standardteckensnittshöjden matchar|
| [is_default_row_hidden](/cells/python-net/sv/aspose.cells/cells/is_default_row_hidden) | Anger om raden är dold som standard.|
| [columns](/cells/python-net/sv/aspose.cells/cells/columns) | Hämtar samlingen av [`Column`](/cells/python-net/sv/aspose.cells/column)-objekt som representerar de enskilda kolumnerna i detta kalkylblad.|
| [ranges](/cells/python-net/sv/aspose.cells/cells/ranges) | Hämtar samlingen av [`Range`](/cells/python-net/sv/aspose.cells/range) objekt som skapades vid körning.|
| [last_cell](/cells/python-net/sv/aspose.cells/cells/last_cell) | Hämtar den sista cellen i detta kalkylblad.|
| [max_display_range](/cells/python-net/sv/aspose.cells/cells/max_display_range) | Hämtar det maximala intervallet som inkluderar data, sammanfogade celler och former.|
| [first_cell](/cells/python-net/sv/aspose.cells/cells/first_cell) | Hämtar den första cellen i detta kalkylblad.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`create_range(self, upper_left_cell, lower_right_cell)`](/cells/python-net/sv/aspose.cells/cells/create_range/#str-str) | Skapar ett [`Range`](/cells/python-net/sv/aspose.cells/range)-objekt från ett cellområde.|
| [`create_range(self, first_row, first_column, total_rows, total_columns)`](/cells/python-net/sv/aspose.cells/cells/create_range/#int-int-int-int) | Skapar ett [`Range`](/cells/python-net/sv/aspose.cells/range)-objekt från ett cellområde.|
| [`create_range(self, address)`](/cells/python-net/sv/aspose.cells/cells/create_range/#str) | Skapar ett [`Range`](/cells/python-net/sv/aspose.cells/range)-objekt från en adress i intervallet.|
| [`create_range(self, first_index, number, is_vertical)`](/cells/python-net/sv/aspose.cells/cells/create_range/#int-int-bool) | Skapar ett [`Range`](/cells/python-net/sv/aspose.cells/range)-objekt från rader av celler eller kolumner av celler.|
| [`get(self, row, column)`](/cells/python-net/sv/aspose.cells/cells/get/#int-int) | Lägg till API for Python Via .Net. eftersom detta [int rad, int kolumn] inte stöds.|
| [`get(self, cell_name)`](/cells/python-net/sv/aspose.cells/cells/get/#str) |Lägg till API for Python Via .Net. eftersom detta [sträng cellnamn] inte stöds.|
| [`import_object_array(self, obj_array, first_row, first_column, is_vertical)`](/cells/python-net/sv/aspose.cells/cells/import_object_array/#list-int-int-bool) | Importerar en datamatris till ett kalkylblad.|
| [`import_object_array(self, obj_array, first_row, first_column, is_vertical, skip)`](/cells/python-net/sv/aspose.cells/cells/import_object_array/#list-int-int-bool-int) | Importerar en datamatris till ett kalkylblad.|
| [`import_array(self, string_array, first_row, first_column, is_vertical)`](/cells/python-net/sv/aspose.cells/cells/import_array/#list-int-int-bool) | Importerar en strängarray till ett kalkylblad.|
| [`import_array(self, int_array, first_row, first_column, is_vertical)`](/cells/python-net/sv/aspose.cells/cells/import_array/#list-int-int-bool) | Importerar en array med heltal till ett kalkylblad.|
| [`import_array(self, double_array, first_row, first_column, is_vertical)`](/cells/python-net/sv/aspose.cells/cells/import_array/#list-int-int-bool) | Importerar en array av double till ett kalkylblad.|
| [`import_csv(self, file_name, splitter, convert_numeric_data, first_row, first_column)`](/cells/python-net/sv/aspose.cells/cells/import_csv/#str-str-bool-int-int) | Importera en CSV-fil till cellerna.|
| [`import_csv(self, stream, splitter, convert_numeric_data, first_row, first_column)`](/cells/python-net/sv/aspose.cells/cells/import_csv/#io.rawiobase-str-bool-int-int) | Importera en CSV-fil till cellerna.|
| [`import_csv(self, file_name, options, first_row, first_column)`](/cells/python-net/sv/aspose.cells/cells/import_csv/#str-aspose.cells.txtloadoptions-int-int) | Importera en CSV-fil till cellerna.|
| [`import_csv(self, stream, options, first_row, first_column)`](/cells/python-net/sv/aspose.cells/cells/import_csv/#io.rawiobase-aspose.cells.txtloadoptions-int-int) | Importera en CSV-fil till cellerna.|
| [`merge(self, first_row, first_column, total_rows, total_columns)`](/cells/python-net/sv/aspose.cells/cells/merge/#int-int-int-int) | Sammanfogar ett angivet cellområde till en enda cell.|
| [`merge(self, first_row, first_column, total_rows, total_columns, merge_conflict)`](/cells/python-net/sv/aspose.cells/cells/merge/#int-int-int-int-bool) | Sammanfogar ett angivet cellområde till en enda cell.|
| [`merge(self, first_row, first_column, total_rows, total_columns, check_conflict, merge_conflict)`](/cells/python-net/sv/aspose.cells/cells/merge/#int-int-int-int-bool-bool) | Sammanfogar ett angivet cellområde till en enda cell.|
| [`get_row_height(self, row, is_original, unit_type)`](/cells/python-net/sv/aspose.cells/cells/get_row_height/#int-bool-aspose.cells.cellsunittype) | Hämtar radhöjden.|
| [`get_row_height(self, row)`](/cells/python-net/sv/aspose.cells/cells/get_row_height/#int) | Hämtar höjden på en specificerad rad, i enhet punkter.|
| [`get_column_width(self, column, is_original, unit_type)`](/cells/python-net/sv/aspose.cells/cells/get_column_width/#int-bool-aspose.cells.cellsunittype) | Hämtar kolumnbredden.|
| [`get_column_width(self, column)`](/cells/python-net/sv/aspose.cells/cells/get_column_width/#int) | Hämtar bredden (i teckenenhet) på den angivna kolumnen i normalvyn|
| [`get_column_width_pixel(self, column)`](/cells/python-net/sv/aspose.cells/cells/get_column_width_pixel/#int) | Hämtar bredden på den angivna kolumnen i normalvyn, i pixlar.|
| [`get_column_width_pixel(self, column, original)`](/cells/python-net/sv/aspose.cells/cells/get_column_width_pixel/#int-bool) | Hämtar bredden på den angivna kolumnen i normalvyn, i pixlar.|
| [`copy_columns(self, source_cells0, source_column_index, destination_column_index, column_number, paste_options)`](/cells/python-net/sv/aspose.cells/cells/copy_columns/#aspose.cells.cells-int-int-int-aspose.cells.pasteoptions) | Kopierar data och format för en hel kolumn.|
| [`copy_columns(self, source_cells0, source_column_index, destination_column_index, column_number)`](/cells/python-net/sv/aspose.cells/cells/copy_columns/#aspose.cells.cells-int-int-int) | Kopierar data och format för en hel kolumn.|
| [`copy_columns(self, source_cells, source_column_index, source_total_columns, destination_column_index, destination_total_columns)`](/cells/python-net/sv/aspose.cells/cells/copy_columns/#aspose.cells.cells-int-int-int-int) | Kopierar data och format för hela kolumnerna.|
| [`copy_rows(self, source_cells, source_row_index, destination_row_index, row_number)`](/cells/python-net/sv/aspose.cells/cells/copy_rows/#aspose.cells.cells-int-int-int) | Kopierar data och format för vissa hela rader.|
| [`copy_rows(self, source_cells0, source_row_index, destination_row_index, row_number, copy_options)`](/cells/python-net/sv/aspose.cells/cells/copy_rows/#aspose.cells.cells-int-int-int-aspose.cells.copyoptions) | Kopierar data och format för vissa hela rader.|
| [`copy_rows(self, source_cells0, source_row_index, destination_row_index, row_number, copy_options, paste_options)`](/cells/python-net/sv/aspose.cells/cells/copy_rows/#aspose.cells.cells-int-int-int-aspose.cells.copyoptions-aspose.cells.pasteoptions) | Kopierar data och format för vissa hela rader.|
| [`group_columns(self, first_index, last_index)`](/cells/python-net/sv/aspose.cells/cells/group_columns/#int-int) | Gruppera kolumner.|
| [`group_columns(self, first_index, last_index, is_hidden)`](/cells/python-net/sv/aspose.cells/cells/group_columns/#int-int-bool) | Gruppera kolumner.|
| [`ungroup_rows(self, first_index, last_index, is_all)`](/cells/python-net/sv/aspose.cells/cells/ungroup_rows/#int-int-bool) | Avgrupperar rader.|
| [`ungroup_rows(self, first_index, last_index)`](/cells/python-net/sv/aspose.cells/cells/ungroup_rows/#int-int) | Avgrupperar rader.|
| [`group_rows(self, first_index, last_index, is_hidden)`](/cells/python-net/sv/aspose.cells/cells/group_rows/#int-int-bool) | Grupperar rader.|
| [`group_rows(self, first_index, last_index)`](/cells/python-net/sv/aspose.cells/cells/group_rows/#int-int) | Grupperar rader.|
| [`delete_column(self, column_index, update_reference)`](/cells/python-net/sv/aspose.cells/cells/delete_column/#int-bool) | Tar bort en kolumn.|
| [`delete_column(self, column_index)`](/cells/python-net/sv/aspose.cells/cells/delete_column/#int) | Tar bort en kolumn.|
| [`delete_columns(self, column_index, total_columns, update_reference)`](/cells/python-net/sv/aspose.cells/cells/delete_columns/#int-int-bool) | Tar bort flera kolumner.|
| [`delete_columns(self, column_index, total_columns, options)`](/cells/python-net/sv/aspose.cells/cells/delete_columns/#int-int-aspose.cells.deleteoptions) | Tar bort flera kolumner.|
| [`delete_row(self, row_index)`](/cells/python-net/sv/aspose.cells/cells/delete_row/#int) | Tar bort en rad.|
| [`delete_row(self, row_index, update_reference)`](/cells/python-net/sv/aspose.cells/cells/delete_row/#int-bool) | Tar bort en rad.|
| [`delete_rows(self, row_index, total_rows)`](/cells/python-net/sv/aspose.cells/cells/delete_rows/#int-int) |Tar bort flera rader.|
| [`delete_rows(self, row_index, total_rows, update_reference)`](/cells/python-net/sv/aspose.cells/cells/delete_rows/#int-int-bool) | Tar bort flera rader i kalkylbladet.|
| [`delete_rows(self, row_index, total_rows, options)`](/cells/python-net/sv/aspose.cells/cells/delete_rows/#int-int-aspose.cells.deleteoptions) | Tar bort flera rader i kalkylbladet.|
| [`delete_blank_columns(self)`](/cells/python-net/sv/aspose.cells/cells/delete_blank_columns/#) | Ta bort alla tomma kolumner som inte innehåller några data.|
| [`delete_blank_columns(self, options)`](/cells/python-net/sv/aspose.cells/cells/delete_blank_columns/#aspose.cells.deleteoptions) | Ta bort alla tomma kolumner som inte innehåller några data.|
| [`delete_blank_rows(self)`](/cells/python-net/sv/aspose.cells/cells/delete_blank_rows/#) | Ta bort alla tomma rader som inte innehåller data eller andra objekt.|
| [`delete_blank_rows(self, options)`](/cells/python-net/sv/aspose.cells/cells/delete_blank_rows/#aspose.cells.deleteoptions) | Ta bort alla tomma rader som inte innehåller data eller några specialobjekt, såsom synliga kommentarer eller pivottabeller.|
| [`insert_columns(self, column_index, total_columns)`](/cells/python-net/sv/aspose.cells/cells/insert_columns/#int-int) | Infogar några kolumner i kalkylbladet.|
| [`insert_columns(self, column_index, total_columns, update_reference)`](/cells/python-net/sv/aspose.cells/cells/insert_columns/#int-int-bool) | Infogar några kolumner i kalkylbladet.|
| [`insert_columns(self, column_index, total_columns, options)`](/cells/python-net/sv/aspose.cells/cells/insert_columns/#int-int-aspose.cells.insertoptions) | Infogar några kolumner i kalkylbladet.|
| [`insert_column(self, column_index, update_reference)`](/cells/python-net/sv/aspose.cells/cells/insert_column/#int-bool) | Infogar en ny kolumn i kalkylbladet.|
| [`insert_column(self, column_index)`](/cells/python-net/sv/aspose.cells/cells/insert_column/#int) | Infogar en ny kolumn i kalkylbladet.|
| [`insert_rows(self, row_index, total_rows, update_reference)`](/cells/python-net/sv/aspose.cells/cells/insert_rows/#int-int-bool) | Infogar flera rader i kalkylbladet.|
| [`insert_rows(self, row_index, total_rows, options)`](/cells/python-net/sv/aspose.cells/cells/insert_rows/#int-int-aspose.cells.insertoptions) | Infogar flera rader i kalkylbladet.|
| [`insert_rows(self, row_index, total_rows)`](/cells/python-net/sv/aspose.cells/cells/insert_rows/#int-int) | Infogar flera rader i kalkylbladet.|
| [`clear_range(self, range)`](/cells/python-net/sv/aspose.cells/cells/clear_range/#aspose.cells.cellarea) | Rensar innehåll och formatering för ett område.|
| [`clear_range(self, start_row, start_column, end_row, end_column)`](/cells/python-net/sv/aspose.cells/cells/clear_range/#int-int-int-int) | Rensar innehåll och formatering för ett område.|
| [`clear_contents(self, range)`](/cells/python-net/sv/aspose.cells/cells/clear_contents/#aspose.cells.cellarea) | Rensar innehållet i ett intervall.|
| [`clear_contents(self, start_row, start_column, end_row, end_column)`](/cells/python-net/sv/aspose.cells/cells/clear_contents/#int-int-int-int) | Rensar innehållet i ett intervall.|
| [`clear_formats(self, range)`](/cells/python-net/sv/aspose.cells/cells/clear_formats/#aspose.cells.cellarea) | Rensar formateringen av ett område.|
| [`clear_formats(self, start_row, start_column, end_row, end_column)`](/cells/python-net/sv/aspose.cells/cells/clear_formats/#int-int-int-int) | Rensar formateringen av ett område.|
| [`find(self, what, previous_cell)`](/cells/python-net/sv/aspose.cells/cells/find/#any-aspose.cells.cell) | Hittar cellen som innehåller indataobjektet.|
| [`find(self, what, previous_cell, find_options)`](/cells/python-net/sv/aspose.cells/cells/find/#any-aspose.cells.cell-aspose.cells.findoptions) | Hittar cellen som innehåller indataobjektet.|
| [`end_cell_in_row(self, row_index)`](/cells/python-net/sv/aspose.cells/cells/end_cell_in_row/#int) | Hämtar den sista cellen i den här raden.|
| [`end_cell_in_row(self, start_row, end_row, start_column, end_column)`](/cells/python-net/sv/aspose.cells/cells/end_cell_in_row/#int-int-int-int) | Hämtar den sista cellen med maximalt radindex i detta intervall.|
| [`end_cell_in_column(self, column_index)`](/cells/python-net/sv/aspose.cells/cells/end_cell_in_column/#int) | Hämtar den sista cellen i den här kolumnen.|
| [`end_cell_in_column(self, start_row, end_row, start_column, end_column)`](/cells/python-net/sv/aspose.cells/cells/end_cell_in_column/#int-int-int-int) | Hämtar den sista cellen med maximalt kolumnindex i detta intervall.|
| [`insert_range(self, area, shift_number, shift_type, update_reference)`](/cells/python-net/sv/aspose.cells/cells/insert_range/#aspose.cells.cellarea-int-aspose.cells.shifttype-bool) | Infogar ett cellområde och flyttar celler enligt skiftalternativet.|
| [`insert_range(self, area, shift_type)`](/cells/python-net/sv/aspose.cells/cells/insert_range/#aspose.cells.cellarea-aspose.cells.shifttype) | Infogar ett cellområde och flyttar celler enligt skiftalternativet.|
| [`insert_range(self, area, shift_number, shift_type)`](/cells/python-net/sv/aspose.cells/cells/insert_range/#aspose.cells.cellarea-int-aspose.cells.shifttype) | Infogar ett cellområde och flyttar celler enligt skiftalternativet.|
| [`subtotal(self, ca, group_by, function, total_list)`](/cells/python-net/sv/aspose.cells/cells/subtotal/#aspose.cells.cellarea-int-aspose.cells.consolidationfunction-list) | Skapar delsummor för intervallet.|
| [`subtotal(self, ca, group_by, function, total_list, replace, page_breaks, summary_below_data)`](/cells/python-net/sv/aspose.cells/cells/subtotal/#aspose.cells.cellarea-int-aspose.cells.consolidationfunction-list-bool-bool-bool) | Skapar delsummor för intervallet.|
| [`remove_duplicates(self)`](/cells/python-net/sv/aspose.cells/cells/remove_duplicates/#) |Tar bort dubbletter av rader i arket.|
| [`remove_duplicates(self, start_row, start_column, end_row, end_column)`](/cells/python-net/sv/aspose.cells/cells/remove_duplicates/#int-int-int-int) | Tar bort dubbletter i intervallet.|
| [`remove_duplicates(self, start_row, start_column, end_row, end_column, has_headers, column_offsets)`](/cells/python-net/sv/aspose.cells/cells/remove_duplicates/#int-int-int-int-bool-list) | Tar bort dubbletter av data i intervallet.|
| [`get_cell_display_style(self, row, column)`](/cells/python-net/sv/aspose.cells/cells/get_cell_display_style/#int-int) | Hämta visningsstilen för en given cell.|
| [`get_cell_display_style(self, row, column, adjacent_borders)`](/cells/python-net/sv/aspose.cells/cells/get_cell_display_style/#int-int-aspose.cells.bordertype) | Hämta visningsstilen för en given cell.|
| [`get_row_enumerator(self)`](/cells/python-net/sv/aspose.cells/cells/get_row_enumerator/#) | Hämtar raduppräknaren.|
| [`get_merged_areas(self)`](/cells/python-net/sv/aspose.cells/cells/get_merged_areas/#) | Hämtar alla sammanslagna celler.|
| [`get_cell(self, row, column)`](/cells/python-net/sv/aspose.cells/cells/get_cell/#int-int) | Hämtar elementet [`Cell`](/cells/python-net/sv/aspose.cells/cell) eller null vid det angivna cellradindexet och kolumnindexet.|
| [`get_row(self, row)`](/cells/python-net/sv/aspose.cells/cells/get_row/#int) | Hämtar elementet [`Row`](/cells/python-net/sv/aspose.cells/row) vid det angivna cellradsindexet.|
| [`check_cell(self, row, column)`](/cells/python-net/sv/aspose.cells/cells/check_cell/#int-int) | Hämtar elementet [`Cell`](/cells/python-net/sv/aspose.cells/cell) eller null vid det angivna cellradindexet och kolumnindexet.|
| [`check_row(self, row)`](/cells/python-net/sv/aspose.cells/cells/check_row/#int) | Hämtar elementet [`Row`](/cells/python-net/sv/aspose.cells/row) eller null-värdet vid det angivna cellradindexet.|
| [`check_column(self, column_index)`](/cells/python-net/sv/aspose.cells/cells/check_column/#int) | Hämtar elementet [`Column`](/cells/python-net/sv/aspose.cells/column) eller null-värdet vid det angivna kolumnindexet.|
| [`is_row_hidden(self, row_index)`](/cells/python-net/sv/aspose.cells/cells/is_row_hidden/#int) | Kontrollerar om en rad vid ett givet index är dold.|
| [`is_column_hidden(self, column_index)`](/cells/python-net/sv/aspose.cells/cells/is_column_hidden/#int) | Kontrollerar om en kolumn vid ett givet index är dold.|
| [`add_range(self, range_object)`](/cells/python-net/sv/aspose.cells/cells/add_range/#aspose.cells.range) | Lägger till en referens till ett områdesobjekt i celler|
| [`clear(self)`](/cells/python-net/sv/aspose.cells/cells/clear/#) | Rensar all data i kalkylbladet.|
| [`import_array_list(self, array_list, first_row, first_column, is_vertical)`](/cells/python-net/sv/aspose.cells/cells/import_array_list/#list-int-int-bool) | Importerar en arraylista med data till ett kalkylblad.|
| [`import_formula_array(self, string_array, first_row, first_column, is_vertical)`](/cells/python-net/sv/aspose.cells/cells/import_formula_array/#list-int-int-bool) | Importerar en array med formeln till ett kalkylblad.|
| [`text_to_columns(self, row, column, total_rows, options)`](/cells/python-net/sv/aspose.cells/cells/text_to_columns/#int-int-int-aspose.cells.txtloadoptions) | Delar upp innehållet i en angiven kolumn i flera kolumner.|
| [`un_merge(self, first_row, first_column, total_rows, total_columns)`](/cells/python-net/sv/aspose.cells/cells/un_merge/#int-int-int-int) | Avlägsnar sammanslagningen av ett angivet område av sammanslagna celler.|
| [`clear_merged_cells(self)`](/cells/python-net/sv/aspose.cells/cells/clear_merged_cells/#) | Rensar alla sammanslagna områden.|
| [`hide_row(self, row)`](/cells/python-net/sv/aspose.cells/cells/hide_row/#int) |Döljer en rad.|
| [`unhide_row(self, row, height)`](/cells/python-net/sv/aspose.cells/cells/unhide_row/#int-float) | Visar en rad.|
| [`hide_rows(self, row, total_rows)`](/cells/python-net/sv/aspose.cells/cells/hide_rows/#int-int) | Döljer flera rader.|
| [`unhide_rows(self, row, total_rows, height)`](/cells/python-net/sv/aspose.cells/cells/unhide_rows/#int-int-float) | Visar de dolda raderna.|
| [`set_row_height_pixel(self, row, pixels)`](/cells/python-net/sv/aspose.cells/cells/set_row_height_pixel/#int-int) | Ställer in radhöjden i pixlar.|
| [`set_row_height_inch(self, row, inches)`](/cells/python-net/sv/aspose.cells/cells/set_row_height_inch/#int-float) | Ställer in radhöjden i tum.|
| [`set_row_height(self, row, height)`](/cells/python-net/sv/aspose.cells/cells/set_row_height/#int-float) | Anger höjden på den angivna raden.|
| [`get_row_original_height_point(self, row)`](/cells/python-net/sv/aspose.cells/cells/get_row_original_height_point/#int) | Hämtar den ursprungliga radens höjd i punktenhet om raden är dold|
| [`get_column_original_width_point(self, column)`](/cells/python-net/sv/aspose.cells/cells/get_column_original_width_point/#int) | Hämtar den ursprungliga kolumnens höjd i punktenhet om kolumnen är dold|
| [`hide_column(self, column)`](/cells/python-net/sv/aspose.cells/cells/hide_column/#int) | Döljer en kolumn.|
| [`unhide_column(self, column, width)`](/cells/python-net/sv/aspose.cells/cells/unhide_column/#int-float) | Visar en kolumn|
| [`hide_columns(self, column, total_columns)`](/cells/python-net/sv/aspose.cells/cells/hide_columns/#int-int) | Dölj flera kolumner.|
| [`unhide_columns(self, column, total_columns, width)`](/cells/python-net/sv/aspose.cells/cells/unhide_columns/#int-int-float) | Visa flera kolumner.|
| [`get_view_row_height(self, row)`](/cells/python-net/sv/aspose.cells/cells/get_view_row_height/#int) | Hämtar höjden på en angiven rad.|
| [`get_row_height_inch(self, row)`](/cells/python-net/sv/aspose.cells/cells/get_row_height_inch/#int) | Hämtar höjden på en angiven rad i enheten tum.|
| [`get_view_row_height_inch(self, row)`](/cells/python-net/sv/aspose.cells/cells/get_view_row_height_inch/#int) | Hämtar höjden på en angiven rad i enheten tum.|
| [`get_row_height_pixel(self, row)`](/cells/python-net/sv/aspose.cells/cells/get_row_height_pixel/#int) | Hämtar höjden på en specificerad rad i pixelenhet.|
| [`set_column_width_pixel(self, column, pixels)`](/cells/python-net/sv/aspose.cells/cells/set_column_width_pixel/#int-int) | Ställer in kolumnbredden i pixlar i normalvyn.|
| [`set_column_width_inch(self, column, inches)`](/cells/python-net/sv/aspose.cells/cells/set_column_width_inch/#int-float) | Ställer in kolumnbredden i tum i normalvyn.|
| [`set_column_width(self, column, width)`](/cells/python-net/sv/aspose.cells/cells/set_column_width/#int-float) | Anger bredden på den angivna kolumnen i normalvyn.|
| [`get_column_width_inch(self, column)`](/cells/python-net/sv/aspose.cells/cells/get_column_width_inch/#int) | Hämtar bredden på den angivna kolumnen i normalvyn, i enheter av tum.|
| [`get_view_column_width_pixel(self, column)`](/cells/python-net/sv/aspose.cells/cells/get_view_column_width_pixel/#int) | Hämta bredden i olika vytyper.|
| [`set_view_column_width_pixel(self, column, pixels)`](/cells/python-net/sv/aspose.cells/cells/set_view_column_width_pixel/#int-int) |Ställer in kolumnens bredd i olika vyer.|
| [`get_last_data_row(self, column)`](/cells/python-net/sv/aspose.cells/cells/get_last_data_row/#int) | Hämtar den sista radindexen för en cell som innehåller data i den angivna kolumnen.|
| [`get_first_data_row(self, column)`](/cells/python-net/sv/aspose.cells/cells/get_first_data_row/#int) | Hämtar den första radens index för en cell som innehåller data i den angivna kolumnen.|
| [`apply_column_style(self, column, style, flag)`](/cells/python-net/sv/aspose.cells/cells/apply_column_style/#int-aspose.cells.style-aspose.cells.styleflag) | Tillämpar format för en hel kolumn.|
| [`apply_row_style(self, row, style, flag)`](/cells/python-net/sv/aspose.cells/cells/apply_row_style/#int-aspose.cells.style-aspose.cells.styleflag) | Tillämpar format för en hel rad.|
| [`apply_style(self, style, flag)`](/cells/python-net/sv/aspose.cells/cells/apply_style/#aspose.cells.style-aspose.cells.styleflag) | Tillämpar format för ett helt kalkylblad.|
| [`copy_column(self, source_cells, source_column_index, destination_column_index)`](/cells/python-net/sv/aspose.cells/cells/copy_column/#aspose.cells.cells-int-int) | Kopierar data och format för en hel kolumn.|
| [`copy_row(self, source_cells, source_row_index, destination_row_index)`](/cells/python-net/sv/aspose.cells/cells/copy_row/#aspose.cells.cells-int-int) | Kopierar data och format för en hel rad.|
| [`get_grouped_row_outline_level(self, row_index)`](/cells/python-net/sv/aspose.cells/cells/get_grouped_row_outline_level/#int) | Hämtar dispositionsnivån (nollbaserad) för raden.|
| [`get_grouped_column_outline_level(self, column_index)`](/cells/python-net/sv/aspose.cells/cells/get_grouped_column_outline_level/#int) | Hämtar dispositionsnivån (nollbaserad) för kolumnen.|
| [`get_max_grouped_column_outline_level(self)`](/cells/python-net/sv/aspose.cells/cells/get_max_grouped_column_outline_level/#) | Hämtar maximal nivå för grupperad kolumndisposition (nollbaserad).|
| [`get_max_grouped_row_outline_level(self)`](/cells/python-net/sv/aspose.cells/cells/get_max_grouped_row_outline_level/#) | Hämtar maximal nivå för grupperade raddispositioner (nollbaserad).|
| [`show_group_detail(self, is_vertical, index)`](/cells/python-net/sv/aspose.cells/cells/show_group_detail/#bool-int) | Expanderar de grupperade raderna/kolumnerna.|
| [`hide_group_detail(self, is_vertical, index)`](/cells/python-net/sv/aspose.cells/cells/hide_group_detail/#bool-int) | Minimerar de grupperade raderna/kolumnerna.|
| [`ungroup_columns(self, first_index, last_index)`](/cells/python-net/sv/aspose.cells/cells/ungroup_columns/#int-int) | Avgrupperar kolumner.|
| [`is_deleting_range_enabled(self, start_row, start_column, total_rows, total_columns)`](/cells/python-net/sv/aspose.cells/cells/is_deleting_range_enabled/#int-int-int-int) | Kontrollera om intervallet kan tas bort.|
| [`is_blank_column(self, column_index)`](/cells/python-net/sv/aspose.cells/cells/is_blank_column/#int) | Kontrollerar om den givna kolumnen är tom (innehåller inga data).|
| [`insert_row(self, row_index)`](/cells/python-net/sv/aspose.cells/cells/insert_row/#int) | Infogar en ny rad i kalkylbladet.|
| [`link_to_xml_map(self, map_name, row, column, path)`](/cells/python-net/sv/aspose.cells/cells/link_to_xml_map/#str-int-int-str) | Länk till en xml-karta.|
| [`move_range(self, source_area, dest_row, dest_column)`](/cells/python-net/sv/aspose.cells/cells/move_range/#aspose.cells.cellarea-int-int) | Flyttar intervallet.|
| [`insert_cut_cells(self, cut_range, row, column, shift_type)`](/cells/python-net/sv/aspose.cells/cells/insert_cut_cells/#aspose.cells.range-int-int-aspose.cells.shifttype) | Infoga klippintervall.|
| [`delete_range(self, start_row, start_column, end_row, end_column, shift_type)`](/cells/python-net/sv/aspose.cells/cells/delete_range/#int-int-int-int-aspose.cells.shifttype) |Tar bort ett cellområde och flyttar celler enligt skiftalternativet.|
| [`retrieve_subtotal_setting(self, ca)`](/cells/python-net/sv/aspose.cells/cells/retrieve_subtotal_setting/#aspose.cells.cellarea) | Hämtar delsummor för intervallet.|
| [`remove_formulas(self)`](/cells/python-net/sv/aspose.cells/cells/remove_formulas/#) | Tar bort alla formler och ersätter med formelns värde.|
| [`convert_string_to_numeric_value(self)`](/cells/python-net/sv/aspose.cells/cells/convert_string_to_numeric_value/#) | Konverterar all strängdata i kalkylbladet till numeriska värden om möjligt.|
| [`get_dependents(self, is_all, row, column)`](/cells/python-net/sv/aspose.cells/cells/get_dependents/#bool-int-int) | Hämta alla celler som refererar till den specifika cellen.|
| [`get_dependents_in_calculation(self, row, column, recursive)`](/cells/python-net/sv/aspose.cells/cells/get_dependents_in_calculation/#int-int-bool) | Hämtar alla celler vars beräknade resultat beror på en specifik cell.|
| [`get_cells_with_place_in_cell_picture(self)`](/cells/python-net/sv/aspose.cells/cells/get_cells_with_place_in_cell_picture/#) | Hämtar alla celler som innehåller inbäddade bilder.|
| [`get_cell_style(self, row, column)`](/cells/python-net/sv/aspose.cells/cells/get_cell_style/#int-int) | Hämta stilen för den givna cellen.|



###  Anmärkningar



###  Se även
* modul [`aspose.cells`](..)
* klass [`Cell`](/cells/python-net/sv/aspose.cells/cell)
* klass [`Column`](/cells/python-net/sv/aspose.cells/column)
* klass [`Range`](/cells/python-net/sv/aspose.cells/range)
* klass [`Row`](/cells/python-net/sv/aspose.cells/row)
