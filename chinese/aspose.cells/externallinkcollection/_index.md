---
title: ExternalLinkCollection类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 580
url: /zh/aspose.cells/externallinkcollection/
is_root: false
---
## ExternalLinkCollection类
表示工作簿中的外部链接集合。



ExternalLinkCollection 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [count](/cells/python-net/zh/aspose.cells/externallinkcollection/count) |获取集合中实际包含的元素数量。|



获取指定索引处的 [`ExternalLink`](/cells/python-net/zh/aspose.cells/externallink) 元素。
### 索引器
|名称|描述|
| :- | :- |
| [index] |元素的从零开始的索引。|


### 方法
|方法|描述|
| :- | :- |
| [`add(self, file_name, sheet_names)`](/cells/python-net/zh/aspose.cells/externallinkcollection/add/#str-list) |添加外部链接。|
| [`add(self, directory_type, file_name, sheet_names)`](/cells/python-net/zh/aspose.cells/externallinkcollection/add/#aspose.cells.directorytype-str-list) |添加外部链接。|
| [`clear(self)`](/cells/python-net/zh/aspose.cells/externallinkcollection/clear/#) |删除所有外部链接。|
| [`clear(self, update_references_as_local)`](/cells/python-net/zh/aspose.cells/externallinkcollection/clear/#bool) |删除所有外部链接。|
| [`remove_at(self, index)`](/cells/python-net/zh/aspose.cells/externallinkcollection/remove_at/#int) |从工作簿中删除指定的外部链接。|
| [`remove_at(self, index, update_references_as_local)`](/cells/python-net/zh/aspose.cells/externallinkcollection/remove_at/#int-bool) |从工作簿中删除指定的外部链接。|



### 例子

```python
from aspose.cells import Workbook

# Open a file with external links
workbook = Workbook("book1.xls")
# Change external link data source
workbook.worksheets.external_links[0].data_source = "d:\\link.xls"

```

### 也可以看看
* 模块[`aspose.cells`](..)
* 类 [`ExternalLink`](/cells/python-net/zh/aspose.cells/externallink)
