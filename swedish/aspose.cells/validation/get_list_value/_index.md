---
title: get_list_value metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 70
url: /sv/aspose.cells/validation/get_list_value/
is_root: false
---
##  get_list_value(self, row, column) {#int-int}
Hämta värdet för listan för valideringen för den angivna cellen.


###  Returnerar

Värdet som ska producera listan för denna validering för den angivna cellen.
Om listan refererar till ett intervall, kommer det returnerade värdet att vara ett [`ReferredArea`](/cells/python-net/sv/aspose.cells/referredarea)-objekt;
Annars kan det returnerade värdet vara null, object[] eller simple object.


```python

def get_list_value(self, row, column):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| row | int | Radindexet.|
| column | int | Kolumnindexet.|
###  Anmärkningar

Endast för validering vars typ är List och har tillämpats på en given cell,
annars returneras null.


###  Se även
* modul [`aspose.cells`](../../)
* klass [`ReferredArea`](/cells/python-net/sv/aspose.cells/referredarea)
* klass [`Validation`](/cells/python-net/sv/aspose.cells/validation)
