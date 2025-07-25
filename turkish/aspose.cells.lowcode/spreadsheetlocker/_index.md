---
title: SpreadsheetLocker sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 170
url: /tr/aspose.cells.lowcode/spreadsheetlocker/
is_root: false
---
##  SpreadsheetLocker sınıfı
E-tablo dosyasını kilitlemek için düşük kodlu API.



SpreadsheetLocker türü aşağıdaki üyeleri ortaya çıkarır:

###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`process(, template_file, result_file, open_password, write_password)`](/cells/python-net/tr/aspose.cells.lowcode/spreadsheetlocker/process/#str-str-str-str) | Belirtilen ayarlarla elektronik tablo dosyasını kilitler.|
| [`process(, load_options, save_options, open_password, write_password)`](/cells/python-net/tr/aspose.cells.lowcode/spreadsheetlocker/process/#aspose.cells.lowcode.lowcodeloadoptions-aspose.cells.lowcode.lowcodesaveoptions-str-str) | Belirtilen ayarlarla elektronik tablo dosyasını kilitler.|
| [`process(, load_options, save_options, open_password, write_password, workbook_password, workbook_type)`](/cells/python-net/tr/aspose.cells.lowcode/spreadsheetlocker/process/#aspose.cells.lowcode.lowcodeloadoptions-aspose.cells.lowcode.lowcodesaveoptions-str-str-str-aspose.cells.protectiontype) | Belirtilen ayarlarla elektronik tablo dosyasını kilitler.|
| [`process(, load_options, save_options, provider)`](/cells/python-net/tr/aspose.cells.lowcode/spreadsheetlocker/process/#aspose.cells.lowcode.lowcodeloadoptions-aspose.cells.lowcode.lowcodesaveoptions-aspose.cells.lowcode.abstractlowcodeprotectionprovider) | Belirtilen ayarlarla elektronik tablo dosyasını kilitler.|



###  Örnek

```python
from aspose.cells.lowcode import SpreadsheetLocker

SpreadsheetLocker.process("template.xlsx", "locked.xlsx", "mypassword", "mypassword")

```

###  Ayrıca bakınız
* modül [`aspose.cells.lowcode`](..)
