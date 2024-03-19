---
title: copy方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 50
url: /zh/aspose.cells/range/copy/
is_root: false
---
##  copy {#aspose.cells.Range}
从源范围复制数据（包括公式）、格式、绘图对象等。



```python
def copy(self, range):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| range | [`Range`](/cells/python-net/zh/aspose.cells/range) |来源 [`Range`](/cells/python-net/zh/aspose.cells/range) 对象。|

### 例子

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Get the first Worksheet Cells.
cells = workbook.worksheets[0].cells
range1 = cells.create_range("A1:A5")
range2 = cells.create_range("A6:A10")
# Copy the range.
range1.copy(range2)
# Save the Excel file
workbook.save("book1.xlsm")

```


##  copy {#aspose.cells.Range-aspose.cells.PasteOptions}
使用粘贴特殊选项复制范围。



```python
def copy(self, range, options):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| range | [`Range`](/cells/python-net/zh/aspose.cells/range) |来源范围。|
| options | [`PasteOptions`](/cells/python-net/zh/aspose.cells/pasteoptions) |粘贴特殊选项。|



### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Range`](/cells/python-net/zh/aspose.cells/range)
