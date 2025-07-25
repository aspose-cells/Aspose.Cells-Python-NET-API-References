---
title: SpreadsheetLocker صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 170
url: /ar/aspose.cells.lowcode/spreadsheetlocker/
is_root: false
---
##  SpreadsheetLocker صف
واجهة برمجة تطبيقات منخفضة الكود لقفل ملف جدول البيانات.



يكشف النوع SpreadsheetLocker عن الأعضاء التاليين:

###  طُرق
| طريقة| وصف|
| :- | :- |
| [`process(, template_file, result_file, open_password, write_password)`](/cells/python-net/ar/aspose.cells.lowcode/spreadsheetlocker/process/#str-str-str-str) | يقوم بقفل ملف جدول البيانات بالإعدادات المحددة.|
| [`process(, load_options, save_options, open_password, write_password)`](/cells/python-net/ar/aspose.cells.lowcode/spreadsheetlocker/process/#aspose.cells.lowcode.lowcodeloadoptions-aspose.cells.lowcode.lowcodesaveoptions-str-str) | يقوم بقفل ملف جدول البيانات بالإعدادات المحددة.|
| [`process(, load_options, save_options, open_password, write_password, workbook_password, workbook_type)`](/cells/python-net/ar/aspose.cells.lowcode/spreadsheetlocker/process/#aspose.cells.lowcode.lowcodeloadoptions-aspose.cells.lowcode.lowcodesaveoptions-str-str-str-aspose.cells.protectiontype) | يقوم بقفل ملف جدول البيانات بالإعدادات المحددة.|
| [`process(, load_options, save_options, provider)`](/cells/python-net/ar/aspose.cells.lowcode/spreadsheetlocker/process/#aspose.cells.lowcode.lowcodeloadoptions-aspose.cells.lowcode.lowcodesaveoptions-aspose.cells.lowcode.abstractlowcodeprotectionprovider) | يقوم بقفل ملف جدول البيانات بالإعدادات المحددة.|



###  مثال

```python
from aspose.cells.lowcode import SpreadsheetLocker

SpreadsheetLocker.process("template.xlsx", "locked.xlsx", "mypassword", "mypassword")

```

###  أنظر أيضا
* الوحدة [`aspose.cells.lowcode`](..)
