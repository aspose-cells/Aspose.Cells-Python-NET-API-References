---
title: PivotField类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 70
url: /zh/aspose.cells.pivot/pivotfield/
is_root: false
---
## PivotField类
表示数据透视表中的一个字段。



PivotField 类型公开以下成员：

### 特性
|属性|描述|
| :- | :- |
| [pivot_items](/cells/python-net/zh/aspose.cells.pivot/pivotfield/pivot_items) |获取数据透视表字段的数据透视项|
| [range](/cells/python-net/zh/aspose.cells.pivot/pivotfield/range) |获取枢轴字段的组范围|
| [group_settings](/cells/python-net/zh/aspose.cells.pivot/pivotfield/group_settings) |获取数据透视表字段的组设置。|
| [is_calculated_field](/cells/python-net/zh/aspose.cells.pivot/pivotfield/is_calculated_field) |指示指定的数据透视表字段是否为计算字段。|
| [base_index](/cells/python-net/zh/aspose.cells.pivot/pivotfield/base_index) |表示基本数据透视字段中的数据透视字段索引。|
| [position](/cells/python-net/zh/aspose.cells.pivot/pivotfield/position) |代表该地区的索引[`PivotField`](/cells/python-net/zh/aspose.cells.pivot/pivotfield)。|
| [name](/cells/python-net/zh/aspose.cells.pivot/pivotfield/name) |代表数据透视字段的名称。|
| [display_name](/cells/python-net/zh/aspose.cells.pivot/pivotfield/display_name) |表示数据透视字段显示名称。|
| [is_auto_subtotals](/cells/python-net/zh/aspose.cells.pivot/pivotfield/is_auto_subtotals) |指示指定字段是否显示自动小计。默认为 true。|
| [drag_to_column](/cells/python-net/zh/aspose.cells.pivot/pivotfield/drag_to_column) |指示指定字段是否可以拖动到列位置。<br/>默认值是true。|
| [drag_to_hide](/cells/python-net/zh/aspose.cells.pivot/pivotfield/drag_to_hide) |指示指定字段是否可以拖动到隐藏位置。<br/>默认值是true。|
| [drag_to_row](/cells/python-net/zh/aspose.cells.pivot/pivotfield/drag_to_row) |指示指定字段是否可以拖动到行位置。<br/>默认值是true。|
| [drag_to_page](/cells/python-net/zh/aspose.cells.pivot/pivotfield/drag_to_page) |指示指定字段是否可以拖动到页面位置。<br/>默认值是true。|
| [drag_to_data](/cells/python-net/zh/aspose.cells.pivot/pivotfield/drag_to_data) |指示指定字段是否可以拖动到数据位置。<br/>默认值是true。|
| [is_multiple_item_selection_allowed](/cells/python-net/zh/aspose.cells.pivot/pivotfield/is_multiple_item_selection_allowed) |指示该字段是否可以有多个项目<br/>在页面字段中选择<br/>默认值为 false。|
| [is_repeat_item_labels](/cells/python-net/zh/aspose.cells.pivot/pivotfield/is_repeat_item_labels) |指示该字段是否可以重复项目标签<br/>默认值为 false。|
| [is_include_new_items_in_filter](/cells/python-net/zh/aspose.cells.pivot/pivotfield/is_include_new_items_in_filter) |指示该字段是否可以包含手动过滤器中的新项目<br/>默认值为 false。|
| [is_insert_page_breaks_between_items](/cells/python-net/zh/aspose.cells.pivot/pivotfield/is_insert_page_breaks_between_items) |指示该字段是否可以在项目之间插入分页符<br/>在每个项目后插入分页符<br/>默认值为 false。|
| [show_all_items](/cells/python-net/zh/aspose.cells.pivot/pivotfield/show_all_items) |指示数据透视表中是否显示所有项目，<br/>即使它们不包含摘要数据。<br/>显示没有数据的项目<br/>默认值为 false。|
| [non_auto_sort_default](/cells/python-net/zh/aspose.cells.pivot/pivotfield/non_auto_sort_default) |指示将应用于此数据透视字段的排序操作是自动排序操作还是简单数据排序。|
| [is_auto_sort](/cells/python-net/zh/aspose.cells.pivot/pivotfield/is_auto_sort) |指示指定的数据透视表字段是否自动排序。|
| [is_ascend_sort](/cells/python-net/zh/aspose.cells.pivot/pivotfield/is_ascend_sort) |指示指定的数据透视表字段是否按升序自动排序。|
| [auto_sort_field](/cells/python-net/zh/aspose.cells.pivot/pivotfield/auto_sort_field) |表示自动排序字段索引。<br/> -1表示PivotField本身，其他表示数据字段的位置。|
| [is_auto_show](/cells/python-net/zh/aspose.cells.pivot/pivotfield/is_auto_show) |指示是否自动显示指定的数据透视表字段，仅对excel 2003有效。|
| [is_ascend_show](/cells/python-net/zh/aspose.cells.pivot/pivotfield/is_ascend_show) |指示指定的数据透视表字段是否自动升序显示。|
| [auto_show_count](/cells/python-net/zh/aspose.cells.pivot/pivotfield/auto_show_count) |表示顶部或底部项目的数量<br/>自动显示在指定的数据透视表字段中。|
| [auto_show_field](/cells/python-net/zh/aspose.cells.pivot/pivotfield/auto_show_field) |表示自动显示字段索引。 -1 表示 PivotField 本身。<br/>它应该是数据字段的索引。|
| [function](/cells/python-net/zh/aspose.cells.pivot/pivotfield/function) |表示用于汇总数据透视表数据字段的函数。|
| [data_display_format](/cells/python-net/zh/aspose.cells.pivot/pivotfield/data_display_format) |表示如何显示数据字段中包含的值。|
| [base_field_index](/cells/python-net/zh/aspose.cells.pivot/pivotfield/base_field_index) |表示自定义计算的基本字段。|
| [base_item_position](/cells/python-net/zh/aspose.cells.pivot/pivotfield/base_item_position) |表示自定义计算的基本字段中的项目。<br/>仅对数据字段有效。<br/>由于PivotItemPosition.Custom仅供读取，如果需要设置PivotItemPosition.Custom，<br/>请设置 PivotField.BaseItemIndex 属性。|
| [base_item_index](/cells/python-net/zh/aspose.cells.pivot/pivotfield/base_item_index) |表示自定义计算的基本字段中的项目。<br/>仅对数据字段有效。|
| [current_page_item](/cells/python-net/zh/aspose.cells.pivot/pivotfield/current_page_item) |表示页面字段显示的当前页面项（仅对页面字段有效）。|
| [number](/cells/python-net/zh/aspose.cells.pivot/pivotfield/number) |表示数字和日期的内置显示格式。|
| [insert_blank_row](/cells/python-net/zh/aspose.cells.pivot/pivotfield/insert_blank_row) |指示是否在每一项后插入空行。|
| [show_subtotal_at_top](/cells/python-net/zh/aspose.cells.pivot/pivotfield/show_subtotal_at_top) |当 ShowInOutlineForm 为 true 时，则在项目列表的顶部而不是底部显示小计|
| [show_in_outline_form](/cells/python-net/zh/aspose.cells.pivot/pivotfield/show_in_outline_form) |指示是否在数据透视表视图上以大纲形式布局此字段|
| [number_format](/cells/python-net/zh/aspose.cells.pivot/pivotfield/number_format) |表示数字和日期的自定义显示格式。|
| [items](/cells/python-net/zh/aspose.cells.pivot/pivotfield/items) |获得所有基础物品；|
| [original_items](/cells/python-net/zh/aspose.cells.pivot/pivotfield/original_items) |获取原始基础物品；|
| [item_count](/cells/python-net/zh/aspose.cells.pivot/pivotfield/item_count) |获取此数据透视字段的基本项目计数。|
| [show_compact](/cells/python-net/zh/aspose.cells.pivot/pivotfield/show_compact) |指示是否显示数据透视表视图上同一列中下一个字段的标签|


