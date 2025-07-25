---
title: characters方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 50
url: /zh/aspose.cells.drawing/oleobject/characters/
is_root: false
---
##  characters(self, start_index, length) {#int-int}
返回表示文本中 characters 范围的 Characters 对象。


### 返回

人物对象。


```python

def characters(self, start_index, length):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| start_index | int |字符开始的索引。|
| length | int |字符数。|
### 注意事项

此方法仅适用于带有标题的形状。
### 例子


```python

fontSetting = shape.characters(0, 4)

```



### 也可以看看
* 模块[`aspose.cells.drawing`](../../)
* 类 [`OleObject`](/cells/python-net/zh/aspose.cells.drawing/oleobject)
