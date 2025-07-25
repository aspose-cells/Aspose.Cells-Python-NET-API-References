---
title: value属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 40
url: /zh/aspose.cells/cellvalue/value/
is_root: false
---
## value属性

获取/设置单元格 value。

### 注意事项

value 必须是与 [`CellValue.type`](/cells/python-net/zh/aspose.cells/cellvalue#type) 对应的正确对象类型：
|类型|价值|
| :- | :- |
|null，任何其他对象将被忽略|
| double |
|日期时间|
|细绳|
|布尔值|
|错误字符串，例如“#VALUE!”，“#NAME?”，...|
### 定义：
```python
@property
def value(self):
    ...
@value.setter
def value(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`CellValue`](/cells/python-net/zh/aspose.cells/cellvalue)
