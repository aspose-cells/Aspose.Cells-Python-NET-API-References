---
title: process Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 20
url: /de/aspose.cells.lowcode/spreadsheetsplitter/process/
is_root: false
---
##  process(, Optionen){#aspose.cells.lowcode.LowCodeSplitOptions}
Teilt die Tabellenkalkulationsdatei in mehrere Teile auf.



```python

@staticmethod
def process(options):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| options | [`LowCodeSplitOptions`](/cells/python-net/de/aspose.cells.lowcode/lowcodesplitoptions) | Optionen zum Aufteilen der Tabelle|


##  process(, Vorlagendatei, Ergebnisdatei){#str-str}
Teilt die angegebene Vorlagendatei in mehrere Teile auf.



```python

@staticmethod
def process(template_file, result_file):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| template_file | str | Die zu teilende Vorlagendatei|
| result_file | str | Die resultierende Datei (Namensmuster)|
###  Bemerkungen

Die Ausgabedateien werden aus der angegebenen Ergebnisdatei erstellt durch
Anhängen der laufenden Nummer des Blattes und des geteilten Teils.
Wenn die angegebene Ausgabedatei beispielsweise Split.xlsx ist, dann wird die generierte
Die Dateien lauten Split_0_0.xlsx, Split_0_1.xlsx, ..., Split_1_0.xlsx, ...


###  Siehe auch
* Modul [`aspose.cells.lowcode`](../../)
* Klasse [`SpreadsheetSplitter`](/cells/python-net/de/aspose.cells.lowcode/spreadsheetsplitter)
