---
title: TxtSaveOptions klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1500
url: /sv/aspose.cells/txtsaveoptions/
is_root: false
---
##  TxtSaveOptions klass
Representerar sparalternativen för csv/tabbavgränsade/andra textformat.



**Arv:** [`TxtSaveOptions`](/cells/python-net/aspose.cells/txtsaveoptions) → 
[`SaveOptions`](/cells/python-net/sv/aspose.cells/saveoptions)



Typen TxtSaveOptions avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [`__init__(self)`](/cells/python-net/sv/aspose.cells/txtsaveoptions/__init__/#) | Skapar alternativ för att spara textfiler.|
| [`__init__(self, save_format)`](/cells/python-net/sv/aspose.cells/txtsaveoptions/__init__/#aspose.cells.saveformat) | Skapar alternativ för att spara textfiler.|


###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [save_format](/cells/python-net/sv/aspose.cells/txtsaveoptions/save_format) | Hämtar filformatet för att spara.|
| [clear_data](/cells/python-net/sv/aspose.cells/txtsaveoptions/clear_data) | Gör arbetsboken tom efter att du har sparat filen.|
| [cached_file_folder](/cells/python-net/sv/aspose.cells/txtsaveoptions/cached_file_folder) | Mappen för tillfälliga filer som kan användas som datacache.|
| [validate_merged_areas](/cells/python-net/sv/aspose.cells/txtsaveoptions/validate_merged_areas) | Anger om sammanslagna celler ska valideras innan filen sparas.|
| [merge_areas](/cells/python-net/sv/aspose.cells/txtsaveoptions/merge_areas) | Anger om områdena för villkorlig formatering och validering ska sammanfogas innan filen sparas.|
| [create_directory](/cells/python-net/sv/aspose.cells/txtsaveoptions/create_directory) | Om "true" är inställt och katalogen inte finns, skapas katalogen automatiskt innan filen sparas.|
| [sort_names](/cells/python-net/sv/aspose.cells/txtsaveoptions/sort_names) |Anger om definierade namn ska sorteras innan filen sparas.|
| [sort_external_names](/cells/python-net/sv/aspose.cells/txtsaveoptions/sort_external_names) | Anger om externt definierade namn ska sorteras innan filen sparas.|
| [refresh_chart_cache](/cells/python-net/sv/aspose.cells/txtsaveoptions/refresh_chart_cache) | Anger om uppdatering av diagramcachedata ska ske|
| [check_excel_restriction](/cells/python-net/sv/aspose.cells/txtsaveoptions/check_excel_restriction) | Om begränsning av Excel-filen ska kontrolleras när användaren ändrar celler relaterade objekt.<br/>Till exempel tillåter inte Excel inmatning av strängvärden som är längre än 32K.<br/> När du anger ett värde som är längre än 32K kommer det att avkortas.|
| [update_smart_art](/cells/python-net/sv/aspose.cells/txtsaveoptions/update_smart_art) | Anger om inställningen för smart konst uppdateras.<br/> Standardvärdet är falskt.|
| [encrypt_document_properties](/cells/python-net/sv/aspose.cells/txtsaveoptions/encrypt_document_properties) | Anger om dokumentegenskaper ska krypteras när det sparas som en .xls-fil.<br/> Standardvärdet är sant.|
| [separator](/cells/python-net/sv/aspose.cells/txtsaveoptions/separator) | Hämtar och anger teckenavgränsare för textfil.|
| [separator_string](/cells/python-net/sv/aspose.cells/txtsaveoptions/separator_string) | Hämtar och anger ett strängvärde som avgränsare.|
| [encoding](/cells/python-net/sv/aspose.cells/txtsaveoptions/encoding) | Hämtar och ställer in standardkodningen.|
| [always_quoted](/cells/python-net/sv/aspose.cells/txtsaveoptions/always_quoted) | Anger om '"' alltid ska läggas till för varje fält.<br/>Om det är sant kommer alla värden att anges i citat;<br/>Om falskt anges kommer värden endast att citeras när det behövs (till exempel<br/>när värden innehåller specialtecken som '"', '\n' eller avgränsare).<br/> Standardvärdet är falskt.|
| [quote_type](/cells/python-net/sv/aspose.cells/txtsaveoptions/quote_type) |Hämtar eller anger hur värden ska citeras i den exporterade textfilen.|
| [format_strategy](/cells/python-net/sv/aspose.cells/txtsaveoptions/format_strategy) | Hämtar och anger formatstrategin vid export av cellvärdet som sträng.|
| [trim_leading_blank_row_and_column](/cells/python-net/sv/aspose.cells/txtsaveoptions/trim_leading_blank_row_and_column) | Anger om inledande tomma rader och kolumner ska trimmas på samma sätt som i MS Excel.<br/> Standardvärdet är sant.|
| [trim_tailing_blank_cells](/cells/python-net/sv/aspose.cells/txtsaveoptions/trim_tailing_blank_cells) | Anger om tomma celler som lämnas kvar på en rad ska trimmas. Standardvärdet är falskt.|
| [keep_separators_for_blank_row](/cells/python-net/sv/aspose.cells/txtsaveoptions/keep_separators_for_blank_row) | Anger om avgränsare ska matas ut för tomma rader.<br/> Standardvärdet är falskt, så som standard kommer innehållet för den tomma raden att vara tomt.|
| [export_area](/cells/python-net/sv/aspose.cells/txtsaveoptions/export_area) | Cellintervallet som ska exporteras.|
| [export_quote_prefix](/cells/python-net/sv/aspose.cells/txtsaveoptions/export_quote_prefix) | Anger om citattecknet ska exporteras som en del av värdet i en cell<br/> när [`Style.quote_prefix`](/cells/python-net/sv/aspose.cells/style#quote_prefix) är sant för den. Standardvärdet är falskt.|
| [export_all_sheets](/cells/python-net/sv/aspose.cells/txtsaveoptions/export_all_sheets) | Anger om alla ark ska exporteras till textfilen.<br/> Om det är falskt, exportera bara ActiveCard, precis som i MS Excel.|



###  Se även
* modul [`aspose.cells`](..)
* klass [`SaveOptions`](/cells/python-net/sv/aspose.cells/saveoptions)
* klass [`TxtSaveOptions`](/cells/python-net/sv/aspose.cells/txtsaveoptions)
