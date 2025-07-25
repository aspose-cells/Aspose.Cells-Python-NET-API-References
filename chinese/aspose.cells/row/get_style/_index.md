---
title: get_style方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 80
url: /zh/aspose.cells/row/get_style/
is_root: false
---
##  get_style(self) {#}
获取此行的样式。



```python

def get_style(self):
    ...
```


### 注意事项

直接修改返回的样式对象不会对该行或该行中的任何单元格产生影响。
您必须拨打 [`Row.apply_style`](/cells/python-net/zh/aspose.cells/row/apply_style) 或 [`Row.set_style`](/cells/python-net/zh/aspose.cells/row/set_style) 方法
将更改应用到此行。

行的样式是此行单元格将继承的样式（那些没有自定义样式设置的单元格，
例如尚未明确设置样式的现有单元格，或尚未实例化的单元格）


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Row`](/cells/python-net/zh/aspose.cells/row)
