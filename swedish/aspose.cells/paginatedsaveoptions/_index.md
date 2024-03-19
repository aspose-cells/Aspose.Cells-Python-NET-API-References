---
title: PaginatedSaveOptions klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1190
url: /sv/aspose.cells/paginatedsaveoptions/
is_root: false
---
##  PaginatedSaveOptions klass
Representerar alternativen för paginering.



**Arv:** [`PaginatedSaveOptions`](/cells/python-net/aspose.cells/paginatedsaveoptions) → 
[`SaveOptions`](/cells/python-net/sv/aspose.cells/saveoptions)



Typen PaginatedSaveOptions avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [save_format](/cells/python-net/sv/aspose.cells/paginatedsaveoptions/save_format) | Hämtar spara filformatet.|
| [clear_data](/cells/python-net/sv/aspose.cells/paginatedsaveoptions/clear_data) | Gör arbetsboken tom efter att du har sparat filen.|
| [cached_file_folder](/cells/python-net/sv/aspose.cells/paginatedsaveoptions/cached_file_folder) | Den cachade filmappen används för att lagra en del stora data.|
| [validate_merged_areas](/cells/python-net/sv/aspose.cells/paginatedsaveoptions/validate_merged_areas) | Anger om sammanslagna celler ska valideras innan filen sparas.|
| [merge_areas](/cells/python-net/sv/aspose.cells/paginatedsaveoptions/merge_areas) | Anger om områdena för villkorlig formatering och validering ska slås samman innan filen sparas.|
| [create_directory](/cells/python-net/sv/aspose.cells/paginatedsaveoptions/create_directory) | Om sant och katalogen inte finns skapas katalogen automatiskt innan filen sparas.|
| [sort_names](/cells/python-net/sv/aspose.cells/paginatedsaveoptions/sort_names) | Anger om du sorterar definierade namn innan filen sparas.|
| [sort_external_names](/cells/python-net/sv/aspose.cells/paginatedsaveoptions/sort_external_names) | Anger om externt definierade namn sorteras innan filen sparas.|
| [refresh_chart_cache](/cells/python-net/sv/aspose.cells/paginatedsaveoptions/refresh_chart_cache) | Anger om diagramcachedata uppdateras|
| [warning_callback](/cells/python-net/sv/aspose.cells/paginatedsaveoptions/warning_callback) | Får eller ställer in varningsåteruppringning.|
| [update_smart_art](/cells/python-net/sv/aspose.cells/paginatedsaveoptions/update_smart_art) | Indikerar om inställningen för smart konst uppdateras.<br/> Standardvärdet är falskt.|
| [default_font](/cells/python-net/sv/aspose.cells/paginatedsaveoptions/default_font) | När tecken i Excel är Unicode och inte är inställda med korrekt typsnitt i cellstil,<br/>De kan visas som block i pdf, bild.<br/>Ställ in standardteckensnittet som MingLiu eller MS Gothic för att visa dessa tecken.<br/> Om den här egenskapen inte är inställd kommer Aspose.Cells att använda systemets standardteckensnitt för att visa dessa unicode-tecken.|
| [check_workbook_default_font](/cells/python-net/sv/aspose.cells/paginatedsaveoptions/check_workbook_default_font) | När tecken i Excel är Unicode och inte är inställda med korrekt typsnitt i cellstil,<br/>De kan visas som block i pdf, bild.<br/> Ställ in detta på sant för att försöka använda arbetsbokens standardteckensnitt för att visa dessa tecken först.|
| [check_font_compatibility](/cells/python-net/sv/aspose.cells/paginatedsaveoptions/check_font_compatibility) | Anger om teckensnittskompatibilitet ska kontrolleras för varje tecken i texten.|
| [is_font_substitution_char_granularity](/cells/python-net/sv/aspose.cells/paginatedsaveoptions/is_font_substitution_char_granularity) |Indikerar om teckensnittet endast ska bytas ut när cellteckensnittet inte är kompatibelt med det.|
| [one_page_per_sheet](/cells/python-net/sv/aspose.cells/paginatedsaveoptions/one_page_per_sheet) | Om OnePagePerSheet är sant , kommer allt innehåll på ett ark endast att matas ut till en sida som resultat.<br/> Pappersstorleken för sidinställningarna kommer att vara ogiltig, och de andra inställningarna för sidinställningarna<br/> kommer fortfarande att träda i kraft.|
| [all_columns_in_one_page_per_sheet](/cells/python-net/sv/aspose.cells/paginatedsaveoptions/all_columns_in_one_page_per_sheet) | Om AllColumnsInOnePagePerSheet är sant , kommer allt kolumninnehåll i ett ark att matas ut till endast en sida i resultat.<br/> Bredden på pappersstorleken för sidinställningarna ignoreras, och de andra inställningarna för sidinställningarna<br/> kommer fortfarande att träda i kraft.|
| [ignore_error](/cells/python-net/sv/aspose.cells/paginatedsaveoptions/ignore_error) | Indikerar om du behöver dölja felet under renderingen.<br/> Felet kan vara fel i form, bild, diagramrendering, etc.|
| [output_blank_page_when_nothing_to_print](/cells/python-net/sv/aspose.cells/paginatedsaveoptions/output_blank_page_when_nothing_to_print) | Indikerar om en tom sida ska matas ut när det inte finns något att skriva ut.|
| [page_index](/cells/python-net/sv/aspose.cells/paginatedsaveoptions/page_index) | Hämtar eller ställer in det 0-baserade indexet för den första sidan som ska sparas.|
| [page_count](/cells/python-net/sv/aspose.cells/paginatedsaveoptions/page_count) | Hämtar eller ställer in antalet sidor som ska sparas.|
| [printing_page_type](/cells/python-net/sv/aspose.cells/paginatedsaveoptions/printing_page_type) | Indikerar vilka sidor som inte kommer att skrivas ut.|
| [gridline_type](/cells/python-net/sv/aspose.cells/paginatedsaveoptions/gridline_type) | Hämtar eller ställer in rutnätstyp.|
| [text_cross_type](/cells/python-net/sv/aspose.cells/paginatedsaveoptions/text_cross_type) | Hämtar eller ställer in visning av texttyp när textbredden är större än cellbredden.|
| [default_edit_language](/cells/python-net/sv/aspose.cells/paginatedsaveoptions/default_edit_language) | Hämtar eller ställer in standardspråk för redigering.|
| [sheet_set](/cells/python-net/sv/aspose.cells/paginatedsaveoptions/sheet_set) |Hämtar eller ställer in arken att rendera. Standard är alla synliga ark i arbetsboken: [`SheetSet.visible`](/cells/python-net/sv/aspose.cells.rendering/sheetset#visible).|
| [draw_object_event_handler](/cells/python-net/sv/aspose.cells/paginatedsaveoptions/draw_object_event_handler) | Implementerar detta gränssnitt för att få DrawObject och Bound vid rendering.|
| [page_saving_callback](/cells/python-net/sv/aspose.cells/paginatedsaveoptions/page_saving_callback) | Kontrollera/indikera framsteg för sidsparprocessen.|
| [emf_render_setting](/cells/python-net/sv/aspose.cells/paginatedsaveoptions/emf_render_setting) | Inställning för rendering av Emf-metafil.|



###  Se även
* modul [`aspose.cells`](..)
* klass [`PaginatedSaveOptions`](/cells/python-net/sv/aspose.cells/paginatedsaveoptions)
* klass [`SaveOptions`](/cells/python-net/sv/aspose.cells/saveoptions)
