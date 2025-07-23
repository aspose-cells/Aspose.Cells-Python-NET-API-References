---
title: update_linked_data_source方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 440
url: /zh/aspose.cells/workbook/update_linked_data_source/
is_root: false
---
##  update_linked_data_source(self, external_workbooks) {#list}
如果此工作簿包含指向其他数据源的外部链接，
Aspose.Cells 将尝试从给定来源检索最新数据。



```python

def update_linked_data_source(self, external_workbooks):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| external_workbooks | list |用于更新此工作簿引用的外部链接数据的工作簿。<br/>这些工作簿与外部链接的匹配由 [`Workbook.file_name`](/cells/python-net/zh/aspose.cells/workbook#file_name) 决定<br/>和 [`ExternalLink.data_source`](/cells/python-net/zh/aspose.cells/externallink#data_source)。因此请确保 [`Workbook.file_name`](/cells/python-net/zh/aspose.cells/workbook#file_name) 已<br/>为每个工作簿指定了适当的值，以便它们可以链接到相应的外部链接。|
### 注意事项

如果某个工作簿找不到相应的外部链接，则该工作簿将被忽略。
因此，当您稍后使用一个新的外部链接设置公式时，您打算将其设置为忽略的工作簿
与之相链接，直到您再次使用这些工作簿调用此方法，才能执行链接。


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Workbook`](/cells/python-net/zh/aspose.cells/workbook)
