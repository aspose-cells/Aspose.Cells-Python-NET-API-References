---
title: remove_date_filter方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 150
url: /zh/aspose.cells/autofilter/remove_date_filter/
is_root: false
---
##  remove_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second) {#int-aspose.cells.DateTimeGroupingType-int-int-int-int-int-int}
删除日期过滤器。



```python

def remove_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| field_index | int |过滤器所基于的字段的整数偏移量<br/>（从列表左侧开始；最左边的字段是字段 0）。|
| date_time_grouping_type | [`DateTimeGroupingType`](/cells/python-net/zh/aspose.cells/datetimegroupingtype) |分组类型|
| year | int |年份。|
| month | int |这个月。|
| day | int |这一天。|
| hour | int |小时。|
| minute | int |一分钟。|
| second | int |第二个。|
### 注意事项

如果 DateTimeGroupingType 为 Year，则只有参数 year 有效。
如果 DateTiemGroupingType 为 Month，则只有参数 year 和 month 有效。


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`AutoFilter`](/cells/python-net/zh/aspose.cells/autofilter)
