---
title: group_by metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 80
url: /sv/aspose.cells.pivot/pivotfield/group_by/
is_root: false
---
##  group_by {#float-bool}
Gruppera automatiskt fältet med internt



```python
def group_by(self, interval, new_field):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| interval | float | Gruppens inre.<br/> Automatiskt värde kommer att tilldelas om det är noll,|
| new_field | bool | Anger om ett nytt fält ska läggas till i pivottabellen.|


##  group_by {#list-bool}
Anpassa gruppera fältet.



```python
def group_by(self, custom_group_items, new_field):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| custom_group_items | list | De anpassade gruppobjekten.|
| new_field | bool |Anger om ett nytt fält ska läggas till i pivottabellen|


##  group_by {#float-float-float-bool}
Gruppera filen efter nummer.



```python
def group_by(self, start, end, interval, new_field):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| start | float | Startvärdet|
| end | float | Slutet på värdet|
| interval | float | Intervallet|
| new_field | bool |Anger om ett nytt fält ska läggas till i pivottabellen|


##  group_by {#DateTime-DateTime-list-float-bool}
Gruppera filen efter datumgrupptyper.



```python
def group_by(self, start, end, groups, interval, first_as_new_field):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| start | DateTime | Startdatum och tid|
| end | DateTime | Slutet på datetime|
| groups | list | Grupptyper|
| interval | float | Intervallet|
| first_as_new_field | bool | Anger om ett nytt fält ska läggas till i pivottabellen.<br/> Endast för det första gruppobjektet.|



###  Se även
* modul [`aspose.cells.pivot`](../../)
* klass [`PivotField`](/cells/python-net/sv/aspose.cells.pivot/pivotfield)
