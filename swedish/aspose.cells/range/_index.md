---
title: Range klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1180
url: /sv/aspose.cells/range/
is_root: false
---
##  Range klass
Inkapslar objektet som representerar ett cellområde i ett kalkylblad.



Typen Range avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [current_region](/cells/python-net/sv/aspose.cells/range/current_region) | Returnerar ett Range-objekt som representerar den aktuella regionen.<br/> Den aktuella regionen är ett område som begränsas av en valfri kombination av tomma rader och tomma kolumner.|
| [hyperlinks](/cells/python-net/sv/aspose.cells/range/hyperlinks) | Hämtar alla hyperlänkar inom intervallet.|
| [row_count](/cells/python-net/sv/aspose.cells/range/row_count) | Hämtar antalet rader i intervallet.|
| [column_count](/cells/python-net/sv/aspose.cells/range/column_count) | Hämtar antalet kolumner i intervallet.|
| [name](/cells/python-net/sv/aspose.cells/range/name) | Hämtar eller anger namnet på intervallet.|
| [refers_to](/cells/python-net/sv/aspose.cells/range/refers_to) | Hämtar intervallet som refererar till.|
| [address](/cells/python-net/sv/aspose.cells/range/address) | Hämtar adressen för intervallet.|
| [left](/cells/python-net/sv/aspose.cells/range/left) | Hämtar avståndet, i punkter, från den vänstra kanten av kolumn A till den vänstra kanten av intervallet.|
| [top](/cells/python-net/sv/aspose.cells/range/top) | Hämtar avståndet, i punkter, från den övre kanten av rad 1 till den övre kanten av intervallet.|
| [width](/cells/python-net/sv/aspose.cells/range/width) | Hämtar bredden på ett intervall i punkter.|
| [height](/cells/python-net/sv/aspose.cells/range/height) | Hämtar bredden på ett intervall i punkter.|
| [first_row](/cells/python-net/sv/aspose.cells/range/first_row) | Hämtar indexet för den första raden i intervallet.|
| [first_column](/cells/python-net/sv/aspose.cells/range/first_column) | Hämtar indexet för den första kolumnen i intervallet.|
| [value](/cells/python-net/sv/aspose.cells/range/value) | Hämtar och ställer in värdet för intervallet.|
| [column_width](/cells/python-net/sv/aspose.cells/range/column_width) | Anger eller hämtar kolumnbredden för detta område|
| [row_height](/cells/python-net/sv/aspose.cells/range/row_height) | Anger eller hämtar höjden på raderna i detta intervall|
| [entire_column](/cells/python-net/sv/aspose.cells/range/entire_column) |Hämtar ett Range-objekt som representerar hela kolumnen (eller kolumnerna) som innehåller det angivna området.|
| [entire_row](/cells/python-net/sv/aspose.cells/range/entire_row) | Hämtar ett Range-objekt som representerar hela raden (eller raderna) som innehåller det angivna området.|
| [worksheet](/cells/python-net/sv/aspose.cells/range/worksheet) | Hämtar [`Range.worksheet`](/cells/python-net/sv/aspose.cells/range#worksheet)-objektet som innehåller detta intervall.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`auto_fill(self, target)`](/cells/python-net/sv/aspose.cells/range/auto_fill/#aspose.cells.range) | Fyll automatiskt målintervallet.|
| [`auto_fill(self, target, auto_fill_type)`](/cells/python-net/sv/aspose.cells/range/auto_fill/#aspose.cells.range-aspose.cells.autofilltype) | Fyll automatiskt målintervallet.|
| [`set_style(self, style, explicit_flag)`](/cells/python-net/sv/aspose.cells/range/set_style/#aspose.cells.style-bool) | Tillämpa cellstilen.|
| [`set_style(self, style)`](/cells/python-net/sv/aspose.cells/range/set_style/#aspose.cells.style) | Anger stilen för intervallet.|
| [`set_outline_borders(self, border_style, border_color)`](/cells/python-net/sv/aspose.cells/range/set_outline_borders/#aspose.cells.cellbordertype-aspose.cells.cellscolor) | Ställer in konturkanterna runt ett cellområde med samma kantstil och färg.|
| [`set_outline_borders(self, border_style, border_color)`](/cells/python-net/sv/aspose.cells/range/set_outline_borders/#aspose.cells.cellbordertype-aspose.pydrawing.color) | Ställer in konturkanterna runt ett cellområde med samma kantstil och färg.|
| [`set_outline_borders(self, border_styles, border_colors)`](/cells/python-net/sv/aspose.cells/range/set_outline_borders/#list-aspose.pydrawing.color[]) | Anger linjekanter runt ett cellområde.|
| [`set_outline_border(self, border_edge, border_style, border_color)`](/cells/python-net/sv/aspose.cells/range/set_outline_border/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.cells.cellscolor) | Anger en kantlinje runt ett cellområde.|
| [`set_outline_border(self, border_edge, border_style, border_color)`](/cells/python-net/sv/aspose.cells/range/set_outline_border/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.pydrawing.color) | Anger en kantlinje runt ett cellområde.|
| [`copy(self, range, options)`](/cells/python-net/sv/aspose.cells/range/copy/#aspose.cells.range-aspose.cells.pasteoptions) | Kopiera intervallet med specialinställningar för klistra in.|
| [`copy(self, range)`](/cells/python-net/sv/aspose.cells/range/copy/#aspose.cells.range) | Kopierar data (inklusive formler), formatering, ritobjekt etc. från ett källområde.|
| [`add_hyperlink(self, address, text_to_display, screen_tip)`](/cells/python-net/sv/aspose.cells/range/add_hyperlink/#str-str-str) | Lägger till en hyperlänk till en angiven cell eller ett cellområde.|
| [`is_intersect(self, range)`](/cells/python-net/sv/aspose.cells/range/is_intersect/#aspose.cells.range) | Anger om intervallet är ett skärningspunkt.|
| [`intersect(self, range)`](/cells/python-net/sv/aspose.cells/range/intersect/#aspose.cells.range) | Returnerar ett [`Range`](/cells/python-net/sv/aspose.cells/range)-objekt som representerar den rektangulära skärningspunkten mellan två områden.|
| [`union_rang(self, range)`](/cells/python-net/sv/aspose.cells/range/union_rang/#aspose.cells.range) | Returnerar unionsresultatet av två områden.|
| [`union_ranges(self, ranges)`](/cells/python-net/sv/aspose.cells/range/union_ranges/#list) | Returnerar unionsresultatet av två områden.|
| [`union(self, range)`](/cells/python-net/sv/aspose.cells/range/union/#aspose.cells.range) | Returnerar unionen av två områden.|
| [`is_blank(self)`](/cells/python-net/sv/aspose.cells/range/is_blank/#) | Anger om intervallet innehåller värden.|
| [`merge(self)`](/cells/python-net/sv/aspose.cells/range/merge/#) |Kombinerar ett cellområde till en enda cell.|
| [`un_merge(self)`](/cells/python-net/sv/aspose.cells/range/un_merge/#) | Avlägsnar sammanslagna celler i detta område.|
| [`put_value(self, string_value, is_converted, set_style)`](/cells/python-net/sv/aspose.cells/range/put_value/#str-bool-bool) | Lägger in ett värde i intervallet. Om lämpligt konverteras värdet till en annan datatyp och cellens talformat återställs.|
| [`apply_style(self, style, flag)`](/cells/python-net/sv/aspose.cells/range/apply_style/#aspose.cells.style-aspose.cells.styleflag) | Tillämpar format för ett helt intervall.|
| [`set_inside_borders(self, border_edge, line_style, border_color)`](/cells/python-net/sv/aspose.cells/range/set_inside_borders/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.cells.cellscolor) | Ställ in innanför intervallets gränser.|
| [`move_to(self, dest_row, dest_column)`](/cells/python-net/sv/aspose.cells/range/move_to/#int-int) | Flytta det aktuella området till målområdet.|
| [`copy_data(self, range)`](/cells/python-net/sv/aspose.cells/range/copy_data/#aspose.cells.range) | Kopierar celldata (inklusive formler) från ett källområde.|
| [`copy_value(self, range)`](/cells/python-net/sv/aspose.cells/range/copy_value/#aspose.cells.range) | Kopierar cellvärde från ett källområde.|
| [`copy_style(self, range)`](/cells/python-net/sv/aspose.cells/range/copy_style/#aspose.cells.range) | Kopierar stilinställningar från ett källintervall.|
| [`transpose(self)`](/cells/python-net/sv/aspose.cells/range/transpose/#) | Transponera (rotera) data från rader till kolumner eller vice versa.|
| [`get(self, row_offset, column_offset)`](/cells/python-net/sv/aspose.cells/range/get/#int-int) | Lägg till API for Python Via .Net. eftersom detta[int, int] inte stöds.|
| [`get_cell_or_null(self, row_offset, column_offset)`](/cells/python-net/sv/aspose.cells/range/get_cell_or_null/#int-int) | Hämtar [`Cell`](/cells/python-net/sv/aspose.cells/cell)-objektet eller null i detta intervall.|
| [`get_offset(self, row_offset, column_offset)`](/cells/python-net/sv/aspose.cells/range/get_offset/#int-int) | Hämtar intervallet [`Range`](/cells/python-net/sv/aspose.cells/range) via offset.|
| [`to_image(self, options)`](/cells/python-net/sv/aspose.cells/range/to_image/#aspose.cells.rendering.imageorprintoptions) | Konverterar intervallet till bild.|
| [`to_json(self, options)`](/cells/python-net/sv/aspose.cells/range/to_json/#aspose.cells.jsonsaveoptions) | Konvertera intervallet till värdet JSON.|
| [`to_html(self, save_options)`](/cells/python-net/sv/aspose.cells/range/to_html/#aspose.cells.htmlsaveoptions) | Konvertera intervallet till html.|
| [`clear(self)`](/cells/python-net/sv/aspose.cells/range/clear/#) | Rensar detta intervall.|
| [`clear_contents(self)`](/cells/python-net/sv/aspose.cells/range/clear_contents/#) | Rensar innehållet i detta intervall.|
| [`clear_formats(self)`](/cells/python-net/sv/aspose.cells/range/clear_formats/#) | Rensar formaten för detta intervall.|
| [`clear_comments(self)`](/cells/python-net/sv/aspose.cells/range/clear_comments/#) | Rensar kommentarerna för det här intervallet.|
| [`clear_hyperlinks(self, clear_format)`](/cells/python-net/sv/aspose.cells/range/clear_hyperlinks/#bool) | Tar bara bort hyperlänkar.|



###  Anmärkningar

Klassen Range betecknar ett område i ett Excel-kalkylblad.
Med detta kan du formatera och ange värde för intervallet.
Och du kan helt enkelt kopiera ett Excel-område också.

###  Exempel

Följande exempel visar hur man skapar ett område och anger ett värde för området i Excel.

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Get the first Worksheet Cells.
cells = workbook.worksheets[0].cells
#  Create a range (A1:D3).
range = cells.create_range("A1", "D3")
#  Set value to the range.
range.value = "Hello"
# Save the Excel file
workbook.save("book1.xlsm")

```

###  Se även
* modul [`aspose.cells`](..)
* klass [`Cell`](/cells/python-net/sv/aspose.cells/cell)
* klass [`Range`](/cells/python-net/sv/aspose.cells/range)
