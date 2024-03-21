---
title: preferred_parsers属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 350
url: /zh/aspose.cells/txtloadoptions/preferred_parsers/
is_root: false
---
## preferred_parsers属性

获取和设置用于加载文本文件的首选值解析器。

### 评论

parsers[0] 是将用于文本模板文件中第一列的解析器，
parsers[1] 是将用于第二列的解析器，...等。
最后一个（parsers[parsers.length-1]）将用于从 parsers.length-1 开始的所有其他列。
如果其中一项为空，则对应的列将由默认解析器 Aspose.Cells 解析。
### 定义：
```python
@property
def preferred_parsers(self):
    ...
@preferred_parsers.setter
def preferred_parsers(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`TxtLoadOptions`](/cells/python-net/zh/aspose.cells/txtloadoptions)
