﻿---
title: SystemTimeInterruptMonitor class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 1390
url: /aspose.cells/systemtimeinterruptmonitor/
is_root: false
---

## SystemTimeInterruptMonitor class

Simple implementation of AbstractInterruptMonitor by checking and comparing current system time with user specified limit.



**Inheritance:** [`SystemTimeInterruptMonitor`](/cells/python-net/aspose.cells/systemtimeinterruptmonitor)



The SystemTimeInterruptMonitor type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self, terminate_without_exception)`](/cells/python-net/aspose.cells/systemtimeinterruptmonitor/__init__/#bool) | Constructs one interruption monitor. |


### Properties
| Property | Description |
| :- | :- |
| [is_interruption_requested](/cells/python-net/aspose.cells/systemtimeinterruptmonitor/is_interruption_requested) | This implementation just checks whether the time cost(from the time when starting this monitor to now) is greater than user specified limit. |
| [terminate_without_exception](/cells/python-net/aspose.cells/systemtimeinterruptmonitor/terminate_without_exception) | See TerminateWithoutException.<br/>This property is specified by user when constructing this monitor instance. |


### Methods
| Method | Description |
| :- | :- |
| [`start_monitor(self, ms_limit)`](/cells/python-net/aspose.cells/systemtimeinterruptmonitor/start_monitor/#int) | Starts the monitor with the specified time limit. The start time to calculate time cost is just when this method is called,<br/>so the procedure which needs to be monitored should be started just after this call. |



### Remarks 


This implementation is just a simple solution for simple scenarios.
It needs to frequently retrieve and check the system time so itself may have a negative impact on performance to some extent.

### See Also
* module [`aspose.cells`](..)
* class [`SystemTimeInterruptMonitor`](/cells/python-net/aspose.cells/systemtimeinterruptmonitor)
