---
title: multi_thread_reading Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1190
url: /de/aspose.cells/cells/multi_thread_reading/
is_root: false
---
##  multi_thread_reading Eigentum

Ruft ab oder legt fest, ob das Zellendatenmodell Multi-Thread-Lesen unterstützen soll.
Der Standardwert dieser Eigenschaft ist „false“.

###  Bemerkungen

Wenn es mehrere Threads gibt, die Row/Cell-Objekte in dieser Sammlung gleichzeitig lesen,
Diese Eigenschaft sollte auf „true“ gesetzt werden, andernfalls kann es zu unerwarteten Ergebnissen kommen.
Durch die Unterstützung des Multi-Thread-Lesens kann die Leistung beim Zugriff auf Row/Cell-Objekte aus dieser Sammlung beeinträchtigt werden.
Bitte beachten Sie, dass einige Funktionen das Multi-Thread-Lesen nicht unterstützen.
wie Formatierungswerte (von [`Cell.string_value`](/cells/python-net/de/aspose.cells/cell#string_value), [`Cell.display_string_value`](/cells/python-net/de/aspose.cells/cell#display_string_value) usw.).
Auch wenn diese Eigenschaft auf „true“ gesetzt ist, können diese APIs beim Multi-Thread-Lesen zu unerwarteten Ergebnissen führen.
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
