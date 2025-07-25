---
title: WorksheetCollection klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1610
url: /sv/aspose.cells/worksheetcollection/
is_root: false
---
##  WorksheetCollection klass
Inkapslar en samling av [`Worksheet`](/cells/python-net/sv/aspose.cells/worksheet) objekt.



Typen WorksheetCollection avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [web_extension_task_panes](/cells/python-net/sv/aspose.cells/worksheetcollection/web_extension_task_panes) | Hämtar listan över åtgärdsfönster.|
| [web_extensions](/cells/python-net/sv/aspose.cells/worksheetcollection/web_extensions) | Hämtar listan över åtgärdsfönster.|
| [threaded_comment_authors](/cells/python-net/sv/aspose.cells/worksheetcollection/threaded_comment_authors) | Hämtar listan över författare till trådade kommentarer.|
| [is_refresh_all_connections](/cells/python-net/sv/aspose.cells/worksheetcollection/is_refresh_all_connections) | Anger om alla kopplingar ska uppdateras när filen öppnas i MS Excel.|
| [names](/cells/python-net/sv/aspose.cells/worksheetcollection/names) | Hämtar samlingen av alla Name-objekt i kalkylbladet.|
| [active_sheet_name](/cells/python-net/sv/aspose.cells/worksheetcollection/active_sheet_name) | Representerar namnet på det aktiva kalkylbladet när kalkylbladet öppnas.|
| [active_sheet_index](/cells/python-net/sv/aspose.cells/worksheetcollection/active_sheet_index) | Representerar indexet för det aktiva kalkylbladet när kalkylbladet öppnas.|
| [dxfs](/cells/python-net/sv/aspose.cells/worksheetcollection/dxfs) | Hämtar de huvudsakliga differentialformateringsposterna.|
| [xml_maps](/cells/python-net/sv/aspose.cells/worksheetcollection/xml_maps) | Hämtar och anger XML-mappningarna i arbetsboken.|
| [built_in_document_properties](/cells/python-net/sv/aspose.cells/worksheetcollection/built_in_document_properties) | Returnerar en [`DocumentProperty`](/cells/python-net/sv/aspose.cells.properties/documentproperty)-samling som representerar alla inbyggda dokumentegenskaper i kalkylarket.|
| [custom_document_properties](/cells/python-net/sv/aspose.cells/worksheetcollection/custom_document_properties) | Returnerar en [`DocumentProperty`](/cells/python-net/sv/aspose.cells.properties/documentproperty)-samling som representerar alla anpassade dokumentegenskaper i kalkylarket.|
| [ole_size](/cells/python-net/sv/aspose.cells/worksheetcollection/ole_size) | Hämtar och anger visad storlek när en arbetsboksfil används som ett Ole-objekt.|
| [external_links](/cells/python-net/sv/aspose.cells/worksheetcollection/external_links) |Representerar externa länkar i en arbetsbok.|
| [table_styles](/cells/python-net/sv/aspose.cells/worksheetcollection/table_styles) | Hämtar [`WorksheetCollection.table_styles`](/cells/python-net/sv/aspose.cells/worksheetcollection#table_styles)-objektet.|
| [revision_logs](/cells/python-net/sv/aspose.cells/worksheetcollection/revision_logs) | Representerar revisionsloggar.|
| [sensitivity_labels](/cells/python-net/sv/aspose.cells/worksheetcollection/sensitivity_labels) | Representerar alla känslighetsetiketter.|
| [capacity](/cells/python-net/sv/aspose.cells/worksheetcollection/capacity) | Hämtar eller anger antalet element som arraylistan kan innehålla.|



Hämtar elementet [`Worksheet`](/cells/python-net/sv/aspose.cells/worksheet) vid det angivna indexet.
###  Indexerare
| Namn| Beskrivning|
| :- | :- |
| [index] | Elementets nollbaserade index.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`get(self, index)`](/cells/python-net/sv/aspose.cells/worksheetcollection/get/#int) | Lägg till API for Python Via .Net. eftersom detta[int index] inte stöds.|
| [`get(self, sheet_name)`](/cells/python-net/sv/aspose.cells/worksheetcollection/get/#str) | Lägg till API for Python Via .Net. eftersom detta [sträng sheetName] inte stöds.|
| [`add(self, type)`](/cells/python-net/sv/aspose.cells/worksheetcollection/add/#aspose.cells.sheettype) | Lägger till ett arbetsblad i samlingen.|
| [`add(self)`](/cells/python-net/sv/aspose.cells/worksheetcollection/add/#) | Lägger till ett arbetsblad i samlingen.|
| [`add(self, sheet_name)`](/cells/python-net/sv/aspose.cells/worksheetcollection/add/#str) | Lägger till ett arbetsblad i samlingen.|
| [`register_add_in_function(self, add_in_file, function_name, lib)`](/cells/python-net/sv/aspose.cells/worksheetcollection/register_add_in_function/#str-str-bool) | Lägger till addin-funktionen i arbetsboken|
| [`register_add_in_function(self, id, function_name)`](/cells/python-net/sv/aspose.cells/worksheetcollection/register_add_in_function/#int-str) | Lägger till addin-funktionen i arbetsboken|
| [`add_copy(self, sheet_name)`](/cells/python-net/sv/aspose.cells/worksheetcollection/add_copy/#str) | Lägger till ett kalkylblad i samlingen och kopierar data från ett befintligt kalkylblad.|
| [`add_copy(self, sheet_index)`](/cells/python-net/sv/aspose.cells/worksheetcollection/add_copy/#int) | Lägger till ett kalkylblad i samlingen och kopierar data från ett befintligt kalkylblad.|
| [`add_copy(self, source, dest_sheet_names)`](/cells/python-net/sv/aspose.cells/worksheetcollection/add_copy/#list-list) | Kopiera en grupp med arbetsblad.|
| [`get_range_by_name(self, range_name)`](/cells/python-net/sv/aspose.cells/worksheetcollection/get_range_by_name/#str) | Hämtar Range-objekt med fördefinierat namn.|
| [`get_range_by_name(self, range_name, current_sheet_index, include_table)`](/cells/python-net/sv/aspose.cells/worksheetcollection/get_range_by_name/#str-int-bool) | Hämtar [`Range`](/cells/python-net/sv/aspose.cells/range) efter fördefinierat namn eller tabellens namn|
| [`refresh_pivot_tables(self)`](/cells/python-net/sv/aspose.cells/worksheetcollection/refresh_pivot_tables/#) | Uppdaterar alla pivottabeller i Excel-filen.|
| [`refresh_pivot_tables(self, option)`](/cells/python-net/sv/aspose.cells/worksheetcollection/refresh_pivot_tables/#aspose.cells.pivot.pivottablerefreshoption) | Uppdaterar alla pivottabeller i Excel-filen.|
| [`copy_to(self, array)`](/cells/python-net/sv/aspose.cells/worksheetcollection/copy_to/#list) |Kopierar hela arraylistan till en kompatibel endimensionell arraylista, med början i början av målarraylistan.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/sv/aspose.cells/worksheetcollection/copy_to/#int-list-int-int) | Kopierar ett elementområde från arraylistan till en kompatibel endimensionell arraylista, med början vid det angivna indexet för målarraylistan.|
| [`index_of(self, item, index)`](/cells/python-net/sv/aspose.cells/worksheetcollection/index_of/#aspose.cells.worksheet-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom intervallet av element i arraylistan som sträcker sig från det angivna indexet till det sista elementet.|
| [`index_of(self, item, index, count)`](/cells/python-net/sv/aspose.cells/worksheetcollection/index_of/#aspose.cells.worksheet-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom elementintervallet i arraylistan som börjar vid det angivna indexet och innehåller det angivna antalet element.|
| [`last_index_of(self, item)`](/cells/python-net/sv/aspose.cells/worksheetcollection/last_index_of/#aspose.cells.worksheet) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom hela arraylistan.|
| [`last_index_of(self, item, index)`](/cells/python-net/sv/aspose.cells/worksheetcollection/last_index_of/#aspose.cells.worksheet-int) |Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom intervallet av element i arraylistan som sträcker sig från det första elementet till det angivna indexet.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/sv/aspose.cells/worksheetcollection/last_index_of/#aspose.cells.worksheet-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom elementintervallet i arraylistan som innehåller det angivna antalet element och slutar vid det angivna indexet.|
| [`create_range(self, address, sheet_index)`](/cells/python-net/sv/aspose.cells/worksheetcollection/create_range/#str-int) | Skapar ett [`Range`](/cells/python-net/sv/aspose.cells/range)-objekt från en adress i intervallet.|
| [`create_union_range(self, address, sheet_index)`](/cells/python-net/sv/aspose.cells/worksheetcollection/create_union_range/#str-int) | Skapar ett [`Range`](/cells/python-net/sv/aspose.cells/range)-objekt från en adress i intervallet.|
| [`get_sheet_by_code_name(self, code_name)`](/cells/python-net/sv/aspose.cells/worksheetcollection/get_sheet_by_code_name/#str) | Hämtar kalkylbladet med kodnamnet.|
| [`sort_names(self)`](/cells/python-net/sv/aspose.cells/worksheetcollection/sort_names/#) | Sorterar de definierade namnen.|
| [`swap_sheet(self, sheet_index1, sheet_index2)`](/cells/python-net/sv/aspose.cells/worksheetcollection/swap_sheet/#int-int) | Byter ut de två arken.|
| [`remove_by_name(self, name)`](/cells/python-net/sv/aspose.cells/worksheetcollection/remove_by_name/#str) | Ta bort ett ark efter arknamn. (CELLSPYTHONNET-192)|
| [`remove_by_index(self, index)`](/cells/python-net/sv/aspose.cells/worksheetcollection/remove_by_index/#int) | Ta bort ett ark för ark-index|
| [`remove_at(self, name)`](/cells/python-net/sv/aspose.cells/worksheetcollection/remove_at/#str) | Tar bort elementet vid ett angivet namn.|
| [`get_named_ranges(self)`](/cells/python-net/sv/aspose.cells/worksheetcollection/get_named_ranges/#) | Hämtar alla fördefinierade namngivna områden i kalkylbladet.|
| [`get_named_ranges_and_tables(self)`](/cells/python-net/sv/aspose.cells/worksheetcollection/get_named_ranges_and_tables/#) | Hämtar alla fördefinierade namngivna områden i kalkylbladet.|
| [`set_ole_size(self, start_row, end_row, start_column, end_column)`](/cells/python-net/sv/aspose.cells/worksheetcollection/set_ole_size/#int-int-int-int) | Anger visad storlek när arbetsboksfilen används som ett Ole-objekt.|
| [`clear_pivottables(self)`](/cells/python-net/sv/aspose.cells/worksheetcollection/clear_pivottables/#) |Rensar pivottabeller från kalkylbladet.|
| [`refresh_all(self)`](/cells/python-net/sv/aspose.cells/worksheetcollection/refresh_all/#) | Uppdatera alla pivottabeller och diagram med pivotkällan.|
| [`binary_search(self, item)`](/cells/python-net/sv/aspose.cells/worksheetcollection/binary_search/#aspose.cells.worksheet) | Söker igenom hela den sorterade arraylistan efter ett element med hjälp av standardjämföraren och returnerar elementets nollbaserade index.|



###  Exempel

```python
from aspose.cells import Workbook

workbook = Workbook()
sheets = workbook.worksheets
# Add a worksheet
sheets.add()
# Change the name of a worksheet
sheets[0].name = "First Sheet"
# Set the active sheet to the second worksheet
sheets.active_sheet_index = 1

```

###  Se även
* modul [`aspose.cells`](..)
* klass [`DocumentProperty`](/cells/python-net/sv/aspose.cells.properties/documentproperty)
* klass [`Range`](/cells/python-net/sv/aspose.cells/range)
* klass [`Worksheet`](/cells/python-net/sv/aspose.cells/worksheet)
