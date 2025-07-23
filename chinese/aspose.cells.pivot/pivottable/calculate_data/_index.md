---
title: calculate_data方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 40
url: /zh/aspose.cells.pivot/pivottable/calculate_data/
is_root: false
---
##  calculate_data(self) {#}
将数据透视表的数据计算到单元格。



```python

def calculate_data(self):
    ...
```


### 注意事项

Cell.如果未调用该方法，则枢轴范围内的值无法返回正确的结果。
此方法使用内部枢轴缓存而不是原始数据源来计算数据。
因此如果数据源发生变化，请先调用RefreshData()方法。

##  calculate_data(self, option) {#aspose.cells.pivot.PivotTableCalculateOption}
使用选项计算数据透视表



```python

def calculate_data(self, option):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| option | [`PivotTableCalculateOption`](/cells/python-net/zh/aspose.cells.pivot/pivottablecalculateoption) |  |



### 也可以看看
* 模块[`aspose.cells.pivot`](../../)
* 类 [`PivotTable`](/cells/python-net/zh/aspose.cells.pivot/pivottable)
