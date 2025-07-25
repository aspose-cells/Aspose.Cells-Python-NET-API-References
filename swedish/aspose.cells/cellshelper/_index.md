---
title: CellsHelper klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 210
url: /sv/aspose.cells/cellshelper/
is_root: false
---
##  CellsHelper klass
Tillhandahåller hjälpfunktioner.



Typen CellsHelper avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [significant_digits](/cells/python-net/sv/aspose.cells/cellshelper/significant_digits) | Hämtar och anger antalet signifikanta siffror.<br/> Standardvärdet är 17.|
| [dpi](/cells/python-net/sv/aspose.cells/cellshelper/dpi) | Hämtar maskinens DPI.|
| [startup_path](/cells/python-net/sv/aspose.cells/cellshelper/startup_path) | Hämtar eller anger startsökvägen, som refereras till av vissa externa formelreferenser.|
| [alt_start_path](/cells/python-net/sv/aspose.cells/cellshelper/alt_start_path) | Hämtar eller anger den alternativa startsökvägen, som refereras till av vissa externa formelreferenser.|
| [library_path](/cells/python-net/sv/aspose.cells/cellshelper/library_path) |Hämtar eller anger bibliotekssökvägen som refereras till av vissa externa formelreferenser.|
| [custom_implementation_factory](/cells/python-net/sv/aspose.cells/cellshelper/custom_implementation_factory) | Hämtar eller ställer in fabriksinställningarna för att skapa instanser med speciell implementering.|
| [is_cloud_platform](/cells/python-net/sv/aspose.cells/cellshelper/is_cloud_platform) | Vänligen ange den här egenskapen True när du kör på en molnplattform, till exempel: Azure, AWSLambda, etc.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`create_safe_sheet_name(, name_proposal)`](/cells/python-net/sv/aspose.cells/cellshelper/create_safe_sheet_name/#str) | Kontrollerar angivet arknamn och skapar ett giltigt namn vid behov.<br/>Om det angivna arknamnet överensstämmer med reglerna för Excel-arknamn, returnera det.<br/>Annars kommer strängen att avkortas om längden överskrider gränsen.<br/> och ogiltiga tecken kommer att ersättas med ' ', och returnera sedan det ombyggda strängvärdet.|
| [`create_safe_sheet_name(, name_proposal, replace_char)`](/cells/python-net/sv/aspose.cells/cellshelper/create_safe_sheet_name/#str-char) | Kontrollerar angivet arknamn och skapar ett giltigt namn vid behov.<br/>Om det angivna arknamnet överensstämmer med reglerna för Excel-arknamn, returnera det.<br/>Annars kommer strängen att avkortas om längden överskrider gränsen.<br/> och ogiltiga tecken kommer att ersättas med ett givet tecken, och returnera sedan det ombyggda strängvärdet.|
| [`get_text_width(, text, font, scaling)`](/cells/python-net/sv/aspose.cells/cellshelper/get_text_width/#str-aspose.cells.font-float) | Hämta textens bredd i enheter av punkter.|
| [`get_version()`](/cells/python-net/sv/aspose.cells/cellshelper/get_version/#) | Hämta den utgivna versionen.|
| [`cell_name_to_index(, cell_name, row, column)`](/cells/python-net/sv/aspose.cells/cellshelper/cell_name_to_index/#str-any-any) | Hämtar cellens rad- och kolumnindex enligt dess namn.|
| [`cell_index_to_name(, row, column)`](/cells/python-net/sv/aspose.cells/cellshelper/cell_index_to_name/#int-int) | Hämtar cellnamn enligt dess rad- och kolumnindex.|
| [`column_index_to_name(, column)`](/cells/python-net/sv/aspose.cells/cellshelper/column_index_to_name/#int) | Hämtar kolumnnamn enligt kolumnindex.|
| [`column_name_to_index(, column_name)`](/cells/python-net/sv/aspose.cells/cellshelper/column_name_to_index/#str) | Hämtar kolumnindex enligt kolumnnamn.|
| [`row_index_to_name(, row)`](/cells/python-net/sv/aspose.cells/cellshelper/row_index_to_name/#int) | Hämtar radnamn enligt radindex.|
| [`row_name_to_index(, row_name)`](/cells/python-net/sv/aspose.cells/cellshelper/row_name_to_index/#str) | Hämtar radindex enligt radnamn.|
| [`convert_r1c1_formula_to_a1(, r_1c1_formula, row, column)`](/cells/python-net/sv/aspose.cells/cellshelper/convert_r1c1_formula_to_a1/#str-int-int) | Konverterar cellens r1c1-formel till A1-formeln.|
| [`convert_a1_formula_to_r1c1(, formula, row, column)`](/cells/python-net/sv/aspose.cells/cellshelper/convert_a1_formula_to_r1c1/#str-int-int) |Konverterar cellens A1-formel till r1c1-formeln.|
| [`get_date_time_from_double(, double_value, date1904)`](/cells/python-net/sv/aspose.cells/cellshelper/get_date_time_from_double/#float-bool) | Konvertera det dubbla värdet till datum- och tidsvärdet.|
| [`get_double_from_date_time(, date_time, date1904)`](/cells/python-net/sv/aspose.cells/cellshelper/get_double_from_date_time/#datetime-bool) | Konvertera datum och tid till dubbelt värde.|
| [`get_used_colors(, workbook)`](/cells/python-net/sv/aspose.cells/cellshelper/get_used_colors/#aspose.cells.workbook) | Hämtar alla använda färger i arbetsboken.|
| [`add_add_in_function(, function, min_count_of_parameters, max_count_of_parameters, paramers_type, function_value_type)`](/cells/python-net/sv/aspose.cells/cellshelper/add_add_in_function/#str-int-int-list-aspose.cells.parametertype) | Lägg till tilläggsfunktion.|
| [`merge_files(, files, cached_file, dest_file)`](/cells/python-net/sv/aspose.cells/cellshelper/merge_files/#list-str-str) | Sammanfogar några stora xls-filer till en xls-fil.|
| [`get_cache_folder()`](/cells/python-net/sv/aspose.cells/cellshelper/get_cache_folder/#) | Hämtar mappen för tillfälliga filer som kan användas som datacache.|
| [`set_cache_folder(, cache)`](/cells/python-net/sv/aspose.cells/cellshelper/set_cache_folder/#str) | Anger mappen för tillfälliga filer som kan användas som datacache.|
| [`need_quote_in_formula(, sheet_name)`](/cells/python-net/sv/aspose.cells/cellshelper/need_quote_in_formula/#str) | Anger om namnet på arket ska omges av enkla citattecken|
| [`init_for_dot_net_core()`](/cells/python-net/sv/aspose.cells/cellshelper/init_for_dot_net_core/#) | Gör initialiseringen för .NetCore-programmet.<br/> Vi föreslår att du anropar den här metoden för all .NetCore-initialisering först.<br/>Till exempel:<br/>CellsHelper.InitForDotNetCore();<br/> Arbetsbok wb = ny arbetsbok();|



###  Se även
* modul [`aspose.cells`](..)
