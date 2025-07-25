---
title: preferred_parsers fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 330
url: /sv/aspose.cells/txtloadoptions/preferred_parsers/
is_root: false
---
##  preferred_parsers fastighet

Hämtar och ställer in föredragna värdeparsers för att läsa in textfiler.

###  Anmärkningar

parsers[0] är den parser som kommer att användas för den första kolumnen i textmallfilen,
parsers[1] är den parser som kommer att användas för den andra kolumnen, ...etc.
Den sista (parsers[parsers.length-1]) kommer att användas för alla andra kolumner med början från parsers.length-1.
Om ett objekt är null, kommer motsvarande kolumn att tolkas av standardtolkaren Aspose.Cells.
###  Definition:
```python
@property
def preferred_parsers(self):
    ...
@preferred_parsers.setter
def preferred_parsers(self, value):
    ...
```

###  Se även
* modul [`aspose.cells`](../../)
* klass [`TxtLoadOptions`](/cells/python-net/sv/aspose.cells/txtloadoptions)
