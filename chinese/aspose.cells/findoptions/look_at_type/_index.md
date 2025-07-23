---
title: look_at_type属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 90
url: /zh/aspose.cells/findoptions/look_at_type/
is_root: false
---
## look_at_type属性

看类型。

### 注意事项

当 [`FindOptions.regex_key`](/cells/python-net/zh/aspose.cells/findoptions#regex_key) 为真并且用户已为正则表达式指定了精确规则时，
出于性能考虑，此属性应设置为 [`LookAtType.ENTIRE_CONTENT`](/cells/python-net/zh/aspose.cells/lookattype#ENTIRE_CONTENT)。
否则我们将重构搜索键以确保它可以根据特定类型进行匹配。
例如，当类型为 [`LookAtType.CONTAINS`](/cells/python-net/zh/aspose.cells/lookattype#CONTAINS)（这是此属性的默认值）时，
我们将自动在搜索键的开头和结尾添加通配符。
这样的话，正则表达式就会变得更加复杂，性能也会下降。
### 定义：
```python
@property
def look_at_type(self):
    ...
@look_at_type.setter
def look_at_type(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`FindOptions`](/cells/python-net/zh/aspose.cells/findoptions)
* 类 [`LookAtType`](/cells/python-net/zh/aspose.cells/lookattype)
