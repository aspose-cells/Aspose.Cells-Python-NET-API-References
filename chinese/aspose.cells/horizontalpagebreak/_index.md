---
title: HorizontalPageBreak类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 780
url: /zh/aspose.cells/horizontalpagebreak/
is_root: false
---
## HorizontalPageBreak类
封装表示水平分页符的对象。



HorizontalPageBreak 类型公开以下成员：

### 特性
|属性|描述|
| :- | :- |
| [start_column](/cells/python-net/zh/aspose.cells/horizontalpagebreak/start_column) |获取此水平分页符的起始列索引。|
| [end_column](/cells/python-net/zh/aspose.cells/horizontalpagebreak/end_column) |获取此水平分页符的结束列索引。|
| [row](/cells/python-net/zh/aspose.cells/horizontalpagebreak/row) |获取从零开始的行索引。|



### 例子

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[0]
# Add a page break at cell Y30
Index = worksheet.horizontal_page_breaks.add("Y30")
# get the newly added horizontal page break
hPageBreak = worksheet.horizontal_page_breaks[Index]

```

### 也可以看看
* 模块[`aspose.cells`](..)
