---
title: detect_file_format Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 20
url: /de/aspose.cells/fileformatutil/detect_file_format/
is_root: false
---
##  detect_file_format(, Stream){#io.RawIOBase}
Erkennt und gibt die Informationen zum Format einer in einem Stream gespeicherten Excel-Datei zurück.


###  Kehrt zurück

Ein [`FileFormatInfo`](/cells/python-net/de/aspose.cells/fileformatinfo)-Objekt, das die erkannten Informationen enthält.


```python

@staticmethod
def detect_file_format(stream):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| stream | io.RawIOBase |  |


##  detect_file_format(, Dateipfad){#str}
Erkennt und gibt Informationen zum Format einer in einer Datei gespeicherten Excel-Datei zurück.


###  Kehrt zurück

Ein [`FileFormatInfo`](/cells/python-net/de/aspose.cells/fileformatinfo)-Objekt, das die erkannten Informationen enthält.


```python

@staticmethod
def detect_file_format(file_path):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| file_path | str | Der Dateipfad.|


##  detect_file_format(, Stream, Passwort){#io.RawIOBase-str}
Erkennt und gibt die Informationen zum Format einer in einem Stream gespeicherten Excel-Datei zurück.


###  Kehrt zurück

Ein [`FileFormatInfo`](/cells/python-net/de/aspose.cells/fileformatinfo)-Objekt, das die erkannten Informationen enthält.


```python

@staticmethod
def detect_file_format(stream, password):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| stream | io.RawIOBase |  |
| password | str | Das Passwort für verschlüsselte ooxml-Dateien.|


##  detect_file_format(, Dateipfad, Passwort){#str-str}
Erkennt und gibt Informationen zum Format einer in einer Datei gespeicherten Excel-Datei zurück.


###  Kehrt zurück

Ein [`FileFormatInfo`](/cells/python-net/de/aspose.cells/fileformatinfo)-Objekt, das die erkannten Informationen enthält.


```python

@staticmethod
def detect_file_format(file_path, password):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| file_path | str | Der Dateipfad.|
| password | str | Das Passwort für verschlüsselte ooxml-Dateien.|



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`FileFormatInfo`](/cells/python-net/de/aspose.cells/fileformatinfo)
* Klasse [`FileFormatUtil`](/cells/python-net/de/aspose.cells/fileformatutil)
