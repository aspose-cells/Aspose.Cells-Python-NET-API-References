---
title: WorkbookMetadata类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 20
url: /zh/aspose.cells.metadata/workbookmetadata/
is_root: false
---
## WorkbookMetadata类
表示元数据。



WorkbookMetadata 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [`__init__(self, file_name, options)`](/cells/python-net/zh/aspose.cells.metadata/workbookmetadata/__init__/#str-aspose.cells.metadata.metadataoptions) |创建元数据对象。|
| [`__init__(self, stream, options)`](/cells/python-net/zh/aspose.cells.metadata/workbookmetadata/__init__/#io.rawiobase-aspose.cells.metadata.metadataoptions) |创建元数据对象。|


### 属性
|属性|描述|
| :- | :- |
| [options](/cells/python-net/zh/aspose.cells.metadata/workbookmetadata/options) |获取元数据的选项。|
| [built_in_document_properties](/cells/python-net/zh/aspose.cells.metadata/workbookmetadata/built_in_document_properties) |返回一个 [`DocumentProperty`](/cells/python-net/zh/aspose.cells.properties/documentproperty) 集合，该集合代表电子表格的所有内置文档属性。|
| [custom_document_properties](/cells/python-net/zh/aspose.cells.metadata/workbookmetadata/custom_document_properties) |返回代表电子表格的所有自定义文档属性的 [`DocumentProperty`](/cells/python-net/zh/aspose.cells.properties/documentproperty) 集合。|


### 方法
|方法|描述|
| :- | :- |
| [`save(self, file_name)`](/cells/python-net/zh/aspose.cells.metadata/workbookmetadata/save/#str) |将修改后的元数据保存到文件中。|
| [`save(self, stream)`](/cells/python-net/zh/aspose.cells.metadata/workbookmetadata/save/#io.rawiobase) |将修改后的元数据保存到流中。|



### 例子

以下示例创建 WorkbookMetadata。

```python
from aspose.cells.metadata import MetadataOptions, MetadataType, WorkbookMetadata

options = MetadataOptions(MetadataType.DOCUMENT_PROPERTIES)
meta = WorkbookMetadata("book1.xlsx", options)
meta.custom_document_properties.add("test", "test")
meta.save("book2.xlsx")

```

### 也可以看看
* 模块[`aspose.cells.metadata`](..)
* 类 [`DocumentProperty`](/cells/python-net/zh/aspose.cells.properties/documentproperty)
