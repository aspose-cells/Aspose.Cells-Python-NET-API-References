---
title: base_item_position属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 320
url: /zh/aspose.cells.pivot/pivotfield/base_item_position/
is_root: false
---
## base_item_position属性

表示使用 ShowDataAs 计算时自定义计算的基本字段中的项目。
仅对数据字段有效。
因为 PivotItemPosition.Custom 仅供读取，如果需要设置 PivotItemPosition.Custom，
请设置 PivotField.BaseItemIndex 属性。

### 注意事项

注意：此属性现已过时。取而代之的是
请改用 PivotField.ShowValuesSetting.BaseItemPositionType 属性。
该方法将于 2024 年 6 月起 12 个月后取消。
Aspose 对于您所遇到的不便深表歉意。
### 定义：
```python
@property
def base_item_position(self):
    ...
@base_item_position.setter
def base_item_position(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells.pivot`](../../)
* 类 [`PivotField`](/cells/python-net/zh/aspose.cells.pivot/pivotfield)
* 类 [`PivotItemPosition`](/cells/python-net/zh/aspose.cells.pivot/pivotitemposition)
