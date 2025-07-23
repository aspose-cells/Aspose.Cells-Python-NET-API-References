---
title: ShapeCollection klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 510
url: /sv/aspose.cells.drawing/shapecollection/
is_root: false
---
##  ShapeCollection klass
Representerar alla former i ett kalkylblad/diagram.



Typen ShapeCollection avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [capacity](/cells/python-net/sv/aspose.cells.drawing/shapecollection/capacity) | Hämtar eller anger antalet element som arraylistan kan innehålla.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`add_shape_in_chart(self, type, placement, left, top, right, bottom, image_data)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_shape_in_chart/#aspose.cells.drawing.msodrawingtype-aspose.cells.drawing.placementtype-int-int-int-int-bytes) | Lägg till en form i diagrammet. Alla enheter är 1/4000 av diagrammets yta.|
| [`add_shape_in_chart(self, type, placement, left, top, right, bottom)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_shape_in_chart/#aspose.cells.drawing.msodrawingtype-aspose.cells.drawing.placementtype-int-int-int-int) | Lägg till en form i diagrammet. Alla enheter är 1/4000 av diagrammets yta.|
| [`add_shape_in_chart_by_scale(self, type, placement, left, top, right, bottom)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_shape_in_chart_by_scale/#aspose.cells.drawing.msodrawingtype-aspose.cells.drawing.placementtype-float-float-float-float) | Lägg till en form i diagrammet. Alla enheter är procentskala av diagrammets yta.|
| [`add_shape_in_chart_by_scale(self, type, placement, left, top, right, bottom, image_data)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_shape_in_chart_by_scale/#aspose.cells.drawing.msodrawingtype-aspose.cells.drawing.placementtype-float-float-float-float-bytes) | Lägg till en form i diagrammet. Alla enheter är 1/4000 av diagrammets yta.|
| [`add_picture(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_picture/#int-int-int-int-io.rawiobase) | Lägger till en bild i samlingen.|
| [`add_picture(self, upper_left_row, upper_left_column, stream, width_scale, height_scale)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_picture/#int-int-io.rawiobase-int-int) | Lägger till en bild i samlingen.|
| [`copy_to(self, array)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/copy_to/#list) |Kopierar hela arraylistan till en kompatibel endimensionell arraylista, med början i början av målarraylistan.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/copy_to/#int-list-int-int) | Kopierar ett elementområde från arraylistan till en kompatibel endimensionell arraylista, med början vid det angivna indexet för målarraylistan.|
| [`index_of(self, item, index)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/index_of/#aspose.cells.drawing.shape-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom intervallet av element i arraylistan som sträcker sig från det angivna indexet till det sista elementet.|
| [`index_of(self, item, index, count)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/index_of/#aspose.cells.drawing.shape-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom elementintervallet i arraylistan som börjar vid det angivna indexet och innehåller det angivna antalet element.|
| [`last_index_of(self, item)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/last_index_of/#aspose.cells.drawing.shape) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom hela arraylistan.|
| [`last_index_of(self, item, index)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/last_index_of/#aspose.cells.drawing.shape-int) |Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom intervallet av element i arraylistan som sträcker sig från det första elementet till det angivna indexet.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/last_index_of/#aspose.cells.drawing.shape-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom elementintervallet i arraylistan som innehåller det angivna antalet element och slutar vid det angivna indexet.|
| [`get(self, name)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/get/#str) | Hämtar [`Shape`](/cells/python-net/sv/aspose.cells.drawing/shape)-objektet med hjälp av formens namn.|
| [`add_copy(self, source_shape, top_row, top, left_column, left)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_copy/#aspose.cells.drawing.shape-int-int-int-int) | Lägger till och kopierar en form till kalkylbladet.|
| [`add_check_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_check_box/#int-int-int-int-int-int) | Lägger till en kryssruta i kalkylbladet.|
| [`add_text_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_text_box/#int-int-int-int-int-int) | Lägger till en textruta i kalkylbladet.|
| [`add_equation(self, top_row, top, left_column, left, height, width)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_equation/#int-int-int-int-int-int) |Lägg till ett ekvationsobjekt i kalkylbladet.|
| [`add_spinner(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_spinner/#int-int-int-int-int-int) | Lägger till en spinner i kalkylbladet.|
| [`add_scroll_bar(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_scroll_bar/#int-int-int-int-int-int) | Lägger till en rullningslist i kalkylbladet.|
| [`add_radio_button(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_radio_button/#int-int-int-int-int-int) | Lägger till en radioknapp i kalkylbladet.|
| [`add_list_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_list_box/#int-int-int-int-int-int) | Lägger till en listbox i kalkylbladet.|
| [`add_combo_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_combo_box/#int-int-int-int-int-int) | Lägger till en kombinationsruta i kalkylbladet.|
| [`add_group_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_group_box/#int-int-int-int-int-int) | Lägger till en gruppruta i kalkylbladet.|
| [`add_button(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_button/#int-int-int-int-int-int) | Lägger till en knapp i kalkylbladet.|
| [`add_label(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_label/#int-int-int-int-int-int) | Lägger till en etikett i kalkylbladet.|
| [`add_label_in_chart(self, top, left, height, width)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_label_in_chart/#int-int-int-int) | Lägger till en etikett i diagrammet.|
| [`add_text_box_in_chart(self, top, left, height, width)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_text_box_in_chart/#int-int-int-int) | Lägger till en textruta i diagrammet.|
| [`add_text_effect_in_chart(self, effect, text, font_name, size, font_bold, font_italic, top, left, height, width)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_text_effect_in_chart/#aspose.cells.drawing.msopresettexteffect-str-str-int-bool-bool-int-int-int-int) | Infogar ett WordArt-objekt i diagrammet|
| [`add_text_effect(self, effect, text, font_name, size, font_bold, font_italic, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_text_effect/#aspose.cells.drawing.msopresettexteffect-str-str-int-bool-bool-int-int-int-int-int-int) | Infogar ett WordArt-objekt.|
| [`add_word_art(self, style, text, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_word_art/#aspose.cells.drawing.presetwordartstyle-str-int-int-int-int-int-int) | Lägger till förinställd WordArt sedan Excel 2007.s|
| [`add_rectangle(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_rectangle/#int-int-int-int-int-int) | Lägger till en rektangelform i kalkylbladet.|
| [`add_oval(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_oval/#int-int-int-int-int-int) | Lägger till en oval i kalkylbladet.|
| [`add_line(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_line/#int-int-int-int-int-int) | Lägger till en linjeform i kalkylbladet.|
| [`add_free_floating_shape(self, type, top, left, height, width, image_data, is_original_size)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_free_floating_shape/#aspose.cells.drawing.msodrawingtype-int-int-int-int-bytes-bool) | Lägger till en fritt flytande form i kalkylbladet. Gäller endast för linje-/bildformer.|
| [`add_arc(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_arc/#int-int-int-int-int-int) | Lägger till en bågform i kalkylbladet.|
| [`add_shape(self, type, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_shape/#aspose.cells.drawing.msodrawingtype-int-int-int-int-int-int) | Lägger till en form i kalkylbladet.|
| [`add_auto_shape(self, type, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_auto_shape/#aspose.cells.drawing.autoshapetype-int-int-int-int-int-int) | Lägger till en autoform i kalkylbladet.|
| [`add_auto_shape_in_chart(self, type, top, left, height, width)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_auto_shape_in_chart/#aspose.cells.drawing.autoshapetype-int-int-int-int) | Lägger till en autofigur i diagrammet.|
| [`add_active_x_control(self, type, top_row, top, left_column, left, width, height)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_active_x_control/#aspose.cells.drawing.activexcontrols.controltype-int-int-int-int-int-int) | Skapar en ActiveX-kontroll.|
| [`add_svg(self, upper_left_row, top, upper_left_column, left, height, width, svg_data, compatible_image_data)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_svg/#int-int-int-int-int-int-bytes-bytes) | Lägger till svg-bild.|
| [`add_icons(self, upper_left_row, top, upper_left_column, left, height, width, image_byte_data, compatible_image_data)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_icons/#int-int-int-int-int-int-bytes-bytes) | Lägger till svg-bild.|
| [`add_linked_picture(self, upper_left_row, upper_left_column, height, width, source_full_name)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_linked_picture/#int-int-int-int-str) |Lägg till en länkad bild.|
| [`add_ole_object_with_linked_image(self, upper_left_row, upper_left_column, height, width, source_full_name)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_ole_object_with_linked_image/#int-int-int-int-str) |Lägg till en länkad bild.|
| [`add_picture_in_chart(self, top, left, stream, width_scale, height_scale)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_picture_in_chart/#int-int-io.rawiobase-int-int) | Lägger till en bild i diagrammet.|
| [`add_ole_object(self, upper_left_row, top, upper_left_column, left, height, width, image_data)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_ole_object/#int-int-int-int-int-int-bytes) | Lägger till ett OleObject.|
| [`copy_comments_in_range(self, shapes, ca, dest_row, dest_column)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/copy_comments_in_range/#aspose.cells.drawing.shapecollection-aspose.cells.cellarea-int-int) | Kopiera alla kommentarer i intervallet.|
| [`copy_in_range(self, source_shapes, ca, dest_row, dest_column, is_contained)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/copy_in_range/#aspose.cells.drawing.shapecollection-aspose.cells.cellarea-int-int-bool) | Kopiera former i området till målområdet.|
| [`delete_in_range(self, ca)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/delete_in_range/#aspose.cells.cellarea) | Ta bort former i intervallet. Kommentarformer kommer inte att tas bort.|
| [`delete_shape(self, shape)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/delete_shape/#aspose.cells.drawing.shape) | Ta bort en form. Om formen finns i gruppen eller är en kommentarform kommer den inte att tas bort.|
| [`group(self, group_items)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/group/#list) | Gruppera formerna.|
| [`ungroup(self, group)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/ungroup/#aspose.cells.drawing.groupshape) | Avgrupperar formobjekten.|
| [`remove_a_shape(self, shape)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/remove_a_shape/#aspose.cells.drawing.shape) | Lägg till API for Python via .Net eftersom denna API inte stöds.|
| [`update_selected_value(self)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/update_selected_value/#) | Uppdatera det markerade värdet med värdet för den länkade cellen eller området för formen.|
| [`add_freeform(self, upper_left_row, top, upper_left_column, left, height, width, paths)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_freeform/#int-int-int-int-int-int-list) | Lägger till en frihandsform i kalkylbladet.|
| [`add_signature_line(self, upper_left_row, upper_left_column, signature_line)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/add_signature_line/#int-int-aspose.cells.drawing.signatureline) | Lägger till en signaturrad i kalkylbladet.|
| [`binary_search(self, item)`](/cells/python-net/sv/aspose.cells.drawing/shapecollection/binary_search/#aspose.cells.drawing.shape) | Söker igenom hela den sorterade arraylistan efter ett element med hjälp av standardjämföraren och returnerar elementets nollbaserade index.|



###  Exempel

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# get ShapeCollection
shapes = workbook.worksheets[0].shapes
# do your business
# Save the excel file.
workbook.save("result.xlsx")

```

###  Se även
* modul [`aspose.cells.drawing`](..)
* klass [`Shape`](/cells/python-net/sv/aspose.cells.drawing/shape)
