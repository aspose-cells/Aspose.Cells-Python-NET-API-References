---
title: get_picture方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 120
url: /zh/aspose.cells/pagesetup/get_picture/
is_root: false
---
##  get_picture(self, is_header, section) {#bool-int}
获取页眉/页脚的 [`Picture`](/cells/python-net/zh/aspose.cells.drawing/picture) 对象。


### 返回

返回 [`Picture`](/cells/python-net/zh/aspose.cells.drawing/picture) 对象。
如果没有图片则返回 null。


```python

def get_picture(self, is_header, section):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| is_header | bool |指示其位于页眉还是页脚。|
| section | int |0：左部分，1：中间部分，2：右部分。|


##  get_picture(self, is_first, is_even, is_header, section) {#bool-bool-bool-int}
获取页眉/页脚的 [`Picture`](/cells/python-net/zh/aspose.cells.drawing/picture) 对象。


### 返回

返回 [`Picture`](/cells/python-net/zh/aspose.cells.drawing/picture) 对象。


```python

def get_picture(self, is_first, is_even, is_header, section):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| is_first | bool |是否获取首页页眉/页脚的图片。|
| is_even | bool |是否获取偶数页页眉/页脚的图片。|
| is_header | bool |是否获取页眉/页脚的图片。|
| section | int |0：左部分，1：中间部分，2：右部分。|



### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`PageSetup`](/cells/python-net/zh/aspose.cells/pagesetup)
* 类 [`Picture`](/cells/python-net/zh/aspose.cells.drawing/picture)
