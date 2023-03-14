---
title: index_of metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 40
url: /sv/aspose.cells.properties/builtindocumentpropertycollection/index_of/
is_root: false
---
##  index_of(name) {#str}
Hämtar indexet för en egenskap efter namn.


###  Returnerar

Det nollbaserade indexet. Negativt värde om det inte hittas.


```python
def index_of(self, name):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| name | str | Egendomens namn som inte är skiftlägeskänsligt.|


##  index_of(item, index) {#DocumentProperty-int}
Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom intervallet av element i arraylistan som sträcker sig från det angivna indexet till det sista elementet.


###  Returnerar

Det nollbaserade indexet för den första förekomsten av värde inom intervallet av element i arraylistan som sträcker sig från startIndex till det sista elementet, om det hittas; annars -1.


```python
def index_of(self, item, index):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| item | [DocumentProperty](/cells/python-net/sv/aspose.cells.properties/documentproperty) | Objektet som ska lokaliseras i arraylistan. Värdet kan vara null.|
| index | int | Det nollbaserade startindexet för sökningen. 0 (noll) är giltig i en tom lista.|


##  index_of(item, index, count) {#DocumentProperty-int-int}
Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom intervallet av element i arraylistan som börjar vid det angivna indexet och innehåller det angivna antalet element.


###  Returnerar

Det nollbaserade indexet för den första förekomsten av värde inom intervallet av element i arraylistan som börjar vid startIndex och innehåller antalet element, om de hittas; annars -1.


```python
def index_of(self, item, index, count):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| item | [DocumentProperty](/cells/python-net/sv/aspose.cells.properties/documentproperty) | Objektet som ska lokaliseras i arraylistan. Värdet kan vara null.|
| index | int | Det nollbaserade startindexet för sökningen. 0 (noll) är giltig i en tom lista.|
| count | int | Antalet element i avsnittet att söka efter.|



###  Se även
* modul [aspose.cells.properties](../../)
* klass [BuiltInDocumentPropertyCollection](/cells/python-net/sv/aspose.cells.properties/builtindocumentpropertycollection)
