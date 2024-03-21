---
title: max_row_count fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 300
url: /sv/aspose.cells/txtloadoptions/max_row_count/
is_root: false
---
##  max_row_count fastighet

Det maximala antalet rader som ska importeras för ett ark.

###  Anmärkningar

De rader som överskrider denna gräns kommer att ignoreras
eller utökas till nästa blad enligt [`TxtLoadOptions.extend_to_next_sheet`](/cells/python-net/sv/aspose.cells/txtloadoptions#extend_to_next_sheet).
Detta antal inkluderar rubrikraderna ([`TxtLoadOptions.header_rows_count`](/cells/python-net/sv/aspose.cells/txtloadoptions#header_rows_count)).
Det högsta tillåtna värdet för den är radgränsen för motsvarande filformat, till exempel för xlsx-filen it 1048576.
Om den här egenskapen inte har specificerats eller det angivna värdet inte är positivt, kommer maxgränsen att användas också.
###  Definition:
```python
@property
def max_row_count(self):
    ...
@max_row_count.setter
def max_row_count(self, value):
    ...
```

###  Se även
* modul [`aspose.cells`](../../)
* klass [`TxtLoadOptions`](/cells/python-net/sv/aspose.cells/txtloadoptions)
