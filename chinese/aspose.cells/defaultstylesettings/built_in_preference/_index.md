---
title: built_in_preference属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 30
url: /zh/aspose.cells/defaultstylesettings/built_in_preference/
is_root: false
---
## built_in_preference属性

指示当样式同时定义内置数字和自定义模式时，数字格式的属性是否优先。
默认值为 false，这意味着只要一种样式不为空，默认将使用自定义模式来格式化值。

### 注意事项

从现有模板文件加载工作簿时，可能为一种样式同时定义了内置数字和自定义模式。
此属性决定在使用样式格式化值时我们是否应该使用内置数字或自定义模式。
### 定义：
```python
@property
def built_in_preference(self):
    ...
@built_in_preference.setter
def built_in_preference(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`DefaultStyleSettings`](/cells/python-net/zh/aspose.cells/defaultstylesettings)
