---
title: get_default_sheet_name metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 80
url: /sv/aspose.cells/settableglobalizationsettings/get_default_sheet_name/
is_root: false
---
##  get_default_sheet_name(self) {#}
Hämtar standardnamnet för att lägga till kalkylblad automatiskt.
Standardinställningen är "Ark".


###  Returnerar

standardnamnet för ark för att lägga till kalkylblad automatiskt


```python

def get_default_sheet_name(self):
    ...
```


###  Anmärkningar

Den automatiskt tillagda (t.ex. av [`WorksheetCollection.add`](/cells/python-net/sv/aspose.cells/worksheetcollection/add))
Arkets namn kommer att vara det angivna namnet plus sekvensnumret.
 Till exempel, för Tyskland kanske användaren vill att bladnamnet ska vara "Tabellenblatt2" istället för "Sheet2".
Sedan kan användaren implementera den här metoden för att returnera "Tabellenblatt".


###  Se även
* modul [`aspose.cells`](../../)
* klass [`SettableGlobalizationSettings`](/cells/python-net/sv/aspose.cells/settableglobalizationsettings)
