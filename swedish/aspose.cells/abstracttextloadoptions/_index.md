---
title: AbstractTextLoadOptions klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 60
url: /sv/aspose.cells/abstracttextloadoptions/
is_root: false
---
##  AbstractTextLoadOptions klass
Vanliga alternativ för att ladda textvärden



**Arv:** [AbstractTextLoadOptions](/cells/python-net/aspose.cells/abstracttextloadoptions) → 
[LoadOptions](/cells/python-net/sv/aspose.cells/loadoptions)



Typen AbstractTextLoadOptions avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [load_format](/cells/python-net/sv/aspose.cells/abstracttextloadoptions/load_format) | Hämtar laddningsformatet.|
| [password](/cells/python-net/sv/aspose.cells/abstracttextloadoptions/password) | Hämtar och ställer in lösenordet för arbetsboken.|
| [parsing_formula_on_open](/cells/python-net/sv/aspose.cells/abstracttextloadoptions/parsing_formula_on_open) | Anger om formeln analyseras när filen läses.|
| [parsing_pivot_cached_records](/cells/python-net/sv/aspose.cells/abstracttextloadoptions/parsing_pivot_cached_records) | Indikerar om tolkar pivotcachade poster när filen laddas.<br/> Standardvärdet är falskt.|
| [language_code](/cells/python-net/sv/aspose.cells/abstracttextloadoptions/language_code) | Hämtar eller ställer in användargränssnittsspråket för Workbook-versionen baserat på CountryCode som har sparat filen.|
| [region](/cells/python-net/sv/aspose.cells/abstracttextloadoptions/region) | Hämtar eller ställer in systemets regionala inställningar baserat på CountryCode vid den tidpunkt då filen laddades.|
| [default_style_settings](/cells/python-net/sv/aspose.cells/abstracttextloadoptions/default_style_settings) | Hämtar standardformatinställningarna för att initiera arbetsbokens stilar|
| [standard_font](/cells/python-net/sv/aspose.cells/abstracttextloadoptions/standard_font) | Ställer in standardtypsnittets standardnamn|
| [standard_font_size](/cells/python-net/sv/aspose.cells/abstracttextloadoptions/standard_font_size) | Ställer in standard standard teckenstorlek.|
| [interrupt_monitor](/cells/python-net/sv/aspose.cells/abstracttextloadoptions/interrupt_monitor) | Hämtar och ställer in avbrottsmonitorn.|
| [ignore_not_printed](/cells/python-net/sv/aspose.cells/abstracttextloadoptions/ignore_not_printed) | Ignorera data som inte skrivs ut om du skriver ut filen direkt|
| [check_data_valid](/cells/python-net/sv/aspose.cells/abstracttextloadoptions/check_data_valid) |Kontrollera om data är giltiga i mallfilen.|
| [check_excel_restriction](/cells/python-net/sv/aspose.cells/abstracttextloadoptions/check_excel_restriction) | Om kontrollera begränsning av excel-fil när användaren ändrar cellrelaterade objekt.<br/>Till exempel tillåter excel inte inmatning av strängvärden som är längre än 32K.<br/>När du matar in ett värde som är längre än 32K, till exempel Cell.PutValue(string), får du ett undantag om den här egenskapen är sann.<br/>Om den här egenskapen är falsk kommer vi att acceptera ditt inmatade strängvärde som cellens värde så att senare<br/>du kan mata ut hela strängvärdet för andra filformat som CSV.<br/>Men om du har angett en sådan typ av värde som är ogiltigt för Excel-filformat,<br/> du bör inte spara arbetsboken som Excel-filformat senare. Annars kan det uppstå ett oväntat fel för den genererade Excel-filen.|
| [keep_unparsed_data](/cells/python-net/sv/aspose.cells/abstracttextloadoptions/keep_unparsed_data) | Behåll den oparsade datan i minnet för arbetsboken när den laddas från mallfilen. Standard är sant.|
| [load_filter](/cells/python-net/sv/aspose.cells/abstracttextloadoptions/load_filter) | Filtret för att ange hur man laddar data.|
| [light_cells_data_handler](/cells/python-net/sv/aspose.cells/abstracttextloadoptions/light_cells_data_handler) | Datahanteraren för att behandla celldata vid läsning av mallfil.|
| [memory_setting](/cells/python-net/sv/aspose.cells/abstracttextloadoptions/memory_setting) | Hämtar eller ställer in alternativen för minnesanvändning.|
| [warning_callback](/cells/python-net/sv/aspose.cells/abstracttextloadoptions/warning_callback) | Får eller ställer in varningsåteruppringning.|
| [auto_fitter_options](/cells/python-net/sv/aspose.cells/abstracttextloadoptions/auto_fitter_options) | Hämtar och ställer in alternativen för automatisk montering|
| [auto_filter](/cells/python-net/sv/aspose.cells/abstracttextloadoptions/auto_filter) | Indikerar om data filtreras automatiskt när filerna laddas.|
| [font_configs](/cells/python-net/sv/aspose.cells/abstracttextloadoptions/font_configs) | Hämtar och ställer in individuella teckensnittskonfigurationer.<br/> Fungerar endast för [Workbook](/cells/python-net/sv/aspose.cells/workbook) som använder denna [LoadOptions](/cells/python-net/sv/aspose.cells/loadoptions) för att ladda.|
| [encoding](/cells/python-net/sv/aspose.cells/abstracttextloadoptions/encoding) | Hämtar och ställer in standardkodningen. Gäller endast för csv-fil.|
| [load_style_strategy](/cells/python-net/sv/aspose.cells/abstracttextloadoptions/load_style_strategy) |Indikerar strategin för att tillämpa stil för analyserade värden vid konvertering av strängvärde till nummer eller datum och tid.|
| [convert_numeric_data](/cells/python-net/sv/aspose.cells/abstracttextloadoptions/convert_numeric_data) | Hämtar eller ställer in ett värde som indikerar om strängen i textfilen konverteras till numerisk data.|
| [convert_date_time_data](/cells/python-net/sv/aspose.cells/abstracttextloadoptions/convert_date_time_data) | Hämtar eller ställer in ett värde som indikerar om strängen i textfilen konverteras till datumdata.|
| [keep_precision](/cells/python-net/sv/aspose.cells/abstracttextloadoptions/keep_precision) | Anger om ett strängvärde inte analyseras om längden är 15.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [set_paper_size(type)](/cells/python-net/sv/aspose.cells/abstracttextloadoptions/set_paper_size/#PaperSizeType) | Ställer in standardstorleken för utskriftspapper från standardskrivarens inställning.|



###  Se även
* modul [aspose.cells](..)
* klass [AbstractTextLoadOptions](/cells/python-net/sv/aspose.cells/abstracttextloadoptions)
* klass [LoadOptions](/cells/python-net/sv/aspose.cells/loadoptions)
* klass [Workbook](/cells/python-net/sv/aspose.cells/workbook)
