---
title: enable_calculation_chain属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 70
url: /zh/aspose.cells/formulasettings/enable_calculation_chain/
is_root: false
---
## enable_calculation_chain属性

是否启用公式的计算链。默认为 false。

### 注意事项

当工作簿中有很多公式，用户需要重复计算时
只需修改其中的一小部分，启用计算链可能会对性能有所帮助。
另一方面，如果启用了链，维护链的模型需要额外的内存，
并且它还需要更多的 CPU 时间来执行一些其他操作，例如更改单元格的值或公式。
将此属性从false更改为true后，将分析并构建计算链
在工作簿第一次计算时，因此第一次计算所需的时间
可能比没有链的正常计算还要多。
### 定义：
```python
@property
def enable_calculation_chain(self):
    ...
@enable_calculation_chain.setter
def enable_calculation_chain(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`FormulaSettings`](/cells/python-net/zh/aspose.cells/formulasettings)
