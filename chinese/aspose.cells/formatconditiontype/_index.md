---
title: FormatConditionType枚举
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 2110
url: /zh/aspose.cells/formatconditiontype/
is_root: false
---
## FormatConditionType枚举
条件格式规则类型。



FormatConditionType 类型公开以下成员：

### 字段
|字段|描述|
| :- | :- |
| CELL_VALUE |此条件格式规则比较单元格值<br/>使用运算符对公式计算结果进行操作。|
| EXPRESSION |此条件格式规则包含一个公式<br/>评估。当公式结果为真时，单元格<br/>突出显示。|
| TOP10 |此条件格式规则突出显示<br/>值属于前 N 个或后 N 个括号，因为<br/>指定的。|
| UNIQUE_VALUES |此条件格式规则突出显示独特的<br/>范围内的值。|
| DUPLICATE_VALUES |此条件格式规则突出显示重复项<br/>值。|
| CONTAINS_TEXT |此条件格式规则突出显示单元格<br/>包含给定文本。相当于使用 SEARCH()<br/>sheet 函数用于判断单元格是否包含<br/>文本。|
| NOT_CONTAINS_TEXT |此条件格式规则突出显示<br/>不包含给定文本。相当于使用 SEARCH()<br/>sheet 函数用于判断单元格是否包含<br/>文本是否。|
| BEGINS_WITH |此条件格式规则突出显示<br/>以给定文本开头的范围。相当于<br/>使用 LEFT() 工作表函数并比较值。|
| ENDS_WITH |此条件格式规则突出显示单元格结尾<br/>给定文本。相当于使用 RIGHT() 表<br/>函数和比较值。|
| CONTAINS_BLANKS |此条件格式规则突出显示<br/>完全为空。相当于使用 LEN(TRIM())。<br/>这意味着如果单元格仅包含字符<br/>TRIM() 将删除，那么它被视为空白。<br/>空单元格也被视为空白。|
| NOT_CONTAINS_BLANKS |此条件格式规则突出显示<br/>不为空。相当于使用 LEN(TRIM())。这<br/>意味着如果单元格仅包含<br/>TRIM() 会删除，则它被视为空白。<br/>空单元格也被视为空白。|
| CONTAINS_ERRORS |此条件格式规则突出显示具有<br/>公式错误。相当于使用 ISERROR() 表<br/>函数来确定是否存在公式错误。|
| NOT_CONTAINS_ERRORS |此条件格式规则突出显示单元格<br/>没有公式错误。相当于使用 ISERROR()<br/> sheet 函数来确定是否存在公式错误。|
| TIME_PERIOD |此条件格式规则突出显示单元格<br/>包含指定时间段内的日期。<br/>单元格的底层值被评估，因此<br/>单元格不需要格式化为日期<br/>评估。例如，对于包含<br/>值 38913 应应用条件格式，如果<br/>该规则要求的值为 7/14/2006。|
| ABOVE_AVERAGE |此条件格式规则突出显示<br/>高于或低于所有值的平均值<br/>范围。|
| COLOR_SCALE |此条件格式规则创建了一个渐变的<br/>细胞上的颜色标度。|
| DATA_BAR |此条件格式规则显示渐变<br/>单元格范围内的数据栏。|
| ICON_SET |此条件格式规则将图标应用于单元格<br/>根据他们的价值观。|



### 也可以看看
* 模块[`aspose.cells`](..)
