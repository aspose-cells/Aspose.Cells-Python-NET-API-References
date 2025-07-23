---
title: Workbook constructeur
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 10
url: /fr/aspose.cells/workbook/__init__/
is_root: false
---
##  \_\_init\_\_(self){#}
Initialise une nouvelle instance de la classe [`Workbook`](/cells/python-net/fr/aspose.cells/workbook).



```python

def __init__(self):
    ...
```


###  Remarques

Le format de fichier par défaut est XLSX. Pour créer d'autres types de fichiers, veuillez utiliser Workbook(FileFormatType).
###  Exemple


Le code suivant montre comment utiliser le constructeur Workbook pour créer et initialiser une nouvelle instance de la classe.

```python
from aspose.cells import Workbook

workbook = Workbook()

```


##  \_\_init\_\_(self, type_de_format_de_fichier){#aspose.cells.FileFormatType}
Initialise une nouvelle instance de la classe [`Workbook`](/cells/python-net/fr/aspose.cells/workbook).



```python

def __init__(self, file_format_type):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| file_format_type | [`FileFormatType`](/cells/python-net/fr/aspose.cells/fileformattype) | Le nouveau format de fichier.|
###  Remarques

Le type de format de fichier par défaut est Excel97To2003.
###  Exemple


Le code suivant montre comment utiliser le constructeur Workbook pour créer et initialiser une nouvelle instance de la classe avec différents types de formats de fichiers.

```python
from aspose.cells import FileFormatType, Workbook

workbook = Workbook(FileFormatType.XLSX)

```


##  \_\_init\_\_(self, fichier){#str}
Initialise une nouvelle instance de la classe [`Workbook`](/cells/python-net/fr/aspose.cells/workbook) et ouvre un fichier.



```python

def __init__(self, file):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| file | str | Le nom du fichier.|


##  \_\_init\_\_(self, flux){#io.RawIOBase}
Initialise une nouvelle instance de la classe [`Workbook`](/cells/python-net/fr/aspose.cells/workbook) et ouvre un flux.



```python

def __init__(self, stream):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| stream | io.RawIOBase | Le ruisseau.|


##  \_\_init\_\_(self, fichier, options_de_chargement){#str-aspose.cells.LoadOptions}
Initialise une nouvelle instance de la classe [`Workbook`](/cells/python-net/fr/aspose.cells/workbook) et ouvre un fichier.



```python

def __init__(self, file, load_options):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| file | str | Le nom du fichier.|
| load_options | [`LoadOptions`](/cells/python-net/fr/aspose.cells/loadoptions) | Les options de chargement|


##  \_\_init\_\_(self, flux, options_de_chargement){#io.RawIOBase-aspose.cells.LoadOptions}
Initialise une nouvelle instance de la classe [`Workbook`](/cells/python-net/fr/aspose.cells/workbook) et ouvre le flux.



```python

def __init__(self, stream, load_options):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| stream | io.RawIOBase | Le ruisseau.|
| load_options | [`LoadOptions`](/cells/python-net/fr/aspose.cells/loadoptions) | Les options de chargement|



###  Voir également
* module [`aspose.cells`](../../)
* classe [`Workbook`](/cells/python-net/fr/aspose.cells/workbook)
