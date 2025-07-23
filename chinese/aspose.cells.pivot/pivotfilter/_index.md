---
title: PivotFilter类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 140
url: /zh/aspose.cells.pivot/pivotfilter/
is_root: false
---
## PivotFilter类
代表 PivotFilter 集合中的 PivotFilter。



PivotFilter 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [use_whole_day](/cells/python-net/zh/aspose.cells.pivot/pivotfilter/use_whole_day) |指示是否在过滤条件中使用整天。|
| [auto_filter](/cells/python-net/zh/aspose.cells.pivot/pivotfilter/auto_filter) |获取枢轴过滤器的自动过滤器。|
| [filter_type](/cells/python-net/zh/aspose.cells.pivot/pivotfilter/filter_type) |获取数据透视过滤器的自动过滤类型。|
| [field_index](/cells/python-net/zh/aspose.cells.pivot/pivotfilter/field_index) |获取此枢轴过滤器所应用的源字段的索引。|
| [filter_category](/cells/python-net/zh/aspose.cells.pivot/pivotfilter/filter_category) |获取此过滤器的类别。|
| [value1](/cells/python-net/zh/aspose.cells.pivot/pivotfilter/value1) |获取标签枢轴过滤器的字符串值1。|
| [value2](/cells/python-net/zh/aspose.cells.pivot/pivotfilter/value2) |获取标签枢轴过滤器的字符串值2。|
| [measure_fld_index](/cells/python-net/zh/aspose.cells.pivot/pivotfilter/measure_fld_index) |获取枢轴过滤器的度量字段索引。|
| [value_field_index](/cells/python-net/zh/aspose.cells.pivot/pivotfilter/value_field_index) |获取值域中值字段的索引。|
| [measure_cube_field_index](/cells/python-net/zh/aspose.cells.pivot/pivotfilter/measure_cube_field_index) |指定度量立方体字段的索引。<br/>此属性仅由 OLAP 数据透视表中的过滤器使用，并指定应在哪个度量上应用值过滤器。|
| [member_property_field_index](/cells/python-net/zh/aspose.cells.pivot/pivotfilter/member_property_field_index) |获取数据透视过滤器的成员属性字段索引。|
| [name](/cells/python-net/zh/aspose.cells.pivot/pivotfilter/name) |获取枢轴过滤器的名称。|
| [evaluation_order](/cells/python-net/zh/aspose.cells.pivot/pivotfilter/evaluation_order) |获取枢轴过滤器的评估顺序。|


### 方法
|方法|描述|
| :- | :- |
| [`get_top_10_value(self)`](/cells/python-net/zh/aspose.cells.pivot/pivotfilter/get_top_10_value/#) |获取过滤器的前 10 个设置。|
| [`get_labels(self)`](/cells/python-net/zh/aspose.cells.pivot/pivotfilter/get_labels/#) |获取标题过滤器的标签。|
| [`get_number_values(self)`](/cells/python-net/zh/aspose.cells.pivot/pivotfilter/get_number_values/#) |获取数字过滤器的值。|
| [`get_date_time_values(self)`](/cells/python-net/zh/aspose.cells.pivot/pivotfilter/get_date_time_values/#) |获取数字过滤器的值。|



### 例子

```python
from aspose.cells import Workbook
from aspose.cells.pivot import PivotFieldType, PivotFilterType, PivotTableStyleType

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
# Add top 10 filter
pivot.base_fields[0].filter_top10(0, PivotFilterType.COUNT, False, 2)
pivot.refresh_data()
pivot.calculate_data()
# do your business
book.save("out.xlsx")

```

### 也可以看看
* 模块[`aspose.cells.pivot`](..)
