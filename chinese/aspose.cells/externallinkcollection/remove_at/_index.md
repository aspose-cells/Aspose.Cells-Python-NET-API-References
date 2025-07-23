---
title: remove_at方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 40
url: /zh/aspose.cells/externallinkcollection/remove_at/
is_root: false
---
##  remove_at(self, index) {#int}
从工作簿中删除指定的外部链接。



```python

def remove_at(self, index):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| index | int |要删除的外部链接的索引。|
### 注意事项

删除外部链接时，所有引用该链接的公式也将被删除，因为
引用将失效。

##  remove_at(self, index, update_references_as_local) {#int-bool}
从工作簿中删除指定的外部链接。



```python

def remove_at(self, index, update_references_as_local):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| index | int |要删除的外部链接的索引。|
| update_references_as_local | bool |是否将给定外部链接的所有引用更新为当前工作簿本身的引用。<br/>检查 [`ExternalLinkCollection.clear`](/cells/python-net/zh/aspose.cells/externallinkcollection/clear) 以获取有关此参数的更多详细信息。|



### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`ExternalLinkCollection`](/cells/python-net/zh/aspose.cells/externallinkcollection)
