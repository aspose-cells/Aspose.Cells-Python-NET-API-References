---
title: Cell klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 140
url: /sv/aspose.cells/cell/
is_root: false
---
##  Cell klass
Kapslar in objektet som representerar en enskild arbetsbokscell.



Typen Cell avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [worksheet](/cells/python-net/sv/aspose.cells/cell/worksheet) |Hämtar föräldrakalkylbladet.|
| [date_time_value](/cells/python-net/sv/aspose.cells/cell/date_time_value) | Hämtar värdet DateTime som finns i cellen.|
| [row](/cells/python-net/sv/aspose.cells/cell/row) | Hämtar radnummer (nollbaserat) för cellen.|
| [column](/cells/python-net/sv/aspose.cells/cell/column) | Hämtar kolumnnummer (nollbaserat) för cellen.|
| [is_formula](/cells/python-net/sv/aspose.cells/cell/is_formula) | Representerar om den angivna cellen innehåller formel.|
| [type](/cells/python-net/sv/aspose.cells/cell/type) | Representerar cellvärdestyp.|
| [name](/cells/python-net/sv/aspose.cells/cell/name) | Får namnet på cellen.|
| [is_error_value](/cells/python-net/sv/aspose.cells/cell/is_error_value) | Kontrollerar om värdet på den här cellen är ett fel.|
| [is_numeric_value](/cells/python-net/sv/aspose.cells/cell/is_numeric_value) | Indikerar om värdet på denna cell är numeriskt (int, double och datetime)|
| [string_value](/cells/python-net/sv/aspose.cells/cell/string_value) | Hämtar strängvärdet som finns i cellen. Om typen av denna cell är sträng, returnera själva strängvärdet.<br/>För andra celltyper kommer det formaterade strängvärdet (formaterat med den angivna stilen för denna cell) att returneras.<br/>Det formaterade cellvärdet är samma som det du kan få från Excel när du kopierar en cell som text (t.ex<br/> kopiera cell till textredigerare eller exportera till csv).|
| [string_value_without_format](/cells/python-net/sv/aspose.cells/cell/string_value_without_format) | Hämtar cellens värde som sträng utan något format.|
| [number_category_type](/cells/python-net/sv/aspose.cells/cell/number_category_type) | Representerar kategoritypen för denna cells nummerformatering.|
| [display_string_value](/cells/python-net/sv/aspose.cells/cell/display_string_value) | Hämtar det formaterade strängvärdet för denna cell efter cells visningsstil.|
| [int_value](/cells/python-net/sv/aspose.cells/cell/int_value) | Hämtar heltalsvärdet som finns i cellen.|
| [double_value](/cells/python-net/sv/aspose.cells/cell/double_value) | Får det dubbla värdet som finns i cellen.|
| [float_value](/cells/python-net/sv/aspose.cells/cell/float_value) | Hämtar flytvärdet som finns i cellen.|
| [bool_value](/cells/python-net/sv/aspose.cells/cell/bool_value) |Hämtar det booleska värdet som finns i cellen.|
| [has_custom_style](/cells/python-net/sv/aspose.cells/cell/has_custom_style) | Indikerar om den här cellen har anpassade stilinställningar (som skiljer sig från standarden som ärvs<br/> från motsvarande rad, kolumn eller arbetsbok).|
| [shared_style_index](/cells/python-net/sv/aspose.cells/cell/shared_style_index) | Hämtar cellens delade stilindex i stilpoolen.|
| [formula](/cells/python-net/sv/aspose.cells/cell/formula) | Hämtar eller ställer in en formel för [`Cell`](/cells/python-net/sv/aspose.cells/cell).|
| [formula_local](/cells/python-net/sv/aspose.cells/cell/formula_local) | Få den språkformaterade formeln för cellen.|
| [r1c1_formula](/cells/python-net/sv/aspose.cells/cell/r1c1_formula) | Hämtar eller ställer in en R1C1-formel för [`Cell`](/cells/python-net/sv/aspose.cells/cell).|
| [contains_external_link](/cells/python-net/sv/aspose.cells/cell/contains_external_link) | Anger om denna cell innehåller en extern länk.<br/> Gäller endast när cellen är en formelcell.|
| [is_array_header](/cells/python-net/sv/aspose.cells/cell/is_array_header) | Indikerar att cellens formel är en matrisformel<br/> och det är den första cellen i arrayen.|
| [is_dynamic_array_formula](/cells/python-net/sv/aspose.cells/cell/is_dynamic_array_formula) | Anger om cellens formel är dynamisk matrisformel (sant) eller äldre matrisformel (falsk).|
| [is_array_formula](/cells/python-net/sv/aspose.cells/cell/is_array_formula) | Anger om cellformeln är en matrisformel.|
| [is_in_array](/cells/python-net/sv/aspose.cells/cell/is_in_array) | Anger om cellformeln är en matrisformel.|
| [is_shared_formula](/cells/python-net/sv/aspose.cells/cell/is_shared_formula) | Anger om cellformeln är en del av delad formel.|
| [is_table_formula](/cells/python-net/sv/aspose.cells/cell/is_table_formula) | Anger om denna cell är en del av tabellformeln.|
| [is_in_table](/cells/python-net/sv/aspose.cells/cell/is_in_table) | Anger om denna cell är en del av tabellformeln.|
| [value](/cells/python-net/sv/aspose.cells/cell/value) | Hämtar/ställer in värdet som finns i den här cellen.|
| [is_style_set](/cells/python-net/sv/aspose.cells/cell/is_style_set) |Indikerar om cellens stil är inställd. Om returnera false betyder det att den här cellen har ett standardcellformat.|
| [is_merged](/cells/python-net/sv/aspose.cells/cell/is_merged) | Kontrollerar om en cell är en del av ett sammanslaget område eller inte.|
| [comment](/cells/python-net/sv/aspose.cells/cell/comment) | Får kommentaren från den här cellen.|
| [html_string](/cells/python-net/sv/aspose.cells/cell/html_string) | Hämtar och ställer in html-strängen som innehåller data och vissa format i denna cell.|
| [embedded_image](/cells/python-net/sv/aspose.cells/cell/embedded_image) | Hämtar och ställer in den inbäddade bilden i cellen.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [put_value](/cells/python-net/sv/aspose.cells/cell/put_value/#bool) | Lägger in ett booleskt värde i cellen.|
| [put_value](/cells/python-net/sv/aspose.cells/cell/put_value/#int) | Lägger in ett heltalsvärde i cellen.|
| [put_value](/cells/python-net/sv/aspose.cells/cell/put_value/#float) | Lägger ett dubbelt värde i cellen.|
| [put_value](/cells/python-net/sv/aspose.cells/cell/put_value/#str-bool-bool) | Lägger ett värde i cellen, om så är lämpligt kommer värdet att konverteras till annan datatyp och cellens talformat återställs.|
| [put_value](/cells/python-net/sv/aspose.cells/cell/put_value/#str-bool) | Lägger in ett strängvärde i cellen och konverterar värdet till en annan datatyp om så är lämpligt.|
| [put_value](/cells/python-net/sv/aspose.cells/cell/put_value/#str) | Lägger ett strängvärde i cellen.|
| [put_value](/cells/python-net/sv/aspose.cells/cell/put_value/#DateTime) | Lägger in ett DateTime-värde i cellen.|
| [put_value](/cells/python-net/sv/aspose.cells/cell/put_value/#any) | Lägger ett objektvärde i cellen.|
| [get_display_style](/cells/python-net/sv/aspose.cells/cell/get_display_style/#) | Hämtar visningsstilen för cellen.<br/>Om den här cellen också påverkas av andra inställningar som villkorlig formatering, listobjekt etc.,<br/>då kan visningsstilen skilja sig från cell.GetStyle().|
| [get_display_style](/cells/python-net/sv/aspose.cells/cell/get_display_style/#bool) | Hämtar visningsstilen för cellen.<br/> Om cellen är villkorligt formaterad är visningsstilen inte samma som cell.GetStyle().|
| [get_style](/cells/python-net/sv/aspose.cells/cell/get_style/#) | Får cellstilen.|
| [get_style](/cells/python-net/sv/aspose.cells/cell/get_style/#bool) | Om checkBorders är sant, kontrollera om andra cellers gränser kommer att påverka stilen för denna cell.|
| [set_style](/cells/python-net/sv/aspose.cells/cell/set_style/#aspose.cells.Style) | Ställer in cellstilen.|
| [set_style](/cells/python-net/sv/aspose.cells/cell/set_style/#aspose.cells.Style-bool) | Tillämpa den ändrade egenskapen för stil på cellen.|
| [set_style](/cells/python-net/sv/aspose.cells/cell/set_style/#aspose.cells.Style-aspose.cells.StyleFlag) | Använd cellformatet baserat på flaggor.|
| [set_formula](/cells/python-net/sv/aspose.cells/cell/set_formula/#str-any) | Ställ in formeln och värdet (beräknat resultat) för formeln.|
| [set_formula](/cells/python-net/sv/aspose.cells/cell/set_formula/#str-bool-bool-any) | Ställ in formeln och värdet på formeln.|
| [set_formula](/cells/python-net/sv/aspose.cells/cell/set_formula/#str-aspose.cells.FormulaParseOptions-any) | Ställ in formeln och värdet (beräknat resultat) för formeln.|
| [set_array_formula](/cells/python-net/sv/aspose.cells/cell/set_array_formula/#str-int-int-bool-bool) | Ställer in en matrisformel till ett cellintervall.|
| [set_array_formula](/cells/python-net/sv/aspose.cells/cell/set_array_formula/#str-int-int) | Ställer in en matrisformel (äldre matrisformel inmatad via CTRL+SHIFT+ENTER i ms excel) till ett cellintervall.|
| [set_array_formula](/cells/python-net/sv/aspose.cells/cell/set_array_formula/#str-int-int-aspose.cells.FormulaParseOptions) | Ställer in en matrisformel till ett cellintervall.|
| [set_array_formula](/cells/python-net/sv/aspose.cells/cell/set_array_formula/#str-int-int-aspose.cells.FormulaParseOptions-list) | Ställer in en matrisformel till ett cellintervall.|
| [set_shared_formula](/cells/python-net/sv/aspose.cells/cell/set_shared_formula/#str-int-int-bool-bool) | Ställer in en formel för ett cellintervall.|
| [set_shared_formula](/cells/python-net/sv/aspose.cells/cell/set_shared_formula/#str-int-int) | Ställer in delade formler till ett cellintervall.|
| [set_shared_formula](/cells/python-net/sv/aspose.cells/cell/set_shared_formula/#str-int-int-aspose.cells.FormulaParseOptions) | Ställer in delade formler till ett cellintervall.|
| [set_shared_formula](/cells/python-net/sv/aspose.cells/cell/set_shared_formula/#str-int-int-aspose.cells.FormulaParseOptions-list) | Ställer in delade formler till ett cellintervall.|
| [get_leafs](/cells/python-net/sv/aspose.cells/cell/get_leafs/#) | Hämta alla celler som refererar till denna cell direkt och behöver uppdateras när den här cellen ändras.|
| [get_leafs](/cells/python-net/sv/aspose.cells/cell/get_leafs/#bool) | Hämta alla celler som kommer att uppdateras när denna cell ändras.|
| [set_dynamic_array_formula](/cells/python-net/sv/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.FormulaParseOptions-bool) |Ställer in dynamisk matrisformel och får formeln att spilla in i närliggande celler om möjligt.|
| [set_dynamic_array_formula](/cells/python-net/sv/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.FormulaParseOptions-list-bool-bool) |Ställer in dynamisk matrisformel och får formeln att spilla in i närliggande celler om möjligt.|
| [set_dynamic_array_formula](/cells/python-net/sv/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.FormulaParseOptions-list-bool-bool-aspose.cells.CalculationOptions) |Ställer in dynamisk matrisformel och får formeln att spilla in i närliggande celler om möjligt.|
| [set_table_formula](/cells/python-net/sv/aspose.cells/cell/set_table_formula/#int-int-str-str-list) | Skapa datatabell med två variabler för ett givet intervall med start från den här cellen.|
| [set_table_formula](/cells/python-net/sv/aspose.cells/cell/set_table_formula/#int-int-str-bool-list) | Skapa datatabell med en variabel för ett givet intervall med start från den här cellen.|
| [set_table_formula](/cells/python-net/sv/aspose.cells/cell/set_table_formula/#int-int-int-int-int-int-list) | Skapa datatabell med två variabler för ett givet intervall med start från den här cellen.|
| [set_table_formula](/cells/python-net/sv/aspose.cells/cell/set_table_formula/#int-int-int-int-bool-list) | Skapa datatabell med en variabel för ett givet intervall med start från den här cellen.|
| [get_characters](/cells/python-net/sv/aspose.cells/cell/get_characters/#) | Returnerar alla teckenobjekt<br/> som representerar ett teckenintervall i celltexten.|
| [get_characters](/cells/python-net/sv/aspose.cells/cell/get_characters/#bool) | Returnerar alla teckenobjekt<br/> som representerar ett teckenintervall i celltexten.|
| [calculate](/cells/python-net/sv/aspose.cells/cell/calculate/#aspose.cells.CalculationOptions) | Beräknar cellens formel.|
| [get_string_value](/cells/python-net/sv/aspose.cells/cell/get_string_value/#aspose.cells.CellValueFormatStrategy) | Hämtar strängvärdet efter specifik formaterad strategi.|
| [get_width_of_value](/cells/python-net/sv/aspose.cells/cell/get_width_of_value/#) | Hämtar bredden på värdet i enhet pixlar.|
| [get_height_of_value](/cells/python-net/sv/aspose.cells/cell/get_height_of_value/#) | Hämtar höjden på värdet i enhet pixlar.|
| [get_format_conditions](/cells/python-net/sv/aspose.cells/cell/get_format_conditions/#) | Hämtar formatvillkor som gäller för denna cell.|
| [get_formula](/cells/python-net/sv/aspose.cells/cell/get_formula/#bool-bool) | Få formeln för denna cell.|
| [get_precedents](/cells/python-net/sv/aspose.cells/cell/get_precedents/#) | Hämtar alla referenser som visas i den här cellens formel.|
| [get_dependents](/cells/python-net/sv/aspose.cells/cell/get_dependents/#bool) | Hämta alla celler vars formel refererar till den här cellen direkt.|
| [get_precedents_in_calculation](/cells/python-net/sv/aspose.cells/cell/get_precedents_in_calculation/#) | Hämtar alla prejudikat (referens till celler i aktuell arbetsbok) som används av denna cells formel när den beräknas.|
| [get_dependents_in_calculation](/cells/python-net/sv/aspose.cells/cell/get_dependents_in_calculation/#bool) | Hämtar alla celler vars beräknade resultat beror på denna cell.|
| [get_array_range](/cells/python-net/sv/aspose.cells/cell/get_array_range/#) |Hämtar matrisintervallet om cellens formel är en matrisformel.|
| [remove_array_formula](/cells/python-net/sv/aspose.cells/cell/remove_array_formula/#bool) | Ta bort matrisformel.|
| [copy](/cells/python-net/sv/aspose.cells/cell/copy/#aspose.cells.Cell) | Kopierar data från en källcell.|
| [characters](/cells/python-net/sv/aspose.cells/cell/characters/#int-int) | Returnerar ett teckenobjekt som representerar ett teckenintervall i celltexten.|
| [replace](/cells/python-net/sv/aspose.cells/cell/replace/#str-str-aspose.cells.ReplaceOptions) | Ersätt texten i cellen med alternativ.|
| [insert_text](/cells/python-net/sv/aspose.cells/cell/insert_text/#int-str) | Infoga några tecken i cellen.<br/> Om cellen är rikt formaterad kan den här metoden behålla den ursprungliga formateringen.|
| [is_rich_text](/cells/python-net/sv/aspose.cells/cell/is_rich_text/#) | Anger om strängvärdet för den här cellen är en rikt formaterad text.|
| [set_characters](/cells/python-net/sv/aspose.cells/cell/set_characters/#list) | Ställer in RTF-format för cellen.|
| [get_merged_range](/cells/python-net/sv/aspose.cells/cell/get_merged_range/#) | Returnerar ett [`Range`](/cells/python-net/sv/aspose.cells/range)-objekt som representerar ett sammanslaget intervall.|
| [get_html_string](/cells/python-net/sv/aspose.cells/cell/get_html_string/#bool) | Hämtar html-strängen som innehåller data och vissa format i denna cell.|
| [to_json](/cells/python-net/sv/aspose.cells/cell/to_json/#) | Konvertera [`Cell`](/cells/python-net/sv/aspose.cells/cell) till JSON strukturdata.|
| [equals](/cells/python-net/sv/aspose.cells/cell/equals/#aspose.cells.Cell) | Kontrollerar om detta objekt refererar till samma cell med ett annat cellobjekt.|
| [get_conditional_formatting_result](/cells/python-net/sv/aspose.cells/cell/get_conditional_formatting_result/#) | Få resultatet av den villkorliga formateringen.|
| [get_validation](/cells/python-net/sv/aspose.cells/cell/get_validation/#) | Får valideringen tillämpad på den här cellen.|
| [get_validation_value](/cells/python-net/sv/aspose.cells/cell/get_validation_value/#) | Hämtar värdet av validering som gällde för den här cellen.|
| [get_table](/cells/python-net/sv/aspose.cells/cell/get_table/#) |Hämtar tabellen som innehåller denna cell.|



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
