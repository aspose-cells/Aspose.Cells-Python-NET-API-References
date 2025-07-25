---
title: add_condition Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 40
url: /de/aspose.cells/formatconditioncollection/add_condition/
is_root: false
---
##  add_condition(self, type) {#aspose.cells.FormatConditionType}
Fügen Sie eine Formatbedingung hinzu.


###  Kehrt zurück

Formatierungsbedingungsobjektindex;


```python

def add_condition(self, type):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| type | [`FormatConditionType`](/cells/python-net/de/aspose.cells/formatconditiontype) | Formatieren Sie den Bedingungstyp.|


##  add_condition(self, type, operator_type, formula1, formula2) {#aspose.cells.FormatConditionType-aspose.cells.OperatorType-str-str}
Fügt eine Formatierungsbedingung hinzu.


###  Kehrt zurück

Formatierungsbedingungsobjektindex;


```python

def add_condition(self, type, operator_type, formula1, formula2):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| type | [`FormatConditionType`](/cells/python-net/de/aspose.cells/formatconditiontype) | Der Typ der Formatbedingung.|
| operator_type | [`OperatorType`](/cells/python-net/de/aspose.cells/operatortype) | Der Operatortyp|
| formula1 | str | Der mit der bedingten Formatierung verknüpfte Wert oder Ausdruck.<br/>Beginnt der Eingabewert mit „=“, wird er als Formel verwendet.<br/>Andernfalls wird es als einfacher Wert (Text, Zahl, Bool) übernommen.<br/> Für Textwerte, die mit „=“ beginnen, kann der Benutzer sie als Formel im Format „=\“=…\““ eingeben.|
| formula2 | str | Der mit der bedingten Formatierung verknüpfte Wert oder Ausdruck.<br/> Das Eingabeformat ist dasselbe wie bei Formel 1|



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`FormatConditionCollection`](/cells/python-net/de/aspose.cells/formatconditioncollection)
