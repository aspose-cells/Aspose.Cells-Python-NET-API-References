---
title: get_list_value方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 70
url: /zh/aspose.cells/validation/get_list_value/
is_root: false
---
##  get_list_value(self, row, column) {#int-int}
获取指定单元格的验证列表的值。


### 返回

为指定单元格生成此验证列表的值。
如果列表引用一个范围，那么返回的值将是一个 [`ReferredArea`](/cells/python-net/zh/aspose.cells/referredarea) 对象；
否则返回的值可能是 null、object[] 或简单对象。


```python

def get_list_value(self, row, column):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| row | int |行索引。|
| column | int |列索引。|
### 注意事项

仅适用于类型为 List 且已应用于给定单元格的验证，
否则将返回 null。


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`ReferredArea`](/cells/python-net/zh/aspose.cells/referredarea)
* 类 [`Validation`](/cells/python-net/zh/aspose.cells/validation)
