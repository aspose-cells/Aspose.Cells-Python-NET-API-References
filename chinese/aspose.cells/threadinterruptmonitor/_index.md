---
title: ThreadInterruptMonitor类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 1410
url: /zh/aspose.cells/threadinterruptmonitor/
is_root: false
---
## ThreadInterruptMonitor类
AbstractInterruptMonitor 的简单实现是通过启动另一个线程来要求在睡眠用户指定的限制后进行中断。



**继承：** [`ThreadInterruptMonitor`](/cells/python-net/zh/aspose.cells/threadinterruptmonitor)



ThreadInterruptMonitor 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [`__init__(self, terminate_without_exception)`](/cells/python-net/zh/aspose.cells/threadinterruptmonitor/__init__/#bool) |构造一个中断监视器。|


### 属性
|属性|描述|
| :- | :- |
| [is_interruption_requested](/cells/python-net/zh/aspose.cells/threadinterruptmonitor/is_interruption_requested) |此实现仅检查时间成本（从启动此监视器到现在）是否大于用户指定的限制。|
| [terminate_without_exception](/cells/python-net/zh/aspose.cells/threadinterruptmonitor/terminate_without_exception) |请参阅TerminateWithoutException。<br/>该属性由用户在构造此监控实例时指定。|


### 方法
|方法|描述|
| :- | :- |
| [`start_monitor(self, ms_limit)`](/cells/python-net/zh/aspose.cells/threadinterruptmonitor/start_monitor/#int) |按照指定的时间限制启动监视器。计算时间成本的开始时间就是调用此方法时。<br/>因此需要监控的程序应该在这个调用之后立即启动。|
| [`finish_monitor(self)`](/cells/python-net/zh/aspose.cells/threadinterruptmonitor/finish_monitor/#) |完成对一个过程的监控。|



### 注意事项

一个监视实例可以重复使用，只要按顺序监视每个进程即可。
它不应该用于在多线程中同时监视多个过程。

### 也可以看看
* 模块[`aspose.cells`](..)
* 类 [`ThreadInterruptMonitor`](/cells/python-net/zh/aspose.cells/threadinterruptmonitor)
