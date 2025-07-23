---
title: HtmlLoadOptions klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 780
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
| [`__init__(self)`](/cells/python-net/sv/aspose.cells/htmlloadoptions/__init__/#) | Skapar alternativ för att ladda filen.|
| [`__init__(self, load_format)`](/cells/python-net/sv/aspose.cells/htmlloadoptions/__init__/#aspose.cells.loadformat) | Skapar alternativ för att ladda filen.|


###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [load_format](/cells/python-net/sv/aspose.cells/htmlloadoptions/load_format) | Hämtar laddningsformatet.|
| [password](/cells/python-net/sv/aspose.cells/htmlloadoptions/password) | Hämtar och anger lösenordet för arbetsboken.|
| [parsing_formula_on_open](/cells/python-net/sv/aspose.cells/htmlloadoptions/parsing_formula_on_open) | Anger om formeln tolkas vid läsning av filen.|
| [parsing_pivot_cached_records](/cells/python-net/sv/aspose.cells/htmlloadoptions/parsing_pivot_cached_records) | Anger om pivot-cachade poster analyseras vid laddning av filen.<br/> Standardvärdet är falskt.|
| [language_code](/cells/python-net/sv/aspose.cells/htmlloadoptions/language_code) | Hämtar eller ställer in användargränssnittsspråket för arbetsboksversionen baserat på landskoden som har sparat filen.|
| [region](/cells/python-net/sv/aspose.cells/htmlloadoptions/region) | Hämtar eller anger de regionala inställningar som används för arbetsboken som ska läsas in.|
| [default_style_settings](/cells/python-net/sv/aspose.cells/htmlloadoptions/default_style_settings) | Hämtar standardinställningarna för stilar för att initiera arbetsbokens stilar|
| [standard_font](/cells/python-net/sv/aspose.cells/htmlloadoptions/standard_font) | Anger standardnamnet för teckensnitt|
| [standard_font_size](/cells/python-net/sv/aspose.cells/htmlloadoptions/standard_font_size) | Ställer in standardteckenstorleken.|
| [ignore_not_printed](/cells/python-net/sv/aspose.cells/htmlloadoptions/ignore_not_printed) | Ignorera data som inte skrivs ut om du skriver ut filen direkt|
| [check_data_valid](/cells/python-net/sv/aspose.cells/htmlloadoptions/check_data_valid) | Kontrollera om data i mallfilen är giltiga.|
| [check_excel_restriction](/cells/python-net/sv/aspose.cells/htmlloadoptions/check_excel_restriction) | Om begränsning av Excel-filen ska kontrolleras när användaren ändrar celler relaterade objekt.<br/>Till exempel tillåter inte Excel inmatning av strängvärden som är längre än 32K.<br/>När du matar in ett värde som är längre än 32K, till exempel Cell.PutValue(string), får du ett undantag om den här egenskapen är sann.<br/>Om den här egenskapen är falsk accepterar vi ditt inmatade strängvärde som cellens värde så att senare<br/>Du kan mata ut hela strängvärdet för andra filformat som CSV.<br/>Om du däremot har angett ett värde som är ogiltigt för Excel-filformatet,<br/>Du bör inte spara arbetsboken som Excel-filformat senare. Annars kan det uppstå oväntade fel för den genererade Excel-filen.|
| [keep_unparsed_data](/cells/python-net/sv/aspose.cells/htmlloadoptions/keep_unparsed_data) | Om oanalyserad data ska sparas i arbetsbokens minne när den laddas från mallfilen. Standardvärdet är sant.|
| [load_filter](/cells/python-net/sv/aspose.cells/htmlloadoptions/load_filter) | Filtret som anger hur data ska laddas.|
| [memory_setting](/cells/python-net/sv/aspose.cells/htmlloadoptions/memory_setting) | Hämtar eller ställer in minnesläget för den inlästa arbetsboken.|
| [auto_fitter_options](/cells/python-net/sv/aspose.cells/htmlloadoptions/auto_fitter_options) | Hämtar och ställer in alternativen för automatisk montering|
| [auto_filter](/cells/python-net/sv/aspose.cells/htmlloadoptions/auto_filter) | Anger om data ska filtreras automatiskt när filerna laddas.|
| [font_configs](/cells/python-net/sv/aspose.cells/htmlloadoptions/font_configs) | Hämtar och ställer in individuella teckensnittskonfigurationer.<br/> Fungerar bara för [`Workbook`](/cells/python-net/sv/aspose.cells/workbook) som använder denna [`LoadOptions`](/cells/python-net/sv/aspose.cells/loadoptions) för att ladda.|
| [ignore_useless_shapes](/cells/python-net/sv/aspose.cells/htmlloadoptions/ignore_useless_shapes) | Anger om oanvändbara former ignoreras.|
| [preserve_padding_spaces_in_formula](/cells/python-net/sv/aspose.cells/htmlloadoptions/preserve_padding_spaces_in_formula) | Anger om de mellanslag och radbrytningar som fylls ut mellan formeltokens ska bevaras<br/>medan man hämtar och ställer in formler.<br/> Standardvärdet är falskt.|
| [encoding](/cells/python-net/sv/aspose.cells/htmlloadoptions/encoding) | Hämtar och ställer in standardkodningen. Gäller endast för csv-filer.|
| [load_style_strategy](/cells/python-net/sv/aspose.cells/htmlloadoptions/load_style_strategy) | Anger strategin för att tillämpa stil för parsade värden vid konvertering av strängvärde till tal eller datum/tid.|
| [convert_numeric_data](/cells/python-net/sv/aspose.cells/htmlloadoptions/convert_numeric_data) |Hämtar eller anger ett värde som anger om strängen i textfilen konverteras till numeriska data.|
| [convert_date_time_data](/cells/python-net/sv/aspose.cells/htmlloadoptions/convert_date_time_data) | Hämtar eller anger ett värde som anger om strängen i textfilen konverteras till datumdata.|
| [keep_precision](/cells/python-net/sv/aspose.cells/htmlloadoptions/keep_precision) | Anger om ett strängvärde inte tolkas om längden är 15.|
| [attached_files_directory](/cells/python-net/sv/aspose.cells/htmlloadoptions/attached_files_directory) | Katalogen där de bifogade filerna kommer att sparas.|
| [load_formulas](/cells/python-net/sv/aspose.cells/htmlloadoptions/load_formulas) | Anger om formler ska importeras om den ursprungliga HTML-filen innehåller formler|
| [support_div_tag](/cells/python-net/sv/aspose.cells/htmlloadoptions/support_div_tag) | Anger om layouten för taggen `<div>` stöds när html-filen innehåller den.<br/> Standardvärdet är falskt.|
| [delete_redundant_spaces](/cells/python-net/sv/aspose.cells/htmlloadoptions/delete_redundant_spaces) | Anger om redundanta mellanslag ska tas bort när texten radbryts med taggen `<br>`.<br/> Standardvärdet är falskt.|
| [auto_fit_cols_and_rows](/cells/python-net/sv/aspose.cells/htmlloadoptions/auto_fit_cols_and_rows) | Anger om kolumner och rader anpassas automatiskt. Standardvärdet är falskt.|
| [convert_formulas_data](/cells/python-net/sv/aspose.cells/htmlloadoptions/convert_formulas_data) |Om sant, konvertera sträng till formel när strängvärdet börjar med tecknet '=', standardvärdet är falskt.|
| [has_formula](/cells/python-net/sv/aspose.cells/htmlloadoptions/has_formula) | Anger om texten är en formel om den börjar med "=".|
| [prog_id](/cells/python-net/sv/aspose.cells/htmlloadoptions/prog_id) | Hämtar program-ID:t för att skapa filen.<br/> Endast för MHT-filer.|
| [table_load_options](/cells/python-net/sv/aspose.cells/htmlloadoptions/table_load_options) | Hämta HtmlTableLoadOptionCollection-instansen|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`set_paper_size(self, type)`](/cells/python-net/sv/aspose.cells/htmlloadoptions/set_paper_size/#aspose.cells.papersizetype) | Ställer in standardpappersstorleken för utskrift från skrivarens standardinställning.|



###  Se även
* modul [`aspose.cells`](..)
* klass [`AbstractTextLoadOptions`](/cells/python-net/sv/aspose.cells/abstracttextloadoptions)
* klass [`HtmlLoadOptions`](/cells/python-net/sv/aspose.cells/htmlloadoptions)
* klass [`LoadOptions`](/cells/python-net/sv/aspose.cells/loadoptions)
* klass [`Workbook`](/cells/python-net/sv/aspose.cells/workbook)
