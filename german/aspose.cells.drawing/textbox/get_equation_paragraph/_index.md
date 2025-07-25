---
title: get_equation_paragraph Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 110
url: /de/aspose.cells.drawing/textbox/get_equation_paragraph/
is_root: false
---
##  get_equation_paragraph(self) {#}
Ruft den ersten mathematischen Absatz aus der TextBody-Eigenschaft des TextBox-Objekts ab.


###  Kehrt zurück

Wenn ein mathematischer Absatz vorhanden ist, wird der erste zurückgegeben, andernfalls wird null zurückgegeben.


```python

def get_equation_paragraph(self):
    ...
```




##  get_equation_paragraph(self, index) {#int}
Holen Sie sich den angegebenen mathematischen Absatz aus der TextBody-Eigenschaft des TextBox-Objekts.
Beachten:
(1) Gibt NULL zurück, wenn der Index außerhalb der Grenzen liegt oder nicht gefunden wurde.
(2) Gibt auch NULL zurück, wenn die angegebene Indexposition kein mathematischer Absatz ist.


###  Kehrt zurück

Gibt den durch den Index angegebenen mathematischen Absatz zurück.


```python

def get_equation_paragraph(self, index):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| index | int | Der Positionsindex des Mathematikabsatzes, beginnend bei 0.|



###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`TextBox`](/cells/python-net/de/aspose.cells.drawing/textbox)
