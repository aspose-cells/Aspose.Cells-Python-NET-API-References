---
title: JsonLoadOptions klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 960
url: /sv/aspose.cells/jsonloadoptions/
is_root: false
---
##  JsonLoadOptions klass
Representerar alternativen för att ladda json-filer



**Arv:** [JsonLoadOptions](/cells/python-net/aspose.cells/jsonloadoptions) → 
[LoadOptions](/cells/python-net/sv/aspose.cells/loadoptions)



Typen JsonLoadOptions avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [JsonLoadOptions()](/cells/python-net/sv/aspose.cells/jsonloadoptions/__init__/#) | Skapar ett alternativ för att ladda filen.|


###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [load_format](/cells/python-net/sv/aspose.cells/jsonloadoptions/load_format) | Hämtar laddningsformatet.|
| [password](/cells/python-net/sv/aspose.cells/jsonloadoptions/password) | Hämtar och ställer in lösenordet för arbetsboken.|
| [parsing_formula_on_open](/cells/python-net/sv/aspose.cells/jsonloadoptions/parsing_formula_on_open) | Anger om formeln analyseras när filen läses.|
| [parsing_pivot_cached_records](/cells/python-net/sv/aspose.cells/jsonloadoptions/parsing_pivot_cached_records) | Indikerar om tolkar pivotcachade poster när filen laddas.<br/> Standardvärdet är falskt.|
| [language_code](/cells/python-net/sv/aspose.cells/jsonloadoptions/language_code) | Hämtar eller ställer in användargränssnittsspråket för Workbook-versionen baserat på CountryCode som har sparat filen.|
| [region](/cells/python-net/sv/aspose.cells/jsonloadoptions/region) | Hämtar eller ställer in systemets regionala inställningar baserat på CountryCode vid den tidpunkt då filen laddades.|
| [default_style_settings](/cells/python-net/sv/aspose.cells/jsonloadoptions/default_style_settings) | Hämtar standardformatinställningarna för att initiera arbetsbokens stilar|
| [standard_font](/cells/python-net/sv/aspose.cells/jsonloadoptions/standard_font) | Ställer in standardtypsnittets standardnamn|
| [standard_font_size](/cells/python-net/sv/aspose.cells/jsonloadoptions/standard_font_size) | Ställer in standard standard teckenstorlek.|
| [interrupt_monitor](/cells/python-net/sv/aspose.cells/jsonloadoptions/interrupt_monitor) | Hämtar och ställer in avbrottsmonitorn.|
| [ignore_not_printed](/cells/python-net/sv/aspose.cells/jsonloadoptions/ignore_not_printed) | Ignorera data som inte skrivs ut om du skriver ut filen direkt|
| [check_data_valid](/cells/python-net/sv/aspose.cells/jsonloadoptions/check_data_valid) |Kontrollera om data är giltiga i mallfilen.|
| [check_excel_restriction](/cells/python-net/sv/aspose.cells/jsonloadoptions/check_excel_restriction) | Om kontrollera begränsning av excel-fil när användaren ändrar cellrelaterade objekt.<br/>Till exempel tillåter excel inte inmatning av strängvärden som är längre än 32K.<br/>När du matar in ett värde som är längre än 32K, till exempel Cell.PutValue(string), får du ett undantag om den här egenskapen är sann.<br/>Om den här egenskapen är falsk kommer vi att acceptera ditt inmatade strängvärde som cellens värde så att senare<br/>du kan mata ut hela strängvärdet för andra filformat som CSV.<br/>Men om du har angett en sådan typ av värde som är ogiltigt för Excel-filformat,<br/> du bör inte spara arbetsboken som Excel-filformat senare. Annars kan det uppstå ett oväntat fel för den genererade Excel-filen.|
| [keep_unparsed_data](/cells/python-net/sv/aspose.cells/jsonloadoptions/keep_unparsed_data) | Behåll den oparsade datan i minnet för arbetsboken när den laddas från mallfilen. Standard är sant.|
| [load_filter](/cells/python-net/sv/aspose.cells/jsonloadoptions/load_filter) | Filtret för att ange hur man laddar data.|
| [light_cells_data_handler](/cells/python-net/sv/aspose.cells/jsonloadoptions/light_cells_data_handler) | Datahanteraren för att behandla celldata vid läsning av mallfil.|
| [memory_setting](/cells/python-net/sv/aspose.cells/jsonloadoptions/memory_setting) | Hämtar eller ställer in alternativen för minnesanvändning.|
| [warning_callback](/cells/python-net/sv/aspose.cells/jsonloadoptions/warning_callback) | Får eller ställer in varningsåteruppringning.|
| [auto_fitter_options](/cells/python-net/sv/aspose.cells/jsonloadoptions/auto_fitter_options) | Hämtar och ställer in alternativen för automatisk montering|
| [auto_filter](/cells/python-net/sv/aspose.cells/jsonloadoptions/auto_filter) | Indikerar om data filtreras automatiskt när filerna laddas.|
| [font_configs](/cells/python-net/sv/aspose.cells/jsonloadoptions/font_configs) | Hämtar och ställer in individuella teckensnittskonfigurationer.<br/> Fungerar endast för [Workbook](/cells/python-net/sv/aspose.cells/workbook) som använder denna [LoadOptions](/cells/python-net/sv/aspose.cells/loadoptions) för att ladda.|
| [start_cell](/cells/python-net/sv/aspose.cells/jsonloadoptions/start_cell) | Hämtar och ställer in startcellen.|
| [layout_options](/cells/python-net/sv/aspose.cells/jsonloadoptions/layout_options) | Alternativen för import json.|
| [multiple_worksheets](/cells/python-net/sv/aspose.cells/jsonloadoptions/multiple_worksheets) | Anger om varje attribut för JsonObject-objekt importeras som ett kalkylblad när alla underordnade noder är matrisnoder.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [set_paper_size(type)](/cells/python-net/sv/aspose.cells/jsonloadoptions/set_paper_size/#PaperSizeType) | Ställer in standardstorleken för utskriftspapper från standardskrivarens inställning.|



###  Se även
* modul [aspose.cells](..)
* klass [JsonLoadOptions](/cells/python-net/sv/aspose.cells/jsonloadoptions)
* klass [LoadOptions](/cells/python-net/sv/aspose.cells/loadoptions)
* klass [Workbook](/cells/python-net/sv/aspose.cells/workbook)
