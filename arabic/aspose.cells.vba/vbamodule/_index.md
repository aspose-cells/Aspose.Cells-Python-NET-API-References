---
title: VbaModule صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 10
url: /ar/aspose.cells.vba/vbamodule/
is_root: false
---
##  VbaModule صف
يمثل الوحدة النمطية في مشروع VBA.



يكشف النوع VbaModule عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [name](/cells/python-net/ar/aspose.cells.vba/vbamodule/name) | يحصل على اسم الوحدة ويحدده.|
| [type](/cells/python-net/ar/aspose.cells.vba/vbamodule/type) | يحصل على نوع الوحدة النمطية.|
| [binary_codes](/cells/python-net/ar/aspose.cells.vba/vbamodule/binary_codes) | يحصل على الرموز الثنائية للوحدة ويقوم بتعيينها.|
| [codes](/cells/python-net/ar/aspose.cells.vba/vbamodule/codes) | يحصل على أكواد الوحدة ويحددها.|



###  مثال

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

###  أنظر أيضا
* الوحدة [`aspose.cells.vba`](..)
