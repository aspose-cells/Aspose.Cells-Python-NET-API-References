---
title: Workbook Konstruktor
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 10
url: /de/aspose.cells/workbook/__init__/
is_root: false
---
##  \_\_init\_\_(selbst){#}
Initialisiert eine neue Instanz der Klasse [`Workbook`](/cells/python-net/de/aspose.cells/workbook).



```python

def __init__(self):
    ...
```


###  Bemerkungen

Der Standarddateiformattyp ist XLSX. Wenn Sie andere Dateitypen erstellen möchten, verwenden Sie bitte Workbook(FileFormatType).
###  Beispiel


Der folgende Code zeigt, wie der Konstruktor Workbook zum Erstellen und Initialisieren einer neuen Instanz der Klasse verwendet wird.

```python
from aspose.cells import Workbook

workbook = Workbook()

```


##  \_\_init\_\_(selbst, Dateiformattyp){#aspose.cells.FileFormatType}
Initialisiert eine neue Instanz der Klasse [`Workbook`](/cells/python-net/de/aspose.cells/workbook).



```python

def __init__(self, file_format_type):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| file_format_type | [`FileFormatType`](/cells/python-net/de/aspose.cells/fileformattype) | Das neue Dateiformat.|
###  Bemerkungen

Der Standarddateiformattyp ist Excel97To2003.
###  Beispiel


Der folgende Code zeigt, wie der Konstruktor Workbook verwendet wird, um eine neue Instanz der Klasse mit verschiedenen Dateiformattypen zu erstellen und zu initialisieren.

```python
from aspose.cells import FileFormatType, Workbook

workbook = Workbook(FileFormatType.XLSX)

```


##  \_\_init\_\_(selbst, Datei){#str}
Initialisiert eine neue Instanz der Klasse [`Workbook`](/cells/python-net/de/aspose.cells/workbook) und öffnet eine Datei.



```python

def __init__(self, file):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| file | str | Der Dateiname.|


##  \_\_init\_\_(selbst, streamen){#io.RawIOBase}
Initialisiert eine neue Instanz der Klasse [`Workbook`](/cells/python-net/de/aspose.cells/workbook) und öffnet einen Stream.



```python

def __init__(self, stream):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| stream | io.RawIOBase | Der Bach.|


##  \_\_init\_\_(selbst, Datei, Ladeoptionen){#str-aspose.cells.LoadOptions}
Initialisiert eine neue Instanz der Klasse [`Workbook`](/cells/python-net/de/aspose.cells/workbook) und öffnet eine Datei.



```python

def __init__(self, file, load_options):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| file | str | Der Dateiname.|
| load_options | [`LoadOptions`](/cells/python-net/de/aspose.cells/loadoptions) | Die Ladeoptionen|


##  \_\_init\_\_(selbst, Stream, Ladeoptionen){#io.RawIOBase-aspose.cells.LoadOptions}
Initialisiert eine neue Instanz der Klasse [`Workbook`](/cells/python-net/de/aspose.cells/workbook) und öffnet den Stream.



```python

def __init__(self, stream, load_options):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| stream | io.RawIOBase | Der Bach.|
| load_options | [`LoadOptions`](/cells/python-net/de/aspose.cells/loadoptions) | Die Ladeoptionen|



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Workbook`](/cells/python-net/de/aspose.cells/workbook)
