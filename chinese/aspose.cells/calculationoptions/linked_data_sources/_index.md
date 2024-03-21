---
title: linked_data_sources属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 80
url: /zh/aspose.cells/calculationoptions/linked_data_sources/
is_root: false
---
## linked_data_sources属性

指定公式中使用的外部链接的数据源。

### 评论

比如[`Workbook.update_linked_data_source`](/cells/python-net/zh/aspose.cells/workbook/update_linked_data_source)，这里你可以指定
待计算公式中使用的外部链接的数据源，尤其是那些
用于间接函数。对于 INDIRECT 函数中使用的外部链接，
它们不被视为工作簿外部链接的一部分，并且无法更新
通过 [`Workbook.update_linked_data_source`](/cells/python-net/zh/aspose.cells/workbook/update_linked_data_source)。
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
