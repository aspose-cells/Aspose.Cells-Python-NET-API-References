---
title: get_leafs metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 160
url: /sv/aspose.cells/cell/get_leafs/
is_root: false
---
##  get_leafs(self) {#}
Hämta alla celler som refererar direkt till den här cellen och behöver uppdateras när cellen ändras.


###  Returnerar

Uppräknare för att räkna upp alla anhöriga (Cell)


```python

def get_leafs(self):
    ...
```


###  Anmärkningar

OBS: Den här klassen är nu föråldrad. Istället,
Använd Cell.GetDependentsInCalculation(bool) för att hämta alla beroenden i beräkningskedjan.
Den här egenskapen kommer att tas bort 12 månader senare från och med maj 2022.
Aspose ber om ursäkt för eventuella besvär du kan ha upplevt.

##  get_leafs(self, recursive) {#bool}
Hämta alla celler som kommer att uppdateras när den här cellen ändras.


###  Returnerar

Uppräknare för att räkna upp alla anhöriga (Cell)


```python

def get_leafs(self, recursive):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| recursive | bool | Om returnerar de löv som inte refererar direkt till den här cellen<br/> men hänvisning till andra blad i denna cell|
###  Anmärkningar

OBS: Den här klassen är nu föråldrad. Istället,
Använd Cell.GetDependentsInCalculation(bool) för att hämta alla beroenden i beräkningskedjan.
Den här egenskapen kommer att tas bort 12 månader senare från och med maj 2022.
Aspose ber om ursäkt för eventuella besvär du kan ha upplevt.


###  Se även
* modul [`aspose.cells`](../../)
* klass [`Cell`](/cells/python-net/sv/aspose.cells/cell)
