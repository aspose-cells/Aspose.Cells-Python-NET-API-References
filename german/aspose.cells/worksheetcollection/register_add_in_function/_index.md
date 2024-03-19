---
title: register_add_in_function Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 180
url: /de/aspose.cells/worksheetcollection/register_add_in_function/
is_root: false
---
##  register_add_in_function {#int-str}
Fügt der Arbeitsmappe eine Add-In-Funktion hinzu


###  Kehrt zurück

URL der Add-In-Datei, die Add-In-Funktionen enthält


```python
def register_add_in_function(self, id, function_name):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| id | int | ID der Daten, die Add-In-Funktionen enthalten,<br/> kann durch den ersten Aufruf von [`WorksheetCollection.register_add_in_function`](/cells/python-net/de/aspose.cells/worksheetcollection/register_add_in_function) für dieselbe Add-In-Datei abgerufen werden.|
| function_name | str | Der Name der Add-In-Funktion|


##  register_add_in_function {#str-str-bool}
Fügt der Arbeitsmappe eine Add-In-Funktion hinzu


###  Kehrt zurück

ID der Daten, die die angegebene Add-In-Funktion enthalten


```python
def register_add_in_function(self, add_in_file, function_name, lib):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| add_in_file | str | Die Datei enthält die Add-In-Funktionen|
| function_name | str | Der Name der Add-In-Funktion|
| lib | bool | ob sich die angegebene Add-In-Datei im Verzeichnis oder Unterverzeichnis der Workbook-Add-In-Bibliothek befindet.<br/>Dieses Flag wird wirksam und macht einen Unterschied, wenn addInFile einen relativen Pfad hat:<br/> „true“ gibt an, dass der Pfad relativ zur Add-In-Bibliothek ist, und „false“ gibt an, dass der Pfad relativ zu dieser Arbeitsmappe ist.|



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`WorksheetCollection`](/cells/python-net/de/aspose.cells/worksheetcollection)
