---
title: add_icon_filter方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 60
url: /zh/aspose.cells/autofilter/add_icon_filter/
is_root: false
---
##  add_icon_filter(self, field_index, icon_set_type, icon_id) {#int-aspose.cells.IconSetType-int}
添加图标过滤器。



```python

def add_icon_filter(self, field_index, icon_set_type, icon_id):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| field_index | int |过滤器所基于的字段的整数偏移量<br/>（从列表左侧开始；最左边的字段是字段 0）。|
| icon_set_type | [`IconSetType`](/cells/python-net/zh/aspose.cells/iconsettype) |图标集类型。|
| icon_id | int |图标 ID。|
### 注意事项

仅支持添加图标过滤器。
如果过滤器是图标过滤器，则不支持检查哪一行可见。


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`AutoFilter`](/cells/python-net/zh/aspose.cells/autofilter)
