---
title: ShapeCollection classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 510
url: /it/aspose.cells.drawing/shapecollection/
is_root: false
---
##  ShapeCollection classe
Rappresenta tutte le forme in un foglio di lavoro/grafico.



Il tipo ShapeCollection espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [capacity](/cells/python-net/it/aspose.cells.drawing/shapecollection/capacity) | Ottiene o imposta il numero di elementi che l'elenco dell'array può contenere.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`add_shape_in_chart(self, type, placement, left, top, right, bottom, image_data)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_shape_in_chart/#aspose.cells.drawing.msodrawingtype-aspose.cells.drawing.placementtype-int-int-int-int-bytes) | Aggiungi una forma al grafico. Ogni unità è pari a 1/4000 dell'area del grafico.|
| [`add_shape_in_chart(self, type, placement, left, top, right, bottom)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_shape_in_chart/#aspose.cells.drawing.msodrawingtype-aspose.cells.drawing.placementtype-int-int-int-int) | Aggiungi una forma al grafico. Ogni unità è pari a 1/4000 dell'area del grafico.|
| [`add_shape_in_chart_by_scale(self, type, placement, left, top, right, bottom)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_shape_in_chart_by_scale/#aspose.cells.drawing.msodrawingtype-aspose.cells.drawing.placementtype-float-float-float-float) | Aggiungi una forma al grafico. Tutte le unità di misura sono in percentuale sulla scala dell'area del grafico.|
| [`add_shape_in_chart_by_scale(self, type, placement, left, top, right, bottom, image_data)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_shape_in_chart_by_scale/#aspose.cells.drawing.msodrawingtype-aspose.cells.drawing.placementtype-float-float-float-float-bytes) | Aggiungi una forma al grafico. Ogni unità è pari a 1/4000 dell'area del grafico.|
| [`add_picture(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_picture/#int-int-int-int-io.rawiobase) | Aggiunge un'immagine alla raccolta.|
| [`add_picture(self, upper_left_row, upper_left_column, stream, width_scale, height_scale)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_picture/#int-int-io.rawiobase-int-int) | Aggiunge un'immagine alla raccolta.|
| [`copy_to(self, array)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/copy_to/#list) |Copia l'intero elenco di array in un elenco di array unidimensionale compatibile, iniziando dall'inizio dell'elenco di array di destinazione.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/copy_to/#int-list-int-int) | Copia un intervallo di elementi dall'elenco di array a un elenco di array unidimensionale compatibile, a partire dall'indice specificato dell'elenco di array di destinazione.|
| [`index_of(self, item, index)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/index_of/#aspose.cells.drawing.shape-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dall'indice specificato all'ultimo elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/index_of/#aspose.cells.drawing.shape-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che inizia dall'indice specificato e contiene il numero specificato di elementi.|
| [`last_index_of(self, item)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/last_index_of/#aspose.cells.drawing.shape) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intero elenco di array.|
| [`last_index_of(self, item, index)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/last_index_of/#aspose.cells.drawing.shape-int) |Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dal primo elemento all'indice specificato.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/last_index_of/#aspose.cells.drawing.shape-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che contiene il numero specificato di elementi e termina all'indice specificato.|
| [`get(self, name)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/get/#str) | Ottiene l'oggetto [`Shape`](/cells/python-net/it/aspose.cells.drawing/shape) in base al nome della forma.|
| [`add_copy(self, source_shape, top_row, top, left_column, left)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_copy/#aspose.cells.drawing.shape-int-int-int-int) | Aggiunge e copia una forma nel foglio di lavoro.|
| [`add_check_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_check_box/#int-int-int-int-int-int) | Aggiunge una casella di controllo al foglio di lavoro.|
| [`add_text_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_text_box/#int-int-int-int-int-int) | Aggiunge una casella di testo al foglio di lavoro.|
| [`add_equation(self, top_row, top, left_column, left, height, width)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_equation/#int-int-int-int-int-int) |Aggiungere un oggetto equazione al foglio di lavoro.|
| [`add_spinner(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_spinner/#int-int-int-int-int-int) | Aggiunge uno Spinner al foglio di lavoro.|
| [`add_scroll_bar(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_scroll_bar/#int-int-int-int-int-int) | Aggiunge una barra di scorrimento al foglio di lavoro.|
| [`add_radio_button(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_radio_button/#int-int-int-int-int-int) | Aggiunge un RadioButton al foglio di lavoro.|
| [`add_list_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_list_box/#int-int-int-int-int-int) | Aggiunge un controllo ListBox al foglio di lavoro.|
| [`add_combo_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_combo_box/#int-int-int-int-int-int) | Aggiunge una casella combinata al foglio di lavoro.|
| [`add_group_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_group_box/#int-int-int-int-int-int) | Aggiunge un GroupBox al foglio di lavoro.|
| [`add_button(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_button/#int-int-int-int-int-int) | Aggiunge un pulsante al foglio di lavoro.|
| [`add_label(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_label/#int-int-int-int-int-int) | Aggiunge un'etichetta al foglio di lavoro.|
| [`add_label_in_chart(self, top, left, height, width)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_label_in_chart/#int-int-int-int) | Aggiunge un'etichetta al grafico.|
| [`add_text_box_in_chart(self, top, left, height, width)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_text_box_in_chart/#int-int-int-int) | Aggiunge una casella di testo al grafico.|
| [`add_text_effect_in_chart(self, effect, text, font_name, size, font_bold, font_italic, top, left, height, width)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_text_effect_in_chart/#aspose.cells.drawing.msopresettexteffect-str-str-int-bool-bool-int-int-int-int) | Inserisce un oggetto WordArt nel grafico|
| [`add_text_effect(self, effect, text, font_name, size, font_bold, font_italic, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_text_effect/#aspose.cells.drawing.msopresettexteffect-str-str-int-bool-bool-int-int-int-int-int-int) | Inserisce un oggetto WordArt.|
| [`add_word_art(self, style, text, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_word_art/#aspose.cells.drawing.presetwordartstyle-str-int-int-int-int-int-int) | Aggiunge WordArt preimpostato da Excel 2007.|
| [`add_rectangle(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_rectangle/#int-int-int-int-int-int) | Aggiunge un oggetto RectangleShape al foglio di lavoro.|
| [`add_oval(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_oval/#int-int-int-int-int-int) | Aggiunge un ovale al foglio di lavoro.|
| [`add_line(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_line/#int-int-int-int-int-int) | Aggiunge una LineShape al foglio di lavoro.|
| [`add_free_floating_shape(self, type, top, left, height, width, image_data, is_original_size)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_free_floating_shape/#aspose.cells.drawing.msodrawingtype-int-int-int-int-bytes-bool) | Aggiunge una forma mobile libera al foglio di lavoro. Si applica solo alle forme linea/immagine.|
| [`add_arc(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_arc/#int-int-int-int-int-int) | Aggiunge un ArcShape al foglio di lavoro.|
| [`add_shape(self, type, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_shape/#aspose.cells.drawing.msodrawingtype-int-int-int-int-int-int) | Aggiunge una forma al foglio di lavoro.|
| [`add_auto_shape(self, type, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_auto_shape/#aspose.cells.drawing.autoshapetype-int-int-int-int-int-int) | Aggiunge una forma automatica al foglio di lavoro.|
| [`add_auto_shape_in_chart(self, type, top, left, height, width)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_auto_shape_in_chart/#aspose.cells.drawing.autoshapetype-int-int-int-int) | Aggiunge una forma automatica al grafico.|
| [`add_active_x_control(self, type, top_row, top, left_column, left, width, height)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_active_x_control/#aspose.cells.drawing.activexcontrols.controltype-int-int-int-int-int-int) | Crea un controllo ActiveX.|
| [`add_svg(self, upper_left_row, top, upper_left_column, left, height, width, svg_data, compatible_image_data)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_svg/#int-int-int-int-int-int-bytes-bytes) | Aggiunge l'immagine svg.|
| [`add_icons(self, upper_left_row, top, upper_left_column, left, height, width, image_byte_data, compatible_image_data)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_icons/#int-int-int-int-int-int-bytes-bytes) | Aggiunge l'immagine svg.|
| [`add_linked_picture(self, upper_left_row, upper_left_column, height, width, source_full_name)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_linked_picture/#int-int-int-int-str) |Aggiungi un'immagine collegata.|
| [`add_ole_object_with_linked_image(self, upper_left_row, upper_left_column, height, width, source_full_name)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_ole_object_with_linked_image/#int-int-int-int-str) |Aggiungi un'immagine collegata.|
| [`add_picture_in_chart(self, top, left, stream, width_scale, height_scale)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_picture_in_chart/#int-int-io.rawiobase-int-int) | Aggiunge un'immagine al grafico.|
| [`add_ole_object(self, upper_left_row, top, upper_left_column, left, height, width, image_data)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_ole_object/#int-int-int-int-int-int-bytes) | Aggiunge un OleObject.|
| [`copy_comments_in_range(self, shapes, ca, dest_row, dest_column)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/copy_comments_in_range/#aspose.cells.drawing.shapecollection-aspose.cells.cellarea-int-int) | Copia tutti i commenti nell'intervallo.|
| [`copy_in_range(self, source_shapes, ca, dest_row, dest_column, is_contained)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/copy_in_range/#aspose.cells.drawing.shapecollection-aspose.cells.cellarea-int-int-bool) | Copia le forme nell'intervallo nell'intervallo di destinazione.|
| [`delete_in_range(self, ca)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/delete_in_range/#aspose.cells.cellarea) | Elimina le forme nell'intervallo. Le forme dei commenti non verranno eliminate.|
| [`delete_shape(self, shape)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/delete_shape/#aspose.cells.drawing.shape) | Elimina una forma. Se la forma è nel gruppo o è una forma di commento, non verrà eliminata.|
| [`group(self, group_items)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/group/#list) | Raggruppa le forme.|
| [`ungroup(self, group)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/ungroup/#aspose.cells.drawing.groupshape) | Separa gli elementi della forma.|
| [`remove_a_shape(self, shape)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/remove_a_shape/#aspose.cells.drawing.shape) | Aggiungi API for Python tramite .Net poiché questo API non è supportato|
| [`update_selected_value(self)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/update_selected_value/#) | Aggiorna il valore selezionato in base al valore della cella collegata o dell'intervallo della forma.|
| [`add_freeform(self, upper_left_row, top, upper_left_column, left, height, width, paths)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_freeform/#int-int-int-int-int-int-list) | Aggiunge una forma libera al foglio di lavoro.|
| [`add_signature_line(self, upper_left_row, upper_left_column, signature_line)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/add_signature_line/#int-int-aspose.cells.drawing.signatureline) | Aggiunge una riga di firma al foglio di lavoro.|
| [`binary_search(self, item)`](/cells/python-net/it/aspose.cells.drawing/shapecollection/binary_search/#aspose.cells.drawing.shape) | Cerca un elemento nell'intero elenco dell'array ordinato utilizzando il comparatore predefinito e restituisce l'indice basato su zero dell'elemento.|



###  Esempio

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

###  Guarda anche
* modulo [`aspose.cells.drawing`](..)
* classe [`Shape`](/cells/python-net/it/aspose.cells.drawing/shape)
