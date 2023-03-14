---
title: terminate_without_exception 属性
second_title: Aspose.Cells for Python via .NET API 参考资料
description:
type: docs
weight: 50
url: /zh/aspose.cells/interruptmonitor/terminate_without_exception/
is_root: false
---
## terminate_without_exception 属性

当程序被中断时，是安静地终止程序还是抛出异常。
默认为false，即[AbstractInterruptMonitor.is_interruption_requested](/cells/python-net/zh/aspose.cells/abstractinterruptmonitor#is_interruption_requested)为true时，
将抛出代码为 [ExceptionType.INTERRUPTED](/cells/python-net/zh/aspose.cells/exceptiontype#INTERRUPTED) 的 [CellsException](/cells/python-net/zh/aspose.cells/cellsexception)。
### 定义：
```python
@property
def terminate_without_exception(self):
    ...
```

### 也可以看看
* 模块 [aspose.cells](../../)
* 类 [CellsException](/cells/python-net/zh/aspose.cells/cellsexception)
* 类 [InterruptMonitor](/cells/python-net/zh/aspose.cells/interruptmonitor)
