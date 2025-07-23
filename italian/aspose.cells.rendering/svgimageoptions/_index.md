---
title: SvgImageOptions classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 130
url: /it/aspose.cells.rendering/svgimageoptions/
is_root: false
---
##  SvgImageOptions classe
Opzioni per la generazione di immagini Svg.



**Eredità:** [`SvgImageOptions`](/cells/python-net/aspose.cells.rendering/svgimageoptions) → 
[`ImageOrPrintOptions`](/cells/python-net/it/aspose.cells.rendering/imageorprintoptions)



Il tipo SvgImageOptions espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [`__init__(self)`](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/__init__/#) | Cttore.|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [save_format](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/save_format) | Ottiene o imposta il tipo di formato del file di output<br/> Supporto Tiff/XPS|
| [print_with_status_dialog](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/print_with_status_dialog) | Se PrintWithStatusDialog = true , verrà visualizzata una finestra di dialogo che mostra lo stato di stampa corrente.<br/> altrimenti non verrà visualizzata alcuna finestra di dialogo.|
| [horizontal_resolution](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/horizontal_resolution) | Ottiene o imposta la risoluzione orizzontale delle immagini generate, in punti per pollice.|
| [vertical_resolution](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/vertical_resolution) | Ottiene o imposta la risoluzione verticale delle immagini generate, in punti per pollice.|
| [tiff_compression](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/tiff_compression) | Ottiene o imposta il tipo di compressione da applicare solo quando si salvano le pagine nel formato `Tiff`.|
| [tiff_color_depth](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/tiff_color_depth) | Ottiene o imposta la profondità di bit da applicare solo quando si salvano le pagine nel formato `Tiff`.|
| [tiff_binarization_method](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/tiff_binarization_method) | Ottiene o imposta il metodo utilizzato durante la conversione delle immagini nel formato 1 bpp<br/>quando [`ImageOrPrintOptions.image_type`](/cells/python-net/it/aspose.cells.rendering/imageorprintoptions#image_type) è Tiff e [`ImageOrPrintOptions.tiff_compression`](/cells/python-net/it/aspose.cells.rendering/imageorprintoptions#tiff_compression) è uguale a Ccitt3 o Ccitt4.|
| [printing_page](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/printing_page) | Indica quali pagine non verranno stampate.|
| [quality](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/quality) | Ottiene o imposta un valore che determina la qualità delle immagini generate<br/> da applicare solo quando si salvano le pagine nel formato `Jpeg`. Il valore predefinito è 100|
| [image_type](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/image_type) | Ottiene o imposta il formato delle immagini generate.<br/> valore predefinito: PNG.|
| [is_cell_auto_fit](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/is_cell_auto_fit) | Indica se la larghezza e l'altezza delle celle vengono adattate automaticamente in base al valore della cella.<br/> Il valore predefinito è falso.|
| [one_page_per_sheet](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/one_page_per_sheet) | Se OnePagePerSheet è true, tutto il contenuto di un foglio verrà riprodotto in una sola pagina del risultato.<br/> Il formato carta di pagesetup non sarà valido e le altre impostazioni di pagesetup<br/> avrà comunque effetto.|
| [all_columns_in_one_page_per_sheet](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/all_columns_in_one_page_per_sheet) | Se AllColumnsInOnePagePerSheet è true, tutto il contenuto delle colonne di un foglio verrà visualizzato in una sola pagina del risultato.<br/> La larghezza del formato carta di pagesetup non sarà valida e le altre impostazioni di pagesetup<br/> avrà comunque effetto.|
| [chart_image_type](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/chart_image_type) | Indicare il tipo di immagine del grafico durante la conversione.<br/> valore predefinito: PNG.|
| [embeded_image_name_in_svg](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/embeded_image_name_in_svg) | Indica il nome del file dell'immagine incorporata in svg.<br/> Dovrebbe essere il percorso completo con la directory come "c:\\xpsEmbedded"|
| [svg_fit_to_view_port](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/svg_fit_to_view_port) | Se questa proprietà è vera, il file SVG generato si adatterà alla porta di visualizzazione.|
| [svg_css_prefix](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/svg_css_prefix) |Ottiene e imposta il prefisso del nome css in svg, il valore predefinito è una stringa vuota.|
| [only_area](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/only_area) | Se questa proprietà è vera, verrà emessa un'area e non verrà applicata alcuna scala.|
| [text_rendering_hint](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/text_rendering_hint) | Specifica la qualità del rendering del testo.<br/> Il valore predefinito è TextRenderingHint.SystemDefault|
| [smoothing_mode](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/smoothing_mode) | Specifica se applicare l'effetto smoothing (antialiasing) alle linee, alle curve e ai bordi delle aree riempite.<br/> Il valore predefinito è SmoothingMode.None|
| [transparent](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/transparent) | Indica se lo sfondo dell'immagine generata deve essere trasparente.|
| [pixel_format](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/pixel_format) | Ottiene o imposta il formato pixel per le immagini generate.|
| [is_font_substitution_char_granularity](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/is_font_substitution_char_granularity) | Indica se sostituire solo il font del carattere quando il font della cella non è compatibile con esso.|
| [page_index](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/page_index) | Ottiene o imposta l'indice basato su 0 della prima pagina da salvare.|
| [page_count](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/page_count) | Ottiene o imposta il numero di pagine da salvare.|
| [is_optimized](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/is_optimized) | Indica se ottimizzare gli elementi di output.|
| [default_font](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/default_font) | Quando i caratteri in Excel sono Unicode e non sono impostati con il font corretto nello stile della cella,<br/>Possono apparire come blocchi in PDF o immagini.<br/>Imposta il carattere predefinito come MingLiu o MS Gothic per visualizzare questi caratteri.<br/>Se questa proprietà non è impostata, Aspose.Cells utilizzerà il font predefinito del sistema per visualizzare questi caratteri Unicode.|
| [check_workbook_default_font](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/check_workbook_default_font) | Quando i caratteri in Excel sono Unicode e non sono impostati con il font corretto nello stile della cella,<br/>Possono apparire come blocchi in PDF o immagini.<br/> Impostare su true per provare a utilizzare il font predefinito della cartella di lavoro per visualizzare prima questi caratteri.|
| [output_blank_page_when_nothing_to_print](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/output_blank_page_when_nothing_to_print) | Indica se stampare una pagina vuota quando non c'è nulla da stampare.|
| [gridline_type](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/gridline_type) | Ottiene o imposta il tipo di griglia.|
| [gridline_color](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/gridline_color) | Ottiene o imposta il colore della griglia.|
| [text_cross_type](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/text_cross_type) | Ottiene o imposta il tipo di testo visualizzato quando la larghezza del testo è maggiore della larghezza della cella.|
| [emf_type](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/emf_type) | Ottiene o imposta un EmfType che specifica il formato del Metafile.<br/> Il valore predefinito è EmfPlusDual.|
| [default_edit_language](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/default_edit_language) | Ottiene o imposta la lingua di modifica predefinita.|
| [sheet_set](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/sheet_set) | Ottiene o imposta i fogli da visualizzare. L'impostazione predefinita è tutti i fogli visibili nella cartella di lavoro: [`SheetSet.visible`](/cells/python-net/it/aspose.cells.rendering/sheetset#visible).|
| [emf_render_setting](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/emf_render_setting) | Impostazione per il rendering dei metafile Emf nel file sorgente.|
| [custom_render_settings](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/custom_render_settings) | Ottiene o imposta impostazioni personalizzate durante il rendering.|
| [fit_to_view_port](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/fit_to_view_port) | Se questa proprietà è vera, il file SVG generato si adatterà alla porta di visualizzazione.|
| [css_prefix](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/css_prefix) |Ottiene e imposta il prefisso del nome css in svg, il valore predefinito è una stringa vuota.|
| [embedded_font_type](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/embedded_font_type) | Ottiene o imposta il tipo di font incorporato in Svg.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`set_desired_size(self, desired_width, desired_height)`](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/set_desired_size/#int-int) | Imposta la larghezza e l'altezza desiderate dell'immagine.|
| [`set_desired_size(self, desired_width, desired_height, keep_aspect_ratio)`](/cells/python-net/it/aspose.cells.rendering/svgimageoptions/set_desired_size/#int-int-bool) | Imposta la larghezza e l'altezza desiderate dell'immagine.|



###  Guarda anche
* modulo [`aspose.cells.rendering`](..)
* classe [`ImageOrPrintOptions`](/cells/python-net/it/aspose.cells.rendering/imageorprintoptions)
* classe [`SvgImageOptions`](/cells/python-net/it/aspose.cells.rendering/svgimageoptions)
