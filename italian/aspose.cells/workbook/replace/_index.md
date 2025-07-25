---
title: Metodo replace
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 350
url: /it/aspose.cells/workbook/replace/
is_root: false
---
##  replace(self, place_holder, new_value) {#str-str}
Sostituisce il valore di una cella con una nuova stringa.



```python

def replace(self, place_holder, new_value):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| place_holder | str | Cell segnaposto|
| new_value | str | Valore stringa da sostituire|

###  Esempio

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
workbook.replace("AnOldValue", "NewValue")

```


##  replace(self, place_holder, new_value) {#str-int}
Sostituisce il valore di una cella con un nuovo numero intero.



```python

def replace(self, place_holder, new_value):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| place_holder | str | Cell segnaposto|
| new_value | int | Valore intero da sostituire|

###  Esempio

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValue = 100
workbook.replace("AnOldValue", newValue)

```


##  replace(self, place_holder, new_value) {#str-float}
Sostituisce il valore di una cella con un nuovo valore double.



```python

def replace(self, place_holder, new_value):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| place_holder | str | Cell segnaposto|
| new_value | float | Doppio valore da sostituire|

###  Esempio

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValue = 100.0
workbook.replace("AnOldValue", newValue)

```


##  replace(self, bool_value, new_value) {#bool-any}
Sostituisce i valori delle celle con nuovi dati.



```python

def replace(self, bool_value, new_value):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| bool_value | bool | Valore booleano da sostituire.|
| new_value | any | Nuovo valore. Può essere una stringa, un intero, un valore double o DateTime.|


##  replace(self, int_value, new_value) {#int-any}
Sostituisce i valori delle celle con nuovi dati.



```python

def replace(self, int_value, new_value):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| int_value | int | Valore intero da sostituire.|
| new_value | any | Nuovo valore. Può essere una stringa, un intero, un valore double o DateTime.|


##  replace(self, place_holder, new_values, is_vertical) {#str-list-bool}
Sostituisce il valore di una cella con una nuova matrice di stringhe.



```python

def replace(self, place_holder, new_values, is_vertical):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| place_holder | str | Cell segnaposto|
| new_values | list | Array di stringhe da sostituire|
| is_vertical | bool | Vero - Verticale, Falso - Orizzontale|

###  Esempio

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValues = ["Tom", "Alice", "Jerry"]
workbook.replace("AnOldValue", newValues, True)

```


##  replace(self, place_holder, new_values, is_vertical) {#str-list-bool}
Sostituisce i valori delle celle con un array di numeri interi.



```python

def replace(self, place_holder, new_values, is_vertical):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| place_holder | str | Cell segnaposto|
| new_values | list | Array di interi da sostituire|
| is_vertical | bool | Vero - Verticale, Falso - Orizzontale|

###  Esempio

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValues = [1, 2, 3]
workbook.replace("AnOldValue", newValues, True)

```


##  replace(self, place_holder, new_values, is_vertical) {#str-list-bool}
Sostituisce i valori delle celle con un array doppio.



```python

def replace(self, place_holder, new_values, is_vertical):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| place_holder | str | Cell segnaposto|
| new_values | list | Doppio array da sostituire|
| is_vertical | bool | Vero - Verticale, Falso - Orizzontale|

###  Esempio

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValues = [1.23, 2.56, 3.14159]
workbook.replace("AnOldValue", newValues, True)

```


##  replace(self, place_holder, new_value, options) {#str-str-aspose.cells.ReplaceOptions}
Sostituisce il valore di una cella con una nuova stringa.



```python

def replace(self, place_holder, new_value, options):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| place_holder | str | Cell segnaposto|
| new_value | str | Valore stringa da sostituire|
| options | [`ReplaceOptions`](/cells/python-net/it/aspose.cells/replaceoptions) | Le opzioni di sostituzione|



###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Workbook`](/cells/python-net/it/aspose.cells/workbook)
