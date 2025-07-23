---
title: check_excel_restriction Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 70
url: /de/aspose.cells.loading/difloadoptions/check_excel_restriction/
is_root: false
---
##  check_excel_restriction Eigentum

Ob die Einschränkung der Excel-Datei überprüft wird, wenn der Benutzer zellenbezogene Objekte ändert.
Beispielsweise erlaubt Excel nicht die Eingabe von Zeichenfolgenwerten, die länger als 32 KB sind.
Wenn Sie einen Wert eingeben, der länger als 32 KB ist, z. B. Cell.PutValue(string), und diese Eigenschaft wahr ist, erhalten Sie eine Ausnahme.
Wenn diese Eigenschaft falsch ist, akzeptieren wir den eingegebenen Stringwert als Zellenwert, sodass später
Sie können den vollständigen Zeichenfolgenwert für andere Dateiformate wie CSV ausgeben.
Wenn Sie jedoch einen Wert festgelegt haben, der für das Excel-Dateiformat ungültig ist,
Sie sollten die Arbeitsmappe später nicht im Excel-Dateiformat speichern. Andernfalls kann es zu unerwarteten Fehlern bei der generierten Excel-Datei kommen.
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
* Modul [`aspose.cells.loading`](../../)
* Klasse [`DifLoadOptions`](/cells/python-net/de/aspose.cells.loading/difloadoptions)
