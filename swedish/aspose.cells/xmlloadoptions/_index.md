---
title: XmlLoadOptions klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1760
url: /sv/aspose.cells/xmlloadoptions/
is_root: false
---
##  XmlLoadOptions klass
Representerar alternativen för att ladda xml.



**Arv:** [`XmlLoadOptions`](/cells/python-net/aspose.cells/xmlloadoptions) → 
[`LoadOptions`](/cells/python-net/sv/aspose.cells/loadoptions)



Typen XmlLoadOptions avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [__init__](/cells/python-net/sv/aspose.cells/xmlloadoptions/__init__/#) | Representerar alternativen för att ladda xml-fil.|
| [__init__](/cells/python-net/sv/aspose.cells/xmlloadoptions/__init__/#aspose.cells.LoadFormat) | Representerar alternativen för att ladda xml-fil.|


###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [load_format](/cells/python-net/sv/aspose.cells/xmlloadoptions/load_format) | Hämtar laddningsformatet.|
| [password](/cells/python-net/sv/aspose.cells/xmlloadoptions/password) | Hämtar och ställer in lösenordet för arbetsboken.|
| [parsing_formula_on_open](/cells/python-net/sv/aspose.cells/xmlloadoptions/parsing_formula_on_open) | Anger om formeln analyseras när filen läses.|
| [parsing_pivot_cached_records](/cells/python-net/sv/aspose.cells/xmlloadoptions/parsing_pivot_cached_records) | Indikerar om tolkar pivotcachade poster när filen laddas.<br/> Standardvärdet är falskt.|
| [language_code](/cells/python-net/sv/aspose.cells/xmlloadoptions/language_code) | Hämtar eller ställer in användargränssnittsspråket för Workbook-versionen baserat på CountryCode som har sparat filen.|
| [region](/cells/python-net/sv/aspose.cells/xmlloadoptions/region) |Hämtar eller ställer in systemets regionala inställningar baserat på CountryCode vid den tidpunkt då filen laddades.|
| [default_style_settings](/cells/python-net/sv/aspose.cells/xmlloadoptions/default_style_settings) | Hämtar standardformatinställningarna för att initiera arbetsbokens stilar|
| [standard_font](/cells/python-net/sv/aspose.cells/xmlloadoptions/standard_font) | Ställer in standardtypsnittets standardnamn|
| [standard_font_size](/cells/python-net/sv/aspose.cells/xmlloadoptions/standard_font_size) | Ställer in standard standard teckenstorlek.|
| [interrupt_monitor](/cells/python-net/sv/aspose.cells/xmlloadoptions/interrupt_monitor) | Hämtar och ställer in avbrottsmonitorn.|
| [ignore_not_printed](/cells/python-net/sv/aspose.cells/xmlloadoptions/ignore_not_printed) | Ignorera data som inte skrivs ut om du skriver ut filen direkt|
| [check_data_valid](/cells/python-net/sv/aspose.cells/xmlloadoptions/check_data_valid) | Kontrollera om data är giltiga i mallfilen.|
| [check_excel_restriction](/cells/python-net/sv/aspose.cells/xmlloadoptions/check_excel_restriction) | Om kontrollera begränsning av excel-fil när användaren ändrar cellrelaterade objekt.<br/>Till exempel tillåter excel inte inmatning av strängvärden som är längre än 32K.<br/>När du matar in ett värde som är längre än 32K, t.ex. Cell.PutValue(string), får du ett undantag om den här egenskapen är sann.<br/>Om den här egenskapen är falsk kommer vi att acceptera ditt inmatade strängvärde som cellens värde så att senare<br/>du kan mata ut hela strängvärdet för andra filformat som CSV.<br/>Men om du har angett en sådan typ av värde som är ogiltigt för Excel-filformat,<br/> du bör inte spara arbetsboken som Excel-filformat senare. Annars kan det uppstå ett oväntat fel för den genererade Excel-filen.|
| [keep_unparsed_data](/cells/python-net/sv/aspose.cells/xmlloadoptions/keep_unparsed_data) | Behåll den oparsade datan i minnet för arbetsboken när den laddas från mallfilen. Standard är sant.|
| [load_filter](/cells/python-net/sv/aspose.cells/xmlloadoptions/load_filter) | Filtret för att ange hur man laddar data.|
| [light_cells_data_handler](/cells/python-net/sv/aspose.cells/xmlloadoptions/light_cells_data_handler) | Datahanteraren för att behandla celldata vid läsning av mallfil.|
| [memory_setting](/cells/python-net/sv/aspose.cells/xmlloadoptions/memory_setting) | Hämtar eller ställer in alternativen för minnesanvändning.|
| [warning_callback](/cells/python-net/sv/aspose.cells/xmlloadoptions/warning_callback) | Får eller ställer in varningsåteruppringning.|
| [auto_fitter_options](/cells/python-net/sv/aspose.cells/xmlloadoptions/auto_fitter_options) | Hämtar och ställer in alternativen för automatisk montering|
| [auto_filter](/cells/python-net/sv/aspose.cells/xmlloadoptions/auto_filter) | Indikerar om data filtreras automatiskt när filerna laddas.|
| [font_configs](/cells/python-net/sv/aspose.cells/xmlloadoptions/font_configs) | Hämtar och ställer in individuella teckensnittskonfigurationer.<br/> Fungerar endast för [`Workbook`](/cells/python-net/sv/aspose.cells/workbook) som använder denna [`LoadOptions`](/cells/python-net/sv/aspose.cells/loadoptions) för att ladda.|
| [ignore_useless_shapes](/cells/python-net/sv/aspose.cells/xmlloadoptions/ignore_useless_shapes) | Anger om värdelösa former ignoreras.|
| [preserve_padding_spaces_in_formula](/cells/python-net/sv/aspose.cells/xmlloadoptions/preserve_padding_spaces_in_formula) | Anger om de mellanslag och radbrytningar som är utfyllda mellan formeltokens bevaras<br/>samtidigt som du hämtar och ställer in formler.<br/> Standardvärdet är falskt.|
| [start_cell](/cells/python-net/sv/aspose.cells/xmlloadoptions/start_cell) | Hämtar och ställer in startcellen.|
| [is_xml_map](/cells/python-net/sv/aspose.cells/xmlloadoptions/is_xml_map) | Anger om xml mappas till Excel.<br/> Standardvärdet är falskt.|
| [contains_multiple_worksheets](/cells/python-net/sv/aspose.cells/xmlloadoptions/contains_multiple_worksheets) | Anger om xml importeras som flera kalkylblad.|
| [convert_numeric_or_date](/cells/python-net/sv/aspose.cells/xmlloadoptions/convert_numeric_or_date) | Anger om värdet i xml-filen konverteras till numeriskt eller datum.|
| [number_format](/cells/python-net/sv/aspose.cells/xmlloadoptions/number_format) | Hämtar och ställer in formatet för numeriskt värde.|
| [date_format](/cells/python-net/sv/aspose.cells/xmlloadoptions/date_format) | Hämtar och ställer in formatet för datumvärdet.|
| [ignore_root_attributes](/cells/python-net/sv/aspose.cells/xmlloadoptions/ignore_root_attributes) | Anger om rotelementets attribut ignoreras.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [set_paper_size](/cells/python-net/sv/aspose.cells/xmlloadoptions/set_paper_size/#aspose.cells.PaperSizeType) | Ställer in standardstorleken för utskriftspapper från standardskrivarens inställning.|



###  Se även
* modul [`aspose.cells`](..)
* klass [`LoadOptions`](/cells/python-net/sv/aspose.cells/loadoptions)
* klass [`Workbook`](/cells/python-net/sv/aspose.cells/workbook)
* klass [`XmlLoadOptions`](/cells/python-net/sv/aspose.cells/xmlloadoptions)
