---
title: user_password propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 130
url: /fr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/user_password/
is_root: false
---
##  user_password propriété

Obtient ou définit le mot de passe utilisateur requis pour ouvrir le document crypté PDF.

###  Remarques

Le mot de passe du propriétaire ou le mot de passe de l'utilisateur sera requis pour ouvrir un document crypté PDF pour visualisation.


Le mot de passe de l'utilisateur peut être nul ou une chaîne vide, dans ce cas aucun mot de passe ne sera demandé à l'utilisateur lors de l'ouverture du document PDF.


L'ouverture du document avec le mot de passe propriétaire correct permet un accès complet au document.


 Ouvrir le document avec le mot de passe utilisateur correct (ou ouvrir un document qui n'a pas de mot de passe utilisateur)
permet un accès limité selon les autorisations spécifiées.
###  Définition:
```python
@property
def user_password(self):
    ...
@user_password.setter
def user_password(self, value):
    ...
```

###  Voir également
* module [`aspose.cells.rendering.pdfsecurity`](../../)
* classe [`PdfSecurityOptions`](/cells/python-net/fr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions)
