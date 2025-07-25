---
title: ListColumn类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 10
url: /zh/aspose.cells.tables/listcolumn/
is_root: false
---
## ListColumn类
代表表中的一列。



ListColumn 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [name](/cells/python-net/zh/aspose.cells.tables/listcolumn/name) |获取并设置列的名称。|
| [totals_calculation](/cells/python-net/zh/aspose.cells.tables/listcolumn/totals_calculation) |获取并设置列表列总计行中的计算类型。|
| [range](/cells/python-net/zh/aspose.cells.tables/listcolumn/range) |获取此列表列的范围。|
| [is_array_formula](/cells/python-net/zh/aspose.cells.tables/listcolumn/is_array_formula) |指示公式是否为数组公式。|
| [formula](/cells/python-net/zh/aspose.cells.tables/listcolumn/formula) |获取和设置列表列的公式。|
| [totals_row_label](/cells/python-net/zh/aspose.cells.tables/listcolumn/totals_row_label) |获取和设置总计行的显示标签。|


### 方法
|方法|描述|
| :- | :- |
| [`get_custom_totals_row_formula(self, is_r1c1, is_local)`](/cells/python-net/zh/aspose.cells.tables/listcolumn/get_custom_totals_row_formula/#bool-bool) |获取此列表列的总计行的公式。|
| [`set_custom_totals_row_formula(self, formula, is_r1c1, is_local)`](/cells/python-net/zh/aspose.cells.tables/listcolumn/set_custom_totals_row_formula/#str-bool-bool) |获取此列表列的总计行的公式。|
| [`get_custom_calculated_formula(self, is_r1c1, is_local)`](/cells/python-net/zh/aspose.cells.tables/listcolumn/get_custom_calculated_formula/#bool-bool) |获取此列表列的公式。|
| [`set_custom_calculated_formula(self, formula, is_r1c1, is_local)`](/cells/python-net/zh/aspose.cells.tables/listcolumn/set_custom_calculated_formula/#str-bool-bool) |设置此列表列的公式。|
| [`get_data_style(self)`](/cells/python-net/zh/aspose.cells.tables/listcolumn/get_data_style/#) |获取表格该列数据的样式。|
| [`set_data_style(self, style)`](/cells/python-net/zh/aspose.cells.tables/listcolumn/set_data_style/#aspose.cells.style) |设置表格此列数据的样式。|



### 例子

```python
from aspose.cells import CellsHelper, Workbook
from aspose.cells.tables import TotalsCalculation

workbook = Workbook()
cells = workbook.worksheets[0].cells
for i in range(5):
    cells.get(0, i).put_value(CellsHelper.column_index_to_name(i))
for row in range(1, 10):
    for column in range(4):
        cells.get(row, column).put_value(row * column)
tables = workbook.worksheets[0].list_objects
index = tables.add(0, 0, 9, 4, True)
table = tables[0]
table.show_totals = True
listColumn = table.list_columns[4]
listColumn.totals_calculation = TotalsCalculation.SUM
listColumn.formula = "=[A]"
workbook.save(r"Book1.xlsx")

```

### 也可以看看
* 模块[`aspose.cells.tables`](..)
