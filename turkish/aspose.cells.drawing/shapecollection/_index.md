---
title: ShapeCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 510
url: /tr/aspose.cells.drawing/shapecollection/
is_root: false
---
##  ShapeCollection sınıfı
Bir çalışma sayfasındaki/grafikteki tüm şekilleri temsil eder.



ShapeCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [capacity](/cells/python-net/tr/aspose.cells.drawing/shapecollection/capacity) | Dizi listesinin içerebileceği eleman sayısını alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`add_shape_in_chart(self, type, placement, left, top, right, bottom, image_data)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_shape_in_chart/#aspose.cells.drawing.msodrawingtype-aspose.cells.drawing.placementtype-int-int-int-int-bytes) | Grafiğe bir şekil ekleyin. Tüm birimler grafik alanının 1/4000'idir.|
| [`add_shape_in_chart(self, type, placement, left, top, right, bottom)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_shape_in_chart/#aspose.cells.drawing.msodrawingtype-aspose.cells.drawing.placementtype-int-int-int-int) | Grafiğe bir şekil ekleyin. Tüm birimler grafik alanının 1/4000'idir.|
| [`add_shape_in_chart_by_scale(self, type, placement, left, top, right, bottom)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_shape_in_chart_by_scale/#aspose.cells.drawing.msodrawingtype-aspose.cells.drawing.placementtype-float-float-float-float) | Grafiğe bir şekil ekleyin. Tüm birimler, grafik alanının yüzdelik ölçeğindedir.|
| [`add_shape_in_chart_by_scale(self, type, placement, left, top, right, bottom, image_data)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_shape_in_chart_by_scale/#aspose.cells.drawing.msodrawingtype-aspose.cells.drawing.placementtype-float-float-float-float-bytes) | Grafiğe bir şekil ekleyin. Tüm birimler grafik alanının 1/4000'idir.|
| [`add_picture(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_picture/#int-int-int-int-io.rawiobase) | Koleksiyona bir resim ekler.|
| [`add_picture(self, upper_left_row, upper_left_column, stream, width_scale, height_scale)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_picture/#int-int-io.rawiobase-int-int) | Koleksiyona bir resim ekler.|
| [`copy_to(self, array)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/copy_to/#list) |Hedef dizi listesinin başından başlayarak tüm dizi listesini uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/copy_to/#int-list-int-int) | Hedef dizi listesinin belirtilen indeksinden başlayarak, dizi listesindeki bir dizi öğeyi uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`index_of(self, item, index)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/index_of/#aspose.cells.drawing.shape-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının, belirtilen indeksten son elemana kadar uzanan ilk oluşumunun sıfırdan başlayan indeksini döndürür.|
| [`index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/index_of/#aspose.cells.drawing.shape-int-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığında belirtilen indeksten başlayıp belirtilen sayıda eleman içeren ilk oluşumun sıfırdan başlayan indeksini döndürür.|
| [`last_index_of(self, item)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/last_index_of/#aspose.cells.drawing.shape) | Belirtilen nesneyi arar ve tüm dizi listesindeki son oluşumun sıfırdan başlayan dizinini döndürür.|
| [`last_index_of(self, item, index)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/last_index_of/#aspose.cells.drawing.shape-int) |Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının ilk elemanından belirtilen dizine kadar uzanan son oluşumun sıfır tabanlı dizinini döndürür.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/last_index_of/#aspose.cells.drawing.shape-int-int) | Belirtilen nesneyi arar ve dizi listesindeki belirtilen sayıda öğeyi içeren ve belirtilen dizinde sona eren öğe aralığındaki son oluşumun sıfır tabanlı dizinini döndürür.|
| [`get(self, name)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/get/#str) | Şeklin adına göre [`Shape`](/cells/python-net/tr/aspose.cells.drawing/shape) nesnesini alır.|
| [`add_copy(self, source_shape, top_row, top, left_column, left)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_copy/#aspose.cells.drawing.shape-int-int-int-int) | Çalışma sayfasına bir şekil ekler ve kopyalar.|
| [`add_check_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_check_box/#int-int-int-int-int-int) | Çalışma sayfasına bir onay kutusu ekler.|
| [`add_text_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_text_box/#int-int-int-int-int-int) | Çalışma sayfasına bir metin kutusu ekler.|
| [`add_equation(self, top_row, top, left_column, left, height, width)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_equation/#int-int-int-int-int-int) |Çalışma sayfasına bir denklem nesnesi ekleyin.|
| [`add_spinner(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_spinner/#int-int-int-int-int-int) | Çalışma sayfasına bir Döndürücü ekler.|
| [`add_scroll_bar(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_scroll_bar/#int-int-int-int-int-int) | Çalışma sayfasına bir Kaydırma Çubuğu ekler.|
| [`add_radio_button(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_radio_button/#int-int-int-int-int-int) | Çalışma sayfasına bir RadioButton ekler.|
| [`add_list_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_list_box/#int-int-int-int-int-int) | Çalışma sayfasına bir ListBox ekler.|
| [`add_combo_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_combo_box/#int-int-int-int-int-int) | Çalışma sayfasına bir ComboBox ekler.|
| [`add_group_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_group_box/#int-int-int-int-int-int) | Çalışma sayfasına bir GroupBox ekler.|
| [`add_button(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_button/#int-int-int-int-int-int) | Çalışma sayfasına bir Düğme ekler.|
| [`add_label(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_label/#int-int-int-int-int-int) | Çalışma sayfasına bir Etiket ekler.|
| [`add_label_in_chart(self, top, left, height, width)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_label_in_chart/#int-int-int-int) | Grafiğe bir etiket ekler.|
| [`add_text_box_in_chart(self, top, left, height, width)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_text_box_in_chart/#int-int-int-int) | Grafiğe bir metin kutusu ekler.|
| [`add_text_effect_in_chart(self, effect, text, font_name, size, font_bold, font_italic, top, left, height, width)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_text_effect_in_chart/#aspose.cells.drawing.msopresettexteffect-str-str-int-bool-bool-int-int-int-int) | Grafiğe bir WordArt nesnesi ekler|
| [`add_text_effect(self, effect, text, font_name, size, font_bold, font_italic, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_text_effect/#aspose.cells.drawing.msopresettexteffect-str-str-int-bool-bool-int-int-int-int-int-int) | Bir WordArt nesnesi ekler.|
| [`add_word_art(self, style, text, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_word_art/#aspose.cells.drawing.presetwordartstyle-str-int-int-int-int-int-int) | Excel 2007'den bu yana önceden ayarlanmış WordArt ekler|
| [`add_rectangle(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_rectangle/#int-int-int-int-int-int) | Çalışma sayfasına bir Dikdörtgen Şekli ekler.|
| [`add_oval(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_oval/#int-int-int-int-int-int) | Çalışma sayfasına bir Oval ekler.|
| [`add_line(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_line/#int-int-int-int-int-int) | Çalışma sayfasına bir Çizgi Şekli ekler.|
| [`add_free_floating_shape(self, type, top, left, height, width, image_data, is_original_size)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_free_floating_shape/#aspose.cells.drawing.msodrawingtype-int-int-int-int-bytes-bool) | Çalışma sayfasına serbest yüzen bir şekil ekler. Sadece çizgi/görüntü şekli için geçerlidir.|
| [`add_arc(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_arc/#int-int-int-int-int-int) | Çalışma sayfasına bir ArcShape ekler.|
| [`add_shape(self, type, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_shape/#aspose.cells.drawing.msodrawingtype-int-int-int-int-int-int) | Çalışma sayfasına bir Şekil ekler.|
| [`add_auto_shape(self, type, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_auto_shape/#aspose.cells.drawing.autoshapetype-int-int-int-int-int-int) | Çalışma sayfasına bir Otomatik Şekil ekler.|
| [`add_auto_shape_in_chart(self, type, top, left, height, width)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_auto_shape_in_chart/#aspose.cells.drawing.autoshapetype-int-int-int-int) | Grafiğe bir Otomatik Şekil ekler.|
| [`add_active_x_control(self, type, top_row, top, left_column, left, width, height)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_active_x_control/#aspose.cells.drawing.activexcontrols.controltype-int-int-int-int-int-int) | Bir Activex Denetimi oluşturur.|
| [`add_svg(self, upper_left_row, top, upper_left_column, left, height, width, svg_data, compatible_image_data)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_svg/#int-int-int-int-int-int-bytes-bytes) | SVG görseli ekler.|
| [`add_icons(self, upper_left_row, top, upper_left_column, left, height, width, image_byte_data, compatible_image_data)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_icons/#int-int-int-int-int-int-bytes-bytes) | SVG görseli ekler.|
| [`add_linked_picture(self, upper_left_row, upper_left_column, height, width, source_full_name)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_linked_picture/#int-int-int-int-str) |Bağlantılı bir resim ekleyin.|
| [`add_ole_object_with_linked_image(self, upper_left_row, upper_left_column, height, width, source_full_name)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_ole_object_with_linked_image/#int-int-int-int-str) |Bağlantılı bir resim ekleyin.|
| [`add_picture_in_chart(self, top, left, stream, width_scale, height_scale)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_picture_in_chart/#int-int-io.rawiobase-int-int) | Tabloya resim ekler.|
| [`add_ole_object(self, upper_left_row, top, upper_left_column, left, height, width, image_data)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_ole_object/#int-int-int-int-int-int-bytes) | Bir OleObject ekler.|
| [`copy_comments_in_range(self, shapes, ca, dest_row, dest_column)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/copy_comments_in_range/#aspose.cells.drawing.shapecollection-aspose.cells.cellarea-int-int) | Aralıktaki tüm yorumları kopyalayın.|
| [`copy_in_range(self, source_shapes, ca, dest_row, dest_column, is_contained)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/copy_in_range/#aspose.cells.drawing.shapecollection-aspose.cells.cellarea-int-int-bool) | Aralıktaki şekilleri hedef aralığa kopyala.|
| [`delete_in_range(self, ca)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/delete_in_range/#aspose.cells.cellarea) | Aralıktaki şekilleri silin.Yorum şekilleri silinmeyecektir.|
| [`delete_shape(self, shape)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/delete_shape/#aspose.cells.drawing.shape) | Bir şekli silin. Şekil gruptaysa veya bir yorum şekliyse silinmez.|
| [`group(self, group_items)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/group/#list) | Şekilleri gruplandırın.|
| [`ungroup(self, group)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/ungroup/#aspose.cells.drawing.groupshape) | Şekil öğelerini gruplandırmayı kaldırır.|
| [`remove_a_shape(self, shape)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/remove_a_shape/#aspose.cells.drawing.shape) | API for Python'i .Net üzerinden ekleyin. Bu API desteklenmediğinden|
| [`update_selected_value(self)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/update_selected_value/#) | Seçili değeri, bağlantılı hücrenin veya şeklin aralığının değerine göre güncelle.|
| [`add_freeform(self, upper_left_row, top, upper_left_column, left, height, width, paths)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_freeform/#int-int-int-int-int-int-list) | Çalışma sayfasına serbest biçimli bir şekil ekler.|
| [`add_signature_line(self, upper_left_row, upper_left_column, signature_line)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/add_signature_line/#int-int-aspose.cells.drawing.signatureline) | Çalışma sayfasına İmza Satırı ekler.|
| [`binary_search(self, item)`](/cells/python-net/tr/aspose.cells.drawing/shapecollection/binary_search/#aspose.cells.drawing.shape) | Varsayılan karşılaştırıcıyı kullanarak sıralanmış dizi listesinin tamamında bir öğe arar ve öğenin sıfırdan başlayan dizinini döndürür.|



###  Örnek

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

###  Ayrıca bakınız
* modül [`aspose.cells.drawing`](..)
* sınıf [`Shape`](/cells/python-net/tr/aspose.cells.drawing/shape)
