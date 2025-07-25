---
title: create_safe_sheet_name Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 90
url: /de/aspose.cells/cellshelper/create_safe_sheet_name/
is_root: false
---
##  create_safe_sheet_name(, Name_Vorschlag){#str}
Überprüft den angegebenen Blattnamen und erstellt bei Bedarf einen gültigen.
Wenn der angegebene Blattname den Regeln für Excel-Blattnamen entspricht, geben Sie ihn zurück.
Andernfalls wird die Zeichenfolge abgeschnitten, wenn die Länge das Limit überschreitet
und ungültige Zeichen werden durch „ “ ersetzt, dann wird der neu erstellte Zeichenfolgenwert zurückgegeben.


###  Kehrt zurück




```python

@staticmethod
def create_safe_sheet_name(name_proposal):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| name_proposal | str | zu verwendender Blattname|


##  create_safe_sheet_name(, Namensvorschlag, Ersetzungszeichen){#str-char}
Überprüft den angegebenen Blattnamen und erstellt bei Bedarf einen gültigen.
Wenn der angegebene Blattname den Regeln für Excel-Blattnamen entspricht, geben Sie ihn zurück.
Andernfalls wird die Zeichenfolge abgeschnitten, wenn die Länge das Limit überschreitet
und ungültige Zeichen werden durch das angegebene Zeichen ersetzt, dann wird der neu erstellte Zeichenfolgenwert zurückgegeben.


###  Kehrt zurück




```python

@staticmethod
def create_safe_sheet_name(name_proposal, replace_char):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| name_proposal | str | zu verwendender Blattname|
| replace_char | char | Zeichen, das zum Ersetzen ungültiger Zeichen im angegebenen Blattnamen verwendet wird|



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`CellsHelper`](/cells/python-net/de/aspose.cells/cellshelper)
