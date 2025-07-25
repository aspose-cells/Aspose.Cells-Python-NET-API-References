---
title: CalculationPrecisionStrategy枚举
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 1790
url: /zh/aspose.cells/calculationprecisionstrategy/
is_root: false
---
## CalculationPrecisionStrategy枚举
列举处理计算精度的策略。
由于IEEE 754浮点运算的精度问题，一些“看似简单”的公式可能无法计算出预期的结果。
例如公式“=-0.45+0.43+0.02”，直接用“+”运算符计算操作数时，结果不为零。对于此类精度问题，
一些特殊的策略可能会产生预期的结果。



CalculationPrecisionStrategy 类型公开以下成员：

### 字段
|字段|描述|
| :- | :- |
| NONE |计算时未应用任何策略。<br/>计算时只需使用原始double值作为操作数并直接返回结果。<br/>性能最高效且适用于大多数情况。|
| ROUND |将计算结果按照有效数字进行四舍五入。|
| DECIMAL |尽可能使用十进制作为操作数。<br/>对于性能而言，效率最低。|



### 也可以看看
* 模块[`aspose.cells`](..)
