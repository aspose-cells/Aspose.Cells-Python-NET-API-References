---
title: Workbook konstruktör
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 10
url: /sv/aspose.cells/workbook/__init__/
is_root: false
---
##  \_\_init\_\_(själv){#}
Initierar en ny instans av klassen [`Workbook`](/cells/python-net/sv/aspose.cells/workbook).



```python

def __init__(self):
    ...
```


###  Anmärkningar

Standardfilformatet är Xlsx. Om du vill skapa andra filtyper, använd Workbook(FileFormatType).
###  Exempel


Följande kod visar hur man använder konstruktorn Workbook för att skapa och initiera en ny instans av klassen.

```python
from aspose.cells import Workbook

workbook = Workbook()

```


##  \_\_init\_\_(self, file_format_type){#aspose.cells.FileFormatType}
Initierar en ny instans av klassen [`Workbook`](/cells/python-net/sv/aspose.cells/workbook).



```python

def __init__(self, file_format_type):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| file_format_type | [`FileFormatType`](/cells/python-net/sv/aspose.cells/fileformattype) | Det nya filformatet.|
###  Anmärkningar

Standardfilformattypen är Excel97To2003.
###  Exempel


Följande kod visar hur man använder konstruktorn Workbook för att skapa och initiera en ny instans av klassen med olika filformattyper.

```python
from aspose.cells import FileFormatType, Workbook

workbook = Workbook(FileFormatType.XLSX)

```


##  \_\_init\_\_(själv, fil){#str}
Initierar en ny instans av klassen [`Workbook`](/cells/python-net/sv/aspose.cells/workbook) och öppnar en fil.



```python

def __init__(self, file):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| file | str | Filnamnet.|


##  \_\_init\_\_(själv, ström){#io.RawIOBase}
Initierar en ny instans av klassen [`Workbook`](/cells/python-net/sv/aspose.cells/workbook) och öppnar en ström.



```python

def __init__(self, stream):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| stream | io.RawIOBase | Strömmen.|


##  \_\_init\_\_(self, file, load_options){#str-aspose.cells.LoadOptions}
Initierar en ny instans av klassen [`Workbook`](/cells/python-net/sv/aspose.cells/workbook) och öppnar en fil.



```python

def __init__(self, file, load_options):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| file | str | Filnamnet.|
| load_options | [`LoadOptions`](/cells/python-net/sv/aspose.cells/loadoptions) | Lastalternativen|


##  \_\_init\_\_(self, stream, load_options){#io.RawIOBase-aspose.cells.LoadOptions}
Initierar en ny instans av klassen [`Workbook`](/cells/python-net/sv/aspose.cells/workbook) och öppnar strömmen.



```python

def __init__(self, stream, load_options):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| stream | io.RawIOBase | Strömmen.|
| load_options | [`LoadOptions`](/cells/python-net/sv/aspose.cells/loadoptions) | Lastalternativen|



###  Se även
* modul [`aspose.cells`](../../)
* klass [`Workbook`](/cells/python-net/sv/aspose.cells/workbook)
