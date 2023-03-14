---
title: process_row方法
second_title: Aspose.Cells for Python via .NET API 参考资料
description:
type: docs
weight: 30
url: /zh/aspose.cells/lightcellsdatahandler/process_row/
is_root: false
---
##  process_row(row) {#Row}
开始处理一行。


### 返回

此行的单元格是否需要处理。 false 忽略此行中的所有单元格。


```python
def process_row(self, row):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| row | [Row](/cells/python-net/zh/aspose.cells/row) |当前正在处理的行对象。|
### 评论

它将在行的属性（例如高度、样式等）之后被调用。已阅读。但是，尚未读取此行中的单元格。


### 也可以看看

* 模块 [aspose.cells](../../)
* 类 [LightCellsDataHandler](/cells/python-net/zh/aspose.cells/lightcellsdatahandler)
