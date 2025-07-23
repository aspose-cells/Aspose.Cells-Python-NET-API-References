---
title: méthode process
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 20
url: /fr/aspose.cells.lowcode/imageconverter/process/
is_root: false
---
##  process(, fichier_modèle, fichier_résultat){#str-str}
Convertit le fichier modèle en images.



```python

@staticmethod
def process(template_file, result_file):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| template_file | str | Le fichier modèle à convertir en images.|
| result_file | str | Le fichier résultant (modèle de nom) pour les images générées.|
###  Remarques

Les fichiers de sortie seront créés à partir du fichier de résultat spécifié
en ajoutant le numéro de séquence de la feuille et de la partie divisée.
Par exemple, si le fichier de sortie spécifié est Image.png, alors l'image générée
les fichiers seront Image_0_0.png, Image_0_1.png, ..., Image_1_0.png, ...

##  process(, options_de_chargement, options_de_sauvegarde){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions}
Convertit le fichier modèle en images



```python

@staticmethod
def process(load_options, save_options):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/fr/aspose.cells.lowcode/lowcodeloadoptions) | Options de saisie et de chargement|
| save_options | [`LowCodeSaveOptions`](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptions) | Options de sortie et d'enregistrement|
###  Remarques

Lors de la conversion en image d'un format prenant en charge plusieurs pages (comme tiff),
le [`LowCodeSaveOptions.output_file`](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptions#output_file) spécifié
ou [`LowCodeSaveOptions.output_stream`](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptions#output_stream) sera utilisé directement pour l'image résultante.


Pour les autres types d'images, si les options d'enregistrement ont spécifié Stream comme sortie,
alors toutes les images résultantes seront enregistrées dans le même flux.
Sinon, les fichiers de sortie seront créés à partir du fichier de sortie spécifié
des options de sauvegarde en ajoutant le numéro de séquence de la feuille et de la partie divisée.
Par exemple, si le fichier de sortie spécifié est Image.png, alors l'image générée
les fichiers seront Image_0_0.png, Image_0_1.png, ..., Image_1_0.png, ...

##  process(, options_de_chargement, options_de_sauvegarde, fournisseur){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-AbstractLowCodeSaveOptionsProvider}




```python

@staticmethod
def process(load_options, save_options, provider):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/fr/aspose.cells.lowcode/lowcodeloadoptions) |  |
| save_options | [`LowCodeSaveOptions`](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptions) |  |
| provider | AbstractLowCodeSaveOptionsProvider |  |



###  Voir également
* module [`aspose.cells.lowcode`](../../)
* classe [`ImageConverter`](/cells/python-net/fr/aspose.cells.lowcode/imageconverter)
