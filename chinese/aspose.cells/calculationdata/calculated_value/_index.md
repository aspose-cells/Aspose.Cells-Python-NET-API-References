---
title: calculated_value属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 60
url: /zh/aspose.cells/calculationdata/calculated_value/
is_root: false
---
## calculated_value属性

获取或设置此函数的计算值。

### 注意事项

用户应在其自定义计算引擎中为引擎支持的功能设置此属性，
稍后获取该属性时将会返回设置的值。
设置值可能的类型为 [`Cell.value`](/cells/python-net/zh/aspose.cells/cell#value)，
或此类值的数组，或范围、名称、ReferredArea。
在设置值之前获取此属性将使函数被计算
默认计算引擎 Aspose.Cells，然后计算值将
返回（对于用户定义的函数，通常应该是#NAME?）。
### 定义：
```python
@property
def calculated_value(self):
    ...
@calculated_value.setter
def calculated_value(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`CalculationData`](/cells/python-net/zh/aspose.cells/calculationdata)
