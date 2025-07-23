---
title: culture_custom属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 170
url: /zh/aspose.cells/style/culture_custom/
is_root: false
---
## culture_custom属性

获取并设置数字格式的文化相关模式字符串。
如果此对象没有设置数字格式，则返回 null。
如果数字格式是内置的，则返回与内置数字对应的模式字符串。

### 注意事项

对于内置数字格式，模式内容（例如，对于某些语言环境，一个内置日期格式是“m / d / y”）
但对于其他一些语言环境，它变为“d/m/y”）和格式说明符（例如，
某些语言环境使用除“y”之外的字符来表示日期格式的年份部分）
依赖于文化；
对于用户指定的自定义格式，只有格式说明符会根据文化而改变，
格式模式的其他部分将不会被修改。
### 定义：
```python
@property
def culture_custom(self):
    ...
@culture_custom.setter
def culture_custom(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Style`](/cells/python-net/zh/aspose.cells/style)
