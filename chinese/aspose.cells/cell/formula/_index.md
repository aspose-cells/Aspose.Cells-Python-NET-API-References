---
title: formula属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 500
url: /zh/aspose.cells/cell/formula/
is_root: false
---
## formula属性

获取或设置 [`Cell`](/cells/python-net/zh/aspose.cells/cell) 中的 formula。

### 注意事项

 formula 字符串始终以等号 (=) 开头。
并且请始终使用逗号（，）作为参数分隔符，例如“=SUM（A1，E1，H2）”。

### 例子

```python
from aspose.cells import Workbook

excel = Workbook()
cells = excel.worksheets[0].cells
cells.get("B6").formula = "=SUM(B2:B5, E1) + sheet1!A1"

```
### 定义：
```python
@property
def formula(self):
    ...
@formula.setter
def formula(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Cell`](/cells/python-net/zh/aspose.cells/cell)
