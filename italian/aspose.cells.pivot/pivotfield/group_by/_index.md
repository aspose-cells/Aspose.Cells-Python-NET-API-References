---
title: Metodo group_by
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 80
url: /it/aspose.cells.pivot/pivotfield/group_by/
is_root: false
---
##  group_by {#float-bool}
Raggruppa automaticamente il campo con internal



```python
def group_by(self, interval, new_field):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| interval | float | L'interno del gruppo.<br/> Il valore automatico verrà assegnato se è zero,|
| new_field | bool | Indica se aggiungere un nuovo campo alla tabella pivot.|


##  group_by {#list-bool}
Raggruppare il campo in modo personalizzato.



```python
def group_by(self, custom_group_items, new_field):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| custom_group_items | list | Gli elementi del gruppo personalizzato.|
| new_field | bool |Indica se aggiungere un nuovo campo alla tabella pivot|


##  group_by {#float-float-float-bool}
Raggruppare il file per numero.



```python
def group_by(self, start, end, interval, new_field):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| start | float | Il valore iniziale|
| end | float | La fine del valore|
| interval | float | L'intervallo|
| new_field | bool |Indica se aggiungere un nuovo campo alla tabella pivot|


##  group_by {#DateTime-DateTime-list-float-bool}
Raggruppare il file in base ai tipi di gruppo di date.



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
