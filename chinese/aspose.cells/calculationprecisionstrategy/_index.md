---
title: CalculationPrecisionStrategy枚举
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 1890
url: /zh/aspose.cells/calculationprecisionstrategy/
is_root: false
---
## CalculationPrecisionStrategy枚举
枚举处理计算精度的策略。
由于IEEE 754浮点运算的精度问题，一些“看似简单”的公式可能无法计算出预期的结果。
如公式“=-0.45+0.43+0.02”，直接用“+”运算符计算操作数时，结果不为零。对于这种精度问题，
一些特殊的策略可能会达到预期的效果。



CalculationPrecisionStrategy 类型公开以下成员：

### 领域
|场地|描述|
| :- | :- |
| NONE |计算中没有应用策略。<br/>计算时直接使用原来的double值作为操作数，直接返回结果。<br/>对性能最有效并且适用于大多数情况。|
| ROUND |计算结果按有效数字进行四舍五入。|
| DECIMAL |尽可能使用小数作为操作数。<br/>性能效率最低。|



### 也可以看看
* 模块[`aspose.cells`](..)
