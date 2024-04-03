---
title: GridAbstractCalculationEngine类
second_title: Aspose.Cells.GridJs for Python via .NET API 参考文献
description:
type: docs
weight: 20
url: /zh/aspose.cellsgridjs/gridabstractcalculationengine/
is_root: false
---
## GridAbstractCalculationEngine类

代表用户自定义计算引擎，扩展默认计算引擎Aspose.Cells。



GridAbstractCalculationEngine 类型公开以下成员：

### 方法
|方法|描述|
| :- | :- |
| [calculate](/cells/python-net/zh/aspose.cellsgridjs/gridabstractcalculationengine/calculate/#aspose.cellsgridjs.GridCalculationData) |使用给定数据计算一个函数。|



### 注意事项


在此实现中，用户不应直接修改工作簿的任何部分（自定义函数的计算结果除外，可以通过 GridCalculationData.CalculatedValue 属性设置）。
否则可能会导致意外结果或异常。
如果用户在某些自定义函数的实现中需要更改计算结果以外的其他数据，
例如，更改单元格的公式、样式等，用户应该在此实现中收集这些数据并将它们更改到公式计算的范围之外。

### 也可以看看
* 模块[`aspose.cellsgridjs`](..)
