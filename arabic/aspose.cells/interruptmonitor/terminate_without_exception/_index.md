---
title: terminate_without_exception الملكية
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 50
url: /ar/aspose.cells/interruptmonitor/terminate_without_exception/
is_root: false
---
##  terminate_without_exception الملكية

عند مقاطعة الإجراء ، سواء إنهاء الإجراء بهدوء أو طرح استثناء.
الافتراضي خطأ ، أي عندما يكون [AbstractInterruptMonitor.is_interruption_requested](/cells/python-net/ar/aspose.cells/abstractinterruptmonitor#is_interruption_requested) صحيحًا ،
سيتم طرح [CellsException](/cells/python-net/ar/aspose.cells/cellsexception) برمز [ExceptionType.INTERRUPTED](/cells/python-net/ar/aspose.cells/exceptiontype#INTERRUPTED).
###  تعريف:
```python
@property
def terminate_without_exception(self):
    ...
```

###  أنظر أيضا
* وحدة [aspose.cells](../../)
* فئة [CellsException](/cells/python-net/ar/aspose.cells/cellsexception)
* فئة [InterruptMonitor](/cells/python-net/ar/aspose.cells/interruptmonitor)
