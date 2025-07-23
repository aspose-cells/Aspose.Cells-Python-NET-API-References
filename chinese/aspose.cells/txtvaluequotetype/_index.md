---
title: TxtValueQuoteType枚举
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 2670
url: /zh/aspose.cells/txtvaluequotetype/
is_root: false
---
## TxtValueQuoteType枚举
指定文本格式文件中的值使用引号的类型。



TxtValueQuoteType 类型公开以下成员：

### 字段
|字段|描述|
| :- | :- |
| NORMAL |所有包含特殊字符（如引号、分隔符）的值都将被引用。<br/>与 ms excel 导出文本文件的行为相同。|
| ALWAYS |所有值都将始终被引用。|
| MINIMUM |仅在需要时才对值进行引用。例如，如果一个值包含引号，但引号不在该值的开头，则该值不会被引用。|
| NEVER |所有值均不带引号。导出的此类文本文件可能无法正确读取，因为缺少所需的引号。|



### 也可以看看
* 模块[`aspose.cells`](..)
