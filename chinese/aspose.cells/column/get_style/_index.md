---
title: get_style方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 30
url: /zh/aspose.cells/column/get_style/
is_root: false
---
##  get_style(self) {#}
获取此列的样式。



```python

def get_style(self):
    ...
```


### 注意事项

直接修改返回的样式对象不会对该列或该列中的任何单元格产生影响。
您必须拨打 [`Column.apply_style`](/cells/python-net/zh/aspose.cells/column/apply_style) 或 [`Column.set_style`](/cells/python-net/zh/aspose.cells/column/set_style) 方法
将更改应用到此列。

列的样式是此列中的单元格将继承的样式（那些没有自定义样式设置的单元格，
例如尚未明确设置样式的现有单元格，或尚未实例化的单元格）


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Column`](/cells/python-net/zh/aspose.cells/column)
