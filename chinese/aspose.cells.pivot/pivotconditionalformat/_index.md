---
title: PivotConditionalFormat类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 60
url: /zh/aspose.cells.pivot/pivotconditionalformat/
is_root: false
---
## PivotConditionalFormat类
表示 PivotFormatCondition 集合中的数据透视表格式条件。



PivotConditionalFormat 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [pivot_areas](/cells/python-net/zh/aspose.cells.pivot/pivotconditionalformat/pivot_areas) |获取所有枢轴区域。|
| [format_conditions](/cells/python-net/zh/aspose.cells.pivot/pivotconditionalformat/format_conditions) |获取数据透视表条件格式的条件。|
| [scope_type](/cells/python-net/zh/aspose.cells.pivot/pivotconditionalformat/scope_type) |获取并设置数据透视表条件格式的范围类型。|
| [rule_type](/cells/python-net/zh/aspose.cells.pivot/pivotconditionalformat/rule_type) |获取并设置数据透视表条件格式的规则类型。|


### 方法
|方法|描述|
| :- | :- |
| [`add_field_area(self, axis_type, field_name)`](/cells/python-net/zh/aspose.cells.pivot/pivotconditionalformat/add_field_area/#aspose.cells.pivot.pivotfieldtype-str) |添加枢轴字段的区域。|
| [`add_field_area(self, axis_type, field)`](/cells/python-net/zh/aspose.cells.pivot/pivotconditionalformat/add_field_area/#aspose.cells.pivot.pivotfieldtype-aspose.cells.pivot.pivotfield) |添加枢轴字段的区域。|
| [`get_cell_areas(self)`](/cells/python-net/zh/aspose.cells.pivot/pivotconditionalformat/get_cell_areas/#) |获取此条件格式适用的所有单元格区域。|
| [`add_cell_area(self, ca)`](/cells/python-net/zh/aspose.cells.pivot/pivotconditionalformat/add_cell_area/#aspose.cells.cellarea) |添加基于数据透视表视图的区域。|
| [`apply_to(self, row, column, scope)`](/cells/python-net/zh/aspose.cells.pivot/pivotconditionalformat/apply_to/#int-int-aspose.cells.pivot.pivotconditionformatscopetype) |将条件格式应用于范围。<br/>仅适用于数据区域。|



### 例子

```python
from aspose.cells import FormatConditionType, OperatorType, Workbook
from aspose.cells.pivot import PivotFieldType, PivotTableStyleType
from aspose.pydrawing import Color

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
# Add PivotFormatCondition
formatIndex = pivot.conditional_formats.add()
pfc = pivot.conditional_formats[formatIndex]
pfc.add_field_area(PivotFieldType.DATA, pivot.data_fields[0])
idx = pfc.format_conditions.add_condition(FormatConditionType.CELL_VALUE)
fc = pfc.format_conditions[idx]
fc.formula1 = "100"
fc.operator = OperatorType.GREATER_OR_EQUAL
fc.style.background_color = Color.red
pivot.refresh_data()
pivot.calculate_data()
# do your business
book.save("out.xlsx")

```

### 也可以看看
* 模块[`aspose.cells.pivot`](..)
