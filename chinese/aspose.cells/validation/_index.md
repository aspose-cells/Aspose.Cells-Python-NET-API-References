---
title: Validation类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 1520
url: /zh/aspose.cells/validation/
is_root: false
---
## Validation类
表示数据验证.设置。



Validation 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [operator](/cells/python-net/zh/aspose.cells/validation/operator) |代表数据验证的操作员。|
| [alert_style](/cells/python-net/zh/aspose.cells/validation/alert_style) |表示验证警报样式。|
| [type](/cells/python-net/zh/aspose.cells/validation/type) |表示数据验证类型。|
| [input_message](/cells/python-net/zh/aspose.cells/validation/input_message) |表示数据验证输入消息。|
| [input_title](/cells/python-net/zh/aspose.cells/validation/input_title) |表示数据验证输入对话框的标题。|
| [error_message](/cells/python-net/zh/aspose.cells/validation/error_message) |表示数据验证错误消息。|
| [error_title](/cells/python-net/zh/aspose.cells/validation/error_title) |表示数据验证错误对话框的标题。|
| [show_input](/cells/python-net/zh/aspose.cells/validation/show_input) |指示当用户选择数据验证范围内的单元格时是否显示数据验证输入消息。|
| [show_error](/cells/python-net/zh/aspose.cells/validation/show_error) |指示当用户输入无效数据时是否显示数据验证错误消息。|
| [ignore_blank](/cells/python-net/zh/aspose.cells/validation/ignore_blank) |指示范围数据验证是否允许空值。|
| [formula1](/cells/python-net/zh/aspose.cells/validation/formula1) |表示与数据验证相关的值或表达式。|
| [formula2](/cells/python-net/zh/aspose.cells/validation/formula2) |表示与数据验证相关的值或表达式。|
| [value1](/cells/python-net/zh/aspose.cells/validation/value1) |表示与数据验证相关的第一个值。|
| [value2](/cells/python-net/zh/aspose.cells/validation/value2) |表示与数据验证相关的第二个值。|
| [in_cell_drop_down](/cells/python-net/zh/aspose.cells/validation/in_cell_drop_down) |指示数据验证是否显示包含可接受值的下拉列表。|
| [areas](/cells/python-net/zh/aspose.cells/validation/areas) |获取包含数据验证设置的所有 [`CellArea`](/cells/python-net/zh/aspose.cells/cellarea)。|


### 方法
|方法|描述|
| :- | :- |
| [`get_formula1(self, is_r1c1, is_local)`](/cells/python-net/zh/aspose.cells/validation/get_formula1/#bool-bool) |获取与此验证相关的值或表达式。|
| [`get_formula1(self, is_r1c1, is_local, row, column)`](/cells/python-net/zh/aspose.cells/validation/get_formula1/#bool-bool-int-int) |获取与特定单元格的此验证相关的值或表达式。|
| [`get_formula2(self, is_r1c1, is_local)`](/cells/python-net/zh/aspose.cells/validation/get_formula2/#bool-bool) |获取与此验证相关的值或表达式。|
| [`get_formula2(self, is_r1c1, is_local, row, column)`](/cells/python-net/zh/aspose.cells/validation/get_formula2/#bool-bool-int-int) |获取与特定单元格的此验证相关的值或表达式。|
| [`add_area(self, cell_area)`](/cells/python-net/zh/aspose.cells/validation/add_area/#aspose.cells.cellarea) |将验证应用于该区域。|
| [`add_area(self, cell_area, check_intersection, check_edge)`](/cells/python-net/zh/aspose.cells/validation/add_area/#aspose.cells.cellarea-bool-bool) |将验证应用于该区域。|
| [`set_formula1(self, formula, is_r1c1, is_local)`](/cells/python-net/zh/aspose.cells/validation/set_formula1/#str-bool-bool) |设置与此验证相关的值或表达式。|
| [`set_formula2(self, formula, is_r1c1, is_local)`](/cells/python-net/zh/aspose.cells/validation/set_formula2/#str-bool-bool) |设置与此验证相关的值或表达式。|
| [`get_list_value(self, row, column)`](/cells/python-net/zh/aspose.cells/validation/get_list_value/#int-int) |获取指定单元格的验证列表的值。|
| [`get_value(self, row, column, is_value1)`](/cells/python-net/zh/aspose.cells/validation/get_value/#int-int-bool) |获取特定单元格的验证值。|
| [`add_areas(self, areas, check_intersection, check_edge)`](/cells/python-net/zh/aspose.cells/validation/add_areas/#list-bool-bool) |将验证应用于给定区域。|
| [`remove_area(self, cell_area)`](/cells/python-net/zh/aspose.cells/validation/remove_area/#aspose.cells.cellarea) |删除范围内的验证设置。|
| [`remove_areas(self, areas)`](/cells/python-net/zh/aspose.cells/validation/remove_areas/#list) |从给定区域删除此验证。|
| [`remove_a_cell(self, row, column)`](/cells/python-net/zh/aspose.cells/validation/remove_a_cell/#int-int) |删除单元格中的验证设置。|
| [`copy(self, source, copy_option)`](/cells/python-net/zh/aspose.cells/validation/copy/#aspose.cells.validation-aspose.cells.copyoptions) |复制验证。|



### 例子

```python
from aspose.cells import CellArea, OperatorType, ValidationType, Workbook

workbook = Workbook()
validations = workbook.worksheets[0].validations
area = CellArea.create_cell_area(0, 0, 1, 1)
validation = validations[validations.add(area)]
validation.type = ValidationType.WHOLE_NUMBER
validation.operator = OperatorType.BETWEEN
validation.formula1 = "3"
validation.formula2 = "1234"

```

### 也可以看看
* 模块[`aspose.cells`](..)
* 类 [`CellArea`](/cells/python-net/zh/aspose.cells/cellarea)
