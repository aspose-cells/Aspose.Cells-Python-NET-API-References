---
title: méthode detect_file_format
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 20
url: /fr/aspose.cells/fileformatutil/detect_file_format/
is_root: false
---
##  detect_file_format(, flux){#io.RawIOBase}
Détecte et renvoie les informations sur un format d'un fichier Excel stocké dans un flux.


###  Retour

Un objet [`FileFormatInfo`](/cells/python-net/fr/aspose.cells/fileformatinfo) qui contient les informations détectées.


```python

@staticmethod
def detect_file_format(stream):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| stream | io.RawIOBase |  |


##  detect_file_format(, chemin_fichier){#str}
Détecte et renvoie les informations sur un format d'un fichier Excel stocké dans un fichier.


###  Retour

Un objet [`FileFormatInfo`](/cells/python-net/fr/aspose.cells/fileformatinfo) qui contient les informations détectées.


```python

@staticmethod
def detect_file_format(file_path):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| file_path | str | Le chemin du fichier.|


##  detect_file_format(, flux, mot de passe){#io.RawIOBase-str}
Détecte et renvoie les informations sur un format d'un fichier Excel stocké dans un flux.


###  Retour

Un objet [`FileFormatInfo`](/cells/python-net/fr/aspose.cells/fileformatinfo) qui contient les informations détectées.


```python

@staticmethod
def detect_file_format(stream, password):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| stream | io.RawIOBase |  |
| password | str | Le mot de passe pour les fichiers ooxml cryptés.|


##  detect_file_format(, chemin_fichier, mot de passe){#str-str}
Détecte et renvoie les informations sur un format d'un fichier Excel stocké dans un fichier.


###  Retour

Un objet [`FileFormatInfo`](/cells/python-net/fr/aspose.cells/fileformatinfo) qui contient les informations détectées.


```python

@staticmethod
def detect_file_format(file_path, password):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| file_path | str | Le chemin du fichier.|
| password | str | Le mot de passe pour les fichiers ooxml cryptés.|



###  Voir également
* module [`aspose.cells`](../../)
* classe [`FileFormatInfo`](/cells/python-net/fr/aspose.cells/fileformatinfo)
* classe [`FileFormatUtil`](/cells/python-net/fr/aspose.cells/fileformatutil)
