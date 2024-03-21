---
title: méthode to_image
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 50
url: /fr/aspose.cells.rendering/workbookrender/to_image/
is_root: false
---
##  to_image {#io.RawIOBase}
Restituez l'intégralité du classeur sous forme d'image Tiff à diffuser.



```python
def to_image(self, stream):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| stream | io.RawIOBase | le flux de l'image de sortie|


##  to_image {#str}
Restituez l'intégralité du classeur sous forme d'image Tiff dans un fichier.



```python
def to_image(self, filename):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| filename | str | le nom de fichier de l'image de sortie|


##  to_image {#int-str}
Rendre certaines pages dans un fichier.



```python
def to_image(self, page_index, file_name):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| page_index | int | indiquer quelle page doit être convertie|
| file_name | str | nom de fichier de l'image de sortie|


##  to_image {#int-io.RawIOBase}
Afficher certaines pages dans un flux.



```python
def to_image(self, page_index, stream):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| page_index | int | indiquer quelle page doit être convertie|
| stream | io.RawIOBase | le flux de l'image de sortie|



###  Voir également
* module [`aspose.cells.rendering`](../../)
* classe [`WorkbookRender`](/cells/python-net/fr/aspose.cells.rendering/workbookrender)
