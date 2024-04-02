---
title: GridWorkbookSettings类
second_title: Aspose.Cells.GridJs for Python via .NET API 参考文献
description:
type: docs
weight: 80
url: /zh/aspose.cellsgridjs/gridworkbooksettings/
is_root: false
---
## GridWorkbookSettings类

代表工作簿的设置。



GridWorkbookSettings 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [__init__](/cells/python-net/zh/aspose.cellsgridjs/gridworkbooksettings/__init__/#) |构造 GridWorkbookSettings 的新实例|


### 特性
|属性|描述|
| :- | :- |
| [max_iteration](/cells/python-net/zh/aspose.cellsgridjs/gridworkbooksettings/max_iteration) |返回或设置解决循环引用的最大迭代次数，默认值为 100。|
| [iteration](/cells/python-net/zh/aspose.cellsgridjs/gridworkbooksettings/iteration) |指示是否使用迭代来解决循环引用。|
| [force_full_calculate](/cells/python-net/zh/aspose.cellsgridjs/gridworkbooksettings/force_full_calculate) |每次触发计算时是否完全计算。|
| [create_calc_chain](/cells/python-net/zh/aspose.cellsgridjs/gridworkbooksettings/create_calc_chain) |指示是否创建计算公式链。默认为 false。|
| [re_calculate_on_open](/cells/python-net/zh/aspose.cellsgridjs/gridworkbooksettings/re_calculate_on_open) |指示打开文件时是否重新计算所有公式。|
| [precision_as_displayed](/cells/python-net/zh/aspose.cellsgridjs/gridworkbooksettings/precision_as_displayed) |如果仅使用显示的数字精度来完成此工作簿中的计算，则为 True|
| [date1904](/cells/python-net/zh/aspose.cellsgridjs/gridworkbooksettings/date1904) |获取或设置一个值，该值表示工作簿是否使用 1904 日期系统。|
| [enable_macros](/cells/python-net/zh/aspose.cellsgridjs/gridworkbooksettings/enable_macros) |启用宏；现在，它仅在将工作表复制到工作簿中的其他工作表时才有效。|
| [check_custom_number_format](/cells/python-net/zh/aspose.cellsgridjs/gridworkbooksettings/check_custom_number_format) |设置Style.Custom时是否检查自定义数字格式。|
| [author](/cells/python-net/zh/aspose.cellsgridjs/gridworkbooksettings/author) |获取/设置文件的作者。|



### 例子


```python
from aspose.cellsgridjs import GridJsWorkbook, GridWorkbookSettings

g = GridJsWorkbook()
gsettings = GridWorkbookSettings()
g.settings = gsettings

```

### 也可以看看
* 模块[`aspose.cellsgridjs`](..)
