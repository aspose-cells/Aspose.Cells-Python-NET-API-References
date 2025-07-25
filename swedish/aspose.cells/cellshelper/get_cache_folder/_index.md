---
title: get_cache_folder metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 100
url: /sv/aspose.cells/cellshelper/get_cache_folder/
is_root: false
---
##  get_cache_folder() {#}
Hämtar mappen för tillfälliga filer som kan användas som datacache.


###  Returnerar

Mapp för cachefiler som har angetts.
Om det inte har angetts returneras null
och systemets tillfälliga sökväg kommer att användas vid behov.


```python

@staticmethod
def get_cache_folder():
    ...
```


###  Anmärkningar

Cachefiler används generellt för vissa funktioner för att beakta minnesprestanda,
som att spara stora datamängder till en xls-fil,
eller använda minnesläge med filcache för cellmodellen.


###  Se även
* modul [`aspose.cells`](../../)
* klass [`CellsHelper`](/cells/python-net/sv/aspose.cells/cellshelper)
