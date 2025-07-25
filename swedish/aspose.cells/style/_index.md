---
title: Style klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1350
url: /sv/aspose.cells/style/
is_root: false
---
##  Style klass
Representerar visningsstilen för Excel-dokumentet, såsom teckensnitt, färg, justering, kantlinje etc.
Objektet Style innehåller alla stilattribut (teckensnitt, talformat, justering och så vidare) som egenskaper.



Typen Style avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [`__init__(self)`](/cells/python-net/sv/aspose.cells/style/__init__/#) | Initierar en ny instans av klassen [`Style`](/cells/python-net/sv/aspose.cells/style).|


###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [background_theme_color](/cells/python-net/sv/aspose.cells/style/background_theme_color) | Hämtar och ställer in bakgrundstemafärgen.|
| [foreground_theme_color](/cells/python-net/sv/aspose.cells/style/foreground_theme_color) | Hämtar och ställer in förgrundstemafärgen.|
| [name](/cells/python-net/sv/aspose.cells/style/name) | Hämtar eller anger namnet på stilen.|
| [pattern](/cells/python-net/sv/aspose.cells/style/pattern) | Hämtar eller anger cellens bakgrundsmönstertyp.|
| [borders](/cells/python-net/sv/aspose.cells/style/borders) | Hämtar [`BorderCollection`](/cells/python-net/sv/aspose.cells/bordercollection) för stilen.|
| [background_color](/cells/python-net/sv/aspose.cells/style/background_color) | Hämtar eller anger en stils bakgrundsfärg.|
| [background_argb_color](/cells/python-net/sv/aspose.cells/style/background_argb_color) | Hämtar och ställer in bakgrundsfärgen med ett 32-bitars ARGB-värde.|
| [foreground_color](/cells/python-net/sv/aspose.cells/style/foreground_color) | Hämtar eller ställer in en stils förgrundsfärg.|
| [foreground_argb_color](/cells/python-net/sv/aspose.cells/style/foreground_argb_color) | Hämtar och ställer in förgrundsfärgen med ett 32-bitars ARGB-värde.|
| [has_borders](/cells/python-net/sv/aspose.cells/style/has_borders) | Kontrollerar om det finns ramar som har angetts för stilen.|
| [parent_style](/cells/python-net/sv/aspose.cells/style/parent_style) | Hämtar den överordnade stilen för den här stilen.|
| [is_number_format_applied](/cells/python-net/sv/aspose.cells/style/is_number_format_applied) | Ange om nummerformateringen ska tillämpas.|
| [is_font_applied](/cells/python-net/sv/aspose.cells/style/is_font_applied) |Ange om teckensnittsformateringen ska tillämpas.|
| [is_alignment_applied](/cells/python-net/sv/aspose.cells/style/is_alignment_applied) | Ange om justeringsformateringen ska tillämpas.|
| [is_border_applied](/cells/python-net/sv/aspose.cells/style/is_border_applied) | Ange om kantformateringen ska tillämpas.|
| [is_fill_applied](/cells/python-net/sv/aspose.cells/style/is_fill_applied) | Ange om fyllningsformateringen ska tillämpas.|
| [is_protection_applied](/cells/python-net/sv/aspose.cells/style/is_protection_applied) | Ange om skyddsformateringen ska tillämpas.|
| [indent_level](/cells/python-net/sv/aspose.cells/style/indent_level) | Representerar indragsnivån för cellen eller området. Kan endast vara ett heltal mellan 0 och 250.|
| [font](/cells/python-net/sv/aspose.cells/style/font) | Hämtar ett [`Style.font`](/cells/python-net/sv/aspose.cells/style#font)-objekt.|
| [rotation_angle](/cells/python-net/sv/aspose.cells/style/rotation_angle) | Representerar textens rotationsvinkel.|
| [horizontal_alignment](/cells/python-net/sv/aspose.cells/style/horizontal_alignment) | Hämtar eller anger den horisontella justeringstypen för texten i en cell.|
| [vertical_alignment](/cells/python-net/sv/aspose.cells/style/vertical_alignment) | Hämtar eller anger den vertikala justeringstypen för texten i en cell.|
| [is_text_wrapped](/cells/python-net/sv/aspose.cells/style/is_text_wrapped) | Hämtar eller anger ett värde som anger om texten i en cell är radbruten.|
| [number](/cells/python-net/sv/aspose.cells/style/number) | Hämtar eller ställer in visningsformatet för siffror och datum. Formateringsmönstren skiljer sig åt för olika regioner.|
| [is_locked](/cells/python-net/sv/aspose.cells/style/is_locked) | Hämtar eller anger ett värde som anger om en cell kan ändras eller inte.|
| [custom](/cells/python-net/sv/aspose.cells/style/custom) | Representerar den anpassade talformatsträngen för detta stilobjekt.<br/>Om det anpassade talformatet inte är inställt (till exempel om talformatet är inbyggt) returneras "".|
| [culture_custom](/cells/python-net/sv/aspose.cells/style/culture_custom) | Hämtar och ställer in den kulturberoende mönstersträngen för talformat.<br/>Om inget talformat har angetts för detta objekt returneras null.<br/> Om talformat är inbyggt returneras mönstersträngen som motsvarar det inbyggda talet.|
| [invariant_custom](/cells/python-net/sv/aspose.cells/style/invariant_custom) | Hämtar den kulturoberoende mönstersträngen för talformat.<br/>Om inget talformat har angetts för detta objekt returneras null.<br/> Om talformat är inbyggt returneras mönstersträngen som motsvarar det inbyggda talet.|
| [is_formula_hidden](/cells/python-net/sv/aspose.cells/style/is_formula_hidden) | Representerar om formeln kommer att döljas när kalkylbladet är skyddat.|
| [shrink_to_fit](/cells/python-net/sv/aspose.cells/style/shrink_to_fit) | Representerar om texten automatiskt krymper för att passa in i den tillgängliga kolumnbredden.|
| [text_direction](/cells/python-net/sv/aspose.cells/style/text_direction) | Representerar textens läsordning.|
| [is_justify_distributed](/cells/python-net/sv/aspose.cells/style/is_justify_distributed) | Anger om cellerna ska vara justerade eller distribuerade på den sista textraden.|
| [quote_prefix](/cells/python-net/sv/aspose.cells/style/quote_prefix) | Anger om cellens värde börjar med ett enkelt citattecken.|
| [is_gradient](/cells/python-net/sv/aspose.cells/style/is_gradient) | Anger om cellskuggningen är ett gradientmönster.|
| [is_percent](/cells/python-net/sv/aspose.cells/style/is_percent) | Anger om talformatet är ett procentformat.|
| [is_date_time](/cells/python-net/sv/aspose.cells/style/is_date_time) | Anger om talformatet är ett datumformat.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`set_border(self, border_type, border_style, border_color)`](/cells/python-net/sv/aspose.cells/style/set_border/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.pydrawing.color) | Anger stilens gränser.|
| [`set_border(self, border_type, border_style, border_color)`](/cells/python-net/sv/aspose.cells/style/set_border/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.cells.cellscolor) | Anger stilens gränser.|
| [`set_pattern_color(self, pattern, color1, color2)`](/cells/python-net/sv/aspose.cells/style/set_pattern_color/#aspose.cells.backgroundtype-aspose.pydrawing.color-aspose.pydrawing.color) |Ställer in bakgrundsfärgen.|
| [`copy(self, style)`](/cells/python-net/sv/aspose.cells/style/copy/#aspose.cells.style) | Kopierar data från ett annat stilobjekt|
| [`update(self)`](/cells/python-net/sv/aspose.cells/style/update/#) | Tillämpa den namngivna stilen på stilarna i de celler som använder den namngivna stilen.<br/>Det fungerar som att klicka på "ok"-knappen efter att du har ändrat stilen.<br/> Gäller endast för namngiven stil.|
| [`is_modified(self, modify_flag)`](/cells/python-net/sv/aspose.cells/style/is_modified/#aspose.cells.stylemodifyflag) | Kontrollerar om de angivna egenskaperna för stilen har ändrats.<br/> Används för stilen för ConditionalFormattings för att kontrollera om de angivna egenskaperna för den här stilen ska användas när ConditionalFormattings tillämpas på en cell.|
| [`set_custom(self, custom, builtin_preference)`](/cells/python-net/sv/aspose.cells/style/set_custom/#str-bool) | Ställer in strängen Anpassat talformat för en cell.|
| [`set_two_color_gradient(self, color1, color2, gradient_style_type, variant)`](/cells/python-net/sv/aspose.cells/style/set_two_color_gradient/#aspose.pydrawing.color-aspose.pydrawing.color-aspose.cells.drawing.gradientstyletype-int) | Ställer in den angivna fyllningen till en tvåfärgad övertoning.|
| [`get_two_color_gradient(self, color1, color2, gradient_style_type, variant)`](/cells/python-net/sv/aspose.cells/style/get_two_color_gradient/#aspose.pydrawing.color&-aspose.pydrawing.color&-any-any) | Hämta inställningen för tvåfärgad gradient.|
| [`get_two_color_gradient_setting(self)`](/cells/python-net/sv/aspose.cells/style/get_two_color_gradient_setting/#) | Hämta inställningen för tvåfärgad gradient.|
| [`to_json(self)`](/cells/python-net/sv/aspose.cells/style/to_json/#) | Konvertera strukturdata från [`Style`](/cells/python-net/sv/aspose.cells/style) till JSON.|



###  Exempel

```python
from aspose.cells import Workbook
from aspose.pydrawing import Color

workbook = Workbook()
sheets = workbook.worksheets
cell = sheets[0].cells.get("A1")
style = cell.get_style()
style.font.name = "Times New Roman"
style.font.color = Color.blue
cell.set_style(style)

```

###  Se även
* modul [`aspose.cells`](..)
* klass [`BorderCollection`](/cells/python-net/sv/aspose.cells/bordercollection)
* klass [`Style`](/cells/python-net/sv/aspose.cells/style)
