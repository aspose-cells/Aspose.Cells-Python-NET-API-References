---
title: WorkbookDesigner类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 1670
url: /zh/aspose.cells/workbookdesigner/
is_root: false
---
## WorkbookDesigner类
封装代表设计器电子表格的对象。



WorkbookDesigner 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [__init__](/cells/python-net/zh/aspose.cells/workbookdesigner/__init__/#) |初始化 [`WorkbookDesigner`](/cells/python-net/zh/aspose.cells/workbookdesigner) 类的新实例。|
| [__init__](/cells/python-net/zh/aspose.cells/workbookdesigner/__init__/#aspose.cells.Workbook) |初始化 [`WorkbookDesigner`](/cells/python-net/zh/aspose.cells/workbookdesigner) 类的新实例。|


### 特性
|属性|描述|
| :- | :- |
| [workbook](/cells/python-net/zh/aspose.cells/workbookdesigner/workbook) |获取和设置 [`WorkbookDesigner.workbook`](/cells/python-net/zh/aspose.cells/workbookdesigner#workbook) 对象。|
| [repeat_formulas_with_subtotal](/cells/python-net/zh/aspose.cells/workbookdesigner/repeat_formulas_with_subtotal) |指示是否与小计行重复公式。|
| [update_empty_string_as_null](/cells/python-net/zh/aspose.cells/workbookdesigner/update_empty_string_as_null) |如果为 TRUE，则值为“”时将插入 Null；|
| [update_reference](/cells/python-net/zh/aspose.cells/workbookdesigner/update_reference) |指示其他工作表中的引用是否将更新。|
| [calculate_formula](/cells/python-net/zh/aspose.cells/workbookdesigner/calculate_formula) |指示是否应计算公式。|
| [call_back](/cells/python-net/zh/aspose.cells/workbookdesigner/call_back) |获取和设置处理smartmarker的回调接口。|
| [line_by_line](/cells/python-net/zh/aspose.cells/workbookdesigner/line_by_line) |是否逐行处理智能标记。|


### 方法
|方法|描述|
| :- | :- |
| [set_data_source](/cells/python-net/zh/aspose.cells/workbookdesigner/set_data_source/#str-aspose.cells.ICellsDataTable) |设置[`ICellsDataTable`](/cells/python-net/zh/aspose.cells/icellsdatatable)对象的数据源。|
| [set_data_source](/cells/python-net/zh/aspose.cells/workbookdesigner/set_data_source/#str-any) |将数据绑定设置到变量。|
| [process](/cells/python-net/zh/aspose.cells/workbookdesigner/process/#) |处理智能标记并填充数据源值。|
| [process](/cells/python-net/zh/aspose.cells/workbookdesigner/process/#bool) |处理智能标记并填充数据源值。|
| [process](/cells/python-net/zh/aspose.cells/workbookdesigner/process/#int-bool) |处理智能标记并填充数据源值。|
| [clear_data_source](/cells/python-net/zh/aspose.cells/workbookdesigner/clear_data_source/#) |清除所有数据源。|
| [set_json_data_source](/cells/python-net/zh/aspose.cells/workbookdesigner/set_json_data_source/#str-str) |  |
| [get_smart_markers](/cells/python-net/zh/aspose.cells/workbookdesigner/get_smart_markers/#) |返回电子表格中智能标记的集合。|



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
* 类 [`ICellsDataTable`](/cells/python-net/zh/aspose.cells/icellsdatatable)
* 类 [`WorkbookDesigner`](/cells/python-net/zh/aspose.cells/workbookdesigner)
