---
title: protect Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 200
url: /de/aspose.cells/worksheet/protect/
is_root: false
---
##  protect {#aspose.cells.ProtectionType}
Schützt das Arbeitsblatt.



```python
def protect(self, type):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| type | [`ProtectionType`](/cells/python-net/de/aspose.cells/protectiontype) | Schutzart.|
###  Bemerkungen

Diese Methode schützt das Arbeitsblatt ohne Passwort. Es kann das Arbeitsblatt protect in allen Versionen der Excel-Datei speichern.

##  protect {#aspose.cells.ProtectionType-str-str}

Schützt das Arbeitsblatt.



```python
def protect(self, type, password, old_password):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| type | [`ProtectionType`](/cells/python-net/de/aspose.cells/protectiontype) | Schutzart.|
| password | str | Passwort.|
| old_password | str | Wenn das Arbeitsblatt bereits durch ein Passwort geschützt ist, geben Sie bitte das alte Passwort ein.<br/> Andernfalls können Sie für diesen Parameter einen Nullwert oder eine leere Zeichenfolge festlegen.|
###  Bemerkungen

Diese Methode kann protect Arbeitsblätter in allen Versionen von Excel-Dateien verwenden.
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
