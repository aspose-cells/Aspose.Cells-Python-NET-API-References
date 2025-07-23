---
title: filter方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 90
url: /zh/aspose.cells/autofilter/filter/
is_root: false
---
##  filter(self, field_index, criteria) {#int-str}
使用指定条件过滤列表。



```python

def filter(self, field_index, criteria):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| field_index | int |过滤器所基于的字段的整数偏移量<br/>（从列表左侧开始；最左边的字段是字段 0）。|
| criteria | str |指定的条件（字符串；例如“101”）。|
### 注意事项

Aspose.Cells 将删除此字段上的所有其他 filter 设置，作为 Ms Excel 97-2003。


### 也可以看看

* 模块[`aspose.cells`](../../)
* 类 [`AutoFilter`](/cells/python-net/zh/aspose.cells/autofilter)
