---
title: SystemTimeInterruptMonitor类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 1390
url: /zh/aspose.cells/systemtimeinterruptmonitor/
is_root: false
---
## SystemTimeInterruptMonitor类
通过检查和比较当前系统时间与用户指定的限制来简单实现 AbstractInterruptMonitor。



**继承：** [`SystemTimeInterruptMonitor`](/cells/python-net/zh/aspose.cells/systemtimeinterruptmonitor)



SystemTimeInterruptMonitor 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [`__init__(self, terminate_without_exception)`](/cells/python-net/zh/aspose.cells/systemtimeinterruptmonitor/__init__/#bool) |构造一个中断监视器。|


### 属性
|属性|描述|
| :- | :- |
| [is_interruption_requested](/cells/python-net/zh/aspose.cells/systemtimeinterruptmonitor/is_interruption_requested) |此实现仅检查时间成本（从启动此监视器到现在）是否大于用户指定的限制。|
| [terminate_without_exception](/cells/python-net/zh/aspose.cells/systemtimeinterruptmonitor/terminate_without_exception) |请参阅TerminateWithoutException。<br/>该属性由用户在构造此监控实例时指定。|


### 方法
|方法|描述|
| :- | :- |
| [`start_monitor(self, ms_limit)`](/cells/python-net/zh/aspose.cells/systemtimeinterruptmonitor/start_monitor/#int) |按照指定的时间限制启动监视器。计算时间成本的开始时间就是调用此方法时。<br/>因此需要监控的程序应该在这个调用之后立即启动。|



### 注意事项

该实现只是针对简单场景的简单解决方案。
它需要频繁地检索和检查系统时间，因此本身可能会在一定程度上对性能产生负面影响。

### 也可以看看
* 模块[`aspose.cells`](..)
* 类 [`SystemTimeInterruptMonitor`](/cells/python-net/zh/aspose.cells/systemtimeinterruptmonitor)
