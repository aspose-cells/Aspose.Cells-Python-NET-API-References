---
title: méthode process
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 20
url: /fr/aspose.cells.lowcode/spreadsheetsplitter/process/
is_root: false
---
##  process(, options){#aspose.cells.lowcode.LowCodeSplitOptions}
Divise le fichier de feuille de calcul en plusieurs parties.



```python

@staticmethod
def process(options):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| options | [`LowCodeSplitOptions`](/cells/python-net/fr/aspose.cells.lowcode/lowcodesplitoptions) | Options de fractionnement de la feuille de calcul|


##  process(, fichier_modèle, fichier_résultat){#str-str}
Divise le fichier modèle donné en plusieurs parties.



```python

@staticmethod
def process(template_file, result_file):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| template_file | str | Le fichier modèle à diviser|
| result_file | str | Le fichier résultant (modèle de nom)|
###  Remarques

Les fichiers de sortie seront créés à partir du fichier résultant spécifié par
ajout du numéro de séquence de la feuille et de la partie divisée.
Par exemple, si le fichier de sortie spécifié est Split.xlsx, alors le fichier généré
les fichiers seront Split_0_0.xlsx, Split_0_1.xlsx, ..., Split_1_0.xlsx, ...


###  Voir également
* module [`aspose.cells.lowcode`](../../)
* classe [`SpreadsheetSplitter`](/cells/python-net/fr/aspose.cells.lowcode/spreadsheetsplitter)
