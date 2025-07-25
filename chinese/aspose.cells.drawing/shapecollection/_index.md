---
title: ShapeCollection类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 510
url: /zh/aspose.cells.drawing/shapecollection/
is_root: false
---
## ShapeCollection类
代表工作表/图表中的所有形状。



ShapeCollection 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [capacity](/cells/python-net/zh/aspose.cells.drawing/shapecollection/capacity) |获取或设置数组列表可包含的元素数量。|


### 方法
|方法|描述|
| :- | :- |
| [`add_shape_in_chart(self, type, placement, left, top, right, bottom, image_data)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_shape_in_chart/#aspose.cells.drawing.msodrawingtype-aspose.cells.drawing.placementtype-int-int-int-int-bytes) |向图表添加形状。所有单位都是图表面积的 1/4000。|
| [`add_shape_in_chart(self, type, placement, left, top, right, bottom)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_shape_in_chart/#aspose.cells.drawing.msodrawingtype-aspose.cells.drawing.placementtype-int-int-int-int) |向图表添加形状。所有单位都是图表面积的 1/4000。|
| [`add_shape_in_chart_by_scale(self, type, placement, left, top, right, bottom)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_shape_in_chart_by_scale/#aspose.cells.drawing.msodrawingtype-aspose.cells.drawing.placementtype-float-float-float-float) |向图表添加形状。所有单位均为图表区域的百分比比例。|
| [`add_shape_in_chart_by_scale(self, type, placement, left, top, right, bottom, image_data)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_shape_in_chart_by_scale/#aspose.cells.drawing.msodrawingtype-aspose.cells.drawing.placementtype-float-float-float-float-bytes) |向图表添加形状。所有单位都是图表面积的 1/4000。|
| [`add_picture(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_picture/#int-int-int-int-io.rawiobase) |将图片添加到收藏夹。|
| [`add_picture(self, upper_left_row, upper_left_column, stream, width_scale, height_scale)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_picture/#int-int-io.rawiobase-int-int) |将图片添加到收藏夹。|
| [`copy_to(self, array)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/copy_to/#list) |将整个数组列表复制到兼容的一维数组列表，从目标数组列表的开头开始。|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/copy_to/#int-list-int-int) |从目标数组列表的指定索引开始，将数组列表中的一系列元素复制到兼容的一维数组列表中。|
| [`index_of(self, item, index)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/index_of/#aspose.cells.drawing.shape-int) |搜索指定的对象并返回从指定索引延伸到最后一个元素的数组列表中元素范围内第一个出现的从零开始的索引。|
| [`index_of(self, item, index, count)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/index_of/#aspose.cells.drawing.shape-int-int) |搜索指定的对象并返回从指定索引开始并包含指定数量元素的数组列表中元素范围内第一次出现的从零开始的索引。|
| [`last_index_of(self, item)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/last_index_of/#aspose.cells.drawing.shape) |搜索指定的对象并返回整个数组列表中最后一次出现的从零开始的索引。|
| [`last_index_of(self, item, index)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/last_index_of/#aspose.cells.drawing.shape-int) |搜索指定的对象并返回从第一个元素延伸到指定索引的数组列表中元素范围内的最后一个出现的从零开始的索引。|
| [`last_index_of(self, item, index, count)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/last_index_of/#aspose.cells.drawing.shape-int-int) |搜索指定的对象并返回包含指定数量的元素并以指定索引结束的数组列表中元素范围内的最后一个出现的从零开始的索引。|
| [`get(self, name)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/get/#str) |通过形状名称获取[`Shape`](/cells/python-net/zh/aspose.cells.drawing/shape)对象。|
| [`add_copy(self, source_shape, top_row, top, left_column, left)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_copy/#aspose.cells.drawing.shape-int-int-int-int) |添加并复制形状到工作表。|
| [`add_check_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_check_box/#int-int-int-int-int-int) |向工作表添加一个复选框。|
| [`add_text_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_text_box/#int-int-int-int-int-int) |向工作表添加一个文本框。|
| [`add_equation(self, top_row, top, left_column, left, height, width)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_equation/#int-int-int-int-int-int) |向工作表添加一个方程对象。|
| [`add_spinner(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_spinner/#int-int-int-int-int-int) |向工作表添加一个 Spinner。|
| [`add_scroll_bar(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_scroll_bar/#int-int-int-int-int-int) |向工作表添加滚动条。|
| [`add_radio_button(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_radio_button/#int-int-int-int-int-int) |向工作表添加一个 RadioButton。|
| [`add_list_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_list_box/#int-int-int-int-int-int) |向工作表添加一个 ListBox。|
| [`add_combo_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_combo_box/#int-int-int-int-int-int) |向工作表添加一个组合框。|
| [`add_group_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_group_box/#int-int-int-int-int-int) |将 GroupBox 添加到工作表。|
| [`add_button(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_button/#int-int-int-int-int-int) |向工作表添加一个按钮。|
| [`add_label(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_label/#int-int-int-int-int-int) |向工作表添加标签。|
| [`add_label_in_chart(self, top, left, height, width)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_label_in_chart/#int-int-int-int) |向图表添加标签。|
| [`add_text_box_in_chart(self, top, left, height, width)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_text_box_in_chart/#int-int-int-int) |向图表添加一个文本框。|
| [`add_text_effect_in_chart(self, effect, text, font_name, size, font_bold, font_italic, top, left, height, width)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_text_effect_in_chart/#aspose.cells.drawing.msopresettexteffect-str-str-int-bool-bool-int-int-int-int) |将艺术字对象插入图表|
| [`add_text_effect(self, effect, text, font_name, size, font_bold, font_italic, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_text_effect/#aspose.cells.drawing.msopresettexteffect-str-str-int-bool-bool-int-int-int-int-int-int) |插入艺术字对象。|
| [`add_word_art(self, style, text, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_word_art/#aspose.cells.drawing.presetwordartstyle-str-int-int-int-int-int-int) |自 Excel 2007 起添加预设艺术字。|
| [`add_rectangle(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_rectangle/#int-int-int-int-int-int) |向工作表添加一个 RectangleShape。|
| [`add_oval(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_oval/#int-int-int-int-int-int) |在工作表中添加一个椭圆。|
| [`add_line(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_line/#int-int-int-int-int-int) |向工作表添加 LineShape。|
| [`add_free_floating_shape(self, type, top, left, height, width, image_data, is_original_size)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_free_floating_shape/#aspose.cells.drawing.msodrawingtype-int-int-int-int-bytes-bool) |向工作表添加自由浮动形状。仅适用于线条/图像形状。|
| [`add_arc(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_arc/#int-int-int-int-int-int) |将 ArcShape 添加到工作表。|
| [`add_shape(self, type, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_shape/#aspose.cells.drawing.msodrawingtype-int-int-int-int-int-int) |向工作表添加形状。|
| [`add_auto_shape(self, type, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_auto_shape/#aspose.cells.drawing.autoshapetype-int-int-int-int-int-int) |向工作表添加自选图形。|
| [`add_auto_shape_in_chart(self, type, top, left, height, width)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_auto_shape_in_chart/#aspose.cells.drawing.autoshapetype-int-int-int-int) |向图表添加自选图形。|
| [`add_active_x_control(self, type, top_row, top, left_column, left, width, height)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_active_x_control/#aspose.cells.drawing.activexcontrols.controltype-int-int-int-int-int-int) |创建一个 Activex 控件。|
| [`add_svg(self, upper_left_row, top, upper_left_column, left, height, width, svg_data, compatible_image_data)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_svg/#int-int-int-int-int-int-bytes-bytes) |添加 svg 图像。|
| [`add_icons(self, upper_left_row, top, upper_left_column, left, height, width, image_byte_data, compatible_image_data)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_icons/#int-int-int-int-int-int-bytes-bytes) |添加 svg 图像。|
| [`add_linked_picture(self, upper_left_row, upper_left_column, height, width, source_full_name)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_linked_picture/#int-int-int-int-str) |添加链接图片。|
| [`add_ole_object_with_linked_image(self, upper_left_row, upper_left_column, height, width, source_full_name)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_ole_object_with_linked_image/#int-int-int-int-str) |添加链接图片。|
| [`add_picture_in_chart(self, top, left, stream, width_scale, height_scale)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_picture_in_chart/#int-int-io.rawiobase-int-int) |向图表添加图片。|
| [`add_ole_object(self, upper_left_row, top, upper_left_column, left, height, width, image_data)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_ole_object/#int-int-int-int-int-int-bytes) |添加一个 OleObject。|
| [`copy_comments_in_range(self, shapes, ca, dest_row, dest_column)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/copy_comments_in_range/#aspose.cells.drawing.shapecollection-aspose.cells.cellarea-int-int) |复制范围内的所有注意事项。|
| [`copy_in_range(self, source_shapes, ca, dest_row, dest_column, is_contained)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/copy_in_range/#aspose.cells.drawing.shapecollection-aspose.cells.cellarea-int-int-bool) |将范围内的形状复制到目标范围。|
| [`delete_in_range(self, ca)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/delete_in_range/#aspose.cells.cellarea) |删除范围内的形状。注释形状不会被删除。|
| [`delete_shape(self, shape)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/delete_shape/#aspose.cells.drawing.shape) |删除形状。如果形状在组中或为注释形状，则不会被删除。|
| [`group(self, group_items)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/group/#list) |将形状分组。|
| [`ungroup(self, group)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/ungroup/#aspose.cells.drawing.groupshape) |取消形状项目的组合。|
| [`remove_a_shape(self, shape)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/remove_a_shape/#aspose.cells.drawing.shape) |通过 .Net 添加 API for Python，因为此 API 不受支持|
| [`update_selected_value(self)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/update_selected_value/#) |通过形状的链接单元格或范围的值更新选定的值。|
| [`add_freeform(self, upper_left_row, top, upper_left_column, left, height, width, paths)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_freeform/#int-int-int-int-int-int-list) |向工作表添加自由形状。|
| [`add_signature_line(self, upper_left_row, upper_left_column, signature_line)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/add_signature_line/#int-int-aspose.cells.drawing.signatureline) |在工作表中添加签名行。|
| [`binary_search(self, item)`](/cells/python-net/zh/aspose.cells.drawing/shapecollection/binary_search/#aspose.cells.drawing.shape) |使用默认比较器在整个排序数组列表中搜索元素，并返回该元素从零开始的索引。|



### 例子

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

### 也可以看看
* 模块[`aspose.cells.drawing`](..)
* 类 [`Shape`](/cells/python-net/zh/aspose.cells.drawing/shape)
