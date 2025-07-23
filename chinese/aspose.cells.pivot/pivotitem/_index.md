---
title: PivotItem类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 180
url: /zh/aspose.cells.pivot/pivotitem/
is_root: false
---
## PivotItem类
代表 PivotField 报表中的一项。



PivotItem 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [is_hidden](/cells/python-net/zh/aspose.cells.pivot/pivotitem/is_hidden) |获取并设置数据透视表项是否隐藏。|
| [position](/cells/python-net/zh/aspose.cells.pivot/pivotitem/position) |指定所有 PivotItems 中的位置索引，而不是同一父节点下的 PivotItems。|
| [position_in_same_parent_node](/cells/python-net/zh/aspose.cells.pivot/pivotitem/position_in_same_parent_node) |指定同一父节点下的 PivotItems 中的位置索引。|
| [is_hide_detail](/cells/python-net/zh/aspose.cells.pivot/pivotitem/is_hide_detail) |获取并设置数据透视表项是否隐藏细节。|
| [is_detail_hidden](/cells/python-net/zh/aspose.cells.pivot/pivotitem/is_detail_hidden) |获取并设置此数据透视表项的详细信息是否隐藏。|
| [is_calculated_item](/cells/python-net/zh/aspose.cells.pivot/pivotitem/is_calculated_item) |指示此数据透视表项是否为计算公式项。|
| [is_formula](/cells/python-net/zh/aspose.cells.pivot/pivotitem/is_formula) |指示此数据透视表项是否为计算公式项。|
| [is_missing](/cells/python-net/zh/aspose.cells.pivot/pivotitem/is_missing) |指示该项目是否从数据源中删除。|
| [value](/cells/python-net/zh/aspose.cells.pivot/pivotitem/value) |获取数据透视表项的值|
| [name](/cells/python-net/zh/aspose.cells.pivot/pivotitem/name) |获取数据透视表项的名称。|
| [index](/cells/python-net/zh/aspose.cells.pivot/pivotitem/index) |获取缓存字段中枢轴项的索引。|


### 方法
|方法|描述|
| :- | :- |
| [`move(self, count, is_same_parent)`](/cells/python-net/zh/aspose.cells.pivot/pivotitem/move/#int-bool) |向上或向下移动项目|
| [`get_formula(self)`](/cells/python-net/zh/aspose.cells.pivot/pivotitem/get_formula/#) |获取该计算项的公式。<br/>仅当此项为计算项时才有效。|
| [`get_string_value(self)`](/cells/python-net/zh/aspose.cells.pivot/pivotitem/get_string_value/#) |获取数据透视项的字符串值<br/>如果值为空，则返回“”|
| [`get_double_value(self)`](/cells/python-net/zh/aspose.cells.pivot/pivotitem/get_double_value/#) |获取数据透视表项的双精度值<br/>如果值为空或者不是数字，则返回 0|
| [`get_date_time_value(self)`](/cells/python-net/zh/aspose.cells.pivot/pivotitem/get_date_time_value/#) |获取数据透视表项的日期时间值<br/>如果值为空，则返回 DateTime.MinValue|



### 也可以看看
* 模块[`aspose.cells.pivot`](..)
