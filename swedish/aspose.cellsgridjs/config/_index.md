---
title: Config klass
second_title: Aspose.Cells.GridJs for Python via .NET API Referenser
description:
type: docs
weight: 10
url: /sv/aspose.cellsgridjs/config/
is_root: false
---
##  Config klass

Representerar alla inställningar för GridJs



Typen Config avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [__init__](/cells/python-net/sv/aspose.cellsgridjs/config/__init__/#) | Konstruerar en ny instans av Config|


###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [save_html_as_zip](/cells/python-net/sv/aspose.cellsgridjs/config/save_html_as_zip) | Ställer in/hämtar om html-fil ska sparas som zip-arkiv, standardinställningen är falsk.|
| [same_image_detecting](/cells/python-net/sv/aspose.cellsgridjs/config/same_image_detecting) | Ställer in/hämtar om det ska kontrolleras om bilden har samma källa, standard är sant<br/> standardvärdet är sant.|
| [auto_optimize_for_large_cells](/cells/python-net/sv/aspose.cellsgridjs/config/auto_optimize_for_large_cells) | Ställer in/hämtar om laddningsprestandan ska optimeras automatiskt för kalkylblad med stora celler<br/> ignorera vissa stilar /kanter för att minska laddningstiden<br/> standardvärdet är sant.|
| [islimit_shape_or_image](/cells/python-net/sv/aspose.cellsgridjs/config/islimit_shape_or_image) |Ställer in/hämtar om det totala antalet visningsformer/bilder ska begränsas i ett kalkylblad, om satt till sant,<br/> GridJs kommer att begränsa den totala visningsformen/bildstorleken i ett kalkylblad till MaxShapeOrImageCount<br/> standardvärdet är sant.|
| [max_shape_or_image_count](/cells/python-net/sv/aspose.cellsgridjs/config/max_shape_or_image_count) | Ställer in/får den totala visningsformen/bildantalet inuti det aktiva arket, det kommer att påverkas när IslimitShapes=true.<br/> standardvärdet är 100.|
| [max_total_shape_or_image_count](/cells/python-net/sv/aspose.cellsgridjs/config/max_total_shape_or_image_count) | Ställer in/får det totala antalet visningsformer/bilder i hela arbetsboken, det kommer att påverkas när IslimitShapes=true.<br/> standardvärdet är 300.|
| [max_shape_or_image_width_or_height](/cells/python-net/sv/aspose.cellsgridjs/config/max_shape_or_image_width_or_height) | Ställer in/hämtar max bredd eller höjd för en form/bild, GridJs ignorerar formen/bilden med bredden eller höjden större än detta, det kommer att påverka när IslimitShapes=true.<br/> standardvärdet är 10 000.|
| [max_pdf_save_seconds](/cells/python-net/sv/aspose.cellsgridjs/config/max_pdf_save_seconds) | Ställer in/får max timeout sekunder vid spara till pdf.<br/> standardvärdet är 10.|
| [ignore_empty_content](/cells/python-net/sv/aspose.cellsgridjs/config/ignore_empty_content) | Ställer in/hämtar om maxintervallet som inkluderar data, stil, sammanslagna celler och former ska visas.<br/> om den sista raden eller kolumnen innehåller celler utan värde och formel men har anpassad stil<br/>då kommer vi inte att visa den här raden/kolumnen när denna vlaue är sann.<br/> standardvärdet är sant.|
| [use_print_area](/cells/python-net/sv/aspose.cellsgridjs/config/use_print_area) |Ställer in/hämtar om PageSetup.PrintArea ska användas för gränssnittets visningsområde när kalkylbladet har inställningen PageSetup för PrintArea.<br/> standardvärdet är false.|
| [load_time_out](/cells/python-net/sv/aspose.cellsgridjs/config/load_time_out) | Ställer in/får ett timeoutavbrott i millisekunder i laddningsfil, när kostnadsperioden för laddning av filen är längre än förväntat, kommer det att leda till undantag.<br/> standardvärdet är -1, vilket betyder att inget timeout-avbrott är inställt.|
| [show_chart_sheet](/cells/python-net/sv/aspose.cellsgridjs/config/show_chart_sheet) | Ställer in/hämtar om diagrammet ska visas.<br/> standardvärdet är false.|
| [page_size](/cells/python-net/sv/aspose.cellsgridjs/config/page_size) | Ställer in/hämtar om paginering ska göras<br/> GridJs kommer att begränsa radstorleken baserat på sidstorleken, om sidstorleken är -1 kommer den inte att göra paginering<br/> standardvärdet är -1|
| [empty_sheet_max_row](/cells/python-net/sv/aspose.cellsgridjs/config/empty_sheet_max_row) | Ställer in/får standard maxrad för ett tomt kalkylblad.<br/> standardvärdet är 12.|
| [empty_sheet_max_col](/cells/python-net/sv/aspose.cellsgridjs/config/empty_sheet_max_col) | Ställer in/får standard maxkolumn för ett tomt kalkylblad.<br/> standardvärdet är 15.|
| [picture_cache_directory](/cells/python-net/sv/aspose.cellsgridjs/config/picture_cache_directory) | Ställer in/hämtar cachekatalogen för bilder.(detta träder i kraft när GridJsWorkbook.CacheImp är null)<br/> standardsökvägen kommer att vara "_piccache" i FileCacheDirectory.|
| [file_cache_directory](/cells/python-net/sv/aspose.cellsgridjs/config/file_cache_directory) |Ställer in/hämtar cachekatalogen för kalkylarksfil.<br/> Vi måste ställa in den till en specifik sökväg innan vi använder GridJs.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [set_license](/cells/python-net/sv/aspose.cellsgridjs/config/set_license/#str) |  |
| [set_license](/cells/python-net/sv/aspose.cellsgridjs/config/set_license/#io.RawIOBase) | Licensierar komponenten.|
| [set_font_folder](/cells/python-net/sv/aspose.cellsgridjs/config/set_font_folder/#str-bool) | Ställer in teckensnittsmappen|
| [set_font_folders](/cells/python-net/sv/aspose.cellsgridjs/config/set_font_folders/#list-bool) | Ställer in typsnittsmapparna|



###  Se även
* modul [`aspose.cellsgridjs`](..)
