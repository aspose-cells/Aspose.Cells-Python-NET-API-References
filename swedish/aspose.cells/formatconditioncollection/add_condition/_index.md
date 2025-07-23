---
title: add_condition metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 40
url: /sv/aspose.cells/formatconditioncollection/add_condition/
is_root: false
---
##  add_condition(self, type) {#aspose.cells.FormatConditionType}
Lägg till ett formatvillkor.


###  Returnerar

Formateringsvillkorsobjektindex;


```python

def add_condition(self, type):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| type | [`FormatConditionType`](/cells/python-net/sv/aspose.cells/formatconditiontype) | Formatvillkorstyp.|


##  add_condition(self, type, operator_type, formula1, formula2) {#aspose.cells.FormatConditionType-aspose.cells.OperatorType-str-str}
Lägger till ett formateringsvillkor.


###  Returnerar

Formateringsvillkorsobjektindex;


```python

def add_condition(self, type, operator_type, formula1, formula2):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| type | [`FormatConditionType`](/cells/python-net/sv/aspose.cells/formatconditiontype) | Typ av formatvillkor.|
| operator_type | [`OperatorType`](/cells/python-net/sv/aspose.cells/operatortype) | Operatörstypen|
| formula1 | str | Värdet eller uttrycket som är associerat med villkorsstyrd formatering.<br/>Om inmatningsvärdet börjar med '=', kommer det att tas som formel.<br/>Annars tas det som vanligt värde (text, tal, bool).<br/> För textvärden som börjar med '=' kan användaren mata in det som en formel i formatet: "=\"=...\".|
| formula2 | str | Värdet eller uttrycket som är associerat med villkorsstyrd formatering.<br/> Inmatningsformatet är detsamma som i formel 1|



###  Se även
* modul [`aspose.cells`](../../)
* klass [`FormatConditionCollection`](/cells/python-net/sv/aspose.cells/formatconditioncollection)
