---
title: set_local_function_name方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 350
url: /zh/aspose.cells/settableglobalizationsettings/set_local_function_name/
is_root: false
---
##  set_local_function_name {#str-str-bool}
设置与给定标准函数名称相对应的区域设置相关函数名称。



```python
def set_local_function_name(self, standard_name, local_name, bidirectional):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| standard_name | str |标准（en-US 区域设置）函数名称。|
| local_name | str |与区域设置相关的函数名称|
| bidirectional | bool |是否自动将本地函数名称映射到标准函数名称。<br/>如果为 true，则本地名称将自动映射到标准名称<br/>所以用户不需要再次拨打[`SettableGlobalizationSettings.set_standard_function_name`](/cells/python-net/zh/aspose.cells/settableglobalizationsettings/set_standard_function_name)<br/>对于相同的标准和本地名称对|



### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`SettableGlobalizationSettings`](/cells/python-net/zh/aspose.cells/settableglobalizationsettings)
