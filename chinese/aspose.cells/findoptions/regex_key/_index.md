---
title: regex_key属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 110
url: /zh/aspose.cells/findoptions/regex_key/
is_root: false
---
## regex_key属性

指示搜索的键是否是正则表达式。
如果为真，则搜索到的键将被视为正则表达式并进行解析。
否则，将根据 ms excel 中的规则解析密钥。

### 注意事项

即使搜索键已指定为正则表达式，
它可能根据指定 [`FindOptions.look_at_type`](/cells/python-net/zh/aspose.cells/findoptions#look_at_type) 进行重构。
例如，当类型为 [`LookAtType.CONTAINS`](/cells/python-net/zh/aspose.cells/lookattype#CONTAINS)（这是此选项的默认值）时，
通配符将自动添加到搜索关键字的开头和结尾，以确保匹配
检查为“包含”。在这种情况下，正则表达式将变得更加复杂
并且性能也会下降。
因此，出于性能考虑，如果用户已经为正则表达式指定了精确的规则，则无需
使用 [`FindOptions.look_at_type`](/cells/python-net/zh/aspose.cells/findoptions#look_at_type) 作为附加约束，用户可以将其设置为 [`LookAtType.ENTIRE_CONTENT`](/cells/python-net/zh/aspose.cells/lookattype#ENTIRE_CONTENT)
以获得更好的性能。
### 定义：
```python
@property
def regex_key(self):
    ...
@regex_key.setter
def regex_key(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`FindOptions`](/cells/python-net/zh/aspose.cells/findoptions)
