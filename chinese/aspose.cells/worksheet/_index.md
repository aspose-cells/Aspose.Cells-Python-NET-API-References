---
title: Worksheet类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 1690
url: /zh/aspose.cells/worksheet/
is_root: false
---
## Worksheet类
封装代表单个工作表的对象。



Worksheet 类型公开以下成员：

### 特性
|属性|描述|
| :- | :- |
| [protection](/cells/python-net/zh/aspose.cells/worksheet/protection) |表示可用于工作表的各种类型的保护选项。支持ExcelXP及以上版本的高级保护选项。|
| [unique_id](/cells/python-net/zh/aspose.cells/worksheet/unique_id) |获取和设置唯一id，与{15DB5C3C-A5A1-48AF-8F25-3D86AC232D4F}相同。|
| [workbook](/cells/python-net/zh/aspose.cells/worksheet/workbook) |获取包含此工作表的工作簿对象。|
| [cells](/cells/python-net/zh/aspose.cells/worksheet/cells) |获取 [`Worksheet.cells`](/cells/python-net/zh/aspose.cells/worksheet#cells) 集合。|
| [query_tables](/cells/python-net/zh/aspose.cells/worksheet/query_tables) |在工作表中获取 [`QueryTableCollection`](/cells/python-net/zh/aspose.cells/querytablecollection)。|
| [pivot_tables](/cells/python-net/zh/aspose.cells/worksheet/pivot_tables) |获取此工作表中的所有数据透视表。|
| [type](/cells/python-net/zh/aspose.cells/worksheet/type) |代表工作表类型。|
| [name](/cells/python-net/zh/aspose.cells/worksheet/name) |获取或设置工作表的名称。|
| [show_formulas](/cells/python-net/zh/aspose.cells/worksheet/show_formulas) |指示是否显示公式或其结果。|
| [is_gridlines_visible](/cells/python-net/zh/aspose.cells/worksheet/is_gridlines_visible) |获取或设置一个值，该值指示网格线是否可见。默认值为 true。|
| [is_row_column_headers_visible](/cells/python-net/zh/aspose.cells/worksheet/is_row_column_headers_visible) |获取或设置一个值，该值指示工作表是否显示行标题和列标题。<br/>默认为 true。|
| [pane_state](/cells/python-net/zh/aspose.cells/worksheet/pane_state) |指示窗格是否具有水平或垂直分割，以及这些分割是否被冻结。|
| [display_zeros](/cells/python-net/zh/aspose.cells/worksheet/display_zeros) |如果显示零值则为 True。|
| [display_right_to_left](/cells/python-net/zh/aspose.cells/worksheet/display_right_to_left) |指示指定的工作表是否从右到左显示，而不是从左到右显示。<br/>默认为 false。|
| [is_outline_shown](/cells/python-net/zh/aspose.cells/worksheet/is_outline_shown) |指示是否显示轮廓。|
| [is_selected](/cells/python-net/zh/aspose.cells/worksheet/is_selected) |指示打开工作簿时是否选择该工作表。|
| [list_objects](/cells/python-net/zh/aspose.cells/worksheet/list_objects) |获取此工作表中的所有 ListObject。|
| [tab_id](/cells/python-net/zh/aspose.cells/worksheet/tab_id) |指定工作表的内部标识符。|
| [horizontal_page_breaks](/cells/python-net/zh/aspose.cells/worksheet/horizontal_page_breaks) |获取 [`HorizontalPageBreakCollection`](/cells/python-net/zh/aspose.cells/horizontalpagebreakcollection) 集合。|
| [vertical_page_breaks](/cells/python-net/zh/aspose.cells/worksheet/vertical_page_breaks) |获取 [`VerticalPageBreakCollection`](/cells/python-net/zh/aspose.cells/verticalpagebreakcollection) 集合。|
| [hyperlinks](/cells/python-net/zh/aspose.cells/worksheet/hyperlinks) |获取 [`HyperlinkCollection`](/cells/python-net/zh/aspose.cells/hyperlinkcollection) 集合。|
| [page_setup](/cells/python-net/zh/aspose.cells/worksheet/page_setup) |表示此表中的页面设置描述。|
| [auto_filter](/cells/python-net/zh/aspose.cells/worksheet/auto_filter) |表示指定工作表的自动过滤器。|
| [has_autofilter](/cells/python-net/zh/aspose.cells/worksheet/has_autofilter) |指示此工作表是否具有自动筛选功能。|
| [transition_evaluation](/cells/python-net/zh/aspose.cells/worksheet/transition_evaluation) |指示是否启用转换公式计算（Lotus 兼容性）选项。|
| [transition_entry](/cells/python-net/zh/aspose.cells/worksheet/transition_entry) |指示是否启用转换公式输入（Lotus 兼容性）选项。|
| [visibility_type](/cells/python-net/zh/aspose.cells/worksheet/visibility_type) |指示此工作表的可见状态。|
| [is_visible](/cells/python-net/zh/aspose.cells/worksheet/is_visible) |表示工作表是否可见。|
| [sparkline_group_collection](/cells/python-net/zh/aspose.cells/worksheet/sparkline_group_collection) |获取工作表中的迷你图组集合。|
| [sparkline_groups](/cells/python-net/zh/aspose.cells/worksheet/sparkline_groups) |获取工作表中的迷你图组。|
| [charts](/cells/python-net/zh/aspose.cells/worksheet/charts) |获取[`Chart`](/cells/python-net/zh/aspose.cells.charts/chart)集合|
| [comments](/cells/python-net/zh/aspose.cells/worksheet/comments) |获取 [`Comment`](/cells/python-net/zh/aspose.cells/comment) 集合。|
| [pictures](/cells/python-net/zh/aspose.cells/worksheet/pictures) |获取 [`Picture`](/cells/python-net/zh/aspose.cells.drawing/picture) 集合。|
| [text_boxes](/cells/python-net/zh/aspose.cells/worksheet/text_boxes) |获取 [`TextBox`](/cells/python-net/zh/aspose.cells.drawing/textbox) 集合。|
| [check_boxes](/cells/python-net/zh/aspose.cells/worksheet/check_boxes) |获取 [`CheckBox`](/cells/python-net/zh/aspose.cells.drawing/checkbox) 集合。|
| [ole_objects](/cells/python-net/zh/aspose.cells/worksheet/ole_objects) |表示工作表中 [`OleObject`](/cells/python-net/zh/aspose.cells.drawing/oleobject) 的集合。|
| [shapes](/cells/python-net/zh/aspose.cells/worksheet/shapes) |返回此工作表中的所有绘图形状。|
| [slicers](/cells/python-net/zh/aspose.cells/worksheet/slicers) |获取工作表中的 Slicer 集合|
| [timelines](/cells/python-net/zh/aspose.cells/worksheet/timelines) |获取工作表中的时间轴集合|
| [index](/cells/python-net/zh/aspose.cells/worksheet/index) |获取工作表集合中工作表的索引。|
| [is_protected](/cells/python-net/zh/aspose.cells/worksheet/is_protected) |指示工作表是否受保护。|
| [validations](/cells/python-net/zh/aspose.cells/worksheet/validations) |获取工作表中的数据验证设置集合。|
| [allow_edit_ranges](/cells/python-net/zh/aspose.cells/worksheet/allow_edit_ranges) |获取工作表中允许编辑范围集合。|
| [error_check_options](/cells/python-net/zh/aspose.cells/worksheet/error_check_options) |获取应用于某些范围的错误检查设置。|
| [outline](/cells/python-net/zh/aspose.cells/worksheet/outline) |获取此工作表上的大纲。|
| [first_visible_row](/cells/python-net/zh/aspose.cells/worksheet/first_visible_row) |表示第一个可见行索引。|
| [first_visible_column](/cells/python-net/zh/aspose.cells/worksheet/first_visible_column) |表示第一个可见列索引。|
| [zoom](/cells/python-net/zh/aspose.cells/worksheet/zoom) |表示比例因子（以百分比表示）。它应该在 10 到 400 之间。|
| [view_type](/cells/python-net/zh/aspose.cells/worksheet/view_type) |获取和设置视图类型。|
| [is_page_break_preview](/cells/python-net/zh/aspose.cells/worksheet/is_page_break_preview) |指示指定的工作表是在普通视图还是分页预览中显示。|
| [is_ruler_visible](/cells/python-net/zh/aspose.cells/worksheet/is_ruler_visible) |指示标尺是否可见。该属性仅适用于分页预览。|
| [tab_color](/cells/python-net/zh/aspose.cells/worksheet/tab_color) |代表工作表选项卡颜色。|
| [code_name](/cells/python-net/zh/aspose.cells/worksheet/code_name) |获取工作表代码名称。|
| [background_image](/cells/python-net/zh/aspose.cells/worksheet/background_image) |获取和设置工作表背景图像。|
| [conditional_formattings](/cells/python-net/zh/aspose.cells/worksheet/conditional_formattings) |获取工作表中的条件格式。|
| [active_cell](/cells/python-net/zh/aspose.cells/worksheet/active_cell) |获取或设置工作表中的活动单元格。|
| [custom_properties](/cells/python-net/zh/aspose.cells/worksheet/custom_properties) |获取一个代表的对象<br/>与工作表关联的标识符信息。|
| [smart_tag_setting](/cells/python-net/zh/aspose.cells/worksheet/smart_tag_setting) |获取工作表的所有 [`SmartTagCollection`](/cells/python-net/zh/aspose.cells.markup/smarttagcollection) 对象。|
| [scenarios](/cells/python-net/zh/aspose.cells/worksheet/scenarios) |获取[`Scenario`](/cells/python-net/zh/aspose.cells/scenario)的集合。|
| [cell_watches](/cells/python-net/zh/aspose.cells/worksheet/cell_watches) |获取在“监视窗口”中监视的此工作表上的单元格集合。|


### 方法
|方法|描述|
| :- | :- |
| [freeze_panes](/cells/python-net/zh/aspose.cells/worksheet/freeze_panes/#int-int-int-int) |冻结工作表中指定单元格处的窗格。|
| [freeze_panes](/cells/python-net/zh/aspose.cells/worksheet/freeze_panes/#str-int-int) |冻结工作表中指定单元格处的窗格。|
| [copy](/cells/python-net/zh/aspose.cells/worksheet/copy/#aspose.cells.Worksheet) |从另一个工作表复制内容和格式。|
| [copy](/cells/python-net/zh/aspose.cells/worksheet/copy/#aspose.cells.Worksheet-aspose.cells.CopyOptions) |从另一个工作表复制内容和格式。|
| [auto_fit_column](/cells/python-net/zh/aspose.cells/worksheet/auto_fit_column/#int-int-int) |自动调整列宽。|
| [auto_fit_column](/cells/python-net/zh/aspose.cells/worksheet/auto_fit_column/#int) |自动调整列宽。|
| [auto_fit_columns](/cells/python-net/zh/aspose.cells/worksheet/auto_fit_columns/#) |自动调整此工作表中的所有列。|
| [auto_fit_columns](/cells/python-net/zh/aspose.cells/worksheet/auto_fit_columns/#aspose.cells.AutoFitterOptions) |自动调整此工作表中的所有列。|
| [auto_fit_columns](/cells/python-net/zh/aspose.cells/worksheet/auto_fit_columns/#int-int) |自动调整列宽。|
| [auto_fit_columns](/cells/python-net/zh/aspose.cells/worksheet/auto_fit_columns/#int-int-aspose.cells.AutoFitterOptions) |自动调整列宽。|
| [auto_fit_columns](/cells/python-net/zh/aspose.cells/worksheet/auto_fit_columns/#int-int-int-int) |自动调整列宽。|
| [auto_fit_columns](/cells/python-net/zh/aspose.cells/worksheet/auto_fit_columns/#int-int-int-int-aspose.cells.AutoFitterOptions) |自动调整列宽。|
| [auto_fit_row](/cells/python-net/zh/aspose.cells/worksheet/auto_fit_row/#int-int-int) |自动调整行高。|
| [auto_fit_row](/cells/python-net/zh/aspose.cells/worksheet/auto_fit_row/#int-int-int-aspose.cells.AutoFitterOptions) |自动调整行高。|
| [auto_fit_row](/cells/python-net/zh/aspose.cells/worksheet/auto_fit_row/#int-int-int-int) |在矩形范围内自动调整行高。|
| [auto_fit_row](/cells/python-net/zh/aspose.cells/worksheet/auto_fit_row/#int) |自动调整行高。|
| [auto_fit_rows](/cells/python-net/zh/aspose.cells/worksheet/auto_fit_rows/#) |自动调整此工作表中的所有行。|
| [auto_fit_rows](/cells/python-net/zh/aspose.cells/worksheet/auto_fit_rows/#bool) |自动调整此工作表中的所有行。|
| [auto_fit_rows](/cells/python-net/zh/aspose.cells/worksheet/auto_fit_rows/#aspose.cells.AutoFitterOptions) |自动调整此工作表中的所有行。|
| [auto_fit_rows](/cells/python-net/zh/aspose.cells/worksheet/auto_fit_rows/#int-int) |在一定范围内自动调整行高。|
| [auto_fit_rows](/cells/python-net/zh/aspose.cells/worksheet/auto_fit_rows/#int-int-aspose.cells.AutoFitterOptions) |在一定范围内自动调整行高。|
| [protect](/cells/python-net/zh/aspose.cells/worksheet/protect/#aspose.cells.ProtectionType) |保护工作表。|
| [protect](/cells/python-net/zh/aspose.cells/worksheet/protect/#aspose.cells.ProtectionType-str-str) |保护工作表。|
| [unprotect](/cells/python-net/zh/aspose.cells/worksheet/unprotect/#) |取消工作表保护。|
| [unprotect](/cells/python-net/zh/aspose.cells/worksheet/unprotect/#str) |取消工作表保护。|
| [calculate_formula](/cells/python-net/zh/aspose.cells/worksheet/calculate_formula/#str) |计算公式。|
| [calculate_formula](/cells/python-net/zh/aspose.cells/worksheet/calculate_formula/#str-aspose.cells.CalculationOptions) |直接计算公式表达式。|
| [calculate_formula](/cells/python-net/zh/aspose.cells/worksheet/calculate_formula/#str-aspose.cells.FormulaParseOptions-aspose.cells.CalculationOptions-int-int-aspose.cells.CalculationData) |直接计算公式表达式。|
| [calculate_formula](/cells/python-net/zh/aspose.cells/worksheet/calculate_formula/#aspose.cells.CalculationOptions-bool) |计算此工作表中的所有公式。|
| [calculate_array_formula](/cells/python-net/zh/aspose.cells/worksheet/calculate_array_formula/#str-aspose.cells.CalculationOptions) |将公式计算为数组公式。|
| [calculate_array_formula](/cells/python-net/zh/aspose.cells/worksheet/calculate_array_formula/#str-aspose.cells.CalculationOptions-int-int) |将公式计算为数组公式。|
| [calculate_array_formula](/cells/python-net/zh/aspose.cells/worksheet/calculate_array_formula/#str-aspose.cells.FormulaParseOptions-aspose.cells.CalculationOptions-int-int-int-int-aspose.cells.CalculationData) |将公式计算为数组公式。|
| [get_panes](/cells/python-net/zh/aspose.cells/worksheet/get_panes/#) |获取窗玻璃。|
| [get_freezed_panes](/cells/python-net/zh/aspose.cells/worksheet/get_freezed_panes/#any-any-any-any) |获取冻结窗格。|
| [split](/cells/python-net/zh/aspose.cells/worksheet/split/#) |分割窗口。|
| [un_freeze_panes](/cells/python-net/zh/aspose.cells/worksheet/un_freeze_panes/#) |解冻工作表中的窗格。|
| [remove_split](/cells/python-net/zh/aspose.cells/worksheet/remove_split/#) |删除分割窗口。|
| [add_page_breaks](/cells/python-net/zh/aspose.cells/worksheet/add_page_breaks/#str) |添加分页符。|
| [advanced_filter](/cells/python-net/zh/aspose.cells/worksheet/advanced_filter/#bool-str-str-str-bool) |使用复杂的标准过滤数据。|
| [remove_auto_filter](/cells/python-net/zh/aspose.cells/worksheet/remove_auto_filter/#) |删除工作表的自动过滤器。|
| [set_visible](/cells/python-net/zh/aspose.cells/worksheet/set_visible/#bool-bool) |设置可见选项。|
| [select_range](/cells/python-net/zh/aspose.cells/worksheet/select_range/#int-int-int-int-bool) |选择一个范围。|
| [remove_all_drawing_objects](/cells/python-net/zh/aspose.cells/worksheet/remove_all_drawing_objects/#) |删除此工作表中的所有绘图对象。|
| [clear_comments](/cells/python-net/zh/aspose.cells/worksheet/clear_comments/#) |清除设计器电子表格中的所有注释。|
| [move_to](/cells/python-net/zh/aspose.cells/worksheet/move_to/#int) |将工作表移动到电子表格中的另一个位置。|
| [replace](/cells/python-net/zh/aspose.cells/worksheet/replace/#str-str) |用新字符串替换所有单元格的文本。|
| [get_selected_ranges](/cells/python-net/zh/aspose.cells/worksheet/get_selected_ranges/#) |获取设计器电子表格中选定的单元格范围。|
| [set_background](/cells/python-net/zh/aspose.cells/worksheet/set_background/#bytes) |设置工作表背景图像。|
| [get_printing_page_breaks](/cells/python-net/zh/aspose.cells/worksheet/get_printing_page_breaks/#aspose.cells.rendering.ImageOrPrintOptions) |获取自动分页符。|
| [start_access_cache](/cells/python-net/zh/aspose.cells/worksheet/start_access_cache/#aspose.cells.AccessCacheOptions) |启动使用缓存访问此工作表中的数据的会话。|
| [close_access_cache](/cells/python-net/zh/aspose.cells/worksheet/close_access_cache/#aspose.cells.AccessCacheOptions) |关闭使用缓存访问此工作表中的数据的会话。|
| [convert_formula_reference_style](/cells/python-net/zh/aspose.cells/worksheet/convert_formula_reference_style/#str-bool-int-int) |转换公式参考样式。|
| [xml_map_query](/cells/python-net/zh/aspose.cells/worksheet/xml_map_query/#str-aspose.cells.XmlMap) |查询映射/链接到 xml 映射的特定路径的单元格区域。|
| [refresh_pivot_tables](/cells/python-net/zh/aspose.cells/worksheet/refresh_pivot_tables/#) |刷新此工作表中的所有数据透视表。|



### 例子

以下示例演示如何使用 .Net 或 VB 冻结窗格并插入工作表的超链接。

```python
from aspose.cells import Workbook

workbook = Workbook()
sheet = workbook.worksheets[0]
# Freeze panes at "AS40" with 10 rows and 10 columns
sheet.freeze_panes("AS40", 10, 10)
# Add a hyperlink in Cell A1
sheet.hyperlinks.add("A1", 1, 1, "http://www.aspose.com")

```

### 也可以看看
* 模块[`aspose.cells`](..)
* 类 [`Chart`](/cells/python-net/zh/aspose.cells.charts/chart)
* 类 [`CheckBox`](/cells/python-net/zh/aspose.cells.drawing/checkbox)
* 类 [`Comment`](/cells/python-net/zh/aspose.cells/comment)
* 类 [`HorizontalPageBreakCollection`](/cells/python-net/zh/aspose.cells/horizontalpagebreakcollection)
* 类 [`HyperlinkCollection`](/cells/python-net/zh/aspose.cells/hyperlinkcollection)
* 类 [`OleObject`](/cells/python-net/zh/aspose.cells.drawing/oleobject)
* 类 [`Picture`](/cells/python-net/zh/aspose.cells.drawing/picture)
* 类 [`QueryTableCollection`](/cells/python-net/zh/aspose.cells/querytablecollection)
* 类 [`Scenario`](/cells/python-net/zh/aspose.cells/scenario)
* 类 [`SmartTagCollection`](/cells/python-net/zh/aspose.cells.markup/smarttagcollection)
* 类 [`TextBox`](/cells/python-net/zh/aspose.cells.drawing/textbox)
* 类 [`VerticalPageBreakCollection`](/cells/python-net/zh/aspose.cells/verticalpagebreakcollection)
