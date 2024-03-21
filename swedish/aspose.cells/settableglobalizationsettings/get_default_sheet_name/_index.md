---
title: get_default_sheet_name metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 80
url: /sv/aspose.cells/settableglobalizationsettings/get_default_sheet_name/
is_root: false
---
##  get_default_sheet_name {#}
Hämtar standardarknamnet för att lägga till kalkylblad automatiskt.
Standard är "Sheet".


###  Returnerar

standardarknamnet för att lägga till kalkylblad automatiskt


```python
def get_default_sheet_name(self):
    ...
```


###  Anmärkningar

Den automatiskt tillagda (som av [`WorksheetCollection.add`](/cells/python-net/sv/aspose.cells/worksheetcollection/add))
arkets namn kommer att vara det angivna namnet plus sekvensnummer.
 Till exempel, för Tyskland kanske användaren vill att arknamnet ska vara "Tabellenblatt2" istället för "Sheet2".
Då kan användaren implementera denna metod för att returnera "Tabellenblatt".


###  Se även
* modul [`aspose.cells`](../../)
* klass [`SettableGlobalizationSettings`](/cells/python-net/sv/aspose.cells/settableglobalizationsettings)
