---
title: get_linked_cell方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 120
url: /zh/aspose.cells.drawing/arcshape/get_linked_cell/
is_root: false
---
##  get_linked_cell(self, is_r1c1, is_local) {#bool-bool}
获取与控件值相关的范围。


### 返回

与控件值关联的范围。


```python

def get_linked_cell(self, is_r1c1, is_local):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| is_r1c1 | bool |公式是否需要格式化为R1C1。|
| is_local | bool |公式是否需要根据语言环境进行格式化。|

### 例子

```python

# You may get results like '$A$1'
link = shape.get_linked_cell(False, False)

```



### 也可以看看
* 模块[`aspose.cells.drawing`](../../)
* 类 [`ArcShape`](/cells/python-net/zh/aspose.cells.drawing/arcshape)
