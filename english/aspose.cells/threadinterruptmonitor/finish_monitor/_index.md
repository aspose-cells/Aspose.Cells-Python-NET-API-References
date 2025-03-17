---
title: finish_monitor method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 20
url: /aspose.cells/threadinterruptmonitor/finish_monitor/
is_root: false
---

## finish_monitor(self) {#}

Finishes the monitor for one procedure.



```python

def finish_monitor(self):
    ...
```


### Remarks

Calling this method after the monitored procedure can release the monitor thread earlier,
especially when there is no interruption for it(the time cost of that procedure is less than the specified time limit).


### See Also
* module [`aspose.cells`](../../)
* class [`ThreadInterruptMonitor`](/cells/python-net/aspose.cells/threadinterruptmonitor)
