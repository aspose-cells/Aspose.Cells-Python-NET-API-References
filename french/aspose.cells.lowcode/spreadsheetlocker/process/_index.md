---
title: méthode process
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 20
url: /fr/aspose.cells.lowcode/spreadsheetlocker/process/
is_root: false
---
##  process(, options_de_chargement, options_de_sauvegarde, fournisseur){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-aspose.cells.lowcode.AbstractLowCodeProtectionProvider}
Verrouille le fichier de feuille de calcul avec les paramètres spécifiés.



```python

@staticmethod
def process(load_options, save_options, provider):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/fr/aspose.cells.lowcode/lowcodeloadoptions) | Options de saisie et de chargement|
| save_options | [`LowCodeSaveOptions`](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptions) | Options de sortie et d'enregistrement|
| provider | [`AbstractLowCodeProtectionProvider`](/cells/python-net/fr/aspose.cells.lowcode/abstractlowcodeprotectionprovider) | Mise en œuvre pour fournir des paramètres de protection|


##  process(, fichier_modèle, fichier_résultat, mot_de_passe_ouvert, mot_de_passe_écrit){#str-str-str-str}
Verrouille le fichier de feuille de calcul avec les paramètres spécifiés.



```python

@staticmethod
def process(template_file, result_file, open_password, write_password):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| template_file | str | Le fichier modèle à verrouiller|
| result_file | str | Le fichier résultant|
| open_password | str | Mot de passe pour le cryptage des fichiers|
| write_password | str |Mot de passe pour la protection de la modification de la feuille de calcul|


##  process(, options_de_chargement, options_de_sauvegarde, mot_de_passe_ouverture, mot_de_passe_écriture){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-str-str}
Verrouille le fichier de feuille de calcul avec les paramètres spécifiés.



```python

@staticmethod
def process(load_options, save_options, open_password, write_password):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/fr/aspose.cells.lowcode/lowcodeloadoptions) | Options de saisie et de chargement|
| save_options | [`LowCodeSaveOptions`](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptions) | Options de sortie et d'enregistrement|
| open_password | str | Mot de passe pour le cryptage des fichiers|
| write_password | str |Mot de passe pour la protection de la modification de la feuille de calcul|


##  process(, options_de_chargement, options_d'enregistrement, mot_de_passe_ouverture, mot_de_passe_écriture, mot_de_passe_du_classeur, type_de_classeur){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-str-str-str-aspose.cells.ProtectionType}
Verrouille le fichier de feuille de calcul avec les paramètres spécifiés.



```python

@staticmethod
def process(load_options, save_options, open_password, write_password, workbook_password, workbook_type):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/fr/aspose.cells.lowcode/lowcodeloadoptions) | Options de saisie et de chargement|
| save_options | [`LowCodeSaveOptions`](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptions) | Options de sortie et d'enregistrement|
| open_password | str | Mot de passe pour le cryptage des fichiers|
| write_password | str |Mot de passe pour la protection de la modification de la feuille de calcul|
| workbook_password | str | Mot de passe pour la protection du classeur|
| workbook_type | [`ProtectionType`](/cells/python-net/fr/aspose.cells/protectiontype) | Type de protection pour protéger le classeur|



###  Voir également
* module [`aspose.cells.lowcode`](../../)
* classe [`SpreadsheetLocker`](/cells/python-net/fr/aspose.cells.lowcode/spreadsheetlocker)
