---
title: ErrorCheckType枚举
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 2000
url: /zh/aspose.cells/errorchecktype/
is_root: false
---
## ErrorCheckType枚举
代表所有错误校验类型。



ErrorCheckType 类型公开以下成员：

### 字段
|字段|描述|
| :- | :- |
| EVALUATION_ERROR |当单元格包含导致错误的公式时忽略错误。|
| CALC |  |
| EMPTY_CELL_REF |当公式引用空单元格时忽略错误。|
| NUMBER_STORED_AS_TEXT |当数字格式化为文本或前面有撇号时忽略错误|
| TEXT_NUMBER |当数字格式化为文本或前面有撇号时忽略错误|
| INCONSIST_RANGE |当公式省略区域中的某些单元格时忽略错误。|
| INCONSIST_FORMULA |当工作表某个区域中的公式与同一区域中的其他公式不同时，忽略错误。|
| TWO_DIGIT_TEXT_YEAR |当公式包含文本格式的单元格且年份以 2 位数字表示时，忽略错误。|
| TEXT_DATE |当公式包含文本格式的单元格且年份以 2 位数字表示时，忽略错误。|
| UNLOCKED_FORMULA |当未锁定的单元格包含公式时忽略错误。|
| UNPROCTED_FORMULA |当未锁定的单元格包含公式时忽略错误。|
| TABLE_DATA_VALIDATION |当表中单元格的值不符合指定的数据验证规则时忽略错误。|
| VALIDATION |当表中单元格的值不符合指定的数据验证规则时忽略错误。|
| CALCULATED_COLUMN |当单元格包含与计算列公式不同的值时忽略错误。|



### 也可以看看
* 模块[`aspose.cells`](..)
