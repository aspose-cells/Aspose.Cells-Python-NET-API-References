---
title: méthode import_excel_file
second_title: Aspose.Cells.GridJs for Python via .NET API Références
description:
type: docs
weight: 110
url: /fr/aspose.cellsgridjs/gridjsworkbook/import_excel_file/
is_root: false
---
##  import_excel_file {#str}

Importe le fichier Excel à partir du chemin du fichier.



```python
def import_excel_file(self, file_name):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| file_name | str | Le chemin complet du fichier.|


##  import_excel_file {#str-str}

Importe le fichier Excel à partir du chemin du fichier.



```python
def import_excel_file(self, uid, file_name):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| uid | str | L'identifiant unique du cache de fichiers, s'il est défini sur null, il sera généré automatiquement.|
| file_name | str | Le chemin complet du fichier.|


##  import_excel_file {#io.RawIOBase-aspose.cellsgridjs.GridLoadFormat}

Importe le fichier Excel à partir du flux de fichiers avec le format de chargement.



```python
def import_excel_file(self, filestream, format):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| filestream | io.RawIOBase | Le flux du fichier Excel .|
| format | [`GridLoadFormat`](/cells/python-net/fr/aspose.cellsgridjs/gridloadformat) | Le LoadFormat du fichier Excel.|


##  import_excel_file {#str-str-str}

Importe le fichier Excel à partir du chemin du fichier et du mot de passe ouvert.



```python
def import_excel_file(self, uid, file_name, password):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| uid | str | L'identifiant unique du cache de fichiers, s'il est défini sur null, il sera généré automatiquement.|
| file_name | str | Le chemin complet du fichier.|
| password | str | Le mot de passe d'ouverture du fichier Excel. La valeur peut être nulle si aucun mot de passe n'est défini.|


##  import_excel_file {#str-io.RawIOBase-aspose.cellsgridjs.GridLoadFormat}

Importe le fichier Excel à partir du flux de fichiers.



```python
def import_excel_file(self, uid, filestream, format):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| uid | str | L'identifiant unique du cache de fichiers, s'il est défini sur null, il sera généré automatiquement.|
| filestream | io.RawIOBase | Le flux du fichier Excel .|
| format | [`GridLoadFormat`](/cells/python-net/fr/aspose.cellsgridjs/gridloadformat) | Le LoadFormat du fichier Excel.|


##  import_excel_file {#io.RawIOBase-aspose.cellsgridjs.GridLoadFormat-str}

Importe le fichier Excel à partir du flux de fichiers avec le format de chargement et le mot de passe d'ouverture.



```python
def import_excel_file(self, filestream, format, password):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| filestream | io.RawIOBase | Le flux du fichier Excel .|
| format | [`GridLoadFormat`](/cells/python-net/fr/aspose.cellsgridjs/gridloadformat) | Le LoadFormat du fichier Excel.|
| password | str | Le mot de passe d'ouverture du fichier Excel. La valeur peut être nulle si aucun mot de passe n'est défini.|


##  import_excel_file {#str-io.RawIOBase-aspose.cellsgridjs.GridLoadFormat-str}

Importe le fichier Excel à partir du flux de fichiers avec le format de chargement et le mot de passe d'ouverture.



```python
def import_excel_file(self, uid, filestream, format, password):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| uid | str | L'identifiant unique du cache de fichiers, s'il est défini sur null, il sera généré automatiquement.|
| filestream | io.RawIOBase | Le flux du fichier Excel .|
| format | [`GridLoadFormat`](/cells/python-net/fr/aspose.cellsgridjs/gridloadformat) | Le LoadFormat du fichier Excel.|
| password | str | Le mot de passe d'ouverture du fichier Excel. La valeur peut être nulle Si aucun mot de passe n'est défini|



###  Voir également
* module [`aspose.cellsgridjs`](../../)
* classe [`GridJsWorkbook`](/cells/python-net/fr/aspose.cellsgridjs/gridjsworkbook)
