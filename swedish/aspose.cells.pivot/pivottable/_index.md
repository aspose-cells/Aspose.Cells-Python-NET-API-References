---
title: PivotTable klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 230
url: /sv/aspose.cells.pivot/pivottable/
is_root: false
---
##  PivotTable klass
Sammanfattande beskrivning för PivotTable.



Typen PivotTable avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [is_excel_2003_compatible](/cells/python-net/sv/aspose.cells.pivot/pivottable/is_excel_2003_compatible) | Anger om pivottabellen är kompatibel med Excel 2003 när pivottabellen uppdateras.<br/>Om det är sant måste en sträng vara mindre än eller lika med 255 tecken, så om strängen är större än 255 tecken,<br/>den kommer att avkortas. Om den är falsk kommer en sträng inte att ha den ovannämnda begränsningen.<br/> Standardvärdet är sant.|
| [refreshed_by_who](/cells/python-net/sv/aspose.cells.pivot/pivottable/refreshed_by_who) | Hämtar namnet på den senaste användaren som uppdaterade den här pivottabellen|
| [refresh_date](/cells/python-net/sv/aspose.cells.pivot/pivottable/refresh_date) | Hämtar det senaste datumet och tiden då pivottabellen uppdaterades.|
| [pivot_table_style_name](/cells/python-net/sv/aspose.cells.pivot/pivottable/pivot_table_style_name) | Hämtar och anger namnet på pivottabellens stil.|
| [pivot_table_style_type](/cells/python-net/sv/aspose.cells.pivot/pivottable/pivot_table_style_type) | Hämtar och ställer in den inbyggda pivottabellens stil.|
| [column_fields](/cells/python-net/sv/aspose.cells.pivot/pivottable/column_fields) | Returnerar ett PivotFields-objekt som för närvarande visas som kolumnfält.|
| [row_fields](/cells/python-net/sv/aspose.cells.pivot/pivottable/row_fields) | Returnerar ett PivotFields-objekt som för närvarande visas som radfält.|
| [page_fields](/cells/python-net/sv/aspose.cells.pivot/pivottable/page_fields) | Returnerar ett PivotFields-objekt som för närvarande visas som sidfält.|
| [data_fields](/cells/python-net/sv/aspose.cells.pivot/pivottable/data_fields) | Hämtar ett PivotField-objekt som representerar alla datafält i en pivottabell.<br/>Skrivskyddad. Den skulle bara vara init när det finns två eller fler datafält i DataPiovtFiels.<br/> Den används bara för att lägga till DataPivotField i pivottabellens rad-/kolumnområde. Standardinställningen är i radområdet.|
| [data_field](/cells/python-net/sv/aspose.cells.pivot/pivottable/data_field) |Hämtar ett [`PivotField`](/cells/python-net/sv/aspose.cells.pivot/pivotfield)-objekt som representerar alla datafält i en pivottabell.<br/>Skrivskyddad.<br/>Den skulle bara skapas när det finns två eller fler datafält i dataregionen.<br/> Standardmässigt finns den i radregionen. Du kan dra den till rad-/kolumnregionen med metoden PivotTable.AddFieldToArea().|
| [base_fields](/cells/python-net/sv/aspose.cells.pivot/pivottable/base_fields) | Returnerar alla grundläggande pivottabellfält.|
| [pivot_filters](/cells/python-net/sv/aspose.cells.pivot/pivottable/pivot_filters) | Returnerar alla filter för pivotfält i pivottabellen.|
| [column_range](/cells/python-net/sv/aspose.cells.pivot/pivottable/column_range) | Returnerar ett CellArea-objekt som representerar området<br/> som innehåller kolumnområdet i pivottabellrapporten. Skrivskyddad.|
| [row_range](/cells/python-net/sv/aspose.cells.pivot/pivottable/row_range) | Returnerar ett CellArea-objekt som representerar området<br/> som innehåller radområdet i pivottabellrapporten. Skrivskyddad.|
| [data_body_range](/cells/python-net/sv/aspose.cells.pivot/pivottable/data_body_range) | Returnerar ett [`CellArea`](/cells/python-net/sv/aspose.cells/cellarea)-objekt som representerar det område som innehåller dataområdet<br/> i listan mellan rubrikraden och infogningsraden. Skrivskyddad.|
| [table_range1](/cells/python-net/sv/aspose.cells.pivot/pivottable/table_range1) | Returnerar ett CellArea-objekt som representerar området som innehåller hela pivottabellrapporten,<br/> men inkluderar inte sidfält. Skrivskyddad.|
| [table_range2](/cells/python-net/sv/aspose.cells.pivot/pivottable/table_range2) | Returnerar ett CellArea-objekt som representerar området som innehåller hela pivottabellrapporten,<br/> inkluderar sidfält. Skrivskyddad.|
| [is_grid_drop_zones](/cells/python-net/sv/aspose.cells.pivot/pivottable/is_grid_drop_zones) | Anger om pivottabellrapporten visar klassisk pivottabelllayout.<br/> (möjliggör dra i fält i rutnätet)|
| [show_column_grand_totals](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_column_grand_totals) |Anger om totalsummor ska visas för kolumnerna i denna pivottabell.|
| [show_row_grand_totals](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_row_grand_totals) | Anger om totalsummor ska visas för raderna i pivottabellen.|
| [column_grand](/cells/python-net/sv/aspose.cells.pivot/pivottable/column_grand) | Anger om pivottabellrapporten visar totalsummor för kolumner.|
| [row_grand](/cells/python-net/sv/aspose.cells.pivot/pivottable/row_grand) | Anger om totalsummor ska visas för raderna i denna pivottabell.|
| [display_null_string](/cells/python-net/sv/aspose.cells.pivot/pivottable/display_null_string) | Anger om pivottabellrapporten visar en anpassad sträng om värdet är null.|
| [null_string](/cells/python-net/sv/aspose.cells.pivot/pivottable/null_string) | Hämtar strängen som visas i celler som innehåller nullvärden<br/> när egenskapen DisplayNullString är sann. Standardvärdet är en tom sträng.|
| [display_error_string](/cells/python-net/sv/aspose.cells.pivot/pivottable/display_error_string) | Anger om pivottabellrapporten visar en anpassad sträng i celler som innehåller fel.|
| [data_field_header_name](/cells/python-net/sv/aspose.cells.pivot/pivottable/data_field_header_name) | Hämtar och anger namnet på värdeområdesfältets rubrik i pivottabellen.|
| [error_string](/cells/python-net/sv/aspose.cells.pivot/pivottable/error_string) | Hämtar strängen som visas i celler som innehåller fel<br/> när egenskapen DisplayErrorString är sann. Standardvärdet är en tom sträng.|
| [is_auto_format](/cells/python-net/sv/aspose.cells.pivot/pivottable/is_auto_format) | Anger om pivottabellrapporten formateras automatiskt.<br/>Kryssrutan "autoformatera tabell" som finns i pivottabellalternativet för Excel 2003|
| [autofit_column_width_on_update](/cells/python-net/sv/aspose.cells.pivot/pivottable/autofit_column_width_on_update) | Anger om kolumnbredd automatiskt anpassas vid uppdatering|
| [auto_format_type](/cells/python-net/sv/aspose.cells.pivot/pivottable/auto_format_type) | Hämtar och anger autoformattypen för pivottabellen.|
| [has_blank_rows](/cells/python-net/sv/aspose.cells.pivot/pivottable/has_blank_rows) | Anger om tomma rader ska läggas till.<br/> Den här egenskapen gäller endast för automatiska formateringstyper för pivottabeller som behöver lägga till tomma rader.|
| [merge_labels](/cells/python-net/sv/aspose.cells.pivot/pivottable/merge_labels) | Sant om etiketterna för objekt på den yttre raden, kolumnobjektet, delsumman och totalsumman i den angivna pivottabellrapporten använder sammanfogade celler.|
| [preserve_formatting](/cells/python-net/sv/aspose.cells.pivot/pivottable/preserve_formatting) | Anger om formateringen bevaras när pivottabellen uppdateras eller beräknas om.|
| [show_drill](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_drill) | Hämtar och anger om knappar för att expandera/minimera ska visas.|
| [enable_drilldown](/cells/python-net/sv/aspose.cells.pivot/pivottable/enable_drilldown) | Hämtar om detaljnivån är aktiverad.|
| [enable_field_dialog](/cells/python-net/sv/aspose.cells.pivot/pivottable/enable_field_dialog) | Anger om dialogrutan Pivottabellfält är tillgänglig<br/> när användaren dubbelklickar på pivottabellfältet.|
| [enable_field_list](/cells/python-net/sv/aspose.cells.pivot/pivottable/enable_field_list) | Anger om fältlistan för pivottabellen är tillgänglig i Excel-vyn.|
| [enable_wizard](/cells/python-net/sv/aspose.cells.pivot/pivottable/enable_wizard) | Anger om pivottabellguiden är tillgänglig.|
| [subtotal_hidden_page_items](/cells/python-net/sv/aspose.cells.pivot/pivottable/subtotal_hidden_page_items) |Anger om dolda sidfältsobjekt i pivottabellrapporten<br/>ingår i delsummor för rader och kolumner, blocksummor och slutsummor.<br/> Standardvärdet är Falskt.|
| [grand_total_name](/cells/python-net/sv/aspose.cells.pivot/pivottable/grand_total_name) | Returnerar etiketten som visas i rubriken för totalsumman, kolumnen eller raden.<br/> Standardvärdet är strängen "Total summa".|
| [manual_update](/cells/python-net/sv/aspose.cells.pivot/pivottable/manual_update) | Anger om pivottabellrapporten endast beräknas om på användarens begäran.|
| [is_multiple_field_filters](/cells/python-net/sv/aspose.cells.pivot/pivottable/is_multiple_field_filters) | Anger ett booleskt värde som anger om fälten i en pivottabell kan ha flera filter inställda på sig.|
| [allow_multiple_filters_per_field](/cells/python-net/sv/aspose.cells.pivot/pivottable/allow_multiple_filters_per_field) | Anger ett booleskt värde som anger om fälten i en pivottabell kan ha flera filter inställda på sig.|
| [missing_items_limit](/cells/python-net/sv/aspose.cells.pivot/pivottable/missing_items_limit) | Anger ett booleskt värde som anger om fälten i en pivottabell kan ha flera filter inställda på sig.|
| [enable_data_value_editing](/cells/python-net/sv/aspose.cells.pivot/pivottable/enable_data_value_editing) | Anger ett booleskt värde som anger om användaren har behörighet att redigera cellerna i dataområdet i pivottabellen.<br/> Aktivera cellredigering i värdeområdet|
| [show_data_tips](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_data_tips) | Anger ett booleskt värde som anger om verktygstips ska visas för pivottabelldataceller.|
| [show_member_property_tips](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_member_property_tips) | Anger ett booleskt värde som anger om information om medlemsegenskaper ska utelämnas från verktygstips för pivottabeller.|
| [show_values_row](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_values_row) | Anger om värderaden visas.|
| [show_empty_col](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_empty_col) | Anger om tomma kolumner ska inkluderas i tabellen|
| [show_empty_row](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_empty_row) |Anger om tomma rader ska inkluderas i tabellen.|
| [field_list_sort_ascending](/cells/python-net/sv/aspose.cells.pivot/pivottable/field_list_sort_ascending) | Anger om fält i pivottabellen är sorterade i en annan ordning än standardordningen i fältlistan.|
| [print_drill](/cells/python-net/sv/aspose.cells.pivot/pivottable/print_drill) | Anger ett booleskt värde som anger om borrindikatorer ska skrivas ut.<br/> skriv ut expandera/minimera-knappar när de visas i pivottabellen.|
| [alt_text_title](/cells/python-net/sv/aspose.cells.pivot/pivottable/alt_text_title) | Hämtar och anger titeln på ändringstexten.|
| [alt_text_description](/cells/python-net/sv/aspose.cells.pivot/pivottable/alt_text_description) | Hämtar beskrivningen av alt-texten.|
| [name](/cells/python-net/sv/aspose.cells.pivot/pivottable/name) | Hämtar namnet på pivottabellen|
| [column_header_caption](/cells/python-net/sv/aspose.cells.pivot/pivottable/column_header_caption) | Hämtar kolumnrubrikens bildtext för pivottabellen.|
| [indent](/cells/python-net/sv/aspose.cells.pivot/pivottable/indent) | Anger indenteringsökningen för den kompakta axeln och kan användas för att ställa in rapportlayouten till kompakt form.|
| [row_header_caption](/cells/python-net/sv/aspose.cells.pivot/pivottable/row_header_caption) | Hämtar radrubrikens bildtext för pivottabellen.|
| [show_row_header_caption](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_row_header_caption) | Anger om radrubrikens rubrik visas i pivottabellrapporten<br/> Anger om fälttexter och filterrullgardinsmenyer ska visas|
| [custom_list_sort](/cells/python-net/sv/aspose.cells.pivot/pivottable/custom_list_sort) | Anger om den inbyggda anpassade listan ska beaktas vid sortering av data|
| [pivot_format_conditions](/cells/python-net/sv/aspose.cells.pivot/pivottable/pivot_format_conditions) | Hämtar formatvillkoren för pivottabellen.|
| [conditional_formats](/cells/python-net/sv/aspose.cells.pivot/pivottable/conditional_formats) | Hämtar de villkorliga formaten för pivottabellen.|
| [page_field_order](/cells/python-net/sv/aspose.cells.pivot/pivottable/page_field_order) |Hämtar och anger i vilken ordning sidfält läggs till i pivottabellrapportens layout.|
| [page_field_wrap_count](/cells/python-net/sv/aspose.cells.pivot/pivottable/page_field_wrap_count) | Hämtar antalet sidfält i varje kolumn eller rad i pivottabellrapporten.|
| [tag](/cells/python-net/sv/aspose.cells.pivot/pivottable/tag) | Hämtar en sträng som sparats med pivottabellrapporten.|
| [save_data](/cells/python-net/sv/aspose.cells.pivot/pivottable/save_data) | Anger om data för pivottabellrapporten sparas med arbetsboken.|
| [refresh_data_on_opening_file](/cells/python-net/sv/aspose.cells.pivot/pivottable/refresh_data_on_opening_file) | Anger om Uppdatera data när fil öppnas.|
| [refresh_data_flag](/cells/python-net/sv/aspose.cells.pivot/pivottable/refresh_data_flag) | Anger om data uppdateras eller inte.|
| [source_type](/cells/python-net/sv/aspose.cells.pivot/pivottable/source_type) | Hämtar datakälltypen för pivottabellen.|
| [external_connection_data_source](/cells/python-net/sv/aspose.cells.pivot/pivottable/external_connection_data_source) | Hämtar den externa anslutningsdatakällan.|
| [data_source](/cells/python-net/sv/aspose.cells.pivot/pivottable/data_source) | Hämtar och ställer in datakällan för pivottabellen.|
| [pivot_formats](/cells/python-net/sv/aspose.cells.pivot/pivottable/pivot_formats) | Hämtar samlingen av format som tillämpats på pivottabellen.|
| [item_print_titles](/cells/python-net/sv/aspose.cells.pivot/pivottable/item_print_titles) | Anger om PivotItem-namn ska upprepas högst upp på varje utskriven sida.|
| [repeat_items_on_each_printed_page](/cells/python-net/sv/aspose.cells.pivot/pivottable/repeat_items_on_each_printed_page) | Anger om pivotobjektens bildtexter på radområdet upprepas på varje utskriven sida för pivotfält i tabellform.|
| [print_titles](/cells/python-net/sv/aspose.cells.pivot/pivottable/print_titles) | Anger om de utskrivna titlarna för kalkylbladet är uppsatta baserat på<br/> i pivottabellrapporten. Standardvärdet är falskt.|
| [display_immediate_items](/cells/python-net/sv/aspose.cells.pivot/pivottable/display_immediate_items) |Anger om objekt i rad- och kolumnområdena är synliga<br/> när dataområdet i pivottabellen är tomt. Standardvärdet är sant.|
| [is_selected](/cells/python-net/sv/aspose.cells.pivot/pivottable/is_selected) | Anger om denna pivottabell är vald.|
| [show_pivot_style_row_header](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_pivot_style_row_header) | Anger om radrubriken i pivottabellen ska ha stilen tillämpad.|
| [show_pivot_style_column_header](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_pivot_style_column_header) | Anger om stilen ska tillämpas på kolumnrubriken i pivottabellen.|
| [show_pivot_style_row_stripes](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_pivot_style_row_stripes) | Anger om radrandformatering tillämpas.|
| [show_pivot_style_column_stripes](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_pivot_style_column_stripes) | Anger om randformatering tillämpas för kolumnen.|
| [show_pivot_style_last_column](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_pivot_style_last_column) | Anger om kolumnformateringen tillämpas.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`remove_field(self, field_type, field_name)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.pivotfieldtype-str) | Tar bort ett fält från ett specifikt fältområde|
| [`remove_field(self, field_type, base_field_index)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.pivotfieldtype-int) | Tar bort ett fält från ett specifikt fältområde|
| [`remove_field(self, field_type, pivot_field)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.pivotfieldtype-aspose.cells.pivot.pivotfield) | Ta bort fält från specifikt fältområde|
| [`add_field_to_area(self, field_type, field_name)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.pivotfieldtype-str) | Lägger till fältet i det specifika området.|
| [`add_field_to_area(self, field_type, base_field_index)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.pivotfieldtype-int) | Lägger till fältet i det specifika området.|
| [`add_field_to_area(self, field_type, pivot_field)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.pivotfieldtype-aspose.cells.pivot.pivotfield) | Lägger till fältet i det specifika området.|
| [`add_calculated_field(self, name, formula, drag_to_data_area)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/add_calculated_field/#str-str-bool) | Lägger till ett beräknat fält i pivotfältet.|
| [`add_calculated_field(self, name, formula)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/add_calculated_field/#str-str) | Lägger till ett beräknat fält i pivotfältet och drar det till dataområdet.|
| [`move(self, row, column)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/move/#int-int) | Flyttar pivottabellen till en annan plats i kalkylbladet.|
| [`move(self, dest_cell_name)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/move/#str) | Flyttar pivottabellen till en annan plats i kalkylbladet.|
| [`move_to(self, row, column)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/move_to/#int-int) | Flyttar pivottabellen till en annan plats i kalkylbladet.|
| [`move_to(self, dest_cell_name)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/move_to/#str) | Flyttar pivottabellen till en annan plats i kalkylbladet.|
| [`get_source(self)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/get_source/#) | Hämta pivottabellens källdata.|
| [`get_source(self, is_original)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/get_source/#bool) | Hämta pivottabellens källdata.|
| [`refresh_data(self)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/refresh_data/#) |Uppdaterar pivottabellens data och inställningar från dess datakälla.|
| [`refresh_data(self, option)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/refresh_data/#aspose.cells.pivot.pivottablerefreshoption) | Uppdaterar pivottabellens data och inställningar från dess datakälla med alternativ.|
| [`calculate_data(self)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/calculate_data/#) | Beräknar pivottabellens data till celler.|
| [`calculate_data(self, option)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/calculate_data/#aspose.cells.pivot.pivottablecalculateoption) | Beräkna pivottabeller med alternativ|
| [`format(self, pivot_area, style)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/format/#aspose.cells.pivot.pivotarea-aspose.cells.style) | Formaterar det markerade området i pivottabellen.|
| [`format(self, ca, style)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/format/#aspose.cells.cellarea-aspose.cells.style) | Formaterar det markerade området i pivottabellen.|
| [`format(self, row, column, style)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/format/#int-int-aspose.cells.style) | Formatera cellen i pivottabellområdet|
| [`set_auto_group_field(self, base_field_index)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/set_auto_group_field/#int) | Ställer in automatisk fältgrupp efter pivottabellen.|
| [`set_auto_group_field(self, pivot_field)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/set_auto_group_field/#aspose.cells.pivot.pivotfield) | Ställer in automatisk fältgrupp efter pivottabellen.|
| [`set_manual_group_field(self, base_field_index, start_val, end_val, group_by_list, interval_num)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/set_manual_group_field/#int-float-float-list-float) | Ställer in manuell fältgrupp efter pivottabellen.|
| [`set_manual_group_field(self, pivot_field, start_val, end_val, group_by_list, interval_num)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/set_manual_group_field/#aspose.cells.pivot.pivotfield-float-float-list-float) | Ställer in manuell fältgrupp efter pivottabellen.|
| [`set_manual_group_field(self, base_field_index, start_val, end_val, group_by_list, interval_num)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/set_manual_group_field/#int-datetime-datetime-list-int) | Ställer in manuell fältgrupp efter pivottabellen.|
| [`set_manual_group_field(self, pivot_field, start_val, end_val, group_by_list, interval_num)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/set_manual_group_field/#aspose.cells.pivot.pivotfield-datetime-datetime-list-int) | Ställer in manuell fältgrupp efter pivottabellen.|
| [`set_ungroup(self, base_field_index)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/set_ungroup/#int) | Anger avgruppering efter pivottabell|
| [`set_ungroup(self, pivot_field)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/set_ungroup/#aspose.cells.pivot.pivotfield) | Anger avgruppering efter pivottabell|
| [`copy_style(self, pivot_table)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/copy_style/#aspose.cells.pivot.pivottable) | Kopierar namngiven stil från en annan pivottabell.|
| [`show_report_filter_page(self, page_field)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_report_filter_page/#aspose.cells.pivot.pivotfield) | Visa alla rapportfiltersidor enligt PivotField, PivotField måste finnas i PageFields.|
| [`show_report_filter_page_by_name(self, field_name)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_report_filter_page_by_name/#str) | Visa alla rapportfiltersidor enligt PivotFields namn. Pivotfältet måste finnas i PageFields.|
| [`show_report_filter_page_by_index(self, pos_index)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_report_filter_page_by_index/#int) | Visa alla rapportfiltersidor enligt positionsindexet i PageFields|
| [`get_fields(self, field_type)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/get_fields/#aspose.cells.pivot.pivotfieldtype) | Hämtar den specifika pivotfältlistan efter region.|
| [`fields(self, field_type)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/fields/#aspose.cells.pivot.pivotfieldtype) | Hämtar de specifika fälten efter fälttyp.|
| [`get_source_data_connections(self)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/get_source_data_connections/#) |Hämtar de externa anslutningsdatakällorna.|
| [`get_names_of_source_data_connections(self)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/get_names_of_source_data_connections/#) | Hämtar namnet på externa källdataanslutningar.|
| [`change_data_source(self, source)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/change_data_source/#list) | Ange pivottabellens källdata.|
| [`clear_data(self)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/clear_data/#) | Rensa pivottabellens data och formatering|
| [`calculate_range(self)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/calculate_range/#) | Beräknar pivottabellens intervall.|
| [`format_all(self, style)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/format_all/#aspose.cells.style) | Formatera alla celler i pivottabellområdet|
| [`format_row(self, row, style)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/format_row/#int-aspose.cells.style) | Formatera raddata i pivottabellområdet|
| [`select_area(self, ca)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/select_area/#aspose.cells.cellarea) | Markera ett område i pivottabellvyn.|
| [`show_detail(self, row_offset, column_offset, new_sheet, dest_row, dest_column)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_detail/#int-int-bool-int-int) | Visa detaljerna för ett objekt i dataområdet till en ny tabell.|
| [`get_horizontal_page_breaks(self)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/get_horizontal_page_breaks/#) | Hämtar horisontella sidbrytningar från denna pivottabell.|
| [`get_horizontal_breaks(self)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/get_horizontal_breaks/#) | Hämtar pivottabellens radindexlista med horisontella sidbrytningar|
| [`show_in_compact_form(self)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_in_compact_form/#) | Layoutar pivottabellen i kompakt form.|
| [`show_in_outline_form(self)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_in_outline_form/#) | Layoutar pivottabellen i dispositionsformat.|
| [`show_in_tabular_form(self)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_in_tabular_form/#) | Layoutar pivottabellen i tabellform.|
| [`get_cell_by_display_name(self, display_name)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/get_cell_by_display_name/#str) | Hämtar objektet [`Cell`](/cells/python-net/sv/aspose.cells/cell) med visningsnamnet PivotField.|
| [`get_children(self)`](/cells/python-net/sv/aspose.cells.pivot/pivottable/get_children/#) | Hämtar de underordnade pivottabellerna som använder dessa pivottabelldata som datakälla.|



###  Exempel

```python
from aspose.cells import FormatConditionType, OperatorType, Workbook
from aspose.cells.pivot import PivotFieldType, PivotFilterType, PivotTableStyleType
from aspose.pydrawing import Color

book = Workbook()
sheet = book.worksheets[0]
cells = sheet.cells
cells.get(0, 0).value = "fruit"
cells.get(1, 0).value = "grape"
cells.get(2, 0).value = "blueberry"
cells.get(3, 0).value = "kiwi"
cells.get(4, 0).value = "cherry"
cells.get(5, 0).value = "grape"
cells.get(6, 0).value = "blueberry"
cells.get(7, 0).value = "kiwi"
cells.get(8, 0).value = "cherry"
cells.get(0, 1).value = "year"
cells.get(1, 1).value = 2020
cells.get(2, 1).value = 2020
cells.get(3, 1).value = 2020
cells.get(4, 1).value = 2020
cells.get(5, 1).value = 2021
cells.get(6, 1).value = 2021
cells.get(7, 1).value = 2021
cells.get(8, 1).value = 2021
cells.get(0, 2).value = "amount"
cells.get(1, 2).value = 50
cells.get(2, 2).value = 60
cells.get(3, 2).value = 70
cells.get(4, 2).value = 80
cells.get(5, 2).value = 90
cells.get(6, 2).value = 100
cells.get(7, 2).value = 110
cells.get(8, 2).value = 120
pivots = sheet.pivot_tables
pivotIndex = pivots.add("=Sheet1!A1:C9", "A12", "TestPivotTable")
pivot = pivots[pivotIndex]
pivot.add_field_to_area(PivotFieldType.ROW, "fruit")
pivot.add_field_to_area(PivotFieldType.COLUMN, "year")
pivot.add_field_to_area(PivotFieldType.DATA, "amount")
pivot.pivot_table_style_type = PivotTableStyleType.PIVOT_TABLE_STYLE_MEDIUM10
# Change PivotField's attributes
rowField = pivot.row_fields[0]
rowField.display_name = "custom display name"
# Add PivotFilter
index = pivot.pivot_filters.add(0, PivotFilterType.COUNT)
filter = pivot.pivot_filters[index]
filter.auto_filter.filter_top10(0, False, False, 2)
# Add PivotFormatCondition
formatIndex = pivot.pivot_format_conditions.add()
pfc = pivot.pivot_format_conditions[formatIndex]
fcc = pfc.format_conditions
fcc.add_area(pivot.data_body_range)
idx = fcc.add_condition(FormatConditionType.CELL_VALUE)
fc = fcc[idx]
fc.formula1 = "100"
fc.operator = OperatorType.GREATER_OR_EQUAL
fc.style.background_color = Color.red
pivot.refresh_data()
pivot.calculate_data()
# do your business
book.save("out.xlsx")

```

###  Se även
* modul [`aspose.cells.pivot`](..)
* klass [`Cell`](/cells/python-net/sv/aspose.cells/cell)
* klass [`CellArea`](/cells/python-net/sv/aspose.cells/cellarea)
* klass [`PivotField`](/cells/python-net/sv/aspose.cells.pivot/pivotfield)
