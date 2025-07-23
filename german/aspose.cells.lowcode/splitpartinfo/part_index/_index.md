---
title: part_index Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 30
url: /de/aspose.cells.lowcode/splitpartinfo/part_index/
is_root: false
---
##  part_index Eigentum

Index des aktuellen Teils in der Sequenz (basierend auf 0).
-1 bedeutet, dass es keine Mehrfachteile gibt und das Ergebnis daher einzeln ist.

###  Bemerkungen

Wenn mehrere Blätter verarbeitet werden müssen und jedes Blatt verarbeitet (aufgeteilt) wird
separat, der Teileindex beginnt für jedes Blatt immer bei 0.
Wenn Sie beispielsweise eine Arbeitsmappe in Bilder konvertieren,
es stellt den Ausgabeseitenindex des aktuell verarbeiteten Blattes dar.
Und -1 bedeutet, dass für das aktuelle Blatt nur eine Seite vorhanden ist.
###  Definition:
```python
@property
def part_index(self):
    ...
```

###  Siehe auch
* Modul [`aspose.cells.lowcode`](../../)
* Klasse [`SplitPartInfo`](/cells/python-net/de/aspose.cells.lowcode/splitpartinfo)
