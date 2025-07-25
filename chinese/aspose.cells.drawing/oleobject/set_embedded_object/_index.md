---
title: set_embedded_object方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 200
url: /zh/aspose.cells.drawing/oleobject/set_embedded_object/
is_root: false
---
##  set_embedded_object(self, link_to_file, object_data, source_file_name, display_as_icon, label) {#bool-bytes-str-bool-str}
设置嵌入的对象数据。



```python

def set_embedded_object(self, link_to_file, object_data, source_file_name, display_as_icon, label):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| link_to_file | bool |指示对象是否链接到文件。如果为 true，则忽略参数 objectData。|
| object_data | bytes |嵌入的对象数据。|
| source_file_name | str |文件名。|
| display_as_icon | bool |指示是否将对象显示为图标。<br/>如果为真，则原始图像数据将被图标覆盖。|
| label | str |图标标签。仅当 displayAsIcon 为 true 时有效。|


##  set_embedded_object(self, link_to_file, object_data, source_file_name, display_as_icon, label, update_icon) {#bool-bytes-str-bool-str-bool}
设置嵌入的对象数据。



```python

def set_embedded_object(self, link_to_file, object_data, source_file_name, display_as_icon, label, update_icon):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| link_to_file | bool |指示对象是否链接到文件。如果为 true，则忽略参数 objectData。|
| object_data | bytes |嵌入的对象数据。|
| source_file_name | str |文件名。|
| display_as_icon | bool |指示是否将对象显示为图标。<br/>如果为真，则原始图像数据将被图标覆盖。|
| label | str |图标标签。仅当 displayAsIcon 为 true 时有效。|
| update_icon | bool |指示是否自动更新图标。|
### 注意事项

由于 Aspose 可以更新嵌入的所有文件图标，因此最好将 `update_icon` 设置为 false 来添加正确的图标。


### 也可以看看

* 模块[`aspose.cells.drawing`](../../)
* 类 [`OleObject`](/cells/python-net/zh/aspose.cells.drawing/oleobject)
