---
title: detect_file_format metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 20
url: /sv/aspose.cells/fileformatutil/detect_file_format/
is_root: false
---
##  detect_file_format(, ström){#io.RawIOBase}
Identifierar och returnerar information om formatet för ett Excel-dokument som lagras i en ström.


###  Returnerar

Ett [`FileFormatInfo`](/cells/python-net/sv/aspose.cells/fileformatinfo)-objekt som innehåller den detekterade informationen.


```python

@staticmethod
def detect_file_format(stream):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| stream | io.RawIOBase |  |


##  detect_file_format(, sökväg till fil){#str}
Identifierar och returnerar information om formatet för ett Excel-dokument som lagras i en fil.


###  Returnerar

Ett [`FileFormatInfo`](/cells/python-net/sv/aspose.cells/fileformatinfo)-objekt som innehåller den detekterade informationen.


```python

@staticmethod
def detect_file_format(file_path):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| file_path | str | Filens sökväg.|


##  detect_file_format(, ström, lösenord){#io.RawIOBase-str}
Identifierar och returnerar information om formatet för ett Excel-dokument som lagras i en ström.


###  Returnerar

Ett [`FileFormatInfo`](/cells/python-net/sv/aspose.cells/fileformatinfo)-objekt som innehåller den detekterade informationen.


```python

@staticmethod
def detect_file_format(stream, password):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| stream | io.RawIOBase |  |
| password | str | Lösenordet för krypterade ooxml-filer.|


##  detect_file_format(, sökväg till fil, lösenord){#str-str}
Identifierar och returnerar information om formatet för ett Excel-dokument som lagras i en fil.


###  Returnerar

Ett [`FileFormatInfo`](/cells/python-net/sv/aspose.cells/fileformatinfo)-objekt som innehåller den detekterade informationen.


```python

@staticmethod
def detect_file_format(file_path, password):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| file_path | str | Filens sökväg.|
| password | str | Lösenordet för krypterade ooxml-filer.|



###  Se även
* modul [`aspose.cells`](../../)
* klass [`FileFormatInfo`](/cells/python-net/sv/aspose.cells/fileformatinfo)
* klass [`FileFormatUtil`](/cells/python-net/sv/aspose.cells/fileformatutil)
