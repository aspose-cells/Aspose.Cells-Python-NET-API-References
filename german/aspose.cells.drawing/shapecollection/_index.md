---
title: ShapeCollection Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 510
url: /de/aspose.cells.drawing/shapecollection/
is_root: false
---
##  ShapeCollection Klasse
Stellt alle Formen in einem Arbeitsblatt/Diagramm dar.



Der Typ ShapeCollection macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [capacity](/cells/python-net/de/aspose.cells.drawing/shapecollection/capacity) | Ruft die Anzahl der Elemente ab, die die Array-Liste enthalten kann, oder legt diese fest.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`add_shape_in_chart(self, type, placement, left, top, right, bottom, image_data)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_shape_in_chart/#aspose.cells.drawing.msodrawingtype-aspose.cells.drawing.placementtype-int-int-int-int-bytes) | Fügen Sie dem Diagramm eine Form hinzu. Alle Einheiten betragen 1/4000 der Diagrammfläche.|
| [`add_shape_in_chart(self, type, placement, left, top, right, bottom)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_shape_in_chart/#aspose.cells.drawing.msodrawingtype-aspose.cells.drawing.placementtype-int-int-int-int) | Fügen Sie dem Diagramm eine Form hinzu. Alle Einheiten betragen 1/4000 der Diagrammfläche.|
| [`add_shape_in_chart_by_scale(self, type, placement, left, top, right, bottom)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_shape_in_chart_by_scale/#aspose.cells.drawing.msodrawingtype-aspose.cells.drawing.placementtype-float-float-float-float) | Fügen Sie dem Diagramm eine Form hinzu. Alle Einheiten sind Prozentwerte der Diagrammfläche.|
| [`add_shape_in_chart_by_scale(self, type, placement, left, top, right, bottom, image_data)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_shape_in_chart_by_scale/#aspose.cells.drawing.msodrawingtype-aspose.cells.drawing.placementtype-float-float-float-float-bytes) | Fügen Sie dem Diagramm eine Form hinzu. Alle Einheiten betragen 1/4000 der Diagrammfläche.|
| [`add_picture(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_picture/#int-int-int-int-io.rawiobase) | Fügt der Sammlung ein Bild hinzu.|
| [`add_picture(self, upper_left_row, upper_left_column, stream, width_scale, height_scale)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_picture/#int-int-io.rawiobase-int-int) | Fügt der Sammlung ein Bild hinzu.|
| [`copy_to(self, array)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/copy_to/#list) |Kopiert die gesamte Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am Anfang der Ziel-Array-Liste.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/copy_to/#int-list-int-int) | Kopiert einen Bereich von Elementen aus der Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am angegebenen Index der Ziel-Array-Liste.|
| [`index_of(self, item, index)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/index_of/#aspose.cells.drawing.shape-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der sich vom angegebenen Index bis zum letzten Element erstreckt.|
| [`index_of(self, item, index, count)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/index_of/#aspose.cells.drawing.shape-int-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der am angegebenen Index beginnt und die angegebene Anzahl von Elementen enthält.|
| [`last_index_of(self, item)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/last_index_of/#aspose.cells.drawing.shape) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb der gesamten Arrayliste zurück.|
| [`last_index_of(self, item, index)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/last_index_of/#aspose.cells.drawing.shape-int) |Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der sich vom ersten Element bis zum angegebenen Index erstreckt.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/last_index_of/#aspose.cells.drawing.shape-int-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der die angegebene Anzahl von Elementen enthält und am angegebenen Index endet.|
| [`get(self, name)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/get/#str) | Ruft das Objekt [`Shape`](/cells/python-net/de/aspose.cells.drawing/shape) anhand des Namens der Form ab.|
| [`add_copy(self, source_shape, top_row, top, left_column, left)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_copy/#aspose.cells.drawing.shape-int-int-int-int) | Fügt dem Arbeitsblatt eine Form hinzu und kopiert sie.|
| [`add_check_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_check_box/#int-int-int-int-int-int) | Fügt dem Arbeitsblatt ein Kontrollkästchen hinzu.|
| [`add_text_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_text_box/#int-int-int-int-int-int) | Fügt dem Arbeitsblatt ein Textfeld hinzu.|
| [`add_equation(self, top_row, top, left_column, left, height, width)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_equation/#int-int-int-int-int-int) |Fügen Sie dem Arbeitsblatt ein Gleichungsobjekt hinzu.|
| [`add_spinner(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_spinner/#int-int-int-int-int-int) | Fügt dem Arbeitsblatt einen Spinner hinzu.|
| [`add_scroll_bar(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_scroll_bar/#int-int-int-int-int-int) | Fügt dem Arbeitsblatt eine Bildlaufleiste hinzu.|
| [`add_radio_button(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_radio_button/#int-int-int-int-int-int) | Fügt dem Arbeitsblatt einen RadioButton hinzu.|
| [`add_list_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_list_box/#int-int-int-int-int-int) | Fügt dem Arbeitsblatt eine ListBox hinzu.|
| [`add_combo_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_combo_box/#int-int-int-int-int-int) | Fügt dem Arbeitsblatt eine ComboBox hinzu.|
| [`add_group_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_group_box/#int-int-int-int-int-int) | Fügt dem Arbeitsblatt eine GroupBox hinzu.|
| [`add_button(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_button/#int-int-int-int-int-int) | Fügt dem Arbeitsblatt eine Schaltfläche hinzu.|
| [`add_label(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_label/#int-int-int-int-int-int) | Fügt dem Arbeitsblatt eine Beschriftung hinzu.|
| [`add_label_in_chart(self, top, left, height, width)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_label_in_chart/#int-int-int-int) | Fügt dem Diagramm eine Beschriftung hinzu.|
| [`add_text_box_in_chart(self, top, left, height, width)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_text_box_in_chart/#int-int-int-int) | Fügt dem Diagramm ein Textfeld hinzu.|
| [`add_text_effect_in_chart(self, effect, text, font_name, size, font_bold, font_italic, top, left, height, width)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_text_effect_in_chart/#aspose.cells.drawing.msopresettexteffect-str-str-int-bool-bool-int-int-int-int) | Fügt ein WordArt-Objekt in das Diagramm ein|
| [`add_text_effect(self, effect, text, font_name, size, font_bold, font_italic, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_text_effect/#aspose.cells.drawing.msopresettexteffect-str-str-int-bool-bool-int-int-int-int-int-int) | Fügt ein WordArt-Objekt ein.|
| [`add_word_art(self, style, text, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_word_art/#aspose.cells.drawing.presetwordartstyle-str-int-int-int-int-int-int) | Fügt seit Excel 2007 voreingestellte WordArt hinzu.|
| [`add_rectangle(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_rectangle/#int-int-int-int-int-int) | Fügt dem Arbeitsblatt eine Rechteckform hinzu.|
| [`add_oval(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_oval/#int-int-int-int-int-int) | Fügt dem Arbeitsblatt ein Oval hinzu.|
| [`add_line(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_line/#int-int-int-int-int-int) | Fügt dem Arbeitsblatt eine Linienform hinzu.|
| [`add_free_floating_shape(self, type, top, left, height, width, image_data, is_original_size)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_free_floating_shape/#aspose.cells.drawing.msodrawingtype-int-int-int-int-bytes-bool) | Fügt dem Arbeitsblatt eine frei schwebende Form hinzu. Gilt nur für Linien-/Bildformen.|
| [`add_arc(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_arc/#int-int-int-int-int-int) | Fügt dem Arbeitsblatt eine ArcShape hinzu.|
| [`add_shape(self, type, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_shape/#aspose.cells.drawing.msodrawingtype-int-int-int-int-int-int) | Fügt dem Arbeitsblatt eine Form hinzu.|
| [`add_auto_shape(self, type, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_auto_shape/#aspose.cells.drawing.autoshapetype-int-int-int-int-int-int) | Fügt dem Arbeitsblatt eine AutoForm hinzu.|
| [`add_auto_shape_in_chart(self, type, top, left, height, width)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_auto_shape_in_chart/#aspose.cells.drawing.autoshapetype-int-int-int-int) | Fügt dem Diagramm eine AutoForm hinzu.|
| [`add_active_x_control(self, type, top_row, top, left_column, left, width, height)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_active_x_control/#aspose.cells.drawing.activexcontrols.controltype-int-int-int-int-int-int) | Erstellt ein ActiveX-Steuerelement.|
| [`add_svg(self, upper_left_row, top, upper_left_column, left, height, width, svg_data, compatible_image_data)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_svg/#int-int-int-int-int-int-bytes-bytes) | Fügt ein SVG-Bild hinzu.|
| [`add_icons(self, upper_left_row, top, upper_left_column, left, height, width, image_byte_data, compatible_image_data)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_icons/#int-int-int-int-int-int-bytes-bytes) | Fügt ein SVG-Bild hinzu.|
| [`add_linked_picture(self, upper_left_row, upper_left_column, height, width, source_full_name)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_linked_picture/#int-int-int-int-str) |Fügen Sie ein verknüpftes Bild hinzu.|
| [`add_ole_object_with_linked_image(self, upper_left_row, upper_left_column, height, width, source_full_name)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_ole_object_with_linked_image/#int-int-int-int-str) |Fügen Sie ein verknüpftes Bild hinzu.|
| [`add_picture_in_chart(self, top, left, stream, width_scale, height_scale)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_picture_in_chart/#int-int-io.rawiobase-int-int) | Fügt dem Diagramm ein Bild hinzu.|
| [`add_ole_object(self, upper_left_row, top, upper_left_column, left, height, width, image_data)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_ole_object/#int-int-int-int-int-int-bytes) | Fügt ein OleObject hinzu.|
| [`copy_comments_in_range(self, shapes, ca, dest_row, dest_column)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/copy_comments_in_range/#aspose.cells.drawing.shapecollection-aspose.cells.cellarea-int-int) | Kopieren Sie alle Kommentare im Bereich.|
| [`copy_in_range(self, source_shapes, ca, dest_row, dest_column, is_contained)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/copy_in_range/#aspose.cells.drawing.shapecollection-aspose.cells.cellarea-int-int-bool) | Kopieren Sie die Formen im Bereich in den Zielbereich.|
| [`delete_in_range(self, ca)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/delete_in_range/#aspose.cells.cellarea) | Löschen Sie Formen im Bereich. Kommentarformen werden nicht gelöscht.|
| [`delete_shape(self, shape)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/delete_shape/#aspose.cells.drawing.shape) | Löschen Sie eine Form. Wenn die Form zur Gruppe gehört oder eine Kommentarform ist, wird sie nicht gelöscht.|
| [`group(self, group_items)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/group/#list) | Gruppieren Sie die Formen.|
| [`ungroup(self, group)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/ungroup/#aspose.cells.drawing.groupshape) | Hebt die Gruppierung der Formelemente auf.|
| [`remove_a_shape(self, shape)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/remove_a_shape/#aspose.cells.drawing.shape) | Fügen Sie API for Python über .Net hinzu, da diese API nicht unterstützt wird|
| [`update_selected_value(self)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/update_selected_value/#) | Aktualisieren Sie den ausgewählten Wert mit dem Wert der verknüpften Zelle oder des Bereichs der Form.|
| [`add_freeform(self, upper_left_row, top, upper_left_column, left, height, width, paths)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_freeform/#int-int-int-int-int-int-list) | Fügt dem Arbeitsblatt eine Freihandform hinzu.|
| [`add_signature_line(self, upper_left_row, upper_left_column, signature_line)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/add_signature_line/#int-int-aspose.cells.drawing.signatureline) | Fügt dem Arbeitsblatt eine Signaturzeile hinzu.|
| [`binary_search(self, item)`](/cells/python-net/de/aspose.cells.drawing/shapecollection/binary_search/#aspose.cells.drawing.shape) | Durchsucht die gesamte sortierte Array-Liste mithilfe des Standardvergleichers nach einem Element und gibt den nullbasierten Index des Elements zurück.|



###  Beispiel

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

###  Siehe auch
* Modul [`aspose.cells.drawing`](..)
* Klasse [`Shape`](/cells/python-net/de/aspose.cells.drawing/shape)
