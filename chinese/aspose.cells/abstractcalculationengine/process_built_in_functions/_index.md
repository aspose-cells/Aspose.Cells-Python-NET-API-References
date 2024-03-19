---
title: process_built_in_functions属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 60
url: /zh/aspose.cells/abstractcalculationengine/process_built_in_functions/
is_root: false
---
## process_built_in_functions属性

是否内置引擎已支持的内置功能
应由该实现进行检查和处理。
默认为 false。

### 评论

如果用户需要改变某些内置函数的计算逻辑，则该属性应设置为true。
否则，出于性能考虑，请将此属性保留为 false。
### 定义：
```python
@property
def process_built_in_functions(self):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`AbstractCalculationEngine`](/cells/python-net/zh/aspose.cells/abstractcalculationengine)
