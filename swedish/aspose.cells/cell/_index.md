---
title: Cell klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 110
url: /sv/aspose.cells/cell/
is_root: false
---
##  Cell klass
Inkapslar objektet som representerar en enskild arbetsbokscell.



Typen Cell avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [worksheet](/cells/python-net/sv/aspose.cells/cell/worksheet) | Hämtar det överordnade arbetsbladet.|
| [date_time_value](/cells/python-net/sv/aspose.cells/cell/date_time_value) | Hämtar DateTime-värdet som finns i cellen.|
| [row](/cells/python-net/sv/aspose.cells/cell/row) | Hämtar radnummer (nollbaserat) för cellen.|
| [column](/cells/python-net/sv/aspose.cells/cell/column) | Hämtar kolumnnumret (nollbaserat) för cellen.|
| [is_formula](/cells/python-net/sv/aspose.cells/cell/is_formula) | Representerar om den angivna cellen innehåller en formel.|
| [has_custom_function](/cells/python-net/sv/aspose.cells/cell/has_custom_function) |Kontrollerar om det finns en anpassad funktion (en funktion som inte stöds) i den här cellens formel.|
| [type](/cells/python-net/sv/aspose.cells/cell/type) | Representerar cellvärdestypen.|
| [name](/cells/python-net/sv/aspose.cells/cell/name) | Hämtar cellens namn.|
| [is_error_value](/cells/python-net/sv/aspose.cells/cell/is_error_value) | Kontrollerar om värdet i den här cellen är ett fel.|
| [is_numeric_value](/cells/python-net/sv/aspose.cells/cell/is_numeric_value) | Anger om värdet i den här cellen är numeriskt (int, double och datetime)|
| [string_value](/cells/python-net/sv/aspose.cells/cell/string_value) | Hämtar strängvärdet som finns i cellen. Om cellens typ är sträng returneras själva strängvärdet.<br/>För andra celltyper returneras det formaterade strängvärdet (formaterat med den angivna stilen för den här cellen).<br/>Det formaterade cellvärdet är samma som det du kan få från Excel när du kopierar en cell som text (t.ex.<br/> kopiera cell till textredigeraren eller exportera till csv).|
| [string_value_without_format](/cells/python-net/sv/aspose.cells/cell/string_value_without_format) | Hämtar cellens värde som en sträng utan format.|
| [number_category_type](/cells/python-net/sv/aspose.cells/cell/number_category_type) | Representerar kategoritypen för den här cellens talformatering.|
| [display_string_value](/cells/python-net/sv/aspose.cells/cell/display_string_value) | Hämtar det formaterade strängvärdet för den här cellen efter cellens visningsstil.|
| [int_value](/cells/python-net/sv/aspose.cells/cell/int_value) | Hämtar heltalsvärdet som finns i cellen.|
| [double_value](/cells/python-net/sv/aspose.cells/cell/double_value) | Hämtar det dubbla värdet som finns i cellen.|
| [float_value](/cells/python-net/sv/aspose.cells/cell/float_value) | Hämtar flyttalsvärdet i cellen.|
| [bool_value](/cells/python-net/sv/aspose.cells/cell/bool_value) | Hämtar det booleska värdet som finns i cellen.|
| [has_custom_style](/cells/python-net/sv/aspose.cells/cell/has_custom_style) | Anger om den här cellen har anpassade stilinställningar (skiljer sig från den standardinställda som ärvs<br/>från motsvarande rad, kolumn eller arbetsbok).|
| [shared_style_index](/cells/python-net/sv/aspose.cells/cell/shared_style_index) | Hämtar cellens delade stilindex i stilpoolen.|
| [formula](/cells/python-net/sv/aspose.cells/cell/formula) | Hämtar eller ställer in en formel för [`Cell`](/cells/python-net/sv/aspose.cells/cell).|
| [formula_local](/cells/python-net/sv/aspose.cells/cell/formula_local) | Hämta cellens språkformaterade formel.|
| [r1c1_formula](/cells/python-net/sv/aspose.cells/cell/r1c1_formula) | Hämtar eller ställer in en R1C1-formel för [`Cell`](/cells/python-net/sv/aspose.cells/cell).|
| [contains_external_link](/cells/python-net/sv/aspose.cells/cell/contains_external_link) | Anger om den här cellen innehåller en extern länk.<br/> Gäller endast när cellen är en formelcell.|
| [is_array_header](/cells/python-net/sv/aspose.cells/cell/is_array_header) | Indikerar att cellens formel är en matrisformel<br/> och det är den första cellen i arrayen.|
| [is_dynamic_array_formula](/cells/python-net/sv/aspose.cells/cell/is_dynamic_array_formula) | Anger om cellens formel är en dynamisk arrayformel (sant) eller en äldre arrayformel (falskt).|
| [is_array_formula](/cells/python-net/sv/aspose.cells/cell/is_array_formula) | Anger om cellformeln är en matrisformel.|
| [is_in_array](/cells/python-net/sv/aspose.cells/cell/is_in_array) | Anger om cellformeln är en matrisformel.|
| [is_shared_formula](/cells/python-net/sv/aspose.cells/cell/is_shared_formula) | Anger om cellformeln är en del av en delad formel.|
| [is_table_formula](/cells/python-net/sv/aspose.cells/cell/is_table_formula) | Anger om den här cellen är en del av tabellformeln.|
| [is_in_table](/cells/python-net/sv/aspose.cells/cell/is_in_table) | Anger om den här cellen är en del av tabellformeln.|
| [value](/cells/python-net/sv/aspose.cells/cell/value) | Hämtar/ställer in värdet i den här cellen.|
| [is_style_set](/cells/python-net/sv/aspose.cells/cell/is_style_set) | Anger om cellens format är angivet. Om returvärdet returneras falskt betyder det att cellen har ett standardcellformat.|
| [is_merged](/cells/python-net/sv/aspose.cells/cell/is_merged) | Kontrollerar om en cell är en del av ett sammanfogat område eller inte.|
| [comment](/cells/python-net/sv/aspose.cells/cell/comment) |Hämtar kommentaren för den här cellen.|
| [html_string](/cells/python-net/sv/aspose.cells/cell/html_string) | Hämtar och anger html-strängen som innehåller data och vissa format i den här cellen.|
| [is_check_box_style](/cells/python-net/sv/aspose.cells/cell/is_check_box_style) | Anger om den här cellen är markerad som en kryssruta.|
| [embedded_image](/cells/python-net/sv/aspose.cells/cell/embedded_image) | Hämtar och ställer in den inbäddade bilden i cellen.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`put_value(self, bool_value)`](/cells/python-net/sv/aspose.cells/cell/put_value/#bool) | Lägger in ett booleskt värde i cellen.|
| [`put_value(self, int_value)`](/cells/python-net/sv/aspose.cells/cell/put_value/#int) | Lägger in ett heltal i cellen.|
| [`put_value(self, double_value)`](/cells/python-net/sv/aspose.cells/cell/put_value/#float) | Lägger in ett dubbelt värde i cellen.|
| [`put_value(self, string_value, is_converted, set_style)`](/cells/python-net/sv/aspose.cells/cell/put_value/#str-bool-bool) | Lägger in ett värde i cellen. Om det är lämpligt konverteras värdet till en annan datatyp och cellens talformat återställs.|
| [`put_value(self, string_value, is_converted)`](/cells/python-net/sv/aspose.cells/cell/put_value/#str-bool) | Lägger in ett strängvärde i cellen och konverterar värdet till en annan datatyp om det är lämpligt.|
| [`put_value(self, string_value)`](/cells/python-net/sv/aspose.cells/cell/put_value/#str) | Lägger in ett strängvärde i cellen.|
| [`put_value(self, date_time)`](/cells/python-net/sv/aspose.cells/cell/put_value/#datetime) | Lägger in ett DateTime-värde i cellen.|
| [`put_value(self, object_value)`](/cells/python-net/sv/aspose.cells/cell/put_value/#any) | Lägger in ett objektvärde i cellen.|
| [`get_display_style(self)`](/cells/python-net/sv/aspose.cells/cell/get_display_style/#) | Hämtar visningsstilen för den här cellen.|
| [`get_display_style(self, include_merged_borders)`](/cells/python-net/sv/aspose.cells/cell/get_display_style/#bool) | Hämtar visningsstilen för den här cellen.|
| [`get_display_style(self, adjacent_borders)`](/cells/python-net/sv/aspose.cells/cell/get_display_style/#aspose.cells.bordertype) | Hämtar visningsstilen för den här cellen.|
| [`get_style(self)`](/cells/python-net/sv/aspose.cells/cell/get_style/#) | Hämtar cellstilen.|
| [`get_style(self, check_borders)`](/cells/python-net/sv/aspose.cells/cell/get_style/#bool) | Om checkBorders är sant, kontrollera om andra cellers kantlinjer påverkar cellens stil.|
| [`set_style(self, style)`](/cells/python-net/sv/aspose.cells/cell/set_style/#aspose.cells.style) | Ställer in cellstilen.|
| [`set_style(self, style, explicit_flag)`](/cells/python-net/sv/aspose.cells/cell/set_style/#aspose.cells.style-bool) | Tillämpa den ändrade egenskapen för stil på cellen.|
| [`set_style(self, style, flag)`](/cells/python-net/sv/aspose.cells/cell/set_style/#aspose.cells.style-aspose.cells.styleflag) |Tillämpa cellstilen baserat på flaggor.|
| [`set_formula(self, formula, value)`](/cells/python-net/sv/aspose.cells/cell/set_formula/#str-any) | Ställ in formeln och värdet (beräknat resultat) för formeln.|
| [`set_formula(self, formula, options)`](/cells/python-net/sv/aspose.cells/cell/set_formula/#str-aspose.cells.formulaparseoptions) | Ställ in formeln och värdet (beräknat resultat) för formeln.|
| [`set_formula(self, formula, is_r1c1, is_local, value)`](/cells/python-net/sv/aspose.cells/cell/set_formula/#str-bool-bool-any) | Ange formeln och formelns värde.|
| [`set_formula(self, formula, options, value)`](/cells/python-net/sv/aspose.cells/cell/set_formula/#str-aspose.cells.formulaparseoptions-any) | Ställ in formeln och värdet (beräknat resultat) för formeln.|
| [`set_array_formula(self, array_formula, row_number, column_number, is_r1c1, is_local)`](/cells/python-net/sv/aspose.cells/cell/set_array_formula/#str-int-int-bool-bool) | Ställer in en matrisformel för ett cellområde.|
| [`set_array_formula(self, array_formula, row_number, column_number)`](/cells/python-net/sv/aspose.cells/cell/set_array_formula/#str-int-int) | Ställer in en arrayformel (en äldre arrayformel som anges via CTRL+SHIFT+ENTER i MS Excel) till ett cellområde.|
| [`set_array_formula(self, array_formula, row_number, column_number, options)`](/cells/python-net/sv/aspose.cells/cell/set_array_formula/#str-int-int-aspose.cells.formulaparseoptions) | Ställer in en matrisformel för ett cellområde.|
| [`set_array_formula(self, array_formula, row_number, column_number, options, values)`](/cells/python-net/sv/aspose.cells/cell/set_array_formula/#str-int-int-aspose.cells.formulaparseoptions-list) | Ställer in en matrisformel för ett cellområde.|
| [`set_shared_formula(self, shared_formula, row_number, column_number, is_r1c1, is_local)`](/cells/python-net/sv/aspose.cells/cell/set_shared_formula/#str-int-int-bool-bool) | Ställer in en formel för ett cellområde.|
| [`set_shared_formula(self, shared_formula, row_number, column_number)`](/cells/python-net/sv/aspose.cells/cell/set_shared_formula/#str-int-int) | Ställer in delade formler till ett cellområde.|
| [`set_shared_formula(self, shared_formula, row_number, column_number, options)`](/cells/python-net/sv/aspose.cells/cell/set_shared_formula/#str-int-int-aspose.cells.formulaparseoptions) | Ställer in delade formler till ett cellområde.|
| [`set_shared_formula(self, shared_formula, row_number, column_number, options, values)`](/cells/python-net/sv/aspose.cells/cell/set_shared_formula/#str-int-int-aspose.cells.formulaparseoptions-list) | Ställer in delade formler till ett cellområde.|
| [`get_leafs(self)`](/cells/python-net/sv/aspose.cells/cell/get_leafs/#) | Hämta alla celler som refererar direkt till den här cellen och behöver uppdateras när cellen ändras.|
| [`get_leafs(self, recursive)`](/cells/python-net/sv/aspose.cells/cell/get_leafs/#bool) | Hämta alla celler som kommer att uppdateras när den här cellen ändras.|
| [`set_dynamic_array_formula(self, array_formula, options, calculate_value)`](/cells/python-net/sv/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.formulaparseoptions-bool) | Ställer in dynamisk matrisformel och får formeln att spillas ut i angränsande celler om möjligt.|
| [`set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value)`](/cells/python-net/sv/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.formulaparseoptions-list-bool-bool) | Ställer in dynamisk matrisformel och får formeln att spillas ut i angränsande celler om möjligt.|
| [`set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value, copts)`](/cells/python-net/sv/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.formulaparseoptions-list-bool-bool-aspose.cells.calculationoptions) | Ställer in dynamisk matrisformel och får formeln att spillas ut i angränsande celler om möjligt.|
| [`set_table_formula(self, row_number, column_number, row_input_cell, column_input_cell, values)`](/cells/python-net/sv/aspose.cells/cell/set_table_formula/#int-int-str-str-list) | Skapa en datatabell med två variabler för ett givet område med början från den här cellen.|
| [`set_table_formula(self, row_number, column_number, input_cell, is_row_input, values)`](/cells/python-net/sv/aspose.cells/cell/set_table_formula/#int-int-str-bool-list) | Skapa en variabel datatabell för ett givet område med början från den här cellen.|
| [`set_table_formula(self, row_number, column_number, row_index_of_row_input_cell, column_index_of_row_input_cell, row_index_of_column_input_cell, column_index_of_column_input_cell, values)`](/cells/python-net/sv/aspose.cells/cell/set_table_formula/#int-int-int-int-int-int-list) | Skapa en datatabell med två variabler för ett givet område med början från den här cellen.|
| [`set_table_formula(self, row_number, column_number, row_index_of_input_cell, column_index_of_input_cell, is_row_input, values)`](/cells/python-net/sv/aspose.cells/cell/set_table_formula/#int-int-int-int-bool-list) | Skapa en variabel datatabell för ett givet område med början från den här cellen.|
| [`get_characters(self)`](/cells/python-net/sv/aspose.cells/cell/get_characters/#) | Returnerar alla Characters-objekt<br/> som representerar ett teckenintervall i celltexten.|
| [`get_characters(self, flag)`](/cells/python-net/sv/aspose.cells/cell/get_characters/#bool) | Returnerar alla Characters-objekt<br/> som representerar ett teckenintervall i celltexten.|
| [`calculate(self, options)`](/cells/python-net/sv/aspose.cells/cell/calculate/#aspose.cells.calculationoptions) | Beräknar cellens formel.|
| [`get_string_value(self, format_strategy)`](/cells/python-net/sv/aspose.cells/cell/get_string_value/#aspose.cells.cellvalueformatstrategy) |Hämtar strängvärdet med en specifik formaterad strategi.|
| [`get_width_of_value(self)`](/cells/python-net/sv/aspose.cells/cell/get_width_of_value/#) | Hämtar värdets bredd i pixlar.|
| [`get_height_of_value(self)`](/cells/python-net/sv/aspose.cells/cell/get_height_of_value/#) | Hämtar höjden på värdet i pixlar.|
| [`get_format_conditions(self)`](/cells/python-net/sv/aspose.cells/cell/get_format_conditions/#) | Hämtar formatvillkor som gäller för den här cellen.|
| [`get_formula(self, is_r1c1, is_local)`](/cells/python-net/sv/aspose.cells/cell/get_formula/#bool-bool) | Hämta formeln för den här cellen.|
| [`get_precedents(self)`](/cells/python-net/sv/aspose.cells/cell/get_precedents/#) | Hämtar alla referenser som visas i den här cellens formel.|
| [`get_dependents(self, is_all)`](/cells/python-net/sv/aspose.cells/cell/get_dependents/#bool) | Hämta alla celler vars formel refererar direkt till den här cellen.|
| [`get_precedents_in_calculation(self)`](/cells/python-net/sv/aspose.cells/cell/get_precedents_in_calculation/#) | Hämtar alla prejudikat (referens till celler i den aktuella arbetsboken) som används av den här cellens formel vid beräkning.|
| [`get_dependents_in_calculation(self, recursive)`](/cells/python-net/sv/aspose.cells/cell/get_dependents_in_calculation/#bool) | Hämtar alla celler vars beräknade resultat är beroende av denna cell.|
| [`get_array_range(self)`](/cells/python-net/sv/aspose.cells/cell/get_array_range/#) | Hämtar arrayområdet om cellens formel är en arrayformel.|
| [`remove_array_formula(self, leave_normal_formula)`](/cells/python-net/sv/aspose.cells/cell/remove_array_formula/#bool) | Ta bort arrayformeln.|
| [`copy(self, cell)`](/cells/python-net/sv/aspose.cells/cell/copy/#aspose.cells.cell) | Kopierar data från en källcell.|
| [`characters(self, start_index, length)`](/cells/python-net/sv/aspose.cells/cell/characters/#int-int) | Returnerar ett Characters-objekt som representerar ett teckenintervall i celltexten.|
| [`replace(self, place_holder, new_value, options)`](/cells/python-net/sv/aspose.cells/cell/replace/#str-str-aspose.cells.replaceoptions) | Ersätt cellens text med alternativ.|
| [`insert_text(self, index, text)`](/cells/python-net/sv/aspose.cells/cell/insert_text/#int-str) | Infoga några tecken i cellen.<br/> Om cellen är rikt formaterad kan den här metoden behålla den ursprungliga formateringen.|
| [`is_rich_text(self)`](/cells/python-net/sv/aspose.cells/cell/is_rich_text/#) |Anger om strängvärdet i den här cellen är en rikt formaterad text.|
| [`set_characters(self, characters)`](/cells/python-net/sv/aspose.cells/cell/set_characters/#list) | Ställer in cellens RTF-format.|
| [`get_merged_range(self)`](/cells/python-net/sv/aspose.cells/cell/get_merged_range/#) | Returnerar ett [`Range`](/cells/python-net/sv/aspose.cells/range)-objekt som representerar ett sammanfogat område.|
| [`get_html_string(self, html5)`](/cells/python-net/sv/aspose.cells/cell/get_html_string/#bool) | Hämtar html-strängen som innehåller data och vissa format i den här cellen.|
| [`to_json(self)`](/cells/python-net/sv/aspose.cells/cell/to_json/#) | Konvertera strukturdata från [`Cell`](/cells/python-net/sv/aspose.cells/cell) till JSON.|
| [`equals(self, cell)`](/cells/python-net/sv/aspose.cells/cell/equals/#aspose.cells.cell) | Kontrollerar om det här objektet refererar till samma cell med ett annat cellobjekt.|
| [`get_conditional_formatting_result(self)`](/cells/python-net/sv/aspose.cells/cell/get_conditional_formatting_result/#) | Hämta resultatet av den villkorliga formateringen.|
| [`get_validation(self)`](/cells/python-net/sv/aspose.cells/cell/get_validation/#) | Hämtar valideringen tillämpad på den här cellen.|
| [`get_validation_value(self)`](/cells/python-net/sv/aspose.cells/cell/get_validation_value/#) | Hämtar valideringsvärdet som tillämpades på den här cellen.|
| [`get_table(self)`](/cells/python-net/sv/aspose.cells/cell/get_table/#) | Hämtar tabellen som innehåller den här cellen.|
| [`get_rich_value(self)`](/cells/python-net/sv/aspose.cells/cell/get_rich_value/#) | Får ett rikt värde av cellen.|



###  Exempel

```python
from aspose.cells import TextAlignmentType, Workbook
from aspose.pydrawing import Color

excel = Workbook()
cells = excel.worksheets[0].cells
# Put a string into a cell
cell = cells.get(0, 0)
cell.put_value("Hello")
first = cell.string_value
# Put an integer into a cell
cell = cells.get("B1")
cell.put_value(12)
second = cell.int_value
# Put a double into a cell
cell = cells.get(0, 2)
cell.put_value(-1.234)
third = cell.double_value
# Put a formula into a cell
cell = cells.get("D1")
cell.formula = "=B1 + C1"
# Put a combined formula: "sum(average(b1,c1), b1)" to cell at b2
cell = cells.get("b2")
cell.formula = "=sum(average(b1,c1), b1)"
# Set style of a cell
style = cell.get_style()
# Set background color
style.background_color = Color.yellow
# Set format of a cell
style.font.name = "Courier New"
style.vertical_alignment = TextAlignmentType.TOP
cell.set_style(style)

```

###  Se även
* modul [`aspose.cells`](..)
* klass [`Cell`](/cells/python-net/sv/aspose.cells/cell)
* klass [`Range`](/cells/python-net/sv/aspose.cells/range)
