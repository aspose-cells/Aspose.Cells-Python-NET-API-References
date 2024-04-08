---
title: méthode insert_image
second_title: Aspose.Cells.GridJs for Python via .NET API Références
description:
type: docs
weight: 130
url: /fr/aspose.cellsgridjs/gridjsworkbook/insert_image/
is_root: false
---
##  insert_image {#str-str-io.RawIOBase-str}

Insère une image dans la feuille de calcul à partir du flux de fichiers ou de l'URL (le flux de fichiers ou l'URL doit être fourni)
 ou
Insère une forme, lorsque le p.type est l'un des AutoShapeType


###  Retour


La chaîne de format JSON de l'image insérée


```python
def insert_image(self, uid, p, s, image_url):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| uid | str | L'identifiant unique du cache de fichiers|
| p | str |La chaîne de format JSON pour l'opération qui spécifie l'emplacement de la cellule, le nom de la feuille de calcul, la ligne supérieure gauche, la colonne supérieure gauche de l'image, etc. {name:'sheet1',ri:1,ci:1} |
| s | io.RawIOBase | Le flux de fichiers du fichier image|
| image_url | str | L'URL du fichier image|



###  Voir également
* module [`aspose.cellsgridjs`](../../)
* classe [`GridJsWorkbook`](/cells/python-net/fr/aspose.cellsgridjs/gridjsworkbook)
