---
title: linked_data_sources属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 60
url: /zh/aspose.cells/calculationoptions/linked_data_sources/
is_root: false
---
## linked_data_sources属性

指定公式中使用的外部链接的数据源。

### 注意事项

例如 [`Workbook.update_linked_data_source`](/cells/python-net/zh/aspose.cells/workbook/update_linked_data_source)，您可以在这里指定
计算公式中使用的外部链接的数据源，特别是那些
用于 INDIRECT 函数。对于 INDIRECT 函数中使用的外部链接，
它们不被视为工作簿外部链接的一部分，并且无法更新
[`Workbook.update_linked_data_source`](/cells/python-net/zh/aspose.cells/workbook/update_linked_data_source)。
这些工作簿与外部链接的匹配由 [`Workbook.file_name`](/cells/python-net/zh/aspose.cells/workbook#file_name) 决定
和 [`ExternalLink.data_source`](/cells/python-net/zh/aspose.cells/externallink#data_source)。因此请确保 [`Workbook.file_name`](/cells/python-net/zh/aspose.cells/workbook#file_name) 已
已指定适当的值（通常应与相应的
为每个工作簿添加 .[`ExternalLink.data_source`](/cells/python-net/zh/aspose.cells/externallink#data_source)，以便它们能够按预期链接。
### 定义：
```python
@property
def linked_data_sources(self):
    ...
@linked_data_sources.setter
def linked_data_sources(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`CalculationOptions`](/cells/python-net/zh/aspose.cells/calculationoptions)
