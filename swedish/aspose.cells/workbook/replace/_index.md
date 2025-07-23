---
title: replace metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 350
url: /sv/aspose.cells/workbook/replace/
is_root: false
---
##  replace(self, place_holder, new_value) {#str-str}
Ersätter en cells värde med en ny sträng.



```python

def replace(self, place_holder, new_value):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| place_holder | str | Cell platshållare|
| new_value | str | Strängvärde att ersätta|

###  Exempel

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
workbook.replace("AnOldValue", "NewValue")

```


##  replace(self, place_holder, new_value) {#str-int}
Ersätter en cells värde med ett nytt heltal.



```python

def replace(self, place_holder, new_value):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| place_holder | str | Cell platshållare|
| new_value | int | Heltalsvärde att ersätta|

###  Exempel

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValue = 100
workbook.replace("AnOldValue", newValue)

```


##  replace(self, place_holder, new_value) {#str-float}
Ersätter en cells värde med en ny double.



```python

def replace(self, place_holder, new_value):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| place_holder | str | Cell platshållare|
| new_value | float | Dubbelt värde att ersätta|

###  Exempel

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValue = 100.0
workbook.replace("AnOldValue", newValue)

```


##  replace(self, bool_value, new_value) {#bool-any}
Ersätter cellernas värden med nya data.



```python

def replace(self, bool_value, new_value):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| bool_value | bool | Det booleska värdet som ska ersättas.|
| new_value | any | Nytt värde. Kan vara ett sträng-, heltal-, dubbel- eller DateTime-värde.|


##  replace(self, int_value, new_value) {#int-any}
Ersätter cellernas värden med nya data.



```python

def replace(self, int_value, new_value):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| int_value | int | Heltalet som ska ersättas.|
| new_value | any | Nytt värde. Kan vara ett sträng-, heltal-, dubbel- eller DateTime-värde.|


##  replace(self, place_holder, new_values, is_vertical) {#str-list-bool}
Ersätter en cells värde med en ny strängmatris.



```python

def replace(self, place_holder, new_values, is_vertical):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| place_holder | str | Cell platshållare|
| new_values | list | Strängmatris att ersätta|
| is_vertical | bool | Sant - Vertikalt, Falskt - Horisontellt|

###  Exempel

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValues = ["Tom", "Alice", "Jerry"]
workbook.replace("AnOldValue", newValues, True)

```


##  replace(self, place_holder, new_values, is_vertical) {#str-list-bool}
Ersätter cellernas värden med en heltalsmatris.



```python

def replace(self, place_holder, new_values, is_vertical):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| place_holder | str | Cell platshållare|
| new_values | list | Heltalsmatris att ersätta|
| is_vertical | bool | Sant - Vertikalt, Falskt - Horisontellt|

###  Exempel

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValues = [1, 2, 3]
workbook.replace("AnOldValue", newValues, True)

```


##  replace(self, place_holder, new_values, is_vertical) {#str-list-bool}
Ersätter cellernas värden med en dubbel array.



```python

def replace(self, place_holder, new_values, is_vertical):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| place_holder | str | Cell platshållare|
| new_values | list | Dubbel array att ersätta|
| is_vertical | bool | Sant - Vertikalt, Falskt - Horisontellt|

###  Exempel

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValues = [1.23, 2.56, 3.14159]
workbook.replace("AnOldValue", newValues, True)

```


##  replace(self, place_holder, new_value, options) {#str-str-aspose.cells.ReplaceOptions}
Ersätter en cells värde med en ny sträng.



```python

def replace(self, place_holder, new_value, options):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| place_holder | str | Cell platshållare|
| new_value | str | Strängvärde att ersätta|
| options | [`ReplaceOptions`](/cells/python-net/sv/aspose.cells/replaceoptions) | Ersättningsalternativen|



###  Se även
* modul [`aspose.cells`](../../)
* klass [`Workbook`](/cells/python-net/sv/aspose.cells/workbook)
