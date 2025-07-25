---
title: SpreadsheetLocker类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 170
url: /zh/aspose.cells.lowcode/spreadsheetlocker/
is_root: false
---
## SpreadsheetLocker类
低代码 API 来锁定电子表格文件。



SpreadsheetLocker 类型公开以下成员：

### 方法
|方法|描述|
| :- | :- |
| [`process(, template_file, result_file, open_password, write_password)`](/cells/python-net/zh/aspose.cells.lowcode/spreadsheetlocker/process/#str-str-str-str) |使用指定的设置锁定电子表格文件。|
| [`process(, load_options, save_options, open_password, write_password)`](/cells/python-net/zh/aspose.cells.lowcode/spreadsheetlocker/process/#aspose.cells.lowcode.lowcodeloadoptions-aspose.cells.lowcode.lowcodesaveoptions-str-str) |使用指定的设置锁定电子表格文件。|
| [`process(, load_options, save_options, open_password, write_password, workbook_password, workbook_type)`](/cells/python-net/zh/aspose.cells.lowcode/spreadsheetlocker/process/#aspose.cells.lowcode.lowcodeloadoptions-aspose.cells.lowcode.lowcodesaveoptions-str-str-str-aspose.cells.protectiontype) |使用指定的设置锁定电子表格文件。|
| [`process(, load_options, save_options, provider)`](/cells/python-net/zh/aspose.cells.lowcode/spreadsheetlocker/process/#aspose.cells.lowcode.lowcodeloadoptions-aspose.cells.lowcode.lowcodesaveoptions-aspose.cells.lowcode.abstractlowcodeprotectionprovider) |使用指定的设置锁定电子表格文件。|



### 例子

```python
from aspose.cells.lowcode import SpreadsheetLocker

SpreadsheetLocker.process("template.xlsx", "locked.xlsx", "mypassword", "mypassword")

```

### 也可以看看
* 模块[`aspose.cells.lowcode`](..)
