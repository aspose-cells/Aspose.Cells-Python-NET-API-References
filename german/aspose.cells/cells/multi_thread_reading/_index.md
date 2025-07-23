---
title: multi_thread_reading Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1220
url: /de/aspose.cells/cells/multi_thread_reading/
is_root: false
---
##  multi_thread_reading Eigentum

Ruft ab oder legt fest, ob das Datenmodell der Zelle das Lesen mehrerer Threads unterstützen soll.
Der Standardwert dieser Eigenschaft ist „false“.

###  Bemerkungen

Wenn mehrere Threads gleichzeitig Row/Cell-Objekte in dieser Sammlung lesen,
Diese Eigenschaft sollte auf „true“ gesetzt werden, da es sonst zu unerwarteten Ergebnissen kommen kann.
Die Unterstützung des Multi-Thread-Lesens kann die Leistung beim Zugriff auf Row/Cell-Objekte aus dieser Sammlung beeinträchtigen.
Bitte beachten Sie, dass einige Funktionen das Lesen mehrerer Threads nicht unterstützen.
wie z. B. das Formatieren von Werten (durch [`Cell.string_value`](/cells/python-net/de/aspose.cells/cell#string_value), [`Cell.display_string_value`](/cells/python-net/de/aspose.cells/cell#display_string_value) usw.).
Selbst wenn diese Eigenschaft auf „true“ gesetzt ist, können diese APIs beim Multithread-Lesen dennoch unerwartete Ergebnisse liefern.
###  Definition:
```python
@property
def multi_thread_reading(self):
    ...
@multi_thread_reading.setter
def multi_thread_reading(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Cells`](/cells/python-net/de/aspose.cells/cells)
