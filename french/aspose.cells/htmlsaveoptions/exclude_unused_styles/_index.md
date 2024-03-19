---
title: exclude_unused_styles propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 150
url: /fr/aspose.cells/htmlsaveoptions/exclude_unused_styles/
is_root: false
---
##  exclude_unused_styles propriété

Indique si les styles inutilisés sont exclus.
Pour les fichiers HTML générés, l'exclusion des styles inutilisés peut réduire la taille du fichier.
sans affecter les effets visuels. La valeur par défaut de cette propriété est donc vraie.
Si l'utilisateur doit conserver tous les styles dans le classeur pour le code HTML généré (comme le scénario dans lequel l'utilisateur
doit restaurer le classeur à partir du code HTML généré ultérieurement), veuillez définir cette propriété sur false.
###  Définition:
```python
@property
def exclude_unused_styles(self):
    ...
@exclude_unused_styles.setter
def exclude_unused_styles(self, value):
    ...
```

###  Voir également
* module [`aspose.cells`](../../)
* classe [`HtmlSaveOptions`](/cells/python-net/fr/aspose.cells/htmlsaveoptions)
