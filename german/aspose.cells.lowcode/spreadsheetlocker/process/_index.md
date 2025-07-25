---
title: process Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 20
url: /de/aspose.cells.lowcode/spreadsheetlocker/process/
is_root: false
---
##  process(, Ladeoptionen, Speicheroptionen, Anbieter){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-aspose.cells.lowcode.AbstractLowCodeProtectionProvider}
Sperrt die Tabellenkalkulationsdatei mit den angegebenen Einstellungen.



```python

@staticmethod
def process(load_options, save_options, provider):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/de/aspose.cells.lowcode/lowcodeloadoptions) | Optionen für Eingabe und Beladung|
| save_options | [`LowCodeSaveOptions`](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptions) | Ausgabe- und Speicheroptionen|
| provider | [`AbstractLowCodeProtectionProvider`](/cells/python-net/de/aspose.cells.lowcode/abstractlowcodeprotectionprovider) | Implementierung zur Bereitstellung von Schutzeinstellungen|


##  process(, Vorlagendatei, Ergebnisdatei, Passwort öffnen, Passwort schreiben){#str-str-str-str}
Sperrt die Tabellenkalkulationsdatei mit den angegebenen Einstellungen.



```python

@staticmethod
def process(template_file, result_file, open_password, write_password):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| template_file | str | Die zu sperrende Vorlagendatei|
| result_file | str | Die resultierende Datei|
| open_password | str | Passwort für die Dateiverschlüsselung|
| write_password | str |Passwort zum Schutz der Tabellenänderung|


##  process(, Ladeoptionen, Speicheroptionen, Passwort öffnen, Passwort schreiben){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-str-str}
Sperrt die Tabellenkalkulationsdatei mit den angegebenen Einstellungen.



```python

@staticmethod
def process(load_options, save_options, open_password, write_password):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/de/aspose.cells.lowcode/lowcodeloadoptions) | Optionen für Eingabe und Beladung|
| save_options | [`LowCodeSaveOptions`](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptions) | Ausgabe- und Speicheroptionen|
| open_password | str | Passwort für die Dateiverschlüsselung|
| write_password | str |Passwort zum Schutz der Tabellenänderung|


##  process(, Ladeoptionen, Speicheroptionen, Öffnen-Passwort, Schreiben-Passwort, Arbeitsmappen-Passwort, Arbeitsmappentyp){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-str-str-str-aspose.cells.ProtectionType}
Sperrt die Tabellenkalkulationsdatei mit den angegebenen Einstellungen.



```python

@staticmethod
def process(load_options, save_options, open_password, write_password, workbook_password, workbook_type):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/de/aspose.cells.lowcode/lowcodeloadoptions) | Optionen für Eingabe und Beladung|
| save_options | [`LowCodeSaveOptions`](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptions) | Ausgabe- und Speicheroptionen|
| open_password | str | Passwort für die Dateiverschlüsselung|
| write_password | str |Passwort zum Schutz der Tabellenänderung|
| workbook_password | str | Passwort zum Schutz der Arbeitsmappe|
| workbook_type | [`ProtectionType`](/cells/python-net/de/aspose.cells/protectiontype) | Schutztyp zum Schutz der Arbeitsmappe|



###  Siehe auch
* Modul [`aspose.cells.lowcode`](../../)
* Klasse [`SpreadsheetLocker`](/cells/python-net/de/aspose.cells.lowcode/spreadsheetlocker)
