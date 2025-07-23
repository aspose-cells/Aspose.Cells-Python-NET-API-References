---
title: get_style_in_pool metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 200
url: /sv/aspose.cells/workbook/get_style_in_pool/
is_root: false
---
##  get_style_in_pool(self, index) {#int}
Hämtar stilen i stilpoolen.
Alla stilar i arbetsboken samlas i en pool.
Det finns bara ett enkelt referensindex i cellerna.


###  Returnerar

Stilen i poolen motsvarar angivet index, kan vara null.


```python

def get_style_in_pool(self, index):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| index | int | Indexet.|
###  Anmärkningar

Om den returnerade stilen ändras, kommer stilen för alla celler (som refererar till denna stil) att ändras.


###  Se även

* modul [`aspose.cells`](../../)
* klass [`Workbook`](/cells/python-net/sv/aspose.cells/workbook)
