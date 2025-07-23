---
title: get_style_in_pool Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 200
url: /de/aspose.cells/workbook/get_style_in_pool/
is_root: false
---
##  get_style_in_pool(self, index) {#int}
Ruft den Stil im Stilpool ab.
Alle Stile in der Arbeitsmappe werden in einem Pool gesammelt.
In den Zellen befindet sich lediglich ein einfacher Referenzindex.


###  Kehrt zurück

Der Stil im Pool entspricht dem angegebenen Index und kann null sein.


```python

def get_style_in_pool(self, index):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| index | int | Der Index.|
###  Bemerkungen

Wenn der zurückgegebene Stil geändert wird, wird der Stil aller Zellen (die auf diesen Stil verweisen) geändert.


###  Siehe auch

* Modul [`aspose.cells`](../../)
* Klasse [`Workbook`](/cells/python-net/de/aspose.cells/workbook)
