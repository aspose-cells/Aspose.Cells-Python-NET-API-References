---
title: pivot_source属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 430
url: /zh/aspose.cells.charts/chart/pivot_source/
is_root: false
---
## pivot_source属性

源是数据透视表的数据。
如果 PivotSource 不为空，则图表为数据透视图。

### 评论

如果数据透视表“PivotTable1”位于文件“Book1.xls”中的工作表“Sheet1”中。
如果图表和数据透视表不在同一工作簿中，则数据透视表来源可能是“[Book1.xls]Sheet1!PivotTable1”。
如果设置该属性，之前的数据源设置将会丢失。
### 定义：
```python
@property
def pivot_source(self):
    ...
@pivot_source.setter
def pivot_source(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells.charts`](../../)
* 类 [`Chart`](/cells/python-net/zh/aspose.cells.charts/chart)
