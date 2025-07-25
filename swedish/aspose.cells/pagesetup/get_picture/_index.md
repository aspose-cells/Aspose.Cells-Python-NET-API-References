---
title: get_picture metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 120
url: /sv/aspose.cells/pagesetup/get_picture/
is_root: false
---
##  get_picture(self, is_header, section) {#bool-int}
Hämtar objektet [`Picture`](/cells/python-net/sv/aspose.cells.drawing/picture) för sidhuvudet/sidfoten.


###  Returnerar

Returnerar [`Picture`](/cells/python-net/sv/aspose.cells.drawing/picture)-objektet.
Returnerar null om det inte finns någon bild.


```python

def get_picture(self, is_header, section):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| is_header | bool | Anger om den finns i sidhuvudet eller sidfoten.|
| section | int |0: Vänster sektion, 1: Mittsektion, 2: Höger sektion.|


##  get_picture(self, is_first, is_even, is_header, section) {#bool-bool-bool-int}
Hämtar objektet [`Picture`](/cells/python-net/sv/aspose.cells.drawing/picture) för sidhuvudet/sidfoten.


###  Returnerar

Returnerar [`Picture`](/cells/python-net/sv/aspose.cells.drawing/picture)-objektet.


```python

def get_picture(self, is_first, is_even, is_header, section):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| is_first | bool | Anger om bilden av första sidans sidhuvud/sidfot hämtas.|
| is_even | bool | Anger om bilden av sidhuvud/sidfot på jämna sidor visas.|
| is_header | bool | Anger om bilden av sidhuvud/sidfot hämtas.|
| section | int |0: Vänster sektion, 1: Mittsektion, 2: Höger sektion.|



###  Se även
* modul [`aspose.cells`](../../)
* klass [`PageSetup`](/cells/python-net/sv/aspose.cells/pagesetup)
* klass [`Picture`](/cells/python-net/sv/aspose.cells.drawing/picture)
