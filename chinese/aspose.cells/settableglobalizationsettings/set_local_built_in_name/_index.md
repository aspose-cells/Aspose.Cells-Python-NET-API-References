---
title: set_local_built_in_name方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 340
url: /zh/aspose.cells/settableglobalizationsettings/set_local_built_in_name/
is_root: false
---
##  set_local_built_in_name {#str-str-bool}
使用给定的标准名称文本设置内置名称的区域设置相关文本。



```python
def set_local_built_in_name(self, standard_name, local_name, bidirectional):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| standard_name | str |内置名称的标准（en-US 区域设置）名称文本。|
| local_name | str |区域设置相关名称文本|
| bidirectional | bool |是否自动将本地名称文本映射到标准名称文本。<br/>如果为 true，则本地名称文本将自动映射到标准名称文本<br/>所以用户不需要再次拨打[`SettableGlobalizationSettings.set_standard_built_in_name`](/cells/python-net/zh/aspose.cells/settableglobalizationsettings/set_standard_built_in_name)<br/>对于相同的标准和本地名称对|



### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`SettableGlobalizationSettings`](/cells/python-net/zh/aspose.cells/settableglobalizationsettings)
