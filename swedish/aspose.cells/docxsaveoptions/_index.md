---
title: DocxSaveOptions klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 510
url: /sv/aspose.cells/docxsaveoptions/
is_root: false
---
##  DocxSaveOptions klass
Representerar alternativ för att spara .docx-fil.



**Arv:** [`DocxSaveOptions`](/cells/python-net/aspose.cells/docxsaveoptions) → 
[`PaginatedSaveOptions`](/cells/python-net/aspose.cells/paginatedsaveoptions) → 
[`SaveOptions`](/cells/python-net/sv/aspose.cells/saveoptions)



Typen DocxSaveOptions avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [__init__](/cells/python-net/sv/aspose.cells/docxsaveoptions/__init__/#) | Representerar alternativ för att spara .docx-fil.|
| [__init__](/cells/python-net/sv/aspose.cells/docxsaveoptions/__init__/#bool) | Representerar alternativ för att spara .docx-fil.|


###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [save_format](/cells/python-net/sv/aspose.cells/docxsaveoptions/save_format) | Hämtar spara filformatet.|
| [clear_data](/cells/python-net/sv/aspose.cells/docxsaveoptions/clear_data) | Gör arbetsboken tom efter att du har sparat filen.|
| [cached_file_folder](/cells/python-net/sv/aspose.cells/docxsaveoptions/cached_file_folder) | Den cachade filmappen används för att lagra en del stora data.|
| [validate_merged_areas](/cells/python-net/sv/aspose.cells/docxsaveoptions/validate_merged_areas) | Anger om sammanslagna celler ska valideras innan filen sparas.|
| [merge_areas](/cells/python-net/sv/aspose.cells/docxsaveoptions/merge_areas) | Anger om områdena för villkorlig formatering och validering ska slås samman innan filen sparas.|
| [create_directory](/cells/python-net/sv/aspose.cells/docxsaveoptions/create_directory) | Om sant och katalogen inte finns skapas katalogen automatiskt innan filen sparas.|
| [sort_names](/cells/python-net/sv/aspose.cells/docxsaveoptions/sort_names) | Anger om du sorterar definierade namn innan filen sparas.|
| [sort_external_names](/cells/python-net/sv/aspose.cells/docxsaveoptions/sort_external_names) | Anger om externt definierade namn sorteras innan filen sparas.|
| [refresh_chart_cache](/cells/python-net/sv/aspose.cells/docxsaveoptions/refresh_chart_cache) | Anger om diagramcachedata uppdateras|
| [warning_callback](/cells/python-net/sv/aspose.cells/docxsaveoptions/warning_callback) | Får eller ställer in varningsåteruppringning.|
| [update_smart_art](/cells/python-net/sv/aspose.cells/docxsaveoptions/update_smart_art) | Indikerar om inställningen för smart konst uppdateras.<br/> Standardvärdet är falskt.|
| [default_font](/cells/python-net/sv/aspose.cells/docxsaveoptions/default_font) | När tecken i Excel är Unicode och inte är inställda med korrekt typsnitt i cellstil,<br/>De kan visas som block i pdf, bild.<br/>Ställ in standardteckensnittet som MingLiu eller MS Gothic för att visa dessa tecken.<br/> Om den här egenskapen inte är inställd kommer Aspose.Cells att använda systemets standardteckensnitt för att visa dessa unicode-tecken.|
| [check_workbook_default_font](/cells/python-net/sv/aspose.cells/docxsaveoptions/check_workbook_default_font) | När tecken i Excel är Unicode och inte är inställda med korrekt typsnitt i cellstil,<br/>De kan visas som block i pdf, bild.<br/> Ställ in detta på sant för att försöka använda arbetsbokens standardteckensnitt för att visa dessa tecken först.|
| [check_font_compatibility](/cells/python-net/sv/aspose.cells/docxsaveoptions/check_font_compatibility) | Anger om teckensnittskompatibilitet ska kontrolleras för varje tecken i texten.|
| [is_font_substitution_char_granularity](/cells/python-net/sv/aspose.cells/docxsaveoptions/is_font_substitution_char_granularity) |Indikerar om teckensnittet endast ska bytas ut när cellteckensnittet inte är kompatibelt med det.|
| [one_page_per_sheet](/cells/python-net/sv/aspose.cells/docxsaveoptions/one_page_per_sheet) | Om OnePagePerSheet är sant , kommer allt innehåll på ett ark endast att matas ut till en sida som resultat.<br/> Pappersstorleken för sidinställningarna kommer att vara ogiltig, och de andra inställningarna för sidinställningarna<br/> kommer fortfarande att träda i kraft.|
| [all_columns_in_one_page_per_sheet](/cells/python-net/sv/aspose.cells/docxsaveoptions/all_columns_in_one_page_per_sheet) | Om AllColumnsInOnePagePerSheet är sant , kommer allt kolumninnehåll i ett ark att matas ut till endast en sida i resultat.<br/> Bredden på pappersstorleken för sidinställningarna ignoreras, och de andra inställningarna för sidinställningarna<br/> kommer fortfarande att träda i kraft.|
| [ignore_error](/cells/python-net/sv/aspose.cells/docxsaveoptions/ignore_error) | Indikerar om du behöver dölja felet under renderingen.<br/> Felet kan vara fel i form, bild, diagramrendering, etc.|
| [output_blank_page_when_nothing_to_print](/cells/python-net/sv/aspose.cells/docxsaveoptions/output_blank_page_when_nothing_to_print) | Indikerar om en tom sida ska matas ut när det inte finns något att skriva ut.|
| [page_index](/cells/python-net/sv/aspose.cells/docxsaveoptions/page_index) | Hämtar eller ställer in det 0-baserade indexet för den första sidan som ska sparas.|
| [page_count](/cells/python-net/sv/aspose.cells/docxsaveoptions/page_count) | Hämtar eller ställer in antalet sidor som ska sparas.|
| [printing_page_type](/cells/python-net/sv/aspose.cells/docxsaveoptions/printing_page_type) | Indikerar vilka sidor som inte kommer att skrivas ut.|
| [gridline_type](/cells/python-net/sv/aspose.cells/docxsaveoptions/gridline_type) | Hämtar eller ställer in rutnätstyp.|
| [text_cross_type](/cells/python-net/sv/aspose.cells/docxsaveoptions/text_cross_type) | Hämtar eller ställer in visning av texttyp när textbredden är större än cellbredden.|
| [default_edit_language](/cells/python-net/sv/aspose.cells/docxsaveoptions/default_edit_language) | Hämtar eller ställer in standardspråk för redigering.|
| [sheet_set](/cells/python-net/sv/aspose.cells/docxsaveoptions/sheet_set) |Hämtar eller ställer in arken att rendera. Standard är alla synliga ark i arbetsboken: [`SheetSet.visible`](/cells/python-net/sv/aspose.cells.rendering/sheetset#visible).|
| [draw_object_event_handler](/cells/python-net/sv/aspose.cells/docxsaveoptions/draw_object_event_handler) | Implementerar detta gränssnitt för att få DrawObject och Bound vid rendering.|
| [page_saving_callback](/cells/python-net/sv/aspose.cells/docxsaveoptions/page_saving_callback) | Kontrollera/indikera framsteg för sidsparprocessen.|
| [emf_render_setting](/cells/python-net/sv/aspose.cells/docxsaveoptions/emf_render_setting) | Inställning för rendering av Emf-metafil.|



###  Se även
* modul [`aspose.cells`](..)
* klass [`DocxSaveOptions`](/cells/python-net/sv/aspose.cells/docxsaveoptions)
* klass [`PaginatedSaveOptions`](/cells/python-net/sv/aspose.cells/paginatedsaveoptions)
* klass [`SaveOptions`](/cells/python-net/sv/aspose.cells/saveoptions)
