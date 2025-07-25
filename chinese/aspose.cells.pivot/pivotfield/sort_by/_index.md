---
title: sort_by方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 230
url: /zh/aspose.cells.pivot/pivotfield/sort_by/
is_root: false
---
##  sort_by(self, sort_type, field_sorted_by) {#aspose.cells.SortOrder-int}
对此数据透视表字段进行排序。



```python

def sort_by(self, sort_type, field_sorted_by):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| sort_type | [`SortOrder`](/cells/python-net/zh/aspose.cells/sortorder) |对此字段进行排序的类型。|
| field_sorted_by | int |按枢轴字段排序的索引。<br/> -1表示按照该字段的数据标签排序，其它表示按照数据字段的索引排序。|


##  sort_by(self, sort_type, field_sorted_by, data_type, cell_name) {#aspose.cells.SortOrder-int-aspose.cells.pivot.PivotLineType-str}
对此数据透视表字段进行排序。



```python

def sort_by(self, sort_type, field_sorted_by, data_type, cell_name):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| sort_type | [`SortOrder`](/cells/python-net/zh/aspose.cells/sortorder) |对此字段进行排序的类型。|
| field_sorted_by | int |按枢轴字段排序的索引。<br/> -1表示按照该字段的数据标签排序，其它表示按照数据字段的索引排序。|
| data_type | [`PivotLineType`](/cells/python-net/zh/aspose.cells.pivot/pivotlinetype) |按其排序的数据类型。|
| cell_name | str |按行或列中的值排序|



### 也可以看看
* 模块[`aspose.cells.pivot`](../../)
* 类 [`PivotField`](/cells/python-net/zh/aspose.cells.pivot/pivotfield)
