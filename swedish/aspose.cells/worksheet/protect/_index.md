---
title: protect metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 220
url: /sv/aspose.cells/worksheet/protect/
is_root: false
---
##  protect(self, type) {#aspose.cells.ProtectionType}
Skyddar kalkylbladet.



```python

def protect(self, type):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| type | [`ProtectionType`](/cells/python-net/sv/aspose.cells/protectiontype) | Skyddstyp.|
###  Anmärkningar

Den här metoden skyddar kalkylbladet utan lösenord. Det kan fungera i alla versioner av Excel-filer.

##  protect(self, type, password, old_password) {#aspose.cells.ProtectionType-str-str}

Skyddar kalkylbladet.



```python

def protect(self, type, password, old_password):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| type | [`ProtectionType`](/cells/python-net/sv/aspose.cells/protectiontype) | Skyddstyp.|
| password | str | Lösenord.|
| old_password | str | Om arbetsbladet redan är lösenordsskyddat, vänligen ange det gamla lösenordet.<br/> Annars kan du ange ett nullvärde eller en tom sträng för den här parametern.|
###  Anmärkningar

Den här metoden kan användas med kalkylbladet protect i alla versioner av Excel-filer.
###  Exempel


```python
from aspose.cells import ProtectionType, Workbook

# Instantiating a Workbook object
excel = Workbook("template.xlsx")
# Accessing the first worksheet in the Excel file
worksheet = excel.worksheets[0]
# Protecting the worksheet with a password
worksheet.protect(ProtectionType.ALL, "aspose", None)
# Saving the modified Excel file in default (that is Excel 20003) format
excel.save("output.xls")

```



###  Se även
* modul [`aspose.cells`](../../)
* klass [`Worksheet`](/cells/python-net/sv/aspose.cells/worksheet)
