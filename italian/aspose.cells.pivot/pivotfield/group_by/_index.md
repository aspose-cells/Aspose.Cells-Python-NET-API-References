---
title: Metodo group_by
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 140
url: /it/aspose.cells.pivot/pivotfield/group_by/
is_root: false
---
##  group_by(self, interval, new_field) {#float-bool}
Raggruppa automaticamente il campo con interno



```python

def group_by(self, interval, new_field):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| interval | float | L'interno del gruppo.<br/> Verrà assegnato un valore automatico se è zero,|
| new_field | bool | Indica se aggiungere un nuovo campo alla tabella pivot.|


##  group_by(self, custom_group_items, new_field) {#list-bool}
Raggruppa il campo in modo personalizzato.


###  ritorna

False significa che questo campo non può essere raggruppato per data e ora.


```python

def group_by(self, custom_group_items, new_field):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| custom_group_items | list | Gli elementi del gruppo personalizzato.|
| new_field | bool | Indica se aggiungere un nuovo campo alla tabella pivot|


##  group_by(self, start, end, interval, new_field) {#float-float-float-bool}
Raggruppa il file in base al numero.


###  ritorna

False significa che questo campo non può essere raggruppato per data e ora.


```python

def group_by(self, start, end, interval, new_field):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| start | float | Il valore iniziale|
| end | float | La fine del valore|
| interval | float | L'intervallo|
| new_field | bool | Indica se aggiungere un nuovo campo alla tabella pivot|


##  group_by(self, start, end, groups, interval, first_as_new_field) {#DateTime-DateTime-list-float-bool}
Raggruppa il file in base ai tipi di gruppo data.


###  ritorna

False significa che questo campo non può essere raggruppato per data e ora.


```python

def group_by(self, start, end, groups, interval, first_as_new_field):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| start | DateTime | La data e l'ora di inizio|
| end | DateTime | La fine di datetime|
| groups | list | Tipi di gruppo|
| interval | float | L'intervallo|
| first_as_new_field | bool | Indica se aggiungere un nuovo campo alla tabella pivot.<br/> Solo per il primo elemento del gruppo.|



###  Guarda anche
* modulo [`aspose.cells.pivot`](../../)
* classe [`PivotField`](/cells/python-net/it/aspose.cells.pivot/pivotfield)
