---
title: is_height_matched属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 190
url: /zh/aspose.cells/row/is_height_matched/
is_root: false
---
## is_height_matched属性

指示行高是否与工作簿当前的默认字体设置匹配。
此属性为 True 还表示行高是“自动”的，无需用户设置自定义高度值。

### 评论

当该属性为true时，如果该行的内容发生变化，
一般需要重新计算行高（如按[`Worksheet.auto_fit_rows`](/cells/python-net/zh/aspose.cells/worksheet/auto_fit_rows)）
当您在 MS Excel 中打开工作簿时，获得与 MS Excel 中显示的结果相同的结果。
### 定义：
```python
@property
def is_height_matched(self):
    ...
@is_height_matched.setter
def is_height_matched(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Row`](/cells/python-net/zh/aspose.cells/row)
