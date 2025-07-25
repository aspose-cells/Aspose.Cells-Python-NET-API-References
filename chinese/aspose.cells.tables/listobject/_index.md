---
title: ListObject类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 30
url: /zh/aspose.cells.tables/listobject/
is_root: false
---
## ListObject类
表示工作表上的列表对象。
 ListObject 对象是 ListObjects 集合的成员。
ListObjects 集合包含工作表上的所有列表对象。



ListObject 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [start_row](/cells/python-net/zh/aspose.cells.tables/listobject/start_row) |获取范围的起始行。|
| [start_column](/cells/python-net/zh/aspose.cells.tables/listobject/start_column) |获取范围的起始列。|
| [end_row](/cells/python-net/zh/aspose.cells.tables/listobject/end_row) |获取范围的结束行。|
| [end_column](/cells/python-net/zh/aspose.cells.tables/listobject/end_column) |获取范围的结束列。|
| [list_columns](/cells/python-net/zh/aspose.cells.tables/listobject/list_columns) |获取 ListObject 的 ListColumns。|
| [show_header_row](/cells/python-net/zh/aspose.cells.tables/listobject/show_header_row) |获取或设置此 ListObject 是否显示标题行。|
| [show_totals](/cells/python-net/zh/aspose.cells.tables/listobject/show_totals) |获取或设置此 ListObject 是否显示总行。|
| [data_range](/cells/python-net/zh/aspose.cells.tables/listobject/data_range) |获取ListObject的数据范围。|
| [query_table](/cells/python-net/zh/aspose.cells.tables/listobject/query_table) |获取链接的查询表。|
| [data_source_type](/cells/python-net/zh/aspose.cells.tables/listobject/data_source_type) |获取表的数据源类型。|
| [auto_filter](/cells/python-net/zh/aspose.cells.tables/listobject/auto_filter) |获取自动过滤。|
| [display_name](/cells/python-net/zh/aspose.cells.tables/listobject/display_name) |获取并设置显示名称。|
| [comment](/cells/python-net/zh/aspose.cells.tables/listobject/comment) |获取和设置表的注释。|
| [show_table_style_first_column](/cells/python-net/zh/aspose.cells.tables/listobject/show_table_style_first_column) |指示表格中的第一列是否应应用样式。|
| [show_table_style_last_column](/cells/python-net/zh/aspose.cells.tables/listobject/show_table_style_last_column) |指示表格中的最后一列是否应应用样式。|
| [show_table_style_row_stripes](/cells/python-net/zh/aspose.cells.tables/listobject/show_table_style_row_stripes) |指示是否应用行条纹格式。|
| [show_table_style_column_stripes](/cells/python-net/zh/aspose.cells.tables/listobject/show_table_style_column_stripes) |指示是否应用列条纹格式。|
| [table_style_type](/cells/python-net/zh/aspose.cells.tables/listobject/table_style_type) |获取并内置表格样式。|
| [table_style_name](/cells/python-net/zh/aspose.cells.tables/listobject/table_style_name) |获取并设置表格样式名称。|
| [xml_map](/cells/python-net/zh/aspose.cells.tables/listobject/xml_map) |获取用于此列表的 [`ListObject.xml_map`](/cells/python-net/zh/aspose.cells.tables/listobject#xml_map)。|
| [alternative_text](/cells/python-net/zh/aspose.cells.tables/listobject/alternative_text) |获取并设置替代文本。|
| [alternative_description](/cells/python-net/zh/aspose.cells.tables/listobject/alternative_description) |获取并设置替代描述。|


### 方法
|方法|描述|
| :- | :- |
| [`put_cell_value(self, row_offset, column_offset, value)`](/cells/python-net/zh/aspose.cells.tables/listobject/put_cell_value/#int-int-any) |将值放入单元格。|
| [`put_cell_value(self, row_offset, column_offset, value, is_totals_row_label)`](/cells/python-net/zh/aspose.cells.tables/listobject/put_cell_value/#int-int-any-bool) |将值放入单元格。|
| [`put_cell_formula(self, row_offset, column_offset, formula)`](/cells/python-net/zh/aspose.cells.tables/listobject/put_cell_formula/#int-int-str) |将公式放入表格中的单元格。|
| [`put_cell_formula(self, row_offset, column_offset, formula, is_totals_row_formula)`](/cells/python-net/zh/aspose.cells.tables/listobject/put_cell_formula/#int-int-str-bool) |将公式放入表格中的单元格。|
| [`convert_to_range(self)`](/cells/python-net/zh/aspose.cells.tables/listobject/convert_to_range/#) |将表转换为范围。|
| [`convert_to_range(self, options)`](/cells/python-net/zh/aspose.cells.tables/listobject/convert_to_range/#aspose.cells.tables.tabletorangeoptions) |将表转换为范围。|
| [`resize(self, start_row, start_column, end_row, end_column, has_headers)`](/cells/python-net/zh/aspose.cells.tables/listobject/resize/#int-int-int-int-bool) |调整列表对象的范围。|
| [`update_column_name(self)`](/cells/python-net/zh/aspose.cells.tables/listobject/update_column_name/#) |从工作表更新所有列表列的名称。|
| [`filter(self)`](/cells/python-net/zh/aspose.cells.tables/listobject/filter/#) |过滤表格。|
| [`apply_style_to_range(self)`](/cells/python-net/zh/aspose.cells.tables/listobject/apply_style_to_range/#) |将表格样式应用到范围。|



### 例子

```python
from aspose.cells import CellsHelper, Workbook
from aspose.cells.tables import TotalsCalculation

workbook = Workbook()
cells = workbook.worksheets[0].cells
for i in range(5):
    cells.get(0, i).put_value(CellsHelper.column_index_to_name(i))
for row in range(1, 10):
    for column in range(5):
        cells.get(row, column).put_value(row * column)
tables = workbook.worksheets[0].list_objects
index = tables.add(0, 0, 9, 4, True)
table = tables[0]
table.show_totals = True
table.list_columns[4].totals_calculation = TotalsCalculation.SUM
workbook.save(r"Book1.xlsx")

```

### 也可以看看
* 模块[`aspose.cells.tables`](..)
