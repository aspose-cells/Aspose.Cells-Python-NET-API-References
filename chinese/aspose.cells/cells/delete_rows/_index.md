---
title: delete_rows方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 260
url: /zh/aspose.cells/cells/delete_rows/
is_root: false
---
##  delete_rows(self, row_index, total_rows) {#int-int}
删除多行。



```python

def delete_rows(self, row_index, total_rows):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| row_index | int |要删除的第一行索引。|
| total_rows | int |要删除的行数。|
### 注意事项

如果删除的范围包含表格（ListObject）的顶部（不是全部），
无法删除范围并且不会执行任何操作。
它的工作方式与 MS Excel 相同。

##  delete_rows(self, row_index, total_rows, update_reference) {#int-int-bool}
删除工作表中的多行。


### 返回




```python

def delete_rows(self, row_index, total_rows, update_reference):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| row_index | int |要删除的第一行的索引。|
| total_rows | int |要删除的行数。|
| update_reference | bool |指示是否更新其他工作表中的引用。|


##  delete_rows(self, row_index, total_rows, options) {#int-int-aspose.cells.DeleteOptions}
删除工作表中的多行。


### 返回




```python

def delete_rows(self, row_index, total_rows, options):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| row_index | int |要删除的第一行的索引。|
| total_rows | int |要删除的行数。|
| options | [`DeleteOptions`](/cells/python-net/zh/aspose.cells/deleteoptions) |删除操作的选项|



### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Cells`](/cells/python-net/zh/aspose.cells/cells)
