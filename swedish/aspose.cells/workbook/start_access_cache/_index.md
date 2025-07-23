---
title: start_access_cache metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 400
url: /sv/aspose.cells/workbook/start_access_cache/
is_root: false
---
##  start_access_cache(self, opts) {#aspose.cells.AccessCacheOptions}
Startar sessionen som använder cacheminnen för att komma åt data.



```python

def start_access_cache(self, opts):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| opts | [`AccessCacheOptions`](/cells/python-net/sv/aspose.cells/accesscacheoptions) | alternativ för dataåtkomst|
###  Anmärkningar

Om cachen för specificerad dataåtkomst kräver att vissa datamodeller i kalkylbladet är "skrivskyddade",
då kommer motsvarande datamodeller i varje kalkylblad i den här arbetsboken att tas som "skrivskyddade"
och användaren bör inte ändra någon av dem.


Efter att åtkomsten till data har avslutats bör [`Workbook.close_access_cache`](/cells/python-net/sv/aspose.cells/workbook/close_access_cache)
anropas med samma alternativ för att rensa alla cacheminnen och återställa normalt åtkomstläge.


###  Se även
* modul [`aspose.cells`](../../)
* klass [`Workbook`](/cells/python-net/sv/aspose.cells/workbook)
