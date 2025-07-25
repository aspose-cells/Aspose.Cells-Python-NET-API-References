---
title: clear方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 30
url: /zh/aspose.cells/externallinkcollection/clear/
is_root: false
---
##  clear(self) {#}
删除所有外部链接。



```python

def clear(self):
    ...
```


### 注意事项

删除外部链接时，所有引用它们的公式也将被删除，因为
引用将失效。

##  clear(self, update_references_as_local) {#bool}
删除所有外部链接。



```python

def clear(self, update_references_as_local):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| update_references_as_local | bool |是否将公式中所有外部链接的引用更新为当前工作簿本身的引用。|
### 注意事项

如果需要更新引用，则公式中外部链接的引用
当可能时将更改为当前工作簿。
例如，一个单元格的原始公式是“='externalsource.xlam'!customfunction()”，
删除外部链接后，公式将变为“=customfunction()”；
当原公式为“='[externalsource.xlam]Sheet1'!$A$1”时，
根据当前工作簿中是否有一个名为“Sheet1”的工作表：
如果为真，则公式将变为“=Sheet1!$A$1”；
如果为假，公式将变为“=#REF!$A$1”。

如果不需要更新参考文献，则所有引用外部链接的公式
也将被删除，因为这些引用变得无效。


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`ExternalLinkCollection`](/cells/python-net/zh/aspose.cells/externallinkcollection)
