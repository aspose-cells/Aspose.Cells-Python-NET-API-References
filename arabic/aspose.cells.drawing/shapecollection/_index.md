---
title: ShapeCollection صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 510
url: /ar/aspose.cells.drawing/shapecollection/
is_root: false
---
##  ShapeCollection صف
يمثل كافة الأشكال في ورقة العمل/المخطط.



يكشف النوع ShapeCollection عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [capacity](/cells/python-net/ar/aspose.cells.drawing/shapecollection/capacity) | يحصل على عدد العناصر التي يمكن أن تحتويها قائمة المصفوفة أو يعينها.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`add_shape_in_chart(self, type, placement, left, top, right, bottom, image_data)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_shape_in_chart/#aspose.cells.drawing.msodrawingtype-aspose.cells.drawing.placementtype-int-int-int-int-bytes) | أضف شكلاً إلى الرسم البياني. كل وحدة هي 1/4000 من مساحة الرسم البياني.|
| [`add_shape_in_chart(self, type, placement, left, top, right, bottom)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_shape_in_chart/#aspose.cells.drawing.msodrawingtype-aspose.cells.drawing.placementtype-int-int-int-int) | أضف شكلاً إلى الرسم البياني. كل وحدة هي 1/4000 من مساحة الرسم البياني.|
| [`add_shape_in_chart_by_scale(self, type, placement, left, top, right, bottom)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_shape_in_chart_by_scale/#aspose.cells.drawing.msodrawingtype-aspose.cells.drawing.placementtype-float-float-float-float) | أضف شكلاً إلى الرسم البياني. جميع الوحدات هي نسبة مئوية من مساحة الرسم البياني.|
| [`add_shape_in_chart_by_scale(self, type, placement, left, top, right, bottom, image_data)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_shape_in_chart_by_scale/#aspose.cells.drawing.msodrawingtype-aspose.cells.drawing.placementtype-float-float-float-float-bytes) | أضف شكلاً إلى الرسم البياني. كل وحدة هي 1/4000 من مساحة الرسم البياني.|
| [`add_picture(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_picture/#int-int-int-int-io.rawiobase) | إضافة صورة إلى المجموعة.|
| [`add_picture(self, upper_left_row, upper_left_column, stream, width_scale, height_scale)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_picture/#int-int-io.rawiobase-int-int) | إضافة صورة إلى المجموعة.|
| [`copy_to(self, array)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/copy_to/#list) |يقوم بنسخ قائمة المصفوفة بأكملها إلى قائمة مصفوفة أحادية البعد متوافقة، بدءًا من بداية قائمة المصفوفة المستهدفة.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/copy_to/#int-list-int-int) | يقوم بنسخ مجموعة من العناصر من قائمة المصفوفة إلى قائمة مصفوفة أحادية البعد متوافقة، بدءًا من الفهرس المحدد لقائمة المصفوفة المستهدفة.|
| [`index_of(self, item, index)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/index_of/#aspose.cells.drawing.shape-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للظهور الأول ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من الفهرس المحدد إلى العنصر الأخير.|
| [`index_of(self, item, index, count)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/index_of/#aspose.cells.drawing.shape-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للظهور الأول ضمن نطاق العناصر في قائمة المصفوفة التي تبدأ بالفهرس المحدد وتحتوي على العدد المحدد من العناصر.|
| [`last_index_of(self, item)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/last_index_of/#aspose.cells.drawing.shape) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للحدث الأخير ضمن قائمة المصفوفة بأكملها.|
| [`last_index_of(self, item, index)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/last_index_of/#aspose.cells.drawing.shape-int) |يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للحدث الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من العنصر الأول إلى الفهرس المحدد.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/last_index_of/#aspose.cells.drawing.shape-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبدئي للصفر للحدث الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تحتوي على عدد محدد من العناصر وتنتهي عند الفهرس المحدد.|
| [`get(self, name)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/get/#str) | يحصل على الكائن [`Shape`](/cells/python-net/ar/aspose.cells.drawing/shape) حسب اسم الشكل.|
| [`add_copy(self, source_shape, top_row, top, left_column, left)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_copy/#aspose.cells.drawing.shape-int-int-int-int) | إضافة شكل ونسخه إلى ورقة العمل.|
| [`add_check_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_check_box/#int-int-int-int-int-int) | إضافة مربع اختيار إلى ورقة العمل.|
| [`add_text_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_text_box/#int-int-int-int-int-int) | إضافة مربع نص إلى ورقة العمل.|
| [`add_equation(self, top_row, top, left_column, left, height, width)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_equation/#int-int-int-int-int-int) |أضف كائن المعادلة إلى ورقة العمل.|
| [`add_spinner(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_spinner/#int-int-int-int-int-int) | إضافة Spinner إلى ورقة العمل.|
| [`add_scroll_bar(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_scroll_bar/#int-int-int-int-int-int) | إضافة شريط التمرير إلى ورقة العمل.|
| [`add_radio_button(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_radio_button/#int-int-int-int-int-int) | إضافة زر راديو إلى ورقة العمل.|
| [`add_list_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_list_box/#int-int-int-int-int-int) | إضافة ListBox إلى ورقة العمل.|
| [`add_combo_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_combo_box/#int-int-int-int-int-int) | إضافة مربع تحرير وسرد إلى ورقة العمل.|
| [`add_group_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_group_box/#int-int-int-int-int-int) | إضافة GroupBox إلى ورقة العمل.|
| [`add_button(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_button/#int-int-int-int-int-int) | إضافة زر إلى ورقة العمل.|
| [`add_label(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_label/#int-int-int-int-int-int) | إضافة تسمية إلى ورقة العمل.|
| [`add_label_in_chart(self, top, left, height, width)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_label_in_chart/#int-int-int-int) | إضافة تسمية إلى الرسم البياني.|
| [`add_text_box_in_chart(self, top, left, height, width)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_text_box_in_chart/#int-int-int-int) | إضافة مربع نص إلى الرسم البياني.|
| [`add_text_effect_in_chart(self, effect, text, font_name, size, font_bold, font_italic, top, left, height, width)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_text_effect_in_chart/#aspose.cells.drawing.msopresettexteffect-str-str-int-bool-bool-int-int-int-int) | إدراج كائن WordArt في الرسم البياني|
| [`add_text_effect(self, effect, text, font_name, size, font_bold, font_italic, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_text_effect/#aspose.cells.drawing.msopresettexteffect-str-str-int-bool-bool-int-int-int-int-int-int) | إدراج كائن WordArt.|
| [`add_word_art(self, style, text, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_word_art/#aspose.cells.drawing.presetwordartstyle-str-int-int-int-int-int-int) | إضافة WordArt مُعد مسبقًا منذ Excel 2007s|
| [`add_rectangle(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_rectangle/#int-int-int-int-int-int) | إضافة شكل مستطيل إلى ورقة العمل.|
| [`add_oval(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_oval/#int-int-int-int-int-int) | إضافة شكل بيضاوي إلى ورقة العمل.|
| [`add_line(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_line/#int-int-int-int-int-int) | إضافة شكل خطي إلى ورقة العمل.|
| [`add_free_floating_shape(self, type, top, left, height, width, image_data, is_original_size)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_free_floating_shape/#aspose.cells.drawing.msodrawingtype-int-int-int-int-bytes-bool) | يضيف شكلاً عائمًا حرًا إلى ورقة العمل. ينطبق فقط على شكل الخط/الصورة.|
| [`add_arc(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_arc/#int-int-int-int-int-int) | إضافة ArcShape إلى ورقة العمل.|
| [`add_shape(self, type, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_shape/#aspose.cells.drawing.msodrawingtype-int-int-int-int-int-int) | إضافة شكل إلى ورقة العمل.|
| [`add_auto_shape(self, type, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_auto_shape/#aspose.cells.drawing.autoshapetype-int-int-int-int-int-int) | إضافة شكل تلقائي إلى ورقة العمل.|
| [`add_auto_shape_in_chart(self, type, top, left, height, width)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_auto_shape_in_chart/#aspose.cells.drawing.autoshapetype-int-int-int-int) | إضافة شكل تلقائي إلى الرسم البياني.|
| [`add_active_x_control(self, type, top_row, top, left_column, left, width, height)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_active_x_control/#aspose.cells.drawing.activexcontrols.controltype-int-int-int-int-int-int) | إنشاء عنصر تحكم Activex.|
| [`add_svg(self, upper_left_row, top, upper_left_column, left, height, width, svg_data, compatible_image_data)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_svg/#int-int-int-int-int-int-bytes-bytes) | إضافة صورة svg.|
| [`add_icons(self, upper_left_row, top, upper_left_column, left, height, width, image_byte_data, compatible_image_data)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_icons/#int-int-int-int-int-int-bytes-bytes) | إضافة صورة svg.|
| [`add_linked_picture(self, upper_left_row, upper_left_column, height, width, source_full_name)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_linked_picture/#int-int-int-int-str) |أضف صورة مرتبطة.|
| [`add_ole_object_with_linked_image(self, upper_left_row, upper_left_column, height, width, source_full_name)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_ole_object_with_linked_image/#int-int-int-int-str) |أضف صورة مرتبطة.|
| [`add_picture_in_chart(self, top, left, stream, width_scale, height_scale)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_picture_in_chart/#int-int-io.rawiobase-int-int) | إضافة صورة إلى الرسم البياني.|
| [`add_ole_object(self, upper_left_row, top, upper_left_column, left, height, width, image_data)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_ole_object/#int-int-int-int-int-int-bytes) | يضيف OleObject.|
| [`copy_comments_in_range(self, shapes, ca, dest_row, dest_column)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/copy_comments_in_range/#aspose.cells.drawing.shapecollection-aspose.cells.cellarea-int-int) | انسخ جميع التعليقات الموجودة في النطاق.|
| [`copy_in_range(self, source_shapes, ca, dest_row, dest_column, is_contained)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/copy_in_range/#aspose.cells.drawing.shapecollection-aspose.cells.cellarea-int-int-bool) | نسخ الأشكال الموجودة في النطاق إلى نطاق الوجهة.|
| [`delete_in_range(self, ca)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/delete_in_range/#aspose.cells.cellarea) | حذف الأشكال الموجودة في النطاق. لن يتم حذف أشكال التعليق.|
| [`delete_shape(self, shape)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/delete_shape/#aspose.cells.drawing.shape) | احذف شكلاً. إذا كان الشكل ضمن المجموعة أو شكل تعليق، فلن يُحذف.|
| [`group(self, group_items)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/group/#list) | تجميع الأشكال.|
| [`ungroup(self, group)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/ungroup/#aspose.cells.drawing.groupshape) | إلغاء تجميع عناصر الشكل.|
| [`remove_a_shape(self, shape)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/remove_a_shape/#aspose.cells.drawing.shape) | أضف API for Python عبر .Net. نظرًا لأن هذا API غير مدعوم|
| [`update_selected_value(self)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/update_selected_value/#) | قم بتحديث القيمة المحددة حسب قيمة الخلية المرتبطة أو نطاق الشكل.|
| [`add_freeform(self, upper_left_row, top, upper_left_column, left, height, width, paths)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_freeform/#int-int-int-int-int-int-list) | يضيف شكلًا حرًا إلى ورقة العمل.|
| [`add_signature_line(self, upper_left_row, upper_left_column, signature_line)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/add_signature_line/#int-int-aspose.cells.drawing.signatureline) | إضافة سطر التوقيع إلى ورقة العمل.|
| [`binary_search(self, item)`](/cells/python-net/ar/aspose.cells.drawing/shapecollection/binary_search/#aspose.cells.drawing.shape) | يبحث في قائمة المصفوفة المفرزة بأكملها عن عنصر باستخدام المقارن الافتراضي ويعيد الفهرس المبني على الصفر للعنصر.|



###  مثال

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

###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](..)
* فئة [`Shape`](/cells/python-net/ar/aspose.cells.drawing/shape)
