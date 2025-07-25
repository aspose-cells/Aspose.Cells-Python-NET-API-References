---
title: طريقة remove_date_filter
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 150
url: /ar/aspose.cells/autofilter/remove_date_filter/
is_root: false
---
##  remove_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second) {#int-aspose.cells.DateTimeGroupingType-int-int-int-int-int-int}
إزالة مرشح التاريخ.



```python

def remove_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| field_index | int | الإزاحة الصحيحة للحقل الذي تريد أن تستند إليه المرشح<br/> (من يسار القائمة؛ الحقل الأيسر هو الحقل 0).|
| date_time_grouping_type | [`DateTimeGroupingType`](/cells/python-net/ar/aspose.cells/datetimegroupingtype) | نوع التجميع|
| year | int | السنة.|
| month | int | الشهر.|
| day | int | اليوم.|
| hour | int | الساعة.|
| minute | int | الدقيقة.|
| second | int | الثانيه|
###  ملاحظات

إذا كان DateTimeGroupingType هو Year، فسيتم فقط التأثير على معلمة year.
إذا كان DateTiemGroupingType هو Month، فسيتم تطبيق تأثير السنة والشهر فقط.


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`AutoFilter`](/cells/python-net/ar/aspose.cells/autofilter)
