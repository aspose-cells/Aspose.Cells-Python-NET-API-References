---
title: HtmlLoadOptions klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 800
url: /sv/aspose.cells/htmlloadoptions/
is_root: false
---
##  HtmlLoadOptions klass
Representerar alternativ vid import av en html-fil.



**Arv:** [`HtmlLoadOptions`](/cells/python-net/aspose.cells/htmlloadoptions) → 
[`AbstractTextLoadOptions`](/cells/python-net/aspose.cells/abstracttextloadoptions) → 
[`LoadOptions`](/cells/python-net/sv/aspose.cells/loadoptions)



Typen HtmlLoadOptions avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [__init__](/cells/python-net/sv/aspose.cells/htmlloadoptions/__init__/#) | Skapar ett alternativ för att ladda filen.|
| [__init__](/cells/python-net/sv/aspose.cells/htmlloadoptions/__init__/#aspose.cells.LoadFormat) | Skapar ett alternativ för att ladda filen.|


###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [load_format](/cells/python-net/sv/aspose.cells/htmlloadoptions/load_format) | Hämtar laddningsformatet.|
| [password](/cells/python-net/sv/aspose.cells/htmlloadoptions/password) | Hämtar och ställer in lösenordet för arbetsboken.|
| [parsing_formula_on_open](/cells/python-net/sv/aspose.cells/htmlloadoptions/parsing_formula_on_open) | Anger om formeln analyseras när filen läses.|
| [parsing_pivot_cached_records](/cells/python-net/sv/aspose.cells/htmlloadoptions/parsing_pivot_cached_records) | Indikerar om tolkar pivotcachade poster när filen laddas.<br/> Standardvärdet är falskt.|
| [language_code](/cells/python-net/sv/aspose.cells/htmlloadoptions/language_code) | Hämtar eller ställer in användargränssnittsspråket för Workbook-versionen baserat på CountryCode som har sparat filen.|
| [region](/cells/python-net/sv/aspose.cells/htmlloadoptions/region) |Hämtar eller ställer in systemets regionala inställningar baserat på CountryCode vid den tidpunkt då filen laddades.|
| [default_style_settings](/cells/python-net/sv/aspose.cells/htmlloadoptions/default_style_settings) | Hämtar standardformatinställningarna för att initiera arbetsbokens stilar|
| [standard_font](/cells/python-net/sv/aspose.cells/htmlloadoptions/standard_font) | Ställer in standardtypsnittets standardnamn|
| [standard_font_size](/cells/python-net/sv/aspose.cells/htmlloadoptions/standard_font_size) | Ställer in standard standard teckenstorlek.|
| [interrupt_monitor](/cells/python-net/sv/aspose.cells/htmlloadoptions/interrupt_monitor) | Hämtar och ställer in avbrottsmonitorn.|
| [ignore_not_printed](/cells/python-net/sv/aspose.cells/htmlloadoptions/ignore_not_printed) | Ignorera data som inte skrivs ut om du skriver ut filen direkt|
| [check_data_valid](/cells/python-net/sv/aspose.cells/htmlloadoptions/check_data_valid) | Kontrollera om data är giltiga i mallfilen.|
| [check_excel_restriction](/cells/python-net/sv/aspose.cells/htmlloadoptions/check_excel_restriction) | Om kontrollera begränsning av excel-fil när användaren ändrar cellrelaterade objekt.<br/>Till exempel tillåter excel inte inmatning av strängvärden som är längre än 32K.<br/>När du matar in ett värde som är längre än 32K, t.ex. Cell.PutValue(string), får du ett undantag om den här egenskapen är sann.<br/>Om den här egenskapen är falsk kommer vi att acceptera ditt inmatade strängvärde som cellens värde så att senare<br/>du kan mata ut hela strängvärdet för andra filformat som CSV.<br/>Men om du har angett en sådan typ av värde som är ogiltigt för Excel-filformat,<br/> du bör inte spara arbetsboken som Excel-filformat senare. Annars kan det uppstå ett oväntat fel för den genererade Excel-filen.|
| [keep_unparsed_data](/cells/python-net/sv/aspose.cells/htmlloadoptions/keep_unparsed_data) | Behåll den oparsade datan i minnet för arbetsboken när den laddas från mallfilen. Standard är sant.|
| [load_filter](/cells/python-net/sv/aspose.cells/htmlloadoptions/load_filter) | Filtret för att ange hur man laddar data.|
| [light_cells_data_handler](/cells/python-net/sv/aspose.cells/htmlloadoptions/light_cells_data_handler) | Datahanteraren för att behandla celldata vid läsning av mallfil.|
| [memory_setting](/cells/python-net/sv/aspose.cells/htmlloadoptions/memory_setting) | Hämtar eller ställer in alternativen för minnesanvändning.|
| [warning_callback](/cells/python-net/sv/aspose.cells/htmlloadoptions/warning_callback) | Får eller ställer in varningsåteruppringning.|
| [auto_fitter_options](/cells/python-net/sv/aspose.cells/htmlloadoptions/auto_fitter_options) | Hämtar och ställer in alternativen för automatisk montering|
| [auto_filter](/cells/python-net/sv/aspose.cells/htmlloadoptions/auto_filter) | Indikerar om data filtreras automatiskt när filerna laddas.|
| [font_configs](/cells/python-net/sv/aspose.cells/htmlloadoptions/font_configs) | Hämtar och ställer in individuella teckensnittskonfigurationer.<br/> Fungerar endast för [`Workbook`](/cells/python-net/sv/aspose.cells/workbook) som använder denna [`LoadOptions`](/cells/python-net/sv/aspose.cells/loadoptions) för att ladda.|
| [ignore_useless_shapes](/cells/python-net/sv/aspose.cells/htmlloadoptions/ignore_useless_shapes) | Anger om värdelösa former ignoreras.|
| [preserve_padding_spaces_in_formula](/cells/python-net/sv/aspose.cells/htmlloadoptions/preserve_padding_spaces_in_formula) | Anger om de mellanslag och radbrytningar som är utfyllda mellan formeltokens bevaras<br/>samtidigt som du hämtar och ställer in formler.<br/> Standardvärdet är falskt.|
| [encoding](/cells/python-net/sv/aspose.cells/htmlloadoptions/encoding) |Hämtar och ställer in standardkodningen. Gäller endast för csv-fil.|
| [load_style_strategy](/cells/python-net/sv/aspose.cells/htmlloadoptions/load_style_strategy) | Indikerar strategin för att tillämpa stil för analyserade värden vid konvertering av strängvärde till nummer eller datum och tid.|
| [convert_numeric_data](/cells/python-net/sv/aspose.cells/htmlloadoptions/convert_numeric_data) | Hämtar eller ställer in ett värde som indikerar om strängen i textfilen konverteras till numerisk data.|
| [convert_date_time_data](/cells/python-net/sv/aspose.cells/htmlloadoptions/convert_date_time_data) | Hämtar eller ställer in ett värde som indikerar om strängen i textfilen konverteras till datumdata.|
| [keep_precision](/cells/python-net/sv/aspose.cells/htmlloadoptions/keep_precision) | Anger om ett strängvärde inte analyseras om längden är 15.|
| [attached_files_directory](/cells/python-net/sv/aspose.cells/htmlloadoptions/attached_files_directory) | Mappen som de bifogade filerna kommer att sparas i.|
| [load_formulas](/cells/python-net/sv/aspose.cells/htmlloadoptions/load_formulas) | Anger om formler importeras om den ursprungliga html-filen innehåller formler|
| [support_div_tag](/cells/python-net/sv/aspose.cells/htmlloadoptions/support_div_tag) |Anger om layouten för `<div>`-taggen stöds när html-filen innehåller den.<br/> Standardvärdet är falskt.|
| [delete_redundant_spaces](/cells/python-net/sv/aspose.cells/htmlloadoptions/delete_redundant_spaces) | Anger om redundanta blanksteg ska raderas när texten radbryts med `<br>`-taggen.<br/> Standardvärdet är falskt.|
| [auto_fit_cols_and_rows](/cells/python-net/sv/aspose.cells/htmlloadoptions/auto_fit_cols_and_rows) | Anger om automatiskt anpassa kolumner och rader. Standardvärdet är falskt.|
| [convert_formulas_data](/cells/python-net/sv/aspose.cells/htmlloadoptions/convert_formulas_data) | om sant, konvertera sträng till formel när strängvärde börjar med tecknet '=', standardvärdet är falskt.|
| [has_formula](/cells/python-net/sv/aspose.cells/htmlloadoptions/has_formula) | Anger om texten är formel om den börjar med "=".|
| [stream_provider](/cells/python-net/sv/aspose.cells/htmlloadoptions/stream_provider) | Hämtar eller ställer in StreamProviderImportHtmlFile för import av objekt.|
| [prog_id](/cells/python-net/sv/aspose.cells/htmlloadoptions/prog_id) | Hämtar program-id för att skapa filen.<br/> Endast för MHT-filer.|
| [table_load_options](/cells/python-net/sv/aspose.cells/htmlloadoptions/table_load_options) | Hämta HtmlTableLoadOptionCollection-instansen|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [set_paper_size](/cells/python-net/sv/aspose.cells/htmlloadoptions/set_paper_size/#aspose.cells.PaperSizeType) | Ställer in standardstorleken för utskriftspapper från standardskrivarens inställning.|



###  Se även
* modul [`aspose.cells`](..)
* klass [`AbstractTextLoadOptions`](/cells/python-net/sv/aspose.cells/abstracttextloadoptions)
* klass [`HtmlLoadOptions`](/cells/python-net/sv/aspose.cells/htmlloadoptions)
* klass [`LoadOptions`](/cells/python-net/sv/aspose.cells/loadoptions)
* klass [`Workbook`](/cells/python-net/sv/aspose.cells/workbook)
