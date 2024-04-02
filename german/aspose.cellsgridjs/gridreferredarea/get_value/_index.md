---
title: get_value Methode
second_title: Aspose.Cells.GridJs for Python via .NET API Referenzen
description:
type: docs
weight: 20
url: /de/aspose.cellsgridjs/gridreferredarea/get_value/
is_root: false
---
##  get_value {#int-int}

Ruft den Zellenwert mit dem angegebenen Offset vom oberen linken Rand dieses Bereichs ab.


###  Kehrt zurück


„#REF!“ wenn dieser Bereich ungültig ist;
„#N/A“, falls angegeben, Offset außerhalb dieses Bereichs;
Andernfalls wird der Zellenwert an der angegebenen Position zurückgegeben.


```python
def get_value(self, row_offset, col_offset):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| row_offset | int | Zeilenversatz von der Startzeile dieses Bereichs|
| col_offset | int | Spaltenversatz von der Startzeile dieses Bereichs|



###  Siehe auch
* Modul [`aspose.cellsgridjs`](../../)
* Klasse [`GridReferredArea`](/cells/python-net/de/aspose.cellsgridjs/gridreferredarea)
