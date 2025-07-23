---
title: طريقة finish_monitor
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 20
url: /ar/aspose.cells/threadinterruptmonitor/finish_monitor/
is_root: false
---
##  finish_monitor(self) {#}
ينهي المراقبة لإجراء واحد.



```python

def finish_monitor(self):
    ...
```


###  ملاحظات

إن استدعاء هذه الطريقة بعد الإجراء الذي تتم مراقبته قد يؤدي إلى تحرير مؤشر ترابط المراقبة في وقت مبكر،
وخاصة عندما لا يكون هناك انقطاع لذلك (التكلفة الزمنية لهذا الإجراء أقل من الحد الزمني المحدد).


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`ThreadInterruptMonitor`](/cells/python-net/ar/aspose.cells/threadinterruptmonitor)
