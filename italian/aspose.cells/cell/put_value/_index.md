---
title: Metodo put_value
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 290
url: /it/aspose.cells/cell/put_value/
is_root: false
---
##  put_value(self, bool_value) {#bool}
Inserisce un valore booleano nella cella.



```python

def put_value(self, bool_value):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| bool_value | bool |  |


##  put_value(self, int_value) {#int}
Inserisce un valore intero nella cella.



```python

def put_value(self, int_value):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| int_value | int | Valore di input|


##  put_value(self, double_value) {#float}
Inserisce un valore doppio nella cella.



```python

def put_value(self, double_value):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| double_value | float | Valore di input|


##  put_value(self, string_value) {#str}
Inserisce un valore stringa nella cella.



```python

def put_value(self, string_value):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| string_value | str | Valore di input|


##  put_value(self, date_time) {#DateTime}
Inserisce un valore DateTime nella cella.



```python

def put_value(self, date_time):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| date_time | DateTime | Valore di input|
###  Osservazioni

Impostando un valore DateTime per una cella non si avrà automaticamente il formato data/ora.
Il valore DateTime è stato mantenuto come valore numerico nel modello dati di MS Excel e Aspose.Cells.
Se il valore numerico verrà preso come valore numerico stesso o come data e ora
dipende dal formato numerico applicato a questa cella. Se questa cella non è stata formattata come data e ora,
verrà visualizzato come valore numerico anche se hai inserito DateTime.
###  Esempio

Questo esempio mostra come impostare il valore DateTime su una cella e visualizzarlo come data e ora.

```python
from aspose.cells import Workbook
from datetime import datetime

excel = Workbook()
cells = excel.worksheets[0].cells
# Put date time into a cell
cell = cells.get(0, 0)
cell.put_value(datetime(2023, 5, 15))
style = cell.get_style(False)
style.number = 14
cell.set_style(style)

```


##  put_value(self, object_value) {#any}
Inserisce un valore oggetto nella cella.



```python

def put_value(self, object_value):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| object_value | any | valore di input|


##  put_value(self, string_value, is_converted) {#str-bool}
Inserisce un valore stringa nella cella e, se appropriato, converte il valore in un altro tipo di dati.



```python

def put_value(self, string_value, is_converted):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| string_value | str | Valore di input|
| is_converted | bool | Vero: convertito in un altro tipo di dati, se appropriato.|


##  put_value(self, string_value, is_converted, set_style) {#str-bool-bool}
Inserisce un valore nella cella; se appropriato, il valore verrà convertito in un altro tipo di dati e il formato numerico della cella verrà reimpostato.



```python

def put_value(self, string_value, is_converted, set_style):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| string_value | str | Valore di input|
| is_converted | bool | Vero: convertito in un altro tipo di dati, se appropriato.|
| set_style | bool | Vero: imposta il formato del numero sullo stile della cella durante la conversione in un altro tipo di dati|



###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Cell`](/cells/python-net/it/aspose.cells/cell)
