---
title: InterruptMonitor类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 990
url: /zh/aspose.cells/interruptmonitor/
is_root: false
---
## InterruptMonitor类
代表有关中断的所有操作符。



**遗产：** [`InterruptMonitor`](/cells/python-net/aspose.cells/interruptmonitor) → 
[`AbstractInterruptMonitor`](/cells/python-net/zh/aspose.cells/abstractinterruptmonitor)



InterruptMonitor 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [__init__](/cells/python-net/zh/aspose.cells/interruptmonitor/__init__/#) |构造一个新的 InterruptMonitor 实例|


### 特性
|属性|描述|
| :- | :- |
| [is_interruption_requested](/cells/python-net/zh/aspose.cells/interruptmonitor/is_interruption_requested) |将监视器标记为请求中断|
| [terminate_without_exception](/cells/python-net/zh/aspose.cells/interruptmonitor/terminate_without_exception) |当程序被中断时，是否安静地终止程序或抛出异常。<br/>默认为false，即[`AbstractInterruptMonitor.is_interruption_requested`](/cells/python-net/zh/aspose.cells/abstractinterruptmonitor#is_interruption_requested)为true时，<br/>将抛出代码为 [`ExceptionType.INTERRUPTED`](/cells/python-net/zh/aspose.cells/exceptiontype#INTERRUPTED) 的 [`CellsException`](/cells/python-net/zh/aspose.cells/cellsexception)。|


### 方法
|方法|描述|
| :- | :- |
| [interrupt](/cells/python-net/zh/aspose.cells/interruptmonitor/interrupt/#) |中断当前操作员。|



### 也可以看看
* 模块[`aspose.cells`](..)
* 类 [`AbstractInterruptMonitor`](/cells/python-net/zh/aspose.cells/abstractinterruptmonitor)
* 类 [`CellsException`](/cells/python-net/zh/aspose.cells/cellsexception)
* 类 [`InterruptMonitor`](/cells/python-net/zh/aspose.cells/interruptmonitor)
