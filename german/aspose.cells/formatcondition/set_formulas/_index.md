---
title: set_formulas Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 60
url: /de/aspose.cells/formatcondition/set_formulas/
is_root: false
---
##  set_formulas(self, formula1, formula2, is_r1c1, is_local) {#str-str-bool-bool}
Legt den Wert oder Ausdruck fest, der mit dieser Formatbedingung verknüpft ist.



```python

def set_formulas(self, formula1, formula2, is_r1c1, is_local):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| formula1 | str | Der mit dieser Formatbedingung verknüpfte Wert oder Ausdruck.<br/>Wenn der Eingabewert mit '=' beginnt, wird er als Formel verwendet. Andernfalls wird er als einfacher Wert (Text, Zahl, Bool) verwendet.<br/> Für Textwerte, die mit „=“ beginnen, kann der Benutzer sie als Formel im Format „=\“=…\““ eingeben.|
| formula2 | str | Der mit dieser Formatbedingung verknüpfte Wert oder Ausdruck. Das Eingabeformat ist dasselbe wie bei Formel1|
| is_r1c1 | bool | Ob es sich bei der Formel um die R1C1-Formel handelt.|
| is_local | bool | Ob die Formel lokal formatiert ist.|



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`FormatCondition`](/cells/python-net/de/aspose.cells/formatcondition)
