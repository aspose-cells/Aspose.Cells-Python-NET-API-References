---
title: region propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 220
url: /fr/aspose.cells.numbers/numbersloadoptions/region/
is_root: false
---
##  region propriété

Obtient ou définit les paramètres régionaux utilisés pour le classeur qui sera chargé.

###  Remarques

Les paramètres régionaux peuvent être utilisés pour initialiser certaines fonctionnalités du classeur
comme les polices, les thèmes, etc.
Pour les formats de fichiers basés sur du texte, tels que CSV, HTML, ..., le paramètre régional
sera également utilisé pour détecter les formats de nombres et analyser les valeurs de texte en valeurs numériques
ou des valeurs datetime pour les cellules.
Ce paramètre sera conservé pour le classeur instancié ultérieurement, c'est-à-dire,
[`WorkbookSettings.region`](/cells/python-net/fr/aspose.cells/workbooksettings#region) du classeur utilisera le même region
avec cette propriété.
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
* module [`aspose.cells.numbers`](../../)
* classe [`CountryCode`](/cells/python-net/fr/aspose.cells/countrycode)
* classe [`NumbersLoadOptions`](/cells/python-net/fr/aspose.cells.numbers/numbersloadoptions)
