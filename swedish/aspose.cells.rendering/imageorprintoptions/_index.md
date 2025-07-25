---
title: ImageOrPrintOptions klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 30
url: /sv/aspose.cells.rendering/imageorprintoptions/
is_root: false
---
##  ImageOrPrintOptions klass
Gör det möjligt att ange alternativ vid rendering av kalkylblad till bilder, utskrift av kalkylblad eller rendering av diagram till bild.



Typen ImageOrPrintOptions avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [`__init__(self)`](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/__init__/#) | Rektor.|


###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [save_format](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/save_format) | Hämtar eller ställer in utdatafilformattypen<br/> Support Tiff/XPS|
| [print_with_status_dialog](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/print_with_status_dialog) | Om PrintWithStatusDialog = true visas en dialogruta som visar aktuell utskriftsstatus.<br/> annars visas ingen sådan dialogruta.|
| [horizontal_resolution](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/horizontal_resolution) | Hämtar eller ställer in den horisontella upplösningen för genererade bilder, i punkter per tum.|
| [vertical_resolution](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/vertical_resolution) | Hämtar eller ställer in den vertikala upplösningen för genererade bilder, i punkter per tum.|
| [tiff_compression](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/tiff_compression) | Hämtar eller ställer in vilken typ av komprimering som endast ska tillämpas när sidor sparas i formatet `Tiff`.|
| [tiff_color_depth](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/tiff_color_depth) | Hämtar eller ställer in bitdjup så att det endast gäller när sidor sparas i formatet `Tiff`.|
| [tiff_binarization_method](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/tiff_binarization_method) | Hämtar eller ställer in metoden som används vid konvertering av bilder till 1 bpp-format<br/>när [`ImageOrPrintOptions.image_type`](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions#image_type) är Tiff och [`ImageOrPrintOptions.tiff_compression`](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions#tiff_compression) är lika med Ccitt3 eller Ccitt4.|
| [printing_page](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/printing_page) | Anger vilka sidor som inte kommer att skrivas ut.|
| [quality](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/quality) | Hämtar eller ställer in ett värde som bestämmer kvaliteten på de genererade bilderna<br/> att endast tillämpas när sidor sparas i formatet `Jpeg`. Standardvärdet är 100|
| [image_type](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/image_type) | Hämtar eller ställer in formatet för de genererade bilderna.<br/> standardvärde: PNG.|
| [is_cell_auto_fit](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/is_cell_auto_fit) | Anger om cellernas bredd och höjd anpassas automatiskt efter cellvärde.<br/> Standardvärdet är falskt.|
| [one_page_per_sheet](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/one_page_per_sheet) | Om OnePagePerSheet är sant kommer allt innehåll i ett ark att matas ut till endast en sida i resultatet.<br/> Pappersstorleken för utskriftsformatet kommer att vara ogiltig, och de andra inställningarna för utskriftsformatet<br/> kommer fortfarande att träda i kraft.|
| [all_columns_in_one_page_per_sheet](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/all_columns_in_one_page_per_sheet) | Om AllColumnsInOnePagePerSheet är sant kommer allt kolumninnehåll i ett ark att matas ut till endast en sida i resultatet.<br/> Bredden på pappersstorleken för sidinställningarna kommer att vara ogiltig, och de andra inställningarna för sidinställningarna<br/> kommer fortfarande att träda i kraft.|
| [chart_image_type](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/chart_image_type) | Ange diagrammets bildtyp vid konvertering.<br/> standardvärde: PNG.|
| [embeded_image_name_in_svg](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/embeded_image_name_in_svg) | Ange filnamnet på den inbäddade bilden i svg.<br/> Detta ska vara den fullständiga sökvägen med en katalog som "c:\\xpsEmbedded"|
| [svg_fit_to_view_port](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/svg_fit_to_view_port) | Om den här egenskapen är sann kommer den genererade svg-filen att anpassas till visningsporten.|
| [svg_css_prefix](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/svg_css_prefix) |Hämtar och anger prefixet för css-namnet i svg, standardvärdet är en tom sträng.|
| [only_area](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/only_area) | Om den här egenskapen är sann kommer ett område att matas ut och ingen skalning kommer att träda i kraft.|
| [text_rendering_hint](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/text_rendering_hint) | Anger kvaliteten på textrenderingen.<br/> Standardvärdet är TextRenderingHint.SystemDefault|
| [smoothing_mode](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/smoothing_mode) | Anger om utjämning (antialiasing) tillämpas på linjer och kurvor samt kanterna på fyllda områden.<br/> Standardvärdet är SmoothingMode.None|
| [transparent](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/transparent) | Anger om bakgrunden på den genererade bilden ska vara transparent.|
| [pixel_format](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/pixel_format) | Hämtar eller ställer in pixelformatet för de genererade bilderna.|
| [is_font_substitution_char_granularity](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/is_font_substitution_char_granularity) | Anger om tecknets teckensnitt endast ska ersättas när cellteckensnittet inte är kompatibelt med det.|
| [page_index](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/page_index) | Hämtar eller ställer in det 0-baserade indexet för den första sidan som ska sparas.|
| [page_count](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/page_count) | Hämtar eller anger antalet sidor som ska sparas.|
| [is_optimized](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/is_optimized) | Anger om utdataelementen ska optimeras.|
| [default_font](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/default_font) | När tecken i Excel är Unicode och inte är inställda med rätt typsnitt i cellstilen,<br/>De kan visas som block i pdf-filen eller bilden.<br/>Ställ in standardteckensnittet, till exempel MingLiu eller MS Gothic, för att visa dessa tecken.<br/>Om den här egenskapen inte är inställd kommer Aspose.Cells att använda systemets standardteckensnitt för att visa dessa Unicode-tecken.|
| [check_workbook_default_font](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/check_workbook_default_font) | När tecken i Excel är Unicode och inte är inställda med rätt typsnitt i cellstilen,<br/>De kan visas som block i pdf-filen eller bilden.<br/> Ställ in detta till sant för att försöka använda arbetsbokens standardteckensnitt för att visa dessa tecken först.|
| [output_blank_page_when_nothing_to_print](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/output_blank_page_when_nothing_to_print) | Anger om en tom sida ska skrivas ut när det inte finns något att skriva ut.|
| [gridline_type](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/gridline_type) | Hämtar eller anger rutnätstyp.|
| [gridline_color](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/gridline_color) | Hämtar eller ställer in rutnätsfärg.|
| [text_cross_type](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/text_cross_type) | Hämtar eller ställer in visningstexttypen när textbredden är större än cellbredden.|
| [emf_type](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/emf_type) | Hämtar eller ställer in en EmfType som anger formatet för metafilen.<br/> Standardvärdet är EmfPlusDual.|
| [default_edit_language](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/default_edit_language) | Hämtar eller ställer in standardredigeringsspråk.|
| [sheet_set](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/sheet_set) | Hämtar eller ställer in vilka ark som ska renderas. Standardvärdet är alla synliga ark i arbetsboken: [`SheetSet.visible`](/cells/python-net/sv/aspose.cells.rendering/sheetset#visible).|
| [emf_render_setting](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/emf_render_setting) | Inställning för att rendera EMF-metafiler i källfilen.|
| [custom_render_settings](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/custom_render_settings) | Hämtar eller ställer in anpassade inställningar under rendering.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`set_desired_size(self, desired_width, desired_height)`](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/set_desired_size/#int-int) | Ställer in önskad bredd och höjd på bilden.|
| [`set_desired_size(self, desired_width, desired_height, keep_aspect_ratio)`](/cells/python-net/sv/aspose.cells.rendering/imageorprintoptions/set_desired_size/#int-int-bool) | Ställer in önskad bredd och höjd på bilden.|



###  Exempel

```python
from aspose.cells import Workbook
from aspose.cells.drawing import ImageType
from aspose.cells.rendering import ImageOrPrintOptions

# Set Image Or Print Options
options = ImageOrPrintOptions()
# Set output image format
options.image_type = ImageType.PNG
# Set Horizontal resolution
options.horizontal_resolution = 300
# Set Vertical Resolution
options.vertical_resolution = 300
# Instantiate Workbook
book = Workbook("test.xls")
# Save chart as Image using ImageOrPrint Options
book.worksheets[0].charts[0].to_image("chart.png", options)

```

###  Se även
* modul [`aspose.cells.rendering`](..)
