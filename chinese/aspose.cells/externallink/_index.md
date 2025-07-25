---
title: ExternalLink类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 570
url: /zh/aspose.cells/externallink/
is_root: false
---
## ExternalLink类
表示工作簿中的外部链接。



ExternalLink 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [type](/cells/python-net/zh/aspose.cells/externallink/type) |获取外部链接的类型。|
| [path_type](/cells/python-net/zh/aspose.cells/externallink/path_type) |获取此外部链接的路径类型|
| [original_data_source](/cells/python-net/zh/aspose.cells/externallink/original_data_source) |表示外部链接存储的数据源。|
| [data_source](/cells/python-net/zh/aspose.cells/externallink/data_source) |表示外部链接的数据源。|
| [is_referred](/cells/python-net/zh/aspose.cells/externallink/is_referred) |表示此外部链接是否被他人引用。|
| [is_visible](/cells/python-net/zh/aspose.cells/externallink/is_visible) |指示此外部链接在 MS Excel 中是否可见。|


### 方法
|方法|描述|
| :- | :- |
| [`add_external_name(self, text, refer_to)`](/cells/python-net/zh/aspose.cells/externallink/add_external_name/#str-str) |添加外部名称。|



### 例子

```python
from aspose.cells import Workbook

# Open a file with external links
workbook = Workbook("book1.xls")
# Get External Link
externalLink = workbook.worksheets.external_links[0]
# Change External Link's Data Source
externalLink.data_source = "d:\\link.xls"

```

### 也可以看看
* 模块[`aspose.cells`](..)
