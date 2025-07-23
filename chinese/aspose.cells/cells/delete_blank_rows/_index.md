---
title: delete_blank_rows方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 210
url: /zh/aspose.cells/cells/delete_blank_rows/
is_root: false
---
##  delete_blank_rows(self) {#}
删除所有不包含任何数据或其他对象的空白行。



```python

def delete_blank_rows(self):
    ...
```




##  delete_blank_rows(self, options) {#aspose.cells.DeleteOptions}
删除所有不包含任何数据或某些特殊对象（例如可见注释、数据透视表）的空白行。



```python

def delete_blank_rows(self, options):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| options | [`DeleteOptions`](/cells/python-net/zh/aspose.cells/deleteoptions) |删除范围的选项。|
### 注意事项

对于要删除的空白行，不仅要求 [`Row.is_blank`](/cells/python-net/zh/aspose.cells/row#is_blank) 为真，
但这些行中的任何单元格都不应该定义可见的注释，
并且没有范围与它们相交的数据透视表。


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Cells`](/cells/python-net/zh/aspose.cells/cells)
