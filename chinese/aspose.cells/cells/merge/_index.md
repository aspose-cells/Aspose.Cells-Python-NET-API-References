---
title: merge方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 780
url: /zh/aspose.cells/cells/merge/
is_root: false
---
##  merge {#int-int-int-int}
将指定范围的单元格合并为单个单元格。



```python
def merge(self, first_row, first_column, total_rows, total_columns):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| first_row | int |该范围的第一行（从零开始）|
| first_column | int |该范围的第一列（从零开始）|
| total_rows | int |行数（从一开始）|
| total_columns | int |列数（以一为基础）|
### 评论

通过区域中左上角单元格的地址引用合并的单元格。

##  merge {#int-int-int-int-bool}

将指定范围的单元格合并为单个单元格。



```python
def merge(self, first_row, first_column, total_rows, total_columns, merge_conflict):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| first_row | int |该范围的第一行（从零开始）|
| first_column | int |该范围的第一列（从零开始）|
| total_rows | int |行数（从一开始）|
| total_columns | int |列数（以一为基础）|
| merge_conflict | bool |合并冲突合并范围。|
### 评论

通过区域中左上角单元格的地址引用合并的单元格。
如果 mergeConflict 为 true 并且合并范围与其他合并单元格冲突，
其他合并的单元格将被自动删除。

##  merge {#int-int-int-int-bool-bool}
将指定范围的单元格合并为单个单元格。



```python
def merge(self, first_row, first_column, total_rows, total_columns, check_conflict, merge_conflict):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| first_row | int |该范围的第一行（从零开始）|
| first_column | int |该范围的第一列（从零开始）|
| total_rows | int |行数（从一开始）|
| total_columns | int |列数（以一为基础）|
| check_conflict | bool |指示检查合并单元格是否与其他合并单元格相交|
| merge_conflict | bool |合并冲突合并范围。|
### 评论

通过区域中左上角单元格的地址引用合并的单元格。
如果 mergeConflict 为 true 并且合并范围与其他合并单元格冲突，
其他合并的单元格将被自动删除。


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Cells`](/cells/python-net/zh/aspose.cells/cells)
