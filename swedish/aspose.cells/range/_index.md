---
title: Range klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1290
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
| [entire_column](/cells/python-net/sv/aspose.cells/range/entire_column) | Hämtar ett Range-objekt som representerar hela kolumnen (eller kolumnerna) som innehåller det angivna intervallet.|
| [entire_row](/cells/python-net/sv/aspose.cells/range/entire_row) |Hämtar ett Range-objekt som representerar hela raden (eller raderna) som innehåller det angivna intervallet.|
| [worksheet](/cells/python-net/sv/aspose.cells/range/worksheet) | Hämtar [`Range.worksheet`](/cells/python-net/sv/aspose.cells/range#worksheet)objektet som innehåller detta intervall.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [auto_fill](/cells/python-net/sv/aspose.cells/range/auto_fill/#aspose.cells.Range) | Fyller automatiskt målområdet.|
| [auto_fill](/cells/python-net/sv/aspose.cells/range/auto_fill/#aspose.cells.Range-aspose.cells.AutoFillType) | Fyller automatiskt målområdet.|
| [set_style](/cells/python-net/sv/aspose.cells/range/set_style/#aspose.cells.Style-bool) | Använd cellformatet.|
| [set_style](/cells/python-net/sv/aspose.cells/range/set_style/#aspose.cells.Style) | Ställer in stilen för intervallet.|
| [set_outline_borders](/cells/python-net/sv/aspose.cells/range/set_outline_borders/#aspose.cells.CellBorderType-aspose.cells.CellsColor) | Ställer in konturkanterna runt ett cellintervall med samma kantstil och färg.|
| [set_outline_borders](/cells/python-net/sv/aspose.cells/range/set_outline_borders/#aspose.cells.CellBorderType-aspose.pydrawing.Color) | Ställer in konturkanterna runt ett cellintervall med samma kantstil och färg.|
| [set_outline_borders](/cells/python-net/sv/aspose.cells/range/set_outline_borders/#list-aspose.pydrawing.Color[]) | Anger linjekanter runt ett cellintervall.|
| [set_outline_border](/cells/python-net/sv/aspose.cells/range/set_outline_border/#aspose.cells.BorderType-aspose.cells.CellBorderType-aspose.cells.CellsColor) | Anger konturkant runt ett cellintervall.|
| [set_outline_border](/cells/python-net/sv/aspose.cells/range/set_outline_border/#aspose.cells.BorderType-aspose.cells.CellBorderType-aspose.pydrawing.Color) | Anger konturkant runt ett cellintervall.|
| [copy](/cells/python-net/sv/aspose.cells/range/copy/#aspose.cells.Range-aspose.cells.PasteOptions) | Kopiera intervallet med specialalternativ för klistra in.|
| [copy](/cells/python-net/sv/aspose.cells/range/copy/#aspose.cells.Range) | Kopierar data (inklusive formler), formatering, rita objekt etc. från ett källområde.|
| [add_hyperlink](/cells/python-net/sv/aspose.cells/range/add_hyperlink/#str-str-str) | Lägger till en hyperlänk till en angiven cell eller ett cellintervall.|
| [get_enumerator](/cells/python-net/sv/aspose.cells/range/get_enumerator/#) | Hämtar enumeratorn för celler i detta intervall.|
| [is_intersect](/cells/python-net/sv/aspose.cells/range/is_intersect/#aspose.cells.Range) | Indikerar om räckvidden är skärande.|
| [intersect](/cells/python-net/sv/aspose.cells/range/intersect/#aspose.cells.Range) | Returnerar ett [`Range`](/cells/python-net/sv/aspose.cells/range)-objekt som representerar den rektangulära skärningspunkten mellan två intervall.|
| [union_rang](/cells/python-net/sv/aspose.cells/range/union_rang/#aspose.cells.Range) | Returnerar unionsresultatet för två intervall.|
| [union](/cells/python-net/sv/aspose.cells/range/union/#aspose.cells.Range) | Returnerar föreningen av två intervall.|
| [is_blank](/cells/python-net/sv/aspose.cells/range/is_blank/#) | Anger om intervallet innehåller värden.|
| [merge](/cells/python-net/sv/aspose.cells/range/merge/#) | Kombinerar ett intervall av celler till en enda cell.|
| [un_merge](/cells/python-net/sv/aspose.cells/range/un_merge/#) |Ta bort sammanslagna celler i detta intervall.|
| [put_value](/cells/python-net/sv/aspose.cells/range/put_value/#str-bool-bool) | Lägger ett värde i intervallet, om så är lämpligt kommer värdet att konverteras till annan datatyp och cellens talformat återställs.|
| [apply_style](/cells/python-net/sv/aspose.cells/range/apply_style/#aspose.cells.Style-aspose.cells.StyleFlag) | Gäller format för en hel rad.|
| [set_inside_borders](/cells/python-net/sv/aspose.cells/range/set_inside_borders/#aspose.cells.BorderType-aspose.cells.CellBorderType-aspose.cells.CellsColor) | Ställ in gränserna för intervallet.|
| [move_to](/cells/python-net/sv/aspose.cells/range/move_to/#int-int) | Flytta det aktuella intervallet till destinationsintervallet.|
| [copy_data](/cells/python-net/sv/aspose.cells/range/copy_data/#aspose.cells.Range) | Kopierar celldata (inklusive formler) från ett källintervall.|
| [copy_value](/cells/python-net/sv/aspose.cells/range/copy_value/#aspose.cells.Range) | Kopierar cellvärde från ett källintervall.|
| [copy_style](/cells/python-net/sv/aspose.cells/range/copy_style/#aspose.cells.Range) | Kopierar stilinställningar från ett källområde.|
| [get_cell_or_null](/cells/python-net/sv/aspose.cells/range/get_cell_or_null/#int-int) | Hämtar [`Cell`](/cells/python-net/sv/aspose.cells/cell) objekt eller null i detta intervall.|
| [get_offset](/cells/python-net/sv/aspose.cells/range/get_offset/#int-int) | Får [`Range`](/cells/python-net/sv/aspose.cells/range) räckvidd med offset.|



###  Anmärkningar

Klassen Range betecknar en region av Excel-kalkylblad.
Med detta kan du formatera och ställa in värdet på intervallet.
Och du kan helt enkelt kopiera sortimentet av Excel också.

###  Exempel

Följande exempel visar hur man skapar ett intervall och ställer in värdet för intervallet för Excel.

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
