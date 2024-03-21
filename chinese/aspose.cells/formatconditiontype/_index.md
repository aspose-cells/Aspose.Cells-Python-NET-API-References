---
title: FormatConditionType枚举
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 2170
url: /zh/aspose.cells/formatconditiontype/
is_root: false
---
## FormatConditionType枚举
条件格式规则类型。



FormatConditionType 类型公开以下成员：

### 领域
|场地|描述|
| :- | :- |
| CELL_VALUE |此条件格式规则比较单元格值<br/>使用运算符将其转换为公式计算结果。|
| EXPRESSION |此条件格式规则包含一个公式<br/>评价。当公式结果为真时，单元格为<br/>突出显示。|
| TOP10 |此条件格式规则突出显示其<br/>值落在顶部 N 或底部 N 括号中，如下所示<br/>指定的。|
| UNIQUE_VALUES |此条件格式规则突出显示独特的<br/>范围内的值。|
| DUPLICATE_VALUES |此条件格式规则突出显示重复项<br/>价值观。|
| CONTAINS_TEXT |此条件格式规则突出显示单元格<br/>包含给定的文本。相当于使用 SEARCH()<br/>sheet函数判断单元格是否包含<br/>文本。|
| NOT_CONTAINS_TEXT |此条件格式规则突出显示以下单元格<br/>不包含给定的文本。相当于使用 SEARCH()<br/>sheet函数判断单元格是否包含<br/>文本与否。|
| BEGINS_WITH |此条件格式规则突出显示中的单元格<br/>以给定文本开头的范围。相当于<br/>使用 LEFT() 表函数并比较值。|
| ENDS_WITH |此条件格式规则突出显示以结尾的单元格<br/>与给定的文本。相当于使用 RIGHT() 表<br/>功能和比较值。|
| CONTAINS_BLANKS |此条件格式规则突出显示以下单元格<br/>完全空白。相当于使用 LEN(TRIM())。<br/>这意味着如果单元格仅包含字符<br/>TRIM() 将删除该内容，则将其视为空白。<br/>空单元格也被视为空白。|
| NOT_CONTAINS_BLANKS |此条件格式规则突出显示以下单元格<br/>不为空。相当于使用 LEN(TRIM())。这<br/>意味着如果单元格仅包含以下字符<br/>TRIM() 将删除，然后将其视为空白。一个<br/>空单元格也被视为空白。|
| CONTAINS_ERRORS |此条件格式规则突出显示单元格<br/>公式错误。相当于使用 ISERROR() 表<br/>函数来判断是否存在公式错误。|
| NOT_CONTAINS_ERRORS |此条件格式规则突出显示单元格<br/>无公式错误。相当于使用 ISERROR()<br/> Sheet 函数来确定是否存在公式错误。|
| TIME_PERIOD |此条件格式规则突出显示单元格<br/>包含指定时间段内的日期。这<br/>单元格的潜在价值被评估，因此<br/>单元格不需要格式化为日期<br/>评价。例如，对于包含以下内容的单元格<br/>值 38913 应应用条件格式，如果<br/>该规则要求值为 7/14/2006。|
| ABOVE_AVERAGE |此条件格式规则突出显示以下单元格<br/>高于或低于所有值的平均值<br/>范围。|
| COLOR_SCALE |此条件格式规则创建分级<br/>细胞上的色标。|
| DATA_BAR |此条件格式规则显示分级<br/>单元格范围内的数据栏。|
| ICON_SET |此条件格式规则将图标应用于单元格<br/>根据他们的价值观。|



### 也可以看看
* 模块[`aspose.cells`](..)
