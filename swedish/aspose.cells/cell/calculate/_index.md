---
title: calculate metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 20
url: /sv/aspose.cells/cell/calculate/
is_root: false
---
##  calculate(options) {#CalculationOptions}
Beräknar cellens formel.



```python
def calculate(self, options):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| options | [CalculationOptions](/cells/python-net/sv/aspose.cells/calculationoptions) | Alternativ för beräkning|


##  calculate(ignore_error, custom_function) {#bool-ICustomFunction}
Beräknar cellens formel.



```python
def calculate(self, ignore_error, custom_function):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| ignore_error | bool | Indikerar om dölj felet i beräkningsformler.<br/> Felet kan vara en funktion som inte stöds, externa länkar, etc.|
| custom_function | [ICustomFunction](/cells/python-net/sv/aspose.cells/icustomfunction) | Den anpassade formelberäkningen fungerar för att utöka beräkningsmotorn.|
###  Anmärkningar

OBS: Denna medlem är nu föråldrad. Istället,
använd metoden Calculate(CalculationOptions).
 Denna metod kommer att tas bort 12 månader senare sedan augusti 2020.
Aspose ber om ursäkt för eventuella besvär du kan ha upplevt.


###  Se även
* modul [aspose.cells](../../)
* klass [Cell](/cells/python-net/sv/aspose.cells/cell)
