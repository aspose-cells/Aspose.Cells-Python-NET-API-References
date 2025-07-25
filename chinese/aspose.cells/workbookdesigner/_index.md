---
title: WorkbookDesigner类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 1580
url: /zh/aspose.cells/workbookdesigner/
is_root: false
---
## WorkbookDesigner类
封装代表设计器电子表格的对象。



WorkbookDesigner 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [`__init__(self)`](/cells/python-net/zh/aspose.cells/workbookdesigner/__init__/#) |初始化 [`WorkbookDesigner`](/cells/python-net/zh/aspose.cells/workbookdesigner) 类的新实例。|
| [`__init__(self, workbook)`](/cells/python-net/zh/aspose.cells/workbookdesigner/__init__/#aspose.cells.workbook) |初始化 [`WorkbookDesigner`](/cells/python-net/zh/aspose.cells/workbookdesigner) 类的新实例。|


### 属性
|属性|描述|
| :- | :- |
| [workbook](/cells/python-net/zh/aspose.cells/workbookdesigner/workbook) |获取并设置 [`WorkbookDesigner.workbook`](/cells/python-net/zh/aspose.cells/workbookdesigner#workbook) 对象。|
| [repeat_formulas_with_subtotal](/cells/python-net/zh/aspose.cells/workbookdesigner/repeat_formulas_with_subtotal) |指示是否重复带有小计行的公式。|
| [update_empty_string_as_null](/cells/python-net/zh/aspose.cells/workbookdesigner/update_empty_string_as_null) |如果为 TRUE，则当值为“”时插入 Null；|
| [update_reference](/cells/python-net/zh/aspose.cells/workbookdesigner/update_reference) |指示其他工作表中的引用是否会更新。|
| [calculate_formula](/cells/python-net/zh/aspose.cells/workbookdesigner/calculate_formula) |指示是否应计算公式。|
| [line_by_line](/cells/python-net/zh/aspose.cells/workbookdesigner/line_by_line) |指示是否逐行处理智能标记。|
| [contains_variables](/cells/python-net/zh/aspose.cells/workbookdesigner/contains_variables) |指示第一个工作表是否包含自定义变量。|


### 方法
|方法|描述|
| :- | :- |
| [`set_data_source(self, data_source, cells_data_table)`](/cells/python-net/zh/aspose.cells/workbookdesigner/set_data_source/#str-icellsdatatable) |  |
| [`set_data_source(self, variable, data)`](/cells/python-net/zh/aspose.cells/workbookdesigner/set_data_source/#str-any) |将数据绑定设置为变量。|
| [`process(self, range, is_preserved)`](/cells/python-net/zh/aspose.cells/workbookdesigner/process/#aspose.cells.range-bool) |处理智能标记并填充数据源值。|
| [`process(self)`](/cells/python-net/zh/aspose.cells/workbookdesigner/process/#) |处理智能标记并填充数据源值。|
| [`process(self, is_preserved)`](/cells/python-net/zh/aspose.cells/workbookdesigner/process/#bool) |处理智能标记并填充数据源值。|
| [`process(self, sheet_index, is_preserved)`](/cells/python-net/zh/aspose.cells/workbookdesigner/process/#int-bool) |处理智能标记并填充数据源值。|
| [`clear_data_source(self)`](/cells/python-net/zh/aspose.cells/workbookdesigner/clear_data_source/#) |清除所有数据源。|
| [`set_json_data_source(self, variable, data)`](/cells/python-net/zh/aspose.cells/workbookdesigner/set_json_data_source/#str-str) |  |
| [`get_smart_markers(self)`](/cells/python-net/zh/aspose.cells/workbookdesigner/get_smart_markers/#) |返回电子表格中的智能标记集合。|



### 例子

```python
from aspose.cells import Workbook, WorkbookDesigner

# Create WorkbookDesigner object.
wd = WorkbookDesigner()
# Open the template file (which contains smart markers).
wd.workbook = Workbook("SmartMarker_Designer.xls")
# Initialize your data from data source
# DataSet ds = new DataSet();
# ...
# Set the datatable as the data source.
# wd.SetDataSource(dt);
# Process the smart markers to fill the data into the worksheets.
wd.process(True)
# Save the excel file.
wd.workbook.save("outSmartMarker_Designer.xls")

```

### 也可以看看
* 模块[`aspose.cells`](..)
* 类 [`WorkbookDesigner`](/cells/python-net/zh/aspose.cells/workbookdesigner)
