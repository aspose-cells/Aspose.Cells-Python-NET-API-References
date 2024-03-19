---
title: skip_error_value属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 160
url: /zh/aspose.cells/exporttableoptions/skip_error_value/
is_root: false
---
## skip_error_value属性

指示是否跳过列的无效值。
例如，如果列类型为decimal，则该值大于decimal.MaxValue
并且这个属性是true，我们不会再抛出异常。
默认值为 false。
### 定义：
```python
@property
def skip_error_value(self):
    ...
@skip_error_value.setter
def skip_error_value(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`ExportTableOptions`](/cells/python-net/zh/aspose.cells/exporttableoptions)
