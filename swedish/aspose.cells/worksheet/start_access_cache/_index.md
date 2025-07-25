---
title: start_access_cache metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 320
url: /sv/aspose.cells/worksheet/start_access_cache/
is_root: false
---
##  start_access_cache(self, opts) {#aspose.cells.AccessCacheOptions}
Startar sessionen som använder cacheminnen för att komma åt data i det här kalkylbladet.



```python

def start_access_cache(self, opts):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| opts | [`AccessCacheOptions`](/cells/python-net/sv/aspose.cells/accesscacheoptions) | alternativ för dataåtkomst|
###  Anmärkningar

Efter att åtkomsten till data har avslutats bör [`Worksheet.close_access_cache`](/cells/python-net/sv/aspose.cells/worksheet/close_access_cache)
anropas med samma alternativ för att rensa alla cacheminnen och återställa normalt åtkomstläge.


###  Se även
* modul [`aspose.cells`](../../)
* klass [`Worksheet`](/cells/python-net/sv/aspose.cells/worksheet)
