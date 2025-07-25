---
title: ungroup方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 500
url: /zh/aspose.cells.drawing/shapecollection/ungroup/
is_root: false
---
##  ungroup(self, group) {#aspose.cells.drawing.GroupShape}
取消形状项目的组合。



```python

def ungroup(self, group):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| group | [`GroupShape`](/cells/python-net/zh/aspose.cells.drawing/groupshape) |群体形状。|
### 注意事项

如果该组形状由另一个组形状分组，则不会执行任何操作。
### 例子


```python

# add first shape
shapes.add_rectangle(2, 0, 2, 0, 50, 50)
# add second shape
shapes.add_rectangle(6, 0, 2, 0, 30, 30)
# group
shapesArr = [shapes[0], shapes[1]]
groupShape = shapes.group(shapesArr)
# ungroup
shapes.ungroup(groupShape)

```



### 也可以看看
* 模块[`aspose.cells.drawing`](../../)
* 类 [`ShapeCollection`](/cells/python-net/zh/aspose.cells.drawing/shapecollection)
