---
title: custom_document_properties属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 300
url: /zh/aspose.cells/worksheetcollection/custom_document_properties/
is_root: false
---
## custom_document_properties属性

返回代表电子表格的所有自定义文档属性的 [`DocumentProperty`](/cells/python-net/zh/aspose.cells.properties/documentproperty) 集合。

### 例子

```python
from aspose.cells import Workbook

workbook = Workbook()
workbook.worksheets.custom_document_properties.add("Checked by", "Jane")

```
### 定义：
```python
@property
def custom_document_properties(self):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`CustomDocumentPropertyCollection`](/cells/python-net/zh/aspose.cells.properties/customdocumentpropertycollection)
* 类 [`DocumentProperty`](/cells/python-net/zh/aspose.cells.properties/documentproperty)
* 类 [`WorksheetCollection`](/cells/python-net/zh/aspose.cells/worksheetcollection)
