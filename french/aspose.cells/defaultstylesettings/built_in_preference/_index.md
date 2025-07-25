---
title: built_in_preference propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 30
url: /fr/aspose.cells/defaultstylesettings/built_in_preference/
is_root: false
---
##  built_in_preference propriété

Indique si la propriété pour le format numérique est préférable lorsque le style définit à la fois un nombre intégré et un modèle personnalisé.
La valeur par défaut est false, ce qui signifie que par défaut, un modèle personnalisé sera utilisé pour formater les valeurs tant qu'il n'est pas vide pour un style.

###  Remarques

Lors du chargement d'un classeur à partir d'un fichier de modèle existant, il est possible que le numéro intégré et le modèle personnalisé soient définis pour un style.
Cette propriété détermine si nous devons utiliser le numéro intégré ou le modèle personnalisé lors du formatage des valeurs avec le style.
###  Définition:
```python
@property
def built_in_preference(self):
    ...
@built_in_preference.setter
def built_in_preference(self, value):
    ...
```

###  Voir également
* module [`aspose.cells`](../../)
* classe [`DefaultStyleSettings`](/cells/python-net/fr/aspose.cells/defaultstylesettings)
