---
title: replace Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 350
url: /de/aspose.cells/workbook/replace/
is_root: false
---
##  replace(self, place_holder, new_value) {#str-str}
Ersetzt den Wert einer Zelle durch eine neue Zeichenfolge.



```python

def replace(self, place_holder, new_value):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| place_holder | str | Cell Platzhalter|
| new_value | str | Zu ersetzender Zeichenfolgenwert|

###  Beispiel

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
workbook.replace("AnOldValue", "NewValue")

```


##  replace(self, place_holder, new_value) {#str-int}
Ersetzt den Wert einer Zelle durch eine neue Ganzzahl.



```python

def replace(self, place_holder, new_value):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| place_holder | str | Cell Platzhalter|
| new_value | int | Zu ersetzender ganzzahliger Wert|

###  Beispiel

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValue = 100
workbook.replace("AnOldValue", newValue)

```


##  replace(self, place_holder, new_value) {#str-float}
Ersetzt den Wert einer Zelle durch einen neuen Double-Wert.



```python

def replace(self, place_holder, new_value):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| place_holder | str | Cell Platzhalter|
| new_value | float | Zu ersetzender Doppelwert|

###  Beispiel

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValue = 100.0
workbook.replace("AnOldValue", newValue)

```


##  replace(self, bool_value, new_value) {#bool-any}
Ersetzt die Werte der Zellen durch neue Daten.



```python

def replace(self, bool_value, new_value):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| bool_value | bool | Der zu ersetzende Boolesche Wert.|
| new_value | any | Neuer Wert. Kann eine Zeichenfolge, eine Ganzzahl, eine doppelte Zahl oder ein DateTime-Wert sein.|


##  replace(self, int_value, new_value) {#int-any}
Ersetzt die Werte der Zellen durch neue Daten.



```python

def replace(self, int_value, new_value):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| int_value | int | Der zu ersetzende Integer-Wert.|
| new_value | any | Neuer Wert. Kann eine Zeichenfolge, eine Ganzzahl, eine doppelte Zahl oder ein DateTime-Wert sein.|


##  replace(self, place_holder, new_values, is_vertical) {#str-list-bool}
Ersetzt den Wert einer Zelle durch ein neues Zeichenfolgenarray.



```python

def replace(self, place_holder, new_values, is_vertical):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| place_holder | str | Cell Platzhalter|
| new_values | list | Zu ersetzendes Zeichenfolgenarray|
| is_vertical | bool | Wahr – Vertikal, Falsch – Horizontal|

###  Beispiel

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValues = ["Tom", "Alice", "Jerry"]
workbook.replace("AnOldValue", newValues, True)

```


##  replace(self, place_holder, new_values, is_vertical) {#str-list-bool}
Ersetzt die Werte der Zellen durch ein ganzzahliges Array.



```python

def replace(self, place_holder, new_values, is_vertical):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| place_holder | str | Cell Platzhalter|
| new_values | list | Zu ersetzendes Integer-Array|
| is_vertical | bool | Wahr – Vertikal, Falsch – Horizontal|

###  Beispiel

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValues = [1, 2, 3]
workbook.replace("AnOldValue", newValues, True)

```


##  replace(self, place_holder, new_values, is_vertical) {#str-list-bool}
Ersetzt die Zellenwerte durch ein doppeltes Array.



```python

def replace(self, place_holder, new_values, is_vertical):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| place_holder | str | Cell Platzhalter|
| new_values | list | Doppeltes Array zum Ersetzen|
| is_vertical | bool | Wahr – Vertikal, Falsch – Horizontal|

###  Beispiel

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValues = [1.23, 2.56, 3.14159]
workbook.replace("AnOldValue", newValues, True)

```


##  replace(self, place_holder, new_value, options) {#str-str-aspose.cells.ReplaceOptions}
Ersetzt den Wert einer Zelle durch eine neue Zeichenfolge.



```python

def replace(self, place_holder, new_value, options):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| place_holder | str | Cell Platzhalter|
| new_value | str | Zu ersetzender Zeichenfolgenwert|
| options | [`ReplaceOptions`](/cells/python-net/de/aspose.cells/replaceoptions) | Die Ersetzungsoptionen|



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Workbook`](/cells/python-net/de/aspose.cells/workbook)
