---
title: get_values Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 30
url: /de/aspose.cells/referredarea/get_values/
is_root: false
---
##  get_values(self) {#}
Ruft Zellwerte in diesem Bereich ab.


###  Kehrt zurück

Wenn dieser Bereich ungültig ist, wird „#REF!“ angezeigt. Wird zurückgegeben;
Wenn es sich bei diesem Bereich um eine einzelne Zelle handelt, wird das Zellenwertobjekt zurückgegeben.
Andernfalls geben Sie ein 2D-Array für alle Werte in diesem Bereich zurück.


```python

def get_values(self):
    ...
```




##  get_values(self, calculate_formulas) {#bool}
Ruft Zellwerte in diesem Bereich ab.


###  Kehrt zurück

Wenn dieser Bereich ungültig ist, wird „#REF!“ angezeigt. Wird zurückgegeben;
Wenn es sich bei diesem Bereich um eine einzelne Zelle handelt, wird das Zellenwertobjekt zurückgegeben.
Andernfalls geben Sie ein 2D-Array für alle Werte in diesem Bereich zurück.


```python

def get_values(self, calculate_formulas):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| calculate_formulas | bool | Wenn in diesem Bereich einige Formeln nicht berechnet wurden,<br/> Dieses Flag gibt an, ob diese Formeln rekursiv berechnet werden sollen|



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`ReferredArea`](/cells/python-net/de/aspose.cells/referredarea)
