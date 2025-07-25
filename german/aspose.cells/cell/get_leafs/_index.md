---
title: get_leafs Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 160
url: /de/aspose.cells/cell/get_leafs/
is_root: false
---
##  get_leafs(self) {#}
Rufen Sie alle Zellen ab, die direkt auf diese Zelle verweisen und aktualisiert werden müssen, wenn diese Zelle geändert wird.


###  Kehrt zurück

Enumerator zum Aufzählen aller Angehörigen (Cell)


```python

def get_leafs(self):
    ...
```


###  Bemerkungen

HINWEIS: Diese Klasse ist mittlerweile veraltet. Stattdessen
Bitte verwenden Sie Cell.GetDependentsInCalculation(bool), um alle abhängigen Objekte in der Berechnungskette abzurufen.
Diese Eigenschaft wird 12 Monate später (ab Mai 2022) entfernt.
Aspose entschuldigt sich für etwaige Unannehmlichkeiten, die Ihnen möglicherweise entstanden sind.

##  get_leafs(self, recursive) {#bool}
Ruft alle Zellen ab, die aktualisiert werden, wenn diese Zelle geändert wird.


###  Kehrt zurück

Enumerator zum Aufzählen aller Angehörigen (Cell)


```python

def get_leafs(self, recursive):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| recursive | bool | Gibt die Blätter zurück, die nicht direkt auf diese Zelle verweisen<br/> aber Verweis auf andere Blätter dieser Zelle|
###  Bemerkungen

HINWEIS: Diese Klasse ist mittlerweile veraltet. Stattdessen
Bitte verwenden Sie Cell.GetDependentsInCalculation(bool), um alle abhängigen Objekte in der Berechnungskette abzurufen.
Diese Eigenschaft wird 12 Monate später (ab Mai 2022) entfernt.
Aspose entschuldigt sich für etwaige Unannehmlichkeiten, die Ihnen möglicherweise entstanden sind.


###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Cell`](/cells/python-net/de/aspose.cells/cell)
