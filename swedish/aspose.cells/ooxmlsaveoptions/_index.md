---
title: OoxmlSaveOptions klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1050
url: /sv/aspose.cells/ooxmlsaveoptions/
is_root: false
---
##  OoxmlSaveOptions klass
Representerar alternativen för att spara en öppen XML-fil i Office.



**Arv:** [`OoxmlSaveOptions`](/cells/python-net/aspose.cells/ooxmlsaveoptions) → 
[`SaveOptions`](/cells/python-net/sv/aspose.cells/saveoptions)



Typen OoxmlSaveOptions avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [`__init__(self)`](/cells/python-net/sv/aspose.cells/ooxmlsaveoptions/__init__/#) | Skapar alternativ för att spara Office Open XML-filer.|
| [`__init__(self, save_format)`](/cells/python-net/sv/aspose.cells/ooxmlsaveoptions/__init__/#aspose.cells.saveformat) | Skapar alternativ för att spara Office Open XML-filer.|


###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [save_format](/cells/python-net/sv/aspose.cells/ooxmlsaveoptions/save_format) | Hämtar filformatet för att spara.|
| [clear_data](/cells/python-net/sv/aspose.cells/ooxmlsaveoptions/clear_data) | Gör arbetsboken tom efter att du har sparat filen.|
| [cached_file_folder](/cells/python-net/sv/aspose.cells/ooxmlsaveoptions/cached_file_folder) | Mappen för tillfälliga filer som kan användas som datacache.|
| [validate_merged_areas](/cells/python-net/sv/aspose.cells/ooxmlsaveoptions/validate_merged_areas) | Anger om sammanslagna celler ska valideras innan filen sparas.|
| [merge_areas](/cells/python-net/sv/aspose.cells/ooxmlsaveoptions/merge_areas) | Anger om områdena för villkorlig formatering och validering ska sammanfogas innan filen sparas.|
| [create_directory](/cells/python-net/sv/aspose.cells/ooxmlsaveoptions/create_directory) | Om "true" är inställt och katalogen inte finns, skapas katalogen automatiskt innan filen sparas.|
| [sort_names](/cells/python-net/sv/aspose.cells/ooxmlsaveoptions/sort_names) |Anger om definierade namn ska sorteras innan filen sparas.|
| [sort_external_names](/cells/python-net/sv/aspose.cells/ooxmlsaveoptions/sort_external_names) | Anger om externt definierade namn ska sorteras innan filen sparas.|
| [refresh_chart_cache](/cells/python-net/sv/aspose.cells/ooxmlsaveoptions/refresh_chart_cache) | Anger om uppdatering av diagramcachedata ska ske|
| [check_excel_restriction](/cells/python-net/sv/aspose.cells/ooxmlsaveoptions/check_excel_restriction) | Om begränsning av Excel-filen ska kontrolleras när användaren ändrar celler relaterade objekt.<br/>Till exempel tillåter inte Excel inmatning av strängvärden som är längre än 32K.<br/> När du anger ett värde som är längre än 32K kommer det att avkortas.|
| [update_smart_art](/cells/python-net/sv/aspose.cells/ooxmlsaveoptions/update_smart_art) | Anger om inställningen för smart konst uppdateras.<br/> Standardvärdet är falskt.|
| [encrypt_document_properties](/cells/python-net/sv/aspose.cells/ooxmlsaveoptions/encrypt_document_properties) | Anger om dokumentegenskaper ska krypteras när det sparas som en .xls-fil.<br/> Standardvärdet är sant.|
| [export_cell_name](/cells/python-net/sv/aspose.cells/ooxmlsaveoptions/export_cell_name) | Anger om cellnamnet ska exporteras till Excel2007 .xlsx (.xlsm, .xltx, .xltm)-fil.<br/>Om utdatafilen kan nås av SQL Server DTS måste det här värdet vara sant.<br/>Om värdet ställs in på falskt ökar prestandan avsevärt och filstorleken minskar när stora filer skapas.<br/> Standardvärdet är sant.|
| [update_zoom](/cells/python-net/sv/aspose.cells/ooxmlsaveoptions/update_zoom) | Anger om skalningsfaktorn ska uppdateras innan filen sparas<br/> om egenskaperna PageSetup.FitToPagesWide och PageSetup.FitToPagesTall styr hur kalkylbladet skalas.|
| [enable_zip64](/cells/python-net/sv/aspose.cells/ooxmlsaveoptions/enable_zip64) | Använd alltid ZIP64-tillägg när du skriver zip-arkiv, även när det är onödigt.|
| [embed_ooxml_as_ole_object](/cells/python-net/sv/aspose.cells/ooxmlsaveoptions/embed_ooxml_as_ole_object) | Anger om Ooxml-filer från OleObject bäddas in som OLE-objekt.|
| [compression_type](/cells/python-net/sv/aspose.cells/ooxmlsaveoptions/compression_type) | Hämtar och anger komprimeringstypen för ooxml-filen.|
| [wps_compatibility](/cells/python-net/sv/aspose.cells/ooxmlsaveoptions/wps_compatibility) | Anger om xls-filen ska göras mer kompatibel med WPS.|



###  Se även
* modul [`aspose.cells`](..)
* klass [`OoxmlSaveOptions`](/cells/python-net/sv/aspose.cells/ooxmlsaveoptions)
* klass [`SaveOptions`](/cells/python-net/sv/aspose.cells/saveoptions)