### 方法
|方法|描述|
| :- | :- |
| [group_by](/cells/python-net/zh/aspose.cells.pivot/pivotfield/group_by/#float-bool) |自动将字段与内部分组|
| [group_by](/cells/python-net/zh/aspose.cells.pivot/pivotfield/group_by/#DateTime-DateTime-list-float-bool) |按日期组类型对文件进行分组。|
| [group_by](/cells/python-net/zh/aspose.cells.pivot/pivotfield/group_by/#float-float-float-bool) |按编号对文件进行分组。|
| [group_by](/cells/python-net/zh/aspose.cells.pivot/pivotfield/group_by/#list-bool) |自定义字段分组。|
| [hide_item](/cells/python-net/zh/aspose.cells.pivot/pivotfield/hide_item/#int-bool) |设置数据字段中的特定数据透视项是否隐藏。|
| [hide_item](/cells/python-net/zh/aspose.cells.pivot/pivotfield/hide_item/#str-bool) |设置数据字段中的特定数据透视项是否隐藏。|
| [get_pivot_filter_by_type](/cells/python-net/zh/aspose.cells.pivot/pivotfield/get_pivot_filter_by_type/#aspose.cells.pivot.PivotFilterType) |按类型获取数据透视字段的数据透视过滤器|
| [get_pivot_filters](/cells/python-net/zh/aspose.cells.pivot/pivotfield/get_pivot_filters/#) |获取数据透视表字段的数据透视表过滤器|
| [get_filters](/cells/python-net/zh/aspose.cells.pivot/pivotfield/get_filters/#) |获取该数据透视字段的所有数据透视过滤器。|
| [init_pivot_items](/cells/python-net/zh/aspose.cells.pivot/pivotfield/init_pivot_items/#) |初始化数据透视字段的数据透视项|
| [ungroup](/cells/python-net/zh/aspose.cells.pivot/pivotfield/ungroup/#) |取消枢轴字段的分组。|
| [get_calculated_field_formula](/cells/python-net/zh/aspose.cells.pivot/pivotfield/get_calculated_field_formula/#) |获取指定计算字段的公式字符串。|
| [set_subtotals](/cells/python-net/zh/aspose.cells.pivot/pivotfield/set_subtotals/#aspose.cells.pivot.PivotFieldSubtotalType-bool) |设置指定字段是否显示小计。|
| [get_subtotals](/cells/python-net/zh/aspose.cells.pivot/pivotfield/get_subtotals/#aspose.cells.pivot.PivotFieldSubtotalType) |指示是否显示指定的小计。|
| [is_hidden_item](/cells/python-net/zh/aspose.cells.pivot/pivotfield/is_hidden_item/#int) |指示特定 PivotItem 是否隐藏。|
| [is_hidden_item_detail](/cells/python-net/zh/aspose.cells.pivot/pivotfield/is_hidden_item_detail/#int) |指示特定 PivotItem 是否隐藏详细信息。|
| [hide_item_detail](/cells/python-net/zh/aspose.cells.pivot/pivotfield/hide_item_detail/#int-bool) |设置数据透视字段中的特定数据透视项是否隐藏详细信息。|
| [hide_detail](/cells/python-net/zh/aspose.cells.pivot/pivotfield/hide_detail/#bool) |设置数据透视字段中的数据透视项是否隐藏详细信息。即折叠/展开该字段。|
| [add_calculated_item](/cells/python-net/zh/aspose.cells.pivot/pivotfield/add_calculated_item/#str-str) |将计算项添加到数据透视表字段。|



### 例子

```python
from aspose.cells import Workbook
from aspose.cells.pivot import PivotFieldType, PivotTableStyleType

book = Workbook()
sheet = book.worksheets[0]
cells = sheet.cells
cells.get(0, 0).value = "fruit"
cells.get(1, 0).value = "grape"
cells.get(2, 0).value = "blueberry"
cells.get(3, 0).value = "kiwi"
cells.get(4, 0).value = "cherry"
cells.get(5, 0).value = "grape"
cells.get(6, 0).value = "blueberry"
cells.get(7, 0).value = "kiwi"
cells.get(8, 0).value = "cherry"
cells.get(0, 1).value = "year"
cells.get(1, 1).value = 2020
cells.get(2, 1).value = 2020
cells.get(3, 1).value = 2020
cells.get(4, 1).value = 2020
cells.get(5, 1).value = 2021
cells.get(6, 1).value = 2021
cells.get(7, 1).value = 2021
cells.get(8, 1).value = 2021
cells.get(0, 2).value = "amount"
cells.get(1, 2).value = 50
cells.get(2, 2).value = 60
cells.get(3, 2).value = 70
cells.get(4, 2).value = 80
cells.get(5, 2).value = 90
cells.get(6, 2).value = 100
cells.get(7, 2).value = 110
cells.get(8, 2).value = 120
pivots = sheet.pivot_tables
pivotIndex = pivots.add("=Sheet1!A1:C9", "A12", "TestPivotTable")
pivot = pivots[pivotIndex]
pivot.add_field_to_area(PivotFieldType.ROW, "fruit")
pivot.add_field_to_area(PivotFieldType.COLUMN, "year")
pivot.add_field_to_area(PivotFieldType.DATA, "amount")
pivot.pivot_table_style_type = PivotTableStyleType.PIVOT_TABLE_STYLE_MEDIUM10
# Change PivotField's attributes
rowField = pivot.row_fields[0]
rowField.display_name = "custom display name"
pivot.refresh_data()
pivot.calculate_data()
# do your business
book.save("out.xlsx")

```

### 也可以看看
* 模块[`aspose.cells.pivot`](..)
* 类 [`PivotField`](/cells/python-net/zh/aspose.cells.pivot/pivotfield)
