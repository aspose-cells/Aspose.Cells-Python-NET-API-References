---
title: CustomDocumentPropertyCollection类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 40
url: /zh/aspose.cells.properties/customdocumentpropertycollection/
is_root: false
---
## CustomDocumentPropertyCollection类
自定义文档属性的集合。



**继承：** [`CustomDocumentPropertyCollection`](/cells/python-net/zh/aspose.cells.properties/customdocumentpropertycollection)



CustomDocumentPropertyCollection 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [capacity](/cells/python-net/zh/aspose.cells.properties/customdocumentpropertycollection/capacity) |获取或设置数组列表可包含的元素数量。|


### 方法
|方法|描述|
| :- | :- |
| [`get(self, name)`](/cells/python-net/zh/aspose.cells.properties/customdocumentpropertycollection/get/#str) |  |
| [`get(self, index)`](/cells/python-net/zh/aspose.cells.properties/customdocumentpropertycollection/get/#int) |  |
| [`index_of(self, name)`](/cells/python-net/zh/aspose.cells.properties/customdocumentpropertycollection/index_of/#str) |  |
| [`index_of(self, item, index)`](/cells/python-net/zh/aspose.cells.properties/customdocumentpropertycollection/index_of/#aspose.cells.properties.documentproperty-int) |搜索指定的对象并返回从指定索引延伸到最后一个元素的数组列表中元素范围内第一个出现的从零开始的索引。|
| [`index_of(self, item, index, count)`](/cells/python-net/zh/aspose.cells.properties/customdocumentpropertycollection/index_of/#aspose.cells.properties.documentproperty-int-int) |搜索指定的对象并返回从指定索引开始并包含指定数量元素的数组列表中元素范围内第一次出现的从零开始的索引。|
| [`copy_to(self, array)`](/cells/python-net/zh/aspose.cells.properties/customdocumentpropertycollection/copy_to/#list) |将整个数组列表复制到兼容的一维数组列表，从目标数组列表的开头开始。|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/zh/aspose.cells.properties/customdocumentpropertycollection/copy_to/#int-list-int-int) |从目标数组列表的指定索引开始，将数组列表中的一系列元素复制到兼容的一维数组列表中。|
| [`last_index_of(self, item)`](/cells/python-net/zh/aspose.cells.properties/customdocumentpropertycollection/last_index_of/#aspose.cells.properties.documentproperty) |搜索指定的对象并返回整个数组列表中最后一次出现的从零开始的索引。|
| [`last_index_of(self, item, index)`](/cells/python-net/zh/aspose.cells.properties/customdocumentpropertycollection/last_index_of/#aspose.cells.properties.documentproperty-int) |搜索指定的对象并返回从第一个元素延伸到指定索引的数组列表中元素范围内的最后一个出现的从零开始的索引。|
| [`last_index_of(self, item, index, count)`](/cells/python-net/zh/aspose.cells.properties/customdocumentpropertycollection/last_index_of/#aspose.cells.properties.documentproperty-int-int) |搜索指定的对象并返回包含指定数量的元素并以指定索引结束的数组列表中元素范围内的最后一个出现的从零开始的索引。|
| [`add(self, name, value)`](/cells/python-net/zh/aspose.cells.properties/customdocumentpropertycollection/add/#str-str) |创建一个新的自定义文档属性**属性类型.String**数据类型。|
| [`add(self, name, value)`](/cells/python-net/zh/aspose.cells.properties/customdocumentpropertycollection/add/#str-int) |创建一个新的自定义文档属性**属性类型.数字**数据类型。|
| [`add(self, name, value)`](/cells/python-net/zh/aspose.cells.properties/customdocumentpropertycollection/add/#str-datetime) |创建一个新的自定义文档属性**属性类型.日期时间**数据类型。|
| [`add(self, name, value)`](/cells/python-net/zh/aspose.cells.properties/customdocumentpropertycollection/add/#str-bool) |创建一个新的自定义文档属性**属性类型.布尔值**数据类型。|
| [`add(self, name, value)`](/cells/python-net/zh/aspose.cells.properties/customdocumentpropertycollection/add/#str-float) |创建一个新的自定义文档属性**属性类型.Float**数据类型。|
| [`binary_search(self, item)`](/cells/python-net/zh/aspose.cells.properties/customdocumentpropertycollection/binary_search/#aspose.cells.properties.documentproperty) |使用默认比较器在整个排序数组列表中搜索元素，并返回该元素从零开始的索引。|
| [`add_link_to_content(self, name, source)`](/cells/python-net/zh/aspose.cells.properties/customdocumentpropertycollection/add_link_to_content/#str-str) |创建链接到内容的新自定义文档属性。|
| [`update_linked_property_value(self)`](/cells/python-net/zh/aspose.cells.properties/customdocumentpropertycollection/update_linked_property_value/#) |更新链接到内容的自定义文档属性值。|
| [`update_linked_range(self)`](/cells/python-net/zh/aspose.cells.properties/customdocumentpropertycollection/update_linked_range/#) |将自定义文档属性值更新为链接范围。|



### 注意事项

每个 [`DocumentProperty`](/cells/python-net/zh/aspose.cells.properties/documentproperty) 对象代表一个容器文档的自定义属性。

### 例子

```python
from aspose.cells import Workbook

# Instantiate a Workbook object
workbook = Workbook("book1.xls")
# Retrieve a list of all custom document properties of the Excel file
customProperties = workbook.worksheets.custom_document_properties

```

### 也可以看看
* 模块[`aspose.cells.properties`](..)
* 类 [`CustomDocumentPropertyCollection`](/cells/python-net/zh/aspose.cells.properties/customdocumentpropertycollection)
* 类 [`DocumentProperty`](/cells/python-net/zh/aspose.cells.properties/documentproperty)
