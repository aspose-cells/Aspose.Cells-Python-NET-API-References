---
title: built_in_document_properties propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 470
url: /fr/aspose.cells/workbook/built_in_document_properties/
is_root: false
---
##  built_in_document_properties propriété

Renvoie une collection [`DocumentProperty`](/cells/python-net/fr/aspose.cells.properties/documentproperty) qui représente toutes les propriétés de document intégrées de la feuille de calcul.

###  Remarques

Il est impossible d'ajouter une nouvelle propriété à la liste des propriétés intégrées d'un document. Vous pouvez uniquement obtenir une propriété intégrée et modifier sa valeur.
Voici la liste des noms de propriétés intégrées :

Titre


Sujet


Auteur


Mots-clés


Commentaires


Modèle


Dernier auteur


Numéro de révision


Nom de l'application


Date de la dernière impression


Date de création


Heure de la dernière sauvegarde


Temps total d'édition


Nombre de pages


Nombre de mots


Nombre de caractères


Sécurité


Catégorie


Format


Directeur


Entreprise


Nombre d'octets


Nombre de lignes


Nombre de paragraphes


Nombre de diapositives


Nombre de notes


Nombre de diapositives cachées


Nombre de clips multimédias

###  Exemple

```python
from aspose.cells import Workbook

workbook = Workbook()
doc = workbook.built_in_document_properties.get("Author")
doc.value = "John Smith"

```
###  Définition:
```python
@property
def built_in_document_properties(self):
    ...
```

###  Voir également
* module [`aspose.cells`](../../)
* classe [`BuiltInDocumentPropertyCollection`](/cells/python-net/fr/aspose.cells.properties/builtindocumentpropertycollection)
* classe [`DocumentProperty`](/cells/python-net/fr/aspose.cells.properties/documentproperty)
* classe [`Workbook`](/cells/python-net/fr/aspose.cells/workbook)
