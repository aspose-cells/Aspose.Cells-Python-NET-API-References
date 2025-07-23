---
title: Workbook costruttore
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 10
url: /it/aspose.cells/workbook/__init__/
is_root: false
---
##  \_\_init\_\_(self){#}
Inizializza una nuova istanza della classe [`Workbook`](/cells/python-net/it/aspose.cells/workbook).



```python

def __init__(self):
    ...
```


###  Osservazioni

Il formato di file predefinito è Xlsx. Per creare altri tipi di file, utilizzare Workbook (FileFormatType).
###  Esempio


Il codice seguente mostra come utilizzare il costruttore Workbook per creare e inizializzare una nuova istanza della classe.

```python
from aspose.cells import Workbook

workbook = Workbook()

```


##  \_\_init\_\_(self, tipo_formato_file){#aspose.cells.FileFormatType}
Inizializza una nuova istanza della classe [`Workbook`](/cells/python-net/it/aspose.cells/workbook).



```python

def __init__(self, file_format_type):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| file_format_type | [`FileFormatType`](/cells/python-net/it/aspose.cells/fileformattype) | Il nuovo formato di file.|
###  Osservazioni

Il formato di file predefinito è Excel97To2003.
###  Esempio


Il codice seguente mostra come utilizzare il costruttore Workbook per creare e inizializzare una nuova istanza della classe con vari tipi di formato di file.

```python
from aspose.cells import FileFormatType, Workbook

workbook = Workbook(FileFormatType.XLSX)

```


##  \_\_init\_\_(self, file){#str}
Inizializza una nuova istanza della classe [`Workbook`](/cells/python-net/it/aspose.cells/workbook) e apre un file.



```python

def __init__(self, file):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| file | str | Il nome del file.|


##  \_\_init\_\_(self, flusso){#io.RawIOBase}
Inizializza una nuova istanza della classe [`Workbook`](/cells/python-net/it/aspose.cells/workbook) e apre un flusso.



```python

def __init__(self, stream):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| stream | io.RawIOBase | Il ruscello.|


##  \_\_init\_\_(self, file, load_options){#str-aspose.cells.LoadOptions}
Inizializza una nuova istanza della classe [`Workbook`](/cells/python-net/it/aspose.cells/workbook) e apre un file.



```python

def __init__(self, file, load_options):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| file | str | Il nome del file.|
| load_options | [`LoadOptions`](/cells/python-net/it/aspose.cells/loadoptions) | Le opzioni di carico|


##  \_\_init\_\_(self, stream, load_options){#io.RawIOBase-aspose.cells.LoadOptions}
Inizializza una nuova istanza della classe [`Workbook`](/cells/python-net/it/aspose.cells/workbook) e apre il flusso.



```python

def __init__(self, stream, load_options):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| stream | io.RawIOBase | Il ruscello.|
| load_options | [`LoadOptions`](/cells/python-net/it/aspose.cells/loadoptions) | Le opzioni di carico|



###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Workbook`](/cells/python-net/it/aspose.cells/workbook)
