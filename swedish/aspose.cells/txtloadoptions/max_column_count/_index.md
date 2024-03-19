---
title: max_column_count fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 290
url: /sv/aspose.cells/txtloadoptions/max_column_count/
is_root: false
---
##  max_column_count fastighet

Det maximala antalet kolumner som ska importeras för ett ark.

###  Anmärkningar

De kolumner som överskrider denna gräns kommer att ignoreras
eller utökas till nästa blad enligt [`TxtLoadOptions.extend_to_next_sheet`](/cells/python-net/sv/aspose.cells/txtloadoptions#extend_to_next_sheet).
Detta antal inkluderar rubrikkolumnerna ([`TxtLoadOptions.header_columns_count`](/cells/python-net/sv/aspose.cells/txtloadoptions#header_columns_count)).
Det maximala värdet för den är kolumngränsen för motsvarande filformat, till exempel för xlsx-filen it 16384.
Om den här egenskapen inte har specificerats eller det angivna värdet inte är positivt, kommer maxgränsen att användas också.
###  Definition:
```python
@property
def max_column_count(self):
    ...
@max_column_count.setter
def max_column_count(self, value):
    ...
```

###  Se även
* modul [`aspose.cells`](../../)
* klass [`TxtLoadOptions`](/cells/python-net/sv/aspose.cells/txtloadoptions)
