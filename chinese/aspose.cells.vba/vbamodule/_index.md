---
title: VbaModule类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 10
url: /zh/aspose.cells.vba/vbamodule/
is_root: false
---
## VbaModule类
代表 VBA 项目中的模块。



VbaModule 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [name](/cells/python-net/zh/aspose.cells.vba/vbamodule/name) |获取并设置模块的名称。|
| [type](/cells/python-net/zh/aspose.cells.vba/vbamodule/type) |获取模块的类型。|
| [binary_codes](/cells/python-net/zh/aspose.cells.vba/vbamodule/binary_codes) |获取和设置模块的二进制代码。|
| [codes](/cells/python-net/zh/aspose.cells.vba/vbamodule/codes) |获取和设置模块的代码。|



### 例子

```python
from aspose.cells import Workbook
from aspose.cells.vba import VbaModuleType

# Instantiating a Workbook object
workbook = Workbook()
#  Init VBA project.
vbaProject = workbook.vba_project
#  Add a new module.
index = vbaProject.modules.add(VbaModuleType.CLASS, "test")
#  Get vba module
vbaModule = vbaProject.modules[index]
#  Set codes
vbaModule.codes = "Sub ShowMessage()\r\nMsgBox \"Welcome to Aspose!\"\r\nEnd Sub"
# Saving the Excel file
workbook.save("book1.xlsm")

```

### 也可以看看
* 模块[`aspose.cells.vba`](..)
