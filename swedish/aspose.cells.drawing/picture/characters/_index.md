---
title: characters metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 50
url: /sv/aspose.cells.drawing/picture/characters/
is_root: false
---
##  characters(self, start_index, length) {#int-int}
Returnerar ett Characters-objekt som representerar ett intervall på characters i texten.


###  Returnerar

Teckenobjekt.


```python

def characters(self, start_index, length):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| start_index | int | Indexet för början av tecknet.|
| length | int | Antalet tecken.|
###  Anmärkningar

Den här metoden fungerar bara på former med titel.
###  Exempel


```python

fontSetting = shape.characters(0, 4)

```



###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`Picture`](/cells/python-net/sv/aspose.cells.drawing/picture)
