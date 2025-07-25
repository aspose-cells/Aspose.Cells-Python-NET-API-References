---
title: invariant_custom propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 260
url: /fr/aspose.cells/style/invariant_custom/
is_root: false
---
##  invariant_custom propriété

Obtient la chaîne de modèle indépendante de la culture pour le format numérique.
Si aucun format numérique n'a été défini pour cet objet, null sera renvoyé.
Si le format numérique est intégré, la chaîne de modèle correspondant au numéro intégré sera renvoyée.

###  Remarques

Pour les formats de nombres intégrés, le contenu du modèle renvoyé dépend toujours de la culture,
par exemple, pour certains paramètres régionaux, il renvoie « m/d/a » et pour d'autres paramètres régionaux, il renvoie « j/m/a ».
La différence avec [`Style.culture_custom`](/cells/python-net/fr/aspose.cells/style#culture_custom) est (c'est aussi ce que signifie indépendant de la culture) :
les spécificateurs de format et les séparateurs sont conservés comme standard, par exemple '/' sera toujours utilisé comme séparateur de date et d'heure
et « y » sera toujours utilisé comme partie « année », quel que soit l'autre caractère spécial utilisé pour les paramètres régionaux spécifiques.
###  Définition:
```python
@property
def invariant_custom(self):
    ...
```

###  Voir également
* module [`aspose.cells`](../../)
* classe [`Style`](/cells/python-net/fr/aspose.cells/style)
