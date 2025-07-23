---
title: register_add_in_function metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 180
url: /sv/aspose.cells/worksheetcollection/register_add_in_function/
is_root: false
---
##  register_add_in_function(self, id, function_name) {#int-str}
Lägger till addin-funktionen i arbetsboken


###  Returnerar

URL till tilläggsfilen som innehåller tilläggsfunktioner


```python

def register_add_in_function(self, id, function_name):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| id | int |ID för data som innehåller tilläggsfunktioner,<br/> kan erhållas genom det första anropet på [`WorksheetCollection.register_add_in_function`](/cells/python-net/sv/aspose.cells/worksheetcollection/register_add_in_function) för samma tilläggsfil.|
| function_name | str | namnet på tilläggsfunktionen|


##  register_add_in_function(self, add_in_file, function_name, lib) {#str-str-bool}
Lägger till addin-funktionen i arbetsboken


###  Returnerar

ID för data som innehåller den givna tilläggsfunktionen


```python

def register_add_in_function(self, add_in_file, function_name, lib):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| add_in_file | str | filen innehåller tilläggsfunktionerna|
| function_name | str | namnet på tilläggsfunktionen|
| lib | bool | om den givna tilläggsfilen finns i katalogen eller underkatalogen till arbetsbokstilläggsbiblioteket.<br/>Denna flagga träder i kraft och gör skillnad när den angivna addInFile har en relativ sökväg:<br/> sant anger att sökvägen är relativ till tilläggsbiblioteket och falskt anger att sökvägen är relativ till den här arbetsboken.|



###  Se även
* modul [`aspose.cells`](../../)
* klass [`WorksheetCollection`](/cells/python-net/sv/aspose.cells/worksheetcollection)
