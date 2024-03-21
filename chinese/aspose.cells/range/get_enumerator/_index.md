---
title: get_enumerator方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 100
url: /zh/aspose.cells/range/get_enumerator/
is_root: false
---
##  get_enumerator {#}
获取此范围内的单元格的枚举数。


### 退货

细胞计数仪


```python
def get_enumerator(self):
    ...
```


### 评论

当通过返回的Enumerator遍历元素时，cells集合
不应修改（例如会导致新的 Cell/Row 被实例化或现有的 Cell/Row 被删除的操作）。
否则枚举器可能无法正确遍历所有单元格（某些元素可能会重复遍历或跳过）。
### 例子

```python
from aspose.cells import Workbook

workbook = Workbook("template.xlsx")
cells = workbook.worksheets[0].cells
en = cells.create_range("B2:C3").get_enumerator()
for cell in en:
    print(cell.name + ": "  + str(cell.value))

```



### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Range`](/cells/python-net/zh/aspose.cells/range)
