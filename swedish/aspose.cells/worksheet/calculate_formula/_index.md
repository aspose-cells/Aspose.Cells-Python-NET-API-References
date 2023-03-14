---
title: calculate_formula metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 80
url: /sv/aspose.cells/worksheet/calculate_formula/
is_root: false
---
##  calculate_formula(formula) {#str}
Beräknar en formel.


###  Returnerar

Beräknat formelresultat.


```python
def calculate_formula(self, formula):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| formula | str | Formel som ska beräknas.|


##  calculate_formula(formula, opts) {#str-CalculationOptions}
Beräknar en formel.


###  Returnerar

Beräknat formelresultat.


```python
def calculate_formula(self, formula, opts):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| formula | str | Formel som ska beräknas.|
| opts | [CalculationOptions](/cells/python-net/sv/aspose.cells/calculationoptions) | Alternativ för att beräkna formel|


##  calculate_formula(options, recursive) {#CalculationOptions-bool}
Beräknar alla formler i detta kalkylblad.



```python
def calculate_formula(self, options, recursive):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| options | [CalculationOptions](/cells/python-net/sv/aspose.cells/calculationoptions) | Alternativ för beräkning|
| recursive | bool | Sant betyder att om kalkylbladets celler beror på cellerna i andra kalkylblad,<br/>de beroende cellerna i andra kalkylblad kommer också att beräknas.<br/> Falskt betyder att alla formler i kalkylbladet har beräknats och att värdena är rätt.|


##  calculate_formula(recursive, ignore_error, custom_function) {#bool-bool-ICustomFunction}
Beräknar alla formler i detta kalkylblad.



```python
def calculate_formula(self, recursive, ignore_error, custom_function):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| recursive | bool | Sant betyder att om kalkylbladets celler beror på cellerna i andra kalkylblad,<br/>de beroende cellerna i andra kalkylblad kommer också att beräknas.<br/> Falskt betyder att alla formler i kalkylbladet har beräknats och att värdena är rätt.|
| ignore_error | bool | Indikerar om dölj felet i beräkningsformler.<br/> Felet kan vara en funktion som inte stöds, externa länkar, etc.|
| custom_function | [ICustomFunction](/cells/python-net/sv/aspose.cells/icustomfunction) | Den anpassade formelberäkningen fungerar för att utöka beräkningsmotorn.|
###  Anmärkningar

OBS: Denna medlem är nu föråldrad. Istället,
använd metoden CalculateFormula(CalculationOptions, bool).
 Denna metod kommer att tas bort 12 månader senare sedan augusti 2020.
Aspose ber om ursäkt för eventuella besvär du kan ha upplevt.


###  Se även
* modul [aspose.cells](../../)
* klass [Worksheet](/cells/python-net/sv/aspose.cells/worksheet)
