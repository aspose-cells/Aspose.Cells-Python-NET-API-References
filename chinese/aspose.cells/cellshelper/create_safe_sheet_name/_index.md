---
title: create_safe_sheet_name方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 90
url: /zh/aspose.cells/cellshelper/create_safe_sheet_name/
is_root: false
---
##  create_safe_sheet_name（，名称提案）{#str}
检查给定的工作表名称并在需要时创建一个有效的工作表名称。
如果给定的 Sheet 名称符合 Excel Sheet 名称规则，则返回该名称。
否则，如果长度超过限制，字符串将被截断
并且无效字符将被替换为' '，然后返回重建的字符串值。


### 返回




```python

@staticmethod
def create_safe_sheet_name(name_proposal):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| name_proposal | str |要使用的工作表名称|


## create_safe_sheet_name（，name_proposal，replace_char）{#str-char}
检查给定的工作表名称并在需要时创建一个有效的工作表名称。
如果给定的 Sheet 名称符合 Excel Sheet 名称规则，则返回该名称。
否则，如果长度超过限制，字符串将被截断
无效字符将被给定的字符替换，然后返回重建的字符串值。


### 返回




```python

@staticmethod
def create_safe_sheet_name(name_proposal, replace_char):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| name_proposal | str |要使用的工作表名称|
| replace_char | char |用于替换给定工作表名称中的无效字符的字符|



### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`CellsHelper`](/cells/python-net/zh/aspose.cells/cellshelper)
