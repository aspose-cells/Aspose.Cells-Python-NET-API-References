---
title: set_formulas metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 60
url: /sv/aspose.cells/formatcondition/set_formulas/
is_root: false
---
##  set_formulas(formula1, formula2, is_r1c1, is_local) {#str-str-bool-bool}
Ställer in värdet eller uttrycket som är associerat med detta formatvillkor.



```python
def set_formulas(self, formula1, formula2, is_r1c1, is_local):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| formula1 | str | Värdet eller uttrycket som är associerat med detta formatvillkor.<br/>Om inmatningsvärdet börjar med '=' kommer det att tas som formel. Annars kommer det att tas som vanligt värde (text, nummer, bool).<br/> För textvärde som börjar med '=' kan användaren mata in det som formel i formatet: "=\"=...\"".|
| formula2 | str | Värdet eller uttrycket som är associerat med detta formatvillkor. Inmatningsformatet är detsamma som formel1|
| is_r1c1 | bool | Om formeln är R1C1-formel.|
| is_local | bool | Om formeln är språkformaterad.|



###  Se även
* modul [aspose.cells](../../)
* klass [FormatCondition](/cells/python-net/sv/aspose.cells/formatcondition)
