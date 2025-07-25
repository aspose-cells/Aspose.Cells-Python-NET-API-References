---
title: remove_filter方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 160
url: /zh/aspose.cells/autofilter/remove_filter/
is_root: false
---
##  remove_filter(self, field_index) {#int}
删除特定的过滤器。



```python

def remove_filter(self, field_index):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| field_index | int |具体过滤指标|


##  remove_filter(self, field_index, criteria) {#int-str}
删除过滤器列的过滤器。



```python

def remove_filter(self, field_index, criteria):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| field_index | int |过滤器所基于的字段的整数偏移量<br/>（从列表左侧开始；最左边的字段是字段 0）。|
| criteria | str |指定的条件（字符串；例如“101”）。<br/>它只能为空，或者是此列中单元格的值之一。|



### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`AutoFilter`](/cells/python-net/zh/aspose.cells/autofilter)
