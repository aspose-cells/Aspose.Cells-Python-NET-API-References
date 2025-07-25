---
title: Metodo detect_file_format
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 20
url: /it/aspose.cells/fileformatutil/detect_file_format/
is_root: false
---
##  detect_file_format(, flusso){#io.RawIOBase}
Rileva e restituisce le informazioni su un formato di un file Excel memorizzato in un flusso.


###  ritorna

Un oggetto [`FileFormatInfo`](/cells/python-net/it/aspose.cells/fileformatinfo) che contiene le informazioni rilevate.


```python

@staticmethod
def detect_file_format(stream):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| stream | io.RawIOBase |  |


##  detect_file_format(, percorso_file){#str}
Rileva e restituisce le informazioni su un formato di un file Excel memorizzato in un file.


###  ritorna

Un oggetto [`FileFormatInfo`](/cells/python-net/it/aspose.cells/fileformatinfo) che contiene le informazioni rilevate.


```python

@staticmethod
def detect_file_format(file_path):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| file_path | str | Il percorso del file.|


##  detect_file_format(, flusso, password){#io.RawIOBase-str}
Rileva e restituisce le informazioni su un formato di un file Excel memorizzato in un flusso.


###  ritorna

Un oggetto [`FileFormatInfo`](/cells/python-net/it/aspose.cells/fileformatinfo) che contiene le informazioni rilevate.


```python

@staticmethod
def detect_file_format(stream, password):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| stream | io.RawIOBase |  |
| password | str | La password per i file ooxml crittografati.|


##  detect_file_format(, percorso_file, password){#str-str}
Rileva e restituisce le informazioni su un formato di un file Excel memorizzato in un file.


###  ritorna

Un oggetto [`FileFormatInfo`](/cells/python-net/it/aspose.cells/fileformatinfo) che contiene le informazioni rilevate.


```python

@staticmethod
def detect_file_format(file_path, password):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| file_path | str | Il percorso del file.|
| password | str | La password per i file ooxml crittografati.|



###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`FileFormatInfo`](/cells/python-net/it/aspose.cells/fileformatinfo)
* classe [`FileFormatUtil`](/cells/python-net/it/aspose.cells/fileformatutil)
