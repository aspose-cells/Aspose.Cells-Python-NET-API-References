---
title: preferred_parsers Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 330
url: /de/aspose.cells/txtloadoptions/preferred_parsers/
is_root: false
---
##  preferred_parsers Eigentum

Ruft bevorzugte Werteparser zum Laden von Textdateien ab und legt sie fest.

###  Bemerkungen

parsers[0] ist der Parser, der für die erste Spalte in der Textvorlagendatei verwendet wird.
parsers[1] ist der Parser, der für die zweite Spalte verwendet wird, ... usw.
Der letzte Wert (parsers[parsers.length-1]) wird für alle anderen Spalten ab parsers.length-1 verwendet.
Wenn ein Element null ist, wird die entsprechende Spalte vom Standardparser Aspose.Cells analysiert.
###  Definition:
```python
@property
def preferred_parsers(self):
    ...
@preferred_parsers.setter
def preferred_parsers(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`TxtLoadOptions`](/cells/python-net/de/aspose.cells/txtloadoptions)
