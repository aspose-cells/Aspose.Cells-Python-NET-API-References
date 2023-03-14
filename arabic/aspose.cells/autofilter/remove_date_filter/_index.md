---
title: طريقة remove_date_filter
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 150
url: /ar/aspose.cells/autofilter/remove_date_filter/
is_root: false
---
##  remove_date_filter(field_index, date_time_grouping_type, year, month, day, hour, minute, second) {#int-DateTimeGroupingType-int-int-int-int-int-int}
يزيل مرشح التاريخ.



```python
def remove_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| field_index | int | إزاحة العدد الصحيح للحقل الذي تريد أن يؤسس عامل التصفية عليه<br/> (من يسار القائمة ؛ الحقل الموجود في أقصى اليسار هو الحقل 0).|
| date_time_grouping_type | [DateTimeGroupingType](/cells/python-net/ar/aspose.cells/datetimegroupingtype) | [DateTimeGroupingType](/cells/python-net/ar/aspose.cells/datetimegroupingtype) |
| year | int | السنة.|
| month | int | الشهر.|
| day | int | اليوم.|
| hour | int | ساعة.|
| minute | int | الدقيقة.|
| second | int | الثاني.|
###  ملاحظات

إذا كانت DateTimeGroupingType هي Year ، فستكون تأثيرات السنة المعيارية فقط.
إذا كان DateTiemGroupingType هو Month ، فسيتم فقط تحديد تأثير السنة والشهر.


###  أنظر أيضا
* وحدة [aspose.cells](../../)
* فئة [AutoFilter](/cells/python-net/ar/aspose.cells/autofilter)
* فئة [DateTimeGroupingType](/cells/python-net/ar/aspose.cells/datetimegroupingtype)
