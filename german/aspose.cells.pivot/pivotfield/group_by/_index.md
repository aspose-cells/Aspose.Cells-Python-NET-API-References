---
title: group_by Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 80
url: /de/aspose.cells.pivot/pivotfield/group_by/
is_root: false
---
##  group_by {#float-bool}
Gruppieren Sie das Feld automatisch mit intern



```python
def group_by(self, interval, new_field):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| interval | float | Das Innere der Gruppe.<br/> Der automatische Wert wird zugewiesen, wenn er Null ist.|
| new_field | bool | Gibt an, ob der Pivot-Tabelle ein neues Feld hinzugefügt wird.|


##  group_by {#list-bool}
Gruppieren Sie das Feld benutzerdefiniert.



```python
def group_by(self, custom_group_items, new_field):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| custom_group_items | list | Die benutzerdefinierten Gruppenelemente.|
| new_field | bool |Gibt an, ob der Pivot-Tabelle ein neues Feld hinzugefügt wird|


##  group_by {#float-float-float-bool}
Gruppieren Sie die Datei nach Nummer.



```python
def group_by(self, start, end, interval, new_field):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| start | float | Der Startwert|
| end | float | Das Ende des Wertes|
| interval | float | Das Intervall|
| new_field | bool |Gibt an, ob der Pivot-Tabelle ein neues Feld hinzugefügt wird|


##  group_by {#DateTime-DateTime-list-float-bool}
Gruppieren Sie die Datei nach den Datumsgruppentypen.



```python
def group_by(self, start, end, groups, interval, first_as_new_field):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| start | DateTime | Das Startdatum und die Uhrzeit|
| end | DateTime | Das Ende von datetime|
| groups | list | Gruppentypen|
| interval | float | Das Intervall|
| first_as_new_field | bool | Gibt an, ob der Pivot-Tabelle ein neues Feld hinzugefügt wird.<br/> Nur für das erste Gruppenelement.|



###  Siehe auch
* Modul [`aspose.cells.pivot`](../../)
* Klasse [`PivotField`](/cells/python-net/de/aspose.cells.pivot/pivotfield)
