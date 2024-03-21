---
title: check_excel_restriction Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 90
url: /de/aspose.cells/ebookloadoptions/check_excel_restriction/
is_root: false
---
##  check_excel_restriction Eigentum

Ob die Einschränkung der Excel-Datei überprüft wird, wenn der Benutzer zellenbezogene Objekte ändert.
Excel erlaubt beispielsweise keine Eingabe von Zeichenfolgenwerten, die länger als 32 KB sind.
Wenn Sie einen Wert eingeben, der länger als 32 KB ist, z. B. Cell.PutValue(string) und diese Eigenschaft wahr ist, erhalten Sie eine Ausnahme.
Wenn diese Eigenschaft falsch ist, akzeptieren wir Ihren Eingabezeichenfolgenwert später als Zellwert
Sie können den vollständigen String-Wert für andere Dateiformate wie CSV ausgeben.
Wenn Sie jedoch einen Wert festgelegt haben, der für das Excel-Dateiformat ungültig ist,
Sie sollten die Arbeitsmappe später nicht im Excel-Dateiformat speichern. Andernfalls kann es zu einem unerwarteten Fehler in der generierten Excel-Datei kommen.
###  Definition:
```python
@property
def check_excel_restriction(self):
    ...
@check_excel_restriction.setter
def check_excel_restriction(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`EbookLoadOptions`](/cells/python-net/de/aspose.cells/ebookloadoptions)
