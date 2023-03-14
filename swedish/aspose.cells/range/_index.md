---
title: Range klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1250
url: /sv/aspose.cells/range/
is_root: false
---
##  Range klass
Kapslar in objektet som representerar ett cellintervall i ett kalkylblad.



Typen Range avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [current_region](/cells/python-net/sv/aspose.cells/range/current_region) |Returnerar ett Range-objekt som representerar den aktuella regionen.<br/> Den aktuella regionen är ett intervall som begränsas av valfri kombination av tomma rader och tomma kolumner.|
| [hyperlinks](/cells/python-net/sv/aspose.cells/range/hyperlinks) | Får alla hyperlänkar i intervallet.|
| [row_count](/cells/python-net/sv/aspose.cells/range/row_count) | Hämtar antalet rader i intervallet.|
| [column_count](/cells/python-net/sv/aspose.cells/range/column_count) | Hämtar antalet kolumner i intervallet.|
| [cell_count](/cells/python-net/sv/aspose.cells/range/cell_count) | Får allt cellantal i intervallet.|
| [name](/cells/python-net/sv/aspose.cells/range/name) | Hämtar eller ställer in namnet på intervallet.|
| [refers_to](/cells/python-net/sv/aspose.cells/range/refers_to) | Får sortimentets hänvisar till.|
| [address](/cells/python-net/sv/aspose.cells/range/address) | Får adress till intervallet.|
| [left](/cells/python-net/sv/aspose.cells/range/left) | Hämtar avståndet, i poäng, från den vänstra kanten av kolumn A till den vänstra kanten av intervallet.|
| [top](/cells/python-net/sv/aspose.cells/range/top) | Hämtar avståndet, i poäng, från den övre kanten av rad 1 till den övre kanten av intervallet.|
| [width](/cells/python-net/sv/aspose.cells/range/width) | Hämtar bredden på ett intervall i punkter.|
| [height](/cells/python-net/sv/aspose.cells/range/height) | Hämtar bredden på ett intervall i punkter.|
| [first_row](/cells/python-net/sv/aspose.cells/range/first_row) | Hämtar indexet för den första raden i intervallet.|
| [first_column](/cells/python-net/sv/aspose.cells/range/first_column) | Hämtar indexet för den första kolumnen i intervallet.|
| [value](/cells/python-net/sv/aspose.cells/range/value) | Hämtar och ställer in värdet på intervallet.|
| [column_width](/cells/python-net/sv/aspose.cells/range/column_width) | Ställer in eller hämtar kolumnbredden för detta intervall|
| [row_height](/cells/python-net/sv/aspose.cells/range/row_height) | Ställer in eller hämtar höjden på rader i detta intervall|
| [entire_column](/cells/python-net/sv/aspose.cells/range/entire_column) |Hämtar ett Range-objekt som representerar hela kolumnen (eller kolumnerna) som innehåller det angivna intervallet.|
| [entire_row](/cells/python-net/sv/aspose.cells/range/entire_row) | Hämtar ett Range-objekt som representerar hela raden (eller raderna) som innehåller det angivna intervallet.|
| [worksheet](/cells/python-net/sv/aspose.cells/range/worksheet) | Hämtar [Range.worksheet](/cells/python-net/sv/aspose.cells/range#worksheet)objektet som innehåller detta intervall.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [auto_fill(target)](/cells/python-net/sv/aspose.cells/range/auto_fill/#Range) | Fyller automatiskt målområdet.|
| [auto_fill(target, auto_fill_type)](/cells/python-net/sv/aspose.cells/range/auto_fill/#Range-AutoFillType) | Fyller automatiskt målområdet.|
| [set_style(style, explicit_flag)](/cells/python-net/sv/aspose.cells/range/set_style/#Style-bool) | Använd cellformatet.|
| [set_style(style)](/cells/python-net/sv/aspose.cells/range/set_style/#Style) | Ställer in stilen för intervallet.|
| [set_outline_borders(border_style, border_color)](/cells/python-net/sv/aspose.cells/range/set_outline_borders/#CellBorderType-CellsColor) | Ställer in konturkanterna runt ett cellintervall med samma kantstil och färg.|
| [set_outline_borders(border_style, border_color)](/cells/python-net/sv/aspose.cells/range/set_outline_borders/#CellBorderType-aspose.pydrawing.Color) | Ställer in konturkanterna runt ett cellintervall med samma kantstil och färg.|
| [set_outline_borders(border_styles, border_colors)](/cells/python-net/sv/aspose.cells/range/set_outline_borders/#list-aspose.pydrawing.Color[]) | Anger linjekanter runt ett cellintervall.|
| [set_outline_border(border_edge, border_style, border_color)](/cells/python-net/sv/aspose.cells/range/set_outline_border/#BorderType-CellBorderType-CellsColor) | Anger konturkant runt ett cellintervall.|
| [set_outline_border(border_edge, border_style, border_color)](/cells/python-net/sv/aspose.cells/range/set_outline_border/#BorderType-CellBorderType-aspose.pydrawing.Color) | Anger konturkant runt ett cellintervall.|
| [copy(range, options)](/cells/python-net/sv/aspose.cells/range/copy/#Range-PasteOptions) | Kopiera intervallet med specialalternativ för klistra in.|
| [copy(range)](/cells/python-net/sv/aspose.cells/range/copy/#Range) | Kopierar data (inklusive formler), formatering, rita objekt etc. från ett källområde.|
| [get_enumerator()](/cells/python-net/sv/aspose.cells/range/get_enumerator/#) | Hämtar enumeratorn för celler i detta intervall.|
| [is_intersect(range)](/cells/python-net/sv/aspose.cells/range/is_intersect/#Range) | Indikerar om räckvidden är skärande.|
| [intersect(range)](/cells/python-net/sv/aspose.cells/range/intersect/#Range) | Returnerar ett [Range](/cells/python-net/sv/aspose.cells/range)-objekt som representerar den rektangulära skärningspunkten mellan två intervall.|
| [union(range)](/cells/python-net/sv/aspose.cells/range/union/#Range) | Returnerar föreningen av två intervall.|
| [merge()](/cells/python-net/sv/aspose.cells/range/merge/#) | Kombinerar ett intervall av celler till en enda cell.|
| [un_merge()](/cells/python-net/sv/aspose.cells/range/un_merge/#) |Ta bort sammanslagna celler i detta intervall.|
| [put_value(string_value, is_converted, set_style)](/cells/python-net/sv/aspose.cells/range/put_value/#str-bool-bool) | Lägger ett värde i intervallet, om så är lämpligt kommer värdet att konverteras till annan datatyp och cellens talformat återställs.|
| [apply_style(style, flag)](/cells/python-net/sv/aspose.cells/range/apply_style/#Style-StyleFlag) | Gäller format för en hel rad.|
| [set_inside_borders(border_edge, line_style, border_color)](/cells/python-net/sv/aspose.cells/range/set_inside_borders/#BorderType-CellBorderType-CellsColor) | Ställ in gränserna för intervallet.|
| [move_to(dest_row, dest_column)](/cells/python-net/sv/aspose.cells/range/move_to/#int-int) | Flytta det aktuella intervallet till destinationsintervallet.|
| [copy_data(range)](/cells/python-net/sv/aspose.cells/range/copy_data/#Range) | Kopierar celldata (inklusive formler) från ett källintervall.|
| [copy_value(range)](/cells/python-net/sv/aspose.cells/range/copy_value/#Range) | Kopierar cellvärde från ett källintervall.|
| [copy_style(range)](/cells/python-net/sv/aspose.cells/range/copy_style/#Range) | Kopierar stilinställningar från ett källområde.|
| [get_cell_or_null(row_offset, column_offset)](/cells/python-net/sv/aspose.cells/range/get_cell_or_null/#int-int) | Hämtar [Cell](/cells/python-net/sv/aspose.cells/cell) objekt eller null i detta intervall.|
| [get_offset(row_offset, column_offset)](/cells/python-net/sv/aspose.cells/range/get_offset/#int-int) | Får [Range](/cells/python-net/sv/aspose.cells/range) räckvidd med offset.|



###  Exempel

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
* modul [aspose.cells](..)
* klass [Cell](/cells/python-net/sv/aspose.cells/cell)
* klass [Range](/cells/python-net/sv/aspose.cells/range)
