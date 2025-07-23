---
title: sheet_name属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 120
url: /zh/aspose.cells/referredarea/sheet_name/
is_root: false
---
## sheet_name属性

指示此引用位于哪张表。

### 注意事项

如果它引用多个工作表，
返回值就像公式中的范围表达式。
例如，公式“=SUM(Sheet1:Sheet3!$A$1:$B$2)”中的引用为“Sheet1:Sheet3”。
### 定义：
```python
@property
def sheet_name(self):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`ReferredArea`](/cells/python-net/zh/aspose.cells/referredarea)
