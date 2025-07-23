---
title: region propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 440
url: /fr/aspose.cells/workbooksettings/region/
is_root: false
---
##  region propriété

Obtient ou définit les paramètres régionaux du classeur.

###  Remarques

1. Paramètres régionaux utilisés par le composant Aspose.Cells pour un classeur chargé à partir d'un fichier modèle :
i). Pour un fichier XLS, des champs sont définis pour les paramètres régionaux et MS Excel enregistre les données de paramètres régionaux dans le fichier lors de l'enregistrement du fichier XLS.
Nous utilisons donc le region enregistré dans le fichier modèle pour le classeur.
Si vous ne souhaitez pas utiliser le region enregistré dans le fichier XLS, veuillez le réinitialiser à celui attendu (par exemple, CountryCode.Default) après avoir chargé le fichier modèle.
Et nous enregistrons également la valeur spécifiée par l'utilisateur (par cette méthode) dans le fichier lors de l'enregistrement d'un fichier XLS.
ii). Pour les autres formats de fichiers, tels que XLSX, XLSB...etc., aucun champ n'est défini pour les paramètres régionaux dans la spécification du format de fichier.
Nous utilisons donc les paramètres régionaux de l’environnement de l’application pour le classeur.
Et, la valeur spécifiée par l'utilisateur (par cette méthode) ne peut pas être conservée pour les fichiers générés avec ces formats de fichiers.
2. Pour l'effet de vue dans MS Excel :
Les paramètres régionaux appliqués ici ne peuvent prendre effet qu'au moment de l'exécution avec le composant Aspose.Cells et non lors de l'affichage du fichier généré avec MS Excel.
Même pour le fichier XLS généré dans lequel les données de paramètres régionaux spécifiées ont été enregistrées, lors de sa visualisation/modification avec MS Excel,
le region utilisé pour effectuer le formatage par MS Excel est toujours les paramètres régionaux par défaut de l'environnement dans lequel MS Excel s'exécute,
Ce n'est pas celui enregistré dans le fichier. Il s'agit du comportement de MS Excel et il ne peut pas être modifié par code.
###  Définition:
```python
@property
def region(self):
    ...
@region.setter
def region(self, value):
    ...
```

###  Voir également
* module [`aspose.cells`](../../)
* classe [`CountryCode`](/cells/python-net/fr/aspose.cells/countrycode)
* classe [`WorkbookSettings`](/cells/python-net/fr/aspose.cells/workbooksettings)
