---
title: protect Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 220
url: /de/aspose.cells/worksheet/protect/
is_root: false
---
##  protect(self, type) {#aspose.cells.ProtectionType}
Schützt das Arbeitsblatt.



```python

def protect(self, type):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| type | [`ProtectionType`](/cells/python-net/de/aspose.cells/protectiontype) | Schutzart.|
###  Bemerkungen

Diese Methode schützt das Arbeitsblatt ohne Kennwort. Sie kann das Arbeitsblatt protect in allen Versionen der Excel-Datei schützen.

##  protect(self, type, password, old_password) {#aspose.cells.ProtectionType-str-str}

Schützt das Arbeitsblatt.



```python

def protect(self, type, password, old_password):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| type | [`ProtectionType`](/cells/python-net/de/aspose.cells/protectiontype) | Schutzart.|
| password | str | Passwort.|
| old_password | str | Wenn das Arbeitsblatt bereits durch ein Passwort geschützt ist, geben Sie bitte das alte Passwort ein.<br/> Andernfalls können Sie diesem Parameter einen Nullwert oder eine leere Zeichenfolge zuweisen.|
###  Bemerkungen

Mit dieser Methode können Sie das Arbeitsblatt protect in allen Versionen von Excel-Dateien verwenden.
###  Beispiel


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



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Worksheet`](/cells/python-net/de/aspose.cells/worksheet)
