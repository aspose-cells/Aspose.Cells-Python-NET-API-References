---
title: add_identify方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 20
url: /zh/aspose.cells.pivot/pivotpagefields/add_identify/
is_root: false
---
##  add_identify(self, range_index, page_item_index) {#int-list}
设置每个页面字段中使用哪个项目标签来标识数据范围。
pageItemIndex.Length 必须等于 PageFieldCount，因此请先添加页面字段。



```python

def add_identify(self, range_index, page_item_index):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| range_index | int |合并数据范围指数。|
| page_item_index | list |每个页面字段中的页面项索引。<br/>pageItemIndex[2] = 1 表示使用第三个字段中的第二项来标识此范围。<br/> pageItemIndex[1] = -1 表示第二个字段中没有可用于标识此范围的项目<br/>并且 MS 将在第二个字段中自动创建“空白”项目来识别该范围。|



### 也可以看看
* 模块[`aspose.cells.pivot`](../../)
* 类 [`PivotPageFields`](/cells/python-net/zh/aspose.cells.pivot/pivotpagefields)
