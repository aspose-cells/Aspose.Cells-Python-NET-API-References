---
title: SvgImageOptions klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 130
url: /sv/aspose.cells.rendering/svgimageoptions/
is_root: false
---
##  SvgImageOptions klass
Alternativ för att generera Svg-bilder.



**Arv:** [`SvgImageOptions`](/cells/python-net/aspose.cells.rendering/svgimageoptions) → 
[`ImageOrPrintOptions`](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions)



Typen SvgImageOptions avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [`__init__(self)`](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/__init__/#) | Rektor.|


###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [save_format](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/save_format) | Hämtar eller ställer in utdatafilformattypen<br/> Support Tiff/XPS|
| [print_with_status_dialog](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/print_with_status_dialog) | Om PrintWithStatusDialog = true visas en dialogruta som visar aktuell utskriftsstatus.<br/> annars visas ingen sådan dialogruta.|
| [horizontal_resolution](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/horizontal_resolution) | Hämtar eller ställer in den horisontella upplösningen för genererade bilder, i punkter per tum.|
| [vertical_resolution](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/vertical_resolution) | Hämtar eller ställer in den vertikala upplösningen för genererade bilder, i punkter per tum.|
| [tiff_compression](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/tiff_compression) | Hämtar eller ställer in vilken typ av komprimering som endast ska tillämpas när sidor sparas i formatet `Tiff`.|
| [tiff_color_depth](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/tiff_color_depth) | Hämtar eller ställer in bitdjup så att det endast gäller när sidor sparas i formatet `Tiff`.|
| [tiff_binarization_method](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/tiff_binarization_method) | Hämtar eller ställer in metoden som används vid konvertering av bilder till 1 bpp-format<br/>när [`ImageOrPrintOptions.image_type`](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions#image_type) är Tiff och [`ImageOrPrintOptions.tiff_compression`](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions#tiff_compression) är lika med Ccitt3 eller Ccitt4.|
| [printing_page](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/printing_page) | Anger vilka sidor som inte kommer att skrivas ut.|
| [quality](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/quality) | Hämtar eller ställer in ett värde som bestämmer kvaliteten på de genererade bilderna<br/> att endast tillämpas när sidor sparas i formatet `Jpeg`. Standardvärdet är 100|
| [image_type](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/image_type) | Hämtar eller ställer in formatet för de genererade bilderna.<br/> standardvärde: PNG.|
| [is_cell_auto_fit](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/is_cell_auto_fit) | Anger om cellernas bredd och höjd anpassas automatiskt efter cellvärde.<br/> Standardvärdet är falskt.|
| [one_page_per_sheet](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/one_page_per_sheet) | Om OnePagePerSheet är sant kommer allt innehåll i ett ark att matas ut till endast en sida i resultatet.<br/> Pappersstorleken för utskriftsformatet kommer att vara ogiltig, och de andra inställningarna för utskriftsformatet<br/> kommer fortfarande att träda i kraft.|
| [all_columns_in_one_page_per_sheet](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/all_columns_in_one_page_per_sheet) | Om AllColumnsInOnePagePerSheet är sant kommer allt kolumninnehåll i ett ark att matas ut till endast en sida i resultatet.<br/> Bredden på pappersstorleken för sidinställningarna kommer att vara ogiltig, och de andra inställningarna för sidinställningarna<br/> kommer fortfarande att träda i kraft.|
| [chart_image_type](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/chart_image_type) | Ange diagrammets bildtyp vid konvertering.<br/> standardvärde: PNG.|
| [embeded_image_name_in_svg](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/embeded_image_name_in_svg) | Ange filnamnet på den inbäddade bilden i svg.<br/> Detta ska vara den fullständiga sökvägen med en katalog som "c:\\xpsEmbedded"|
| [svg_fit_to_view_port](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/svg_fit_to_view_port) | Om den här egenskapen är sann kommer den genererade svg-filen att anpassas till visningsporten.|
| [svg_css_prefix](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/svg_css_prefix) |Hämtar och anger prefixet för css-namnet i svg, standardvärdet är en tom sträng.|
| [only_area](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/only_area) | Om den här egenskapen är sann kommer ett område att matas ut och ingen skalning kommer att träda i kraft.|
| [text_rendering_hint](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/text_rendering_hint) | Anger kvaliteten på textrenderingen.<br/> Standardvärdet är TextRenderingHint.SystemDefault|
| [smoothing_mode](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/smoothing_mode) | Anger om utjämning (antialiasing) tillämpas på linjer och kurvor samt kanterna på fyllda områden.<br/> Standardvärdet är SmoothingMode.None|
| [transparent](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/transparent) | Anger om bakgrunden på den genererade bilden ska vara transparent.|
| [pixel_format](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/pixel_format) | Hämtar eller ställer in pixelformatet för de genererade bilderna.|
| [is_font_substitution_char_granularity](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/is_font_substitution_char_granularity) | Anger om tecknets teckensnitt endast ska ersättas när cellteckensnittet inte är kompatibelt med det.|
| [page_index](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/page_index) | Hämtar eller ställer in det 0-baserade indexet för den första sidan som ska sparas.|
| [page_count](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/page_count) | Hämtar eller anger antalet sidor som ska sparas.|
| [is_optimized](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/is_optimized) | Anger om utdataelementen ska optimeras.|
| [default_font](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/default_font) | När tecken i Excel är Unicode och inte är inställda med rätt typsnitt i cellstilen,<br/>De kan visas som block i pdf-filen eller bilden.<br/>Ställ in standardteckensnittet, till exempel MingLiu eller MS Gothic, för att visa dessa tecken.<br/>Om den här egenskapen inte är inställd kommer Aspose.Cells att använda systemets standardteckensnitt för att visa dessa Unicode-tecken.|
| [check_workbook_default_font](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/check_workbook_default_font) | När tecken i Excel är Unicode och inte är inställda med rätt typsnitt i cellstilen,<br/>De kan visas som block i pdf-filen eller bilden.<br/> Ställ in detta till sant för att försöka använda arbetsbokens standardteckensnitt för att visa dessa tecken först.|
| [output_blank_page_when_nothing_to_print](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/output_blank_page_when_nothing_to_print) | Anger om en tom sida ska skrivas ut när det inte finns något att skriva ut.|
| [gridline_type](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/gridline_type) | Hämtar eller anger rutnätstyp.|
| [gridline_color](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/gridline_color) | Hämtar eller ställer in rutnätsfärg.|
| [text_cross_type](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/text_cross_type) | Hämtar eller ställer in visningstexttypen när textbredden är större än cellbredden.|
| [emf_type](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/emf_type) | Hämtar eller ställer in en EmfType som anger formatet för metafilen.<br/> Standardvärdet är EmfPlusDual.|
| [default_edit_language](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/default_edit_language) | Hämtar eller ställer in standardredigeringsspråk.|
| [sheet_set](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/sheet_set) | Hämtar eller ställer in vilka ark som ska renderas. Standardvärdet är alla synliga ark i arbetsboken: [`SheetSet.visible`](/cells/python-net/sv/aspose.cells.rendering/sheetset#visible).|
| [emf_render_setting](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/emf_render_setting) | Inställning för att rendera EMF-metafiler i källfilen.|
| [custom_render_settings](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/custom_render_settings) | Hämtar eller ställer in anpassade inställningar under rendering.|
| [fit_to_view_port](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/fit_to_view_port) | Om den här egenskapen är sann kommer den genererade svg-filen att anpassas till visningsporten.|
| [css_prefix](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/css_prefix) |Hämtar och anger prefixet för css-namnet i svg, standardvärdet är en tom sträng.|
| [embedded_font_type](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/embedded_font_type) | Hämtar eller anger typen av teckensnitt som är inbäddat i Svg.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`set_desired_size(self, desired_width, desired_height)`](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/set_desired_size/#int-int) | Ställer in önskad bredd och höjd på bilden.|
| [`set_desired_size(self, desired_width, desired_height, keep_aspect_ratio)`](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions/set_desired_size/#int-int-bool) | Ställer in önskad bredd och höjd på bilden.|



###  Se även
* modul [`aspose.cells.rendering`](..)
* klass [`ImageOrPrintOptions`](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions)
* klass [`SvgImageOptions`](/cells/python-net/sv/aspose.cells.rendering/svgimageoptions)
