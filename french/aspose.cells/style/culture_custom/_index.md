---
title: culture_custom propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 170
url: /fr/aspose.cells/style/culture_custom/
is_root: false
---
##  culture_custom propriété

Obtient et définit la chaîne de modèle dépendante de la culture pour le format numérique.
Si aucun format numérique n'a été défini pour cet objet, null sera renvoyé.
Si le format numérique est intégré, la chaîne de modèle correspondant au numéro intégré sera renvoyée.

###  Remarques

Pour le format de nombre intégré, le contenu du modèle (par exemple, un format de date intégré est « m/d/y » pour certains paramètres régionaux,
mais pour d'autres paramètres régionaux, cela devient « j/m/a ») et le spécificateur de format (par exemple,
certains paramètres régionaux utilisent un caractère autre que « y » pour représenter la partie année pour le formatage de la date)
dépendent de la culture ;
Pour le format personnalisé spécifié par l'utilisateur, seuls les spécificateurs de format sont modifiés en fonction de la culture,
les autres parties du modèle de formatage ne seront pas modifiées.
###  Définition:
```python
@property
def culture_custom(self):
    ...
@culture_custom.setter
def culture_custom(self, value):
    ...
```

###  Voir également
* module [`aspose.cells`](../../)
* classe [`Style`](/cells/python-net/fr/aspose.cells/style)
