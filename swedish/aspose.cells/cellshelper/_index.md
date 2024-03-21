---
title: CellsHelper klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 240
url: /sv/aspose.cells/cellshelper/
is_root: false
---
##  CellsHelper klass
Tillhandahåller hjälpfunktioner.



Typen CellsHelper avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [significant_digits](/cells/python-net/sv/aspose.cells/cellshelper/significant_digits) | Hämtar och ställer in antalet signifikanta siffror.<br/> Standardvärdet är 17.|
| [dpi](/cells/python-net/sv/aspose.cells/cellshelper/dpi) | Får maskinens DPI.|
| [startup_path](/cells/python-net/sv/aspose.cells/cellshelper/startup_path) | Hämtar eller ställer in startsökvägen, som refereras till av vissa externa formelreferenser.|
| [alt_start_path](/cells/python-net/sv/aspose.cells/cellshelper/alt_start_path) | Hämtar eller ställer in den alternativa startsökvägen, som refereras till av vissa externa formelreferenser.|
| [library_path](/cells/python-net/sv/aspose.cells/cellshelper/library_path) | Hämtar eller ställer in bibliotekssökvägen som hänvisas till av vissa externa formelreferenser.|
| [custom_implementation_factory](/cells/python-net/sv/aspose.cells/cellshelper/custom_implementation_factory) | Får eller ställer in fabriken för att skapa instanser med speciell implementering.|
| [is_cloud_platform](/cells/python-net/sv/aspose.cells/cellshelper/is_cloud_platform) | Vänligen ange den här egenskapen True när du kör på en molnplattform, som: Azure, AWSLambda, etc,|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [create_safe_sheet_name](/cells/python-net/sv/aspose.cells/cellshelper/create_safe_sheet_name/#str) | Kontrollerar det angivna arknamnet och skapar ett giltigt vid behov.<br/>Om det angivna arknamnet överensstämmer med reglerna för Excel-arknamn, returnera det.<br/>Annars kommer strängen att trunkeras om längden överskrider gränsen<br/>och ogiltiga tecken kommer att ersättas med ' ', och returnerar sedan det ombyggda strängvärdet.|
| [create_safe_sheet_name](/cells/python-net/sv/aspose.cells/cellshelper/create_safe_sheet_name/#str-char) | Kontrollerar det angivna arknamnet och skapar ett giltigt vid behov.<br/>Om det angivna arknamnet överensstämmer med reglerna för Excel-arknamn, returnera det.<br/>Annars kommer strängen att trunkeras om längden överskrider gränsen<br/> och ogiltiga tecken kommer att ersättas med ett givet tecken, och returnerar sedan det ombyggda strängvärdet.|
| [get_text_width](/cells/python-net/sv/aspose.cells/cellshelper/get_text_width/#str-aspose.cells.Font-float) | Få textens bredd i poängenhet.|
| [get_version](/cells/python-net/sv/aspose.cells/cellshelper/get_version/#) | Hämta releaseversionen.|
| [cell_name_to_index](/cells/python-net/sv/aspose.cells/cellshelper/cell_name_to_index/#str-any-any) | Hämtar cellrads- och kolumnindex enligt dess namn.|
| [cell_index_to_name](/cells/python-net/sv/aspose.cells/cellshelper/cell_index_to_name/#int-int) | Hämtar cellnamn enligt dess rad- och kolumnindex.|
| [column_index_to_name](/cells/python-net/sv/aspose.cells/cellshelper/column_index_to_name/#int) | Hämtar kolumnnamn enligt kolumnindex.|
| [column_name_to_index](/cells/python-net/sv/aspose.cells/cellshelper/column_name_to_index/#str) | Får kolumnindex enligt kolumnnamn.|
| [row_index_to_name](/cells/python-net/sv/aspose.cells/cellshelper/row_index_to_name/#int) | Hämtar radnamn enligt radindex.|
| [row_name_to_index](/cells/python-net/sv/aspose.cells/cellshelper/row_name_to_index/#str) | Får radindex enligt radnamn.|
| [convert_r1c1_formula_to_a1](/cells/python-net/sv/aspose.cells/cellshelper/convert_r1c1_formula_to_a1/#str-int-int) | Konverterar cellens r1c1-formel till A1-formel.|
| [convert_a1_formula_to_r1c1](/cells/python-net/sv/aspose.cells/cellshelper/convert_a1_formula_to_r1c1/#str-int-int) | Konverterar A1-formeln för cellen till r1c1-formeln.|
| [get_date_time_from_double](/cells/python-net/sv/aspose.cells/cellshelper/get_date_time_from_double/#float-bool) | Konvertera det dubbla värdet till datum och tid.|
| [get_double_from_date_time](/cells/python-net/sv/aspose.cells/cellshelper/get_double_from_date_time/#DateTime-bool) | Konvertera datum och tid till dubbelt värde.|
| [get_used_colors](/cells/python-net/sv/aspose.cells/cellshelper/get_used_colors/#aspose.cells.Workbook) | Får alla använda färger i arbetsboken.|
| [add_add_in_function](/cells/python-net/sv/aspose.cells/cellshelper/add_add_in_function/#str-int-int-list-aspose.cells.ParameterType) | Lägg till tilläggsfunktion.|
| [merge_files](/cells/python-net/sv/aspose.cells/cellshelper/merge_files/#list-str-str) | Slår ihop några stora xls-filer till en xls-fil.|
| [need_quote_in_formula](/cells/python-net/sv/aspose.cells/cellshelper/need_quote_in_formula/#str) |Anger om bladets namn ska ingå i enkla citattecken|
| [init_for_dot_net_core](/cells/python-net/sv/aspose.cells/cellshelper/init_for_dot_net_core/#) | Gör initieringen för .NetCore-programmet.<br/> Vi föreslår att du först anropar den här metoden för all .NetCore-initiering.<br/>Till exempel:<br/>CellsHelper.InitForDotNetCore();<br/> Arbetsbok wb = ny arbetsbok();|



###  Se även
* modul [`aspose.cells`](..)
