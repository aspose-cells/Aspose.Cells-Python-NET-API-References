---
title: AutoFilter类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 40
url: /zh/aspose.cells/autofilter/
is_root: false
---
## AutoFilter类
表示对指定工作表进行自动筛选。



AutoFilter 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [sorter](/cells/python-net/zh/aspose.cells/autofilter/sorter) |获取数据分类器。|
| [range](/cells/python-net/zh/aspose.cells/autofilter/range) |代表指定自动筛选适用的范围。|
| [show_filter_button](/cells/python-net/zh/aspose.cells/autofilter/show_filter_button) |指示此列的自动筛选按钮是否可见。|
| [filter_columns](/cells/python-net/zh/aspose.cells/autofilter/filter_columns) |获取过滤列的集合。|


### 方法
|方法|描述|
| :- | :- |
| [`get_cell_area(self)`](/cells/python-net/zh/aspose.cells/autofilter/get_cell_area/#) |获取此自动筛选器适用的 [`CellArea`](/cells/python-net/zh/aspose.cells/cellarea)。|
| [`get_cell_area(self, refresh_applied_range)`](/cells/python-net/zh/aspose.cells/autofilter/get_cell_area/#bool) |获取指定自动筛选器适用的 [`CellArea`](/cells/python-net/zh/aspose.cells/cellarea)。|
| [`remove_filter(self, field_index, criteria)`](/cells/python-net/zh/aspose.cells/autofilter/remove_filter/#int-str) |删除过滤器列的过滤器。|
| [`remove_filter(self, field_index)`](/cells/python-net/zh/aspose.cells/autofilter/remove_filter/#int) |删除特定的过滤器。|
| [`custom(self, field_index, operator_type1, criteria1)`](/cells/python-net/zh/aspose.cells/autofilter/custom/#int-aspose.cells.filteroperatortype-any) |使用自定义标准过滤列表。|
| [`custom(self, field_index, operator_type1, criteria1, is_and, operator_type2, criteria2)`](/cells/python-net/zh/aspose.cells/autofilter/custom/#int-aspose.cells.filteroperatortype-any-bool-aspose.cells.filteroperatortype-any) |使用自定义标准过滤列表。|
| [`refresh(self)`](/cells/python-net/zh/aspose.cells/autofilter/refresh/#) |刷新自动过滤器以隐藏或取消隐藏行。|
| [`refresh(self, hide_rows)`](/cells/python-net/zh/aspose.cells/autofilter/refresh/#bool) |获取所有隐藏行的索引。|
| [`set_range(self, row, start_column, end_column)`](/cells/python-net/zh/aspose.cells/autofilter/set_range/#int-int-int) |设置指定自动筛选适用的范围。|
| [`add_filter(self, field_index, criteria)`](/cells/python-net/zh/aspose.cells/autofilter/add_filter/#int-str) |为过滤列添加过滤器。|
| [`add_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second)`](/cells/python-net/zh/aspose.cells/autofilter/add_date_filter/#int-aspose.cells.datetimegroupingtype-int-int-int-int-int-int) |添加日期过滤器。|
| [`remove_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second)`](/cells/python-net/zh/aspose.cells/autofilter/remove_date_filter/#int-aspose.cells.datetimegroupingtype-int-int-int-int-int-int) |删除日期过滤器。|
| [`filter(self, field_index, criteria)`](/cells/python-net/zh/aspose.cells/autofilter/filter/#int-str) |使用指定条件过滤列表。|
| [`filter_top10(self, field_index, is_top, is_percent, item_count)`](/cells/python-net/zh/aspose.cells/autofilter/filter_top10/#int-bool-bool-int) |筛选列表中的前 10 个项目|
| [`dynamic_filter(self, field_index, dynamic_filter_type)`](/cells/python-net/zh/aspose.cells/autofilter/dynamic_filter/#int-aspose.cells.dynamicfiltertype) |添加动态过滤器。|
| [`add_font_color_filter(self, field_index, color)`](/cells/python-net/zh/aspose.cells/autofilter/add_font_color_filter/#int-aspose.cells.cellscolor) |添加字体颜色过滤器。|
| [`add_fill_color_filter(self, field_index, pattern, foreground_color, background_color)`](/cells/python-net/zh/aspose.cells/autofilter/add_fill_color_filter/#int-aspose.cells.backgroundtype-aspose.cells.cellscolor-aspose.cells.cellscolor) |添加填充颜色滤镜。|
| [`add_icon_filter(self, field_index, icon_set_type, icon_id)`](/cells/python-net/zh/aspose.cells/autofilter/add_icon_filter/#int-aspose.cells.iconsettype-int) |添加图标过滤器。|
| [`match_blanks(self, field_index)`](/cells/python-net/zh/aspose.cells/autofilter/match_blanks/#int) |匹配列表中的所有空白单元格。|
| [`match_non_blanks(self, field_index)`](/cells/python-net/zh/aspose.cells/autofilter/match_non_blanks/#int) |匹配列表中所有非空白单元格。|
| [`show_all(self)`](/cells/python-net/zh/aspose.cells/autofilter/show_all/#) |取消隐藏所有行。|



### 例子

```python
from aspose.cells import Workbook

# Creating a file stream containing the Excel file to be opened
# Instantiating a Workbook object
workbook = Workbook("template.xlsx")
# Accessing the first worksheet in the Excel file
worksheet = workbook.worksheets[0]
# Creating AutoFilter by giving the cells range of the heading row
worksheet.auto_filter.range = "A1:B1"
# Filtering columns with specified values
worksheet.auto_filter.filter(1, "Bananas")
# Saving the modified Excel file.
workbook.save("output.xls")

```

### 也可以看看
* 模块[`aspose.cells`](..)
* 类 [`CellArea`](/cells/python-net/zh/aspose.cells/cellarea)
