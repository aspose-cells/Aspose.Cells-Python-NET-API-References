---
title: get_array_mode_parameters metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 20
url: /sv/aspose.cells/customfunctiondefinition/get_array_mode_parameters/
is_root: false
---
##  get_array_mode_parameters(self, function_name) {#str}
Hämtar indexen för parametrar för givna anpassade funktioner som behöver beräknas i arrayläge.


###  Returnerar

Index för de parametrar som behöver beräknas i arrayläge för en given anpassad funktion.
Standardvärdet är null, det finns ingen parameter som behöver beräknas i arrayläge för den anpassade funktionen.


```python

def get_array_mode_parameters(self, function_name):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| function_name | str | Namn på den anpassade funktionen.|
###  Anmärkningar

För ett uttryck som behöver beräknas, med A:A+B:B som exempel:
Generellt sett i värdeläge beräknas det till ett enda värde enligt den aktuella cellbasen.
Men i arrayläge kommer alla värden för A1+B1, A2+B2, A3+B3,... att beräknas och användas för beräkningen.


###  Se även
* modul [`aspose.cells`](../../)
* klass [`CustomFunctionDefinition`](/cells/python-net/sv/aspose.cells/customfunctiondefinition)
