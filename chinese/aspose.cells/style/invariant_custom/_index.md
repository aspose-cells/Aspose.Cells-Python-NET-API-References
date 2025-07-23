---
title: invariant_custom属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 260
url: /zh/aspose.cells/style/invariant_custom/
is_root: false
---
## invariant_custom属性

获取与文化无关的数字格式模式字符串。
如果此对象没有设置数字格式，则返回 null。
如果数字格式是内置的，则返回与内置数字对应的模式字符串。

### 注意事项

对于内置数字格式，返回的模式内容仍然依赖于文化，
例如，对于某些语言环境，它返回“m/d/y”，而对于其他一些语言环境，它返回“d/m/y”。
与 [`Style.culture_custom`](/cells/python-net/zh/aspose.cells/style#culture_custom) 的区别是（这也是文化独立的意思）：
格式说明符和分隔符保持标准，例如“/”将始终用作日期时间分隔符
并且无论特定语言环境使用什么其他特殊字符，“y”始终用作“年份”部分。
### 定义：
```python
@property
def invariant_custom(self):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Style`](/cells/python-net/zh/aspose.cells/style)
