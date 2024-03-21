---
title: PivotTable klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 180
url: /sv/aspose.cells.pivot/pivottable/
is_root: false
---
##  PivotTable klass
Sammanfattande beskrivning för PivotTable.



Typen PivotTable avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [is_excel_2003_compatible](/cells/python-net/sv/aspose.cells.pivot/pivottable/is_excel_2003_compatible) | Anger om pivottabellen är kompatibel med Excel2003 vid uppdatering av pivottabell,<br/>om sant måste en sträng vara mindre än eller lika med 255 tecken, så om strängen är större än 255 tecken,<br/>den kommer att trunkeras. om det är falskt kommer en sträng inte att ha den ovannämnda begränsningen.<br/> Standardvärdet är sant.|
| [refreshed_by_who](/cells/python-net/sv/aspose.cells.pivot/pivottable/refreshed_by_who) | Hämtar namnet på användaren som senast uppdaterade pivottabellen|
| [refresh_date](/cells/python-net/sv/aspose.cells.pivot/pivottable/refresh_date) | Hämtar datumet när pivottabellen senast uppdaterades.|
| [pivot_table_style_name](/cells/python-net/sv/aspose.cells.pivot/pivottable/pivot_table_style_name) | Hämtar och ställer in det vridbara stilnamnet.|
| [pivot_table_style_type](/cells/python-net/sv/aspose.cells.pivot/pivottable/pivot_table_style_type) | Får och ställer in den inbyggda pivottabellstilen.|
| [column_fields](/cells/python-net/sv/aspose.cells.pivot/pivottable/column_fields) | Returnerar ett PivotFields-objekt som för närvarande visas som kolumnfält.|
| [row_fields](/cells/python-net/sv/aspose.cells.pivot/pivottable/row_fields) | Returnerar ett PivotFields-objekt som för närvarande visas som radfält.|
| [page_fields](/cells/python-net/sv/aspose.cells.pivot/pivottable/page_fields) | Returnerar ett PivotFields-objekt som för närvarande visas som sidfält.|
| [data_fields](/cells/python-net/sv/aspose.cells.pivot/pivottable/data_fields) | Hämtar ett PivotField-objekt som representerar alla datafält i en pivottabell.<br/>Endast skrivskyddad. Det skulle vara init endast när det finns två eller flera datafält i DataPiovtFiels.<br/> Det används bara för att lägga till DataPivotField till pivottabellens rad-/kolumnområde. Standard är i radområdet.|
| [data_field](/cells/python-net/sv/aspose.cells.pivot/pivottable/data_field) | Hämtar ett PivotField-objekt som representerar alla datafält i en pivottabell.<br/>Endast skrivskyddad. Det skulle vara init endast när det finns två eller flera datafält i DataPiovtFiels.<br/> Det används bara för att lägga till DataPivotField till pivottabellens rad-/kolumnområde. Standard är i radområdet.|
| [base_fields](/cells/python-net/sv/aspose.cells.pivot/pivottable/base_fields) | Returnerar ett PivotFields-objekt som inkluderar alla fält i pivottabellsrapporten|
| [pivot_filters](/cells/python-net/sv/aspose.cells.pivot/pivottable/pivot_filters) | Returnerar ett PivotFilterCollection-objekt.|
| [column_range](/cells/python-net/sv/aspose.cells.pivot/pivottable/column_range) |Returnerar ett CellArea-objekt som representerar intervallet<br/> som innehåller kolumnområdet i pivottabellrapporten. Skrivskyddad.|
| [row_range](/cells/python-net/sv/aspose.cells.pivot/pivottable/row_range) |Returnerar ett CellArea-objekt som representerar intervallet<br/> som innehåller radområdet i pivottabellrapporten. Skrivskyddad.|
| [data_body_range](/cells/python-net/sv/aspose.cells.pivot/pivottable/data_body_range) | Returnerar ett CellArea-objekt som representerar intervallet som innehåller dataområdet<br/> i listan mellan rubrikraden och infogningsraden. Skrivskyddad.|
| [table_range1](/cells/python-net/sv/aspose.cells.pivot/pivottable/table_range1) | Returnerar ett CellArea-objekt som representerar intervallet som innehåller hela pivottabellsrapporten,<br/> men inkluderar inte sidfält. Skrivskyddad.|
| [table_range2](/cells/python-net/sv/aspose.cells.pivot/pivottable/table_range2) | Returnerar ett CellArea-objekt som representerar intervallet som innehåller hela pivottabellsrapporten,<br/> inkluderar sidfält. Skrivskyddad.|
| [column_grand](/cells/python-net/sv/aspose.cells.pivot/pivottable/column_grand) | Anger om pivottabellsrapporten visar totalsummor för kolumner.|
| [is_grid_drop_zones](/cells/python-net/sv/aspose.cells.pivot/pivottable/is_grid_drop_zones) | Anger om pivottabellrapporten visar klassisk pivotbar layout.<br/> (möjliggör att dra fält i rutnätet)|
| [row_grand](/cells/python-net/sv/aspose.cells.pivot/pivottable/row_grand) | Anger om pivottabellsrapporten visar totalsummor för rader.|
| [display_null_string](/cells/python-net/sv/aspose.cells.pivot/pivottable/display_null_string) | Anger om pivottabellsrapporten visar en anpassad sträng<br/> i celler som innehåller nullvärden.|
| [null_string](/cells/python-net/sv/aspose.cells.pivot/pivottable/null_string) | Hämtar strängen som visas i celler som innehåller nollvärden<br/>när egenskapen DisplayNullString är true. Standardvärdet är en tom sträng.|
| [display_error_string](/cells/python-net/sv/aspose.cells.pivot/pivottable/display_error_string) | Anger om pivottabellsrapporten visar en anpassad sträng i celler som innehåller fel.|
| [data_field_header_name](/cells/python-net/sv/aspose.cells.pivot/pivottable/data_field_header_name) | Hämtar och ställer in namnet på värdeområdets fälthuvud i pivottabellen.|
| [error_string](/cells/python-net/sv/aspose.cells.pivot/pivottable/error_string) | Hämtar strängen som visas i celler som innehåller fel<br/> när egenskapen DisplayErrorString är true. Standardvärdet är en tom sträng.|
| [is_auto_format](/cells/python-net/sv/aspose.cells.pivot/pivottable/is_auto_format) | Anger om pivottabellsrapporten formateras automatiskt.<br/> Kryssrutan "autoformat tabell" som är ett pivotbart alternativ för Excel 2003|
| [autofit_column_width_on_update](/cells/python-net/sv/aspose.cells.pivot/pivottable/autofit_column_width_on_update) | Anger om kolumnbredden automatiskt anpassas vid uppdatering|
| [auto_format_type](/cells/python-net/sv/aspose.cells.pivot/pivottable/auto_format_type) | Hämtar automatisk formattyp för PivotTable.|
| [has_blank_rows](/cells/python-net/sv/aspose.cells.pivot/pivottable/has_blank_rows) | Anger om tomma rader ska läggas till.<br/> Den här egenskapen gäller endast för automatiska formattyper för pivottabeller som behöver lägga till tomma rader.|
| [merge_labels](/cells/python-net/sv/aspose.cells.pivot/pivottable/merge_labels) | Indikerar om den angivna pivottabellrapportens yttre radpost, kolumnpost, delsumma,<br/> och totala etiketter använder sammanslagna celler.|
| [preserve_formatting](/cells/python-net/sv/aspose.cells.pivot/pivottable/preserve_formatting) |Anger om formateringen bevaras när pivottabellen uppdateras eller räknas om.|
| [show_drill](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_drill) | Hämtar om expandera/komprimera knappar visas.|
| [enable_drilldown](/cells/python-net/sv/aspose.cells.pivot/pivottable/enable_drilldown) | Hämtar om drilldown är aktiverat.|
| [enable_field_dialog](/cells/python-net/sv/aspose.cells.pivot/pivottable/enable_field_dialog) | Anger om dialogrutan Pivottabellfält är tillgänglig<br/> när användaren dubbelklickar på PivotTable-fältet.|
| [enable_field_list](/cells/python-net/sv/aspose.cells.pivot/pivottable/enable_field_list) | Hämtar om aktivera fältlistan för pivottabellen.|
| [enable_wizard](/cells/python-net/sv/aspose.cells.pivot/pivottable/enable_wizard) | Anger om PivotTable Wizard är tillgänglig.|
| [subtotal_hidden_page_items](/cells/python-net/sv/aspose.cells.pivot/pivottable/subtotal_hidden_page_items) | Anger om dolda sidfältsobjekt i pivottabellrapporten<br/>ingår i delsummor för rader och kolumner, blocksummor och totalsummor.<br/> Standardvärdet är False.|
| [grand_total_name](/cells/python-net/sv/aspose.cells.pivot/pivottable/grand_total_name) | Returnerar textsträngsetiketten som visas i kolumnen eller radrubriken.<br/> Standardvärdet är strängen "Grand Total".|
| [manual_update](/cells/python-net/sv/aspose.cells.pivot/pivottable/manual_update) | Anger om pivottabellsrapporten endast beräknas om på användarens begäran.|
| [is_multiple_field_filters](/cells/python-net/sv/aspose.cells.pivot/pivottable/is_multiple_field_filters) | Anger ett booleskt värde som indikerar om fälten i en pivottabell kan ha flera filter inställda på dem.|
| [missing_items_limit](/cells/python-net/sv/aspose.cells.pivot/pivottable/missing_items_limit) | Anger ett booleskt värde som indikerar om fälten i en pivottabell kan ha flera filter inställda på dem.|
| [enable_data_value_editing](/cells/python-net/sv/aspose.cells.pivot/pivottable/enable_data_value_editing) |Anger ett booleskt värde som indikerar om användaren har tillåtelse att redigera cellerna i dataområdet för pivottabellen.<br/> Aktivera cellredigering i värdeområdet|
| [show_data_tips](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_data_tips) | Anger ett booleskt värde som anger om verktygstips ska visas för pivottabelldataceller.|
| [show_member_property_tips](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_member_property_tips) | Anger ett booleskt värde som anger om medlemsegenskapsinformation ska utelämnas från pivottabellens verktygstips.|
| [show_values_row](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_values_row) | Anger ett booleskt värde som anger om raden visar värden.<br/> visa värderaden|
| [show_empty_col](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_empty_col) | Anger ett booleskt värde som anger om tomma kolumner ska inkluderas i tabellen|
| [show_empty_row](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_empty_row) | Anger ett booleskt värde som anger om tomma rader ska inkluderas i tabellen.|
| [field_list_sort_ascending](/cells/python-net/sv/aspose.cells.pivot/pivottable/field_list_sort_ascending) | Anger ett booleskt värde som indikerar om fält i pivottabellen är sorterade i icke-standardordning i fältlistan.|
| [print_drill](/cells/python-net/sv/aspose.cells.pivot/pivottable/print_drill) | Anger ett booleskt värde som anger om borrindikatorer ska skrivas ut.<br/> skriv ut expandera/komprimera knappar när de visas på vridbar.|
| [alt_text_title](/cells/python-net/sv/aspose.cells.pivot/pivottable/alt_text_title) |Får titeln på altertexten|
| [alt_text_description](/cells/python-net/sv/aspose.cells.pivot/pivottable/alt_text_description) | Får beskrivningen av alt-texten|
| [name](/cells/python-net/sv/aspose.cells.pivot/pivottable/name) | Hämtar namnet på pivottabellen|
| [column_header_caption](/cells/python-net/sv/aspose.cells.pivot/pivottable/column_header_caption) | Hämtar kolumnrubriktexten för pivottabellen.|
| [indent](/cells/python-net/sv/aspose.cells.pivot/pivottable/indent) | Anger indragningsökningen för kompakt axel och kan användas för att ställa in rapportlayouten till kompakt formulär.|
| [row_header_caption](/cells/python-net/sv/aspose.cells.pivot/pivottable/row_header_caption) | Hämtar rubrikens radrubrik för pivottabellen.|
| [show_row_header_caption](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_row_header_caption) | Anger om radrubrikens bildtext visas i pivottabellsrapporten<br/> Anger om Visa fälttexter och filterrullgardinsmenyer|
| [custom_list_sort](/cells/python-net/sv/aspose.cells.pivot/pivottable/custom_list_sort) | Anger om överväga inbyggd anpassad lista vid sortering av data|
| [pivot_format_conditions](/cells/python-net/sv/aspose.cells.pivot/pivottable/pivot_format_conditions) | Hämtar formatvillkoren för pivottabellen.|
| [page_field_order](/cells/python-net/sv/aspose.cells.pivot/pivottable/page_field_order) | Hämtar ordningen i vilken sidfält läggs till i pivottabellsrapportens layout.|
| [page_field_wrap_count](/cells/python-net/sv/aspose.cells.pivot/pivottable/page_field_wrap_count) | Hämtar antalet sidfält i varje kolumn eller rad i pivottabellrapporten.|
| [tag](/cells/python-net/sv/aspose.cells.pivot/pivottable/tag) | Hämtar en sträng som sparas med pivottabellsrapporten.|
| [save_data](/cells/python-net/sv/aspose.cells.pivot/pivottable/save_data) | Anger om data för pivottabellsrapporten sparas med arbetsboken.|
| [refresh_data_on_opening_file](/cells/python-net/sv/aspose.cells.pivot/pivottable/refresh_data_on_opening_file) | Indikerar om Uppdatera data vid öppning av fil.|
| [refresh_data_flag](/cells/python-net/sv/aspose.cells.pivot/pivottable/refresh_data_flag) |Indikerar om data uppdateras eller inte.|
| [external_connection_data_source](/cells/python-net/sv/aspose.cells.pivot/pivottable/external_connection_data_source) | Hämtar den externa anslutningsdatakällan.|
| [data_source](/cells/python-net/sv/aspose.cells.pivot/pivottable/data_source) | Hämtar och ställer in datakällan för pivottabellen.|
| [pivot_formats](/cells/python-net/sv/aspose.cells.pivot/pivottable/pivot_formats) | Hämtar samlingen av format som tillämpas på pivottabell.|
| [item_print_titles](/cells/python-net/sv/aspose.cells.pivot/pivottable/item_print_titles) | En bit som specificerar om pivotobjekttexter på radaxeln<br/> upprepas på varje utskriven sida för pivotfält i tabellform.|
| [print_titles](/cells/python-net/sv/aspose.cells.pivot/pivottable/print_titles) | Anger om utskriftstitlarna för kalkylbladet är inställda<br/> i pivottabellsrapporten. Standardvärdet är falskt.|
| [display_immediate_items](/cells/python-net/sv/aspose.cells.pivot/pivottable/display_immediate_items) | Anger om objekt i rad- och kolumnområdena är synliga<br/> när dataområdet i pivottabellen är tomt. Standardvärdet är sant.|
| [is_selected](/cells/python-net/sv/aspose.cells.pivot/pivottable/is_selected) | Indikerar om pivottabellen är vald.|
| [show_pivot_style_row_header](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_pivot_style_row_header) | Anger om radhuvudet i pivottabellen ska ha stilen tillämpad.|
| [show_pivot_style_column_header](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_pivot_style_column_header) | Anger om kolumnrubriken i pivottabellen ska ha stilen tillämpad.|
| [show_pivot_style_row_stripes](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_pivot_style_row_stripes) | Indikerar om radrandsformatering tillämpas.|
| [show_pivot_style_column_stripes](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_pivot_style_column_stripes) | Indikerar om formatering av kolumnrand används.|
| [show_pivot_style_last_column](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_pivot_style_last_column) | Indikerar om formatering av kolumnrand används.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [remove_field](/cells/python-net/sv/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.PivotFieldType-str) |Tar bort ett fält från ett specifikt fältområde|
| [remove_field](/cells/python-net/sv/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.PivotFieldType-int) |Tar bort ett fält från ett specifikt fältområde|
| [remove_field](/cells/python-net/sv/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.PivotFieldType-aspose.cells.pivot.PivotField) | Ta bort fält från specifikt fältområde|
| [add_field_to_area](/cells/python-net/sv/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.PivotFieldType-str) | Lägger till fältet till det specifika området.|
| [add_field_to_area](/cells/python-net/sv/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.PivotFieldType-int) | Lägger till fältet till det specifika området.|
| [add_field_to_area](/cells/python-net/sv/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.PivotFieldType-aspose.cells.pivot.PivotField) | Lägger till fältet till det specifika området.|
| [add_calculated_field](/cells/python-net/sv/aspose.cells.pivot/pivottable/add_calculated_field/#str-str-bool) | Lägger till ett beräknat fält till pivotfält.|
| [add_calculated_field](/cells/python-net/sv/aspose.cells.pivot/pivottable/add_calculated_field/#str-str) | Lägger till ett beräknat fält till pivotfältet och dra det till dataområdet.|
| [move](/cells/python-net/sv/aspose.cells.pivot/pivottable/move/#int-int) | Flyttar pivottabellen till en annan plats i kalkylbladet.|
| [move](/cells/python-net/sv/aspose.cells.pivot/pivottable/move/#str) | Flyttar pivottabellen till en annan plats i kalkylbladet.|
| [format](/cells/python-net/sv/aspose.cells.pivot/pivottable/format/#aspose.cells.pivot.PivotArea-aspose.cells.Style) | Formaterar valt område i pivottabellen.|
| [format](/cells/python-net/sv/aspose.cells.pivot/pivottable/format/#int-int-aspose.cells.Style) | Formatera cellen i det vridbara området|
| [set_auto_group_field](/cells/python-net/sv/aspose.cells.pivot/pivottable/set_auto_group_field/#int) | Ställer in automatisk fältgrupp efter pivottabellen.|
| [set_auto_group_field](/cells/python-net/sv/aspose.cells.pivot/pivottable/set_auto_group_field/#aspose.cells.pivot.PivotField) | Ställer in automatisk fältgrupp efter pivottabellen.|
| [set_manual_group_field](/cells/python-net/sv/aspose.cells.pivot/pivottable/set_manual_group_field/#int-float-float-list-float) | Ställer in manuell fältgrupp efter pivottabellen.|
| [set_manual_group_field](/cells/python-net/sv/aspose.cells.pivot/pivottable/set_manual_group_field/#aspose.cells.pivot.PivotField-float-float-list-float) | Ställer in manuell fältgrupp efter pivottabellen.|
| [set_manual_group_field](/cells/python-net/sv/aspose.cells.pivot/pivottable/set_manual_group_field/#int-DateTime-DateTime-list-int) | Ställer in manuell fältgrupp efter pivottabellen.|
| [set_manual_group_field](/cells/python-net/sv/aspose.cells.pivot/pivottable/set_manual_group_field/#aspose.cells.pivot.PivotField-DateTime-DateTime-list-int) | Ställer in manuell fältgrupp efter pivottabellen.|
| [set_ungroup](/cells/python-net/sv/aspose.cells.pivot/pivottable/set_ungroup/#int) | Delar upp grupperingen efter pivottabellen|
| [set_ungroup](/cells/python-net/sv/aspose.cells.pivot/pivottable/set_ungroup/#aspose.cells.pivot.PivotField) | Delar upp grupperingen efter pivottabellen|
| [copy_style](/cells/python-net/sv/aspose.cells.pivot/pivottable/copy_style/#aspose.cells.pivot.PivotTable) | Kopierar namngiven stil från en annan pivottabell.|
| [show_report_filter_page](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_report_filter_page/#aspose.cells.pivot.PivotField) | Visa alla rapportfiltersidor enligt PivotField, PivotField måste finnas i PageFields.|
| [show_report_filter_page_by_name](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_report_filter_page_by_name/#str) | Visa alla rapportfiltersidor enligt PivotFields namn, PivotField måste finnas i PageFields.|
| [show_report_filter_page_by_index](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_report_filter_page_by_index/#int) | Visa alla rapportfiltersidor enligt positionsindex i sidfälten|
| [fields](/cells/python-net/sv/aspose.cells.pivot/pivottable/fields/#aspose.cells.pivot.PivotFieldType) | Hämtar de specifika fälten efter fälttyp.|
| [change_data_source](/cells/python-net/sv/aspose.cells.pivot/pivottable/change_data_source/#list) |Ställ in pivotables källdata.<br/> Blad1!$A$1:$C$3|
| [get_source](/cells/python-net/sv/aspose.cells.pivot/pivottable/get_source/#) | Få pivottables källdata.|
| [refresh_data](/cells/python-net/sv/aspose.cells.pivot/pivottable/refresh_data/#) | Uppdaterar pivotables data och inställning från dess datakälla.|
| [calculate_data](/cells/python-net/sv/aspose.cells.pivot/pivottable/calculate_data/#) | Beräknar pivotables data till celler.|
| [clear_data](/cells/python-net/sv/aspose.cells.pivot/pivottable/clear_data/#) | Rensa pivottabellens data och formatering|
| [calculate_range](/cells/python-net/sv/aspose.cells.pivot/pivottable/calculate_range/#) | Beräknar pivotables räckvidd.|
| [format_all](/cells/python-net/sv/aspose.cells.pivot/pivottable/format_all/#aspose.cells.Style) | Formatera hela cellen i det vridbara området|
| [format_row](/cells/python-net/sv/aspose.cells.pivot/pivottable/format_row/#int-aspose.cells.Style) | Formatera raddata i det vridbara området|
| [get_horizontal_breaks](/cells/python-net/sv/aspose.cells.pivot/pivottable/get_horizontal_breaks/#) | hämta pivottabellsradindexlista över horisontella sidbrytningar|
| [show_in_compact_form](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_in_compact_form/#) | Layouter pivottabellen i kompakt form.|
| [show_in_outline_form](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_in_outline_form/#) | Layouter pivottabellen i konturform.|
| [show_in_tabular_form](/cells/python-net/sv/aspose.cells.pivot/pivottable/show_in_tabular_form/#) | Layouter pivottabellen i tabellform.|
| [get_cell_by_display_name](/cells/python-net/sv/aspose.cells.pivot/pivottable/get_cell_by_display_name/#str) | Hämtar objektet [`Cell`](/cells/python-net/sv/aspose.cells/cell) med visningsnamnet PivotField.|
| [get_children](/cells/python-net/sv/aspose.cells.pivot/pivottable/get_children/#) | Hämtar barnpivottabellerna som använder denna pivottabelldata som datakälla.|



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
