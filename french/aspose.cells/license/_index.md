---
title: License classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1020
url: /fr/aspose.cells/license/
is_root: false
---
##  License classe
Fournit des méthodes pour obtenir une licence pour le composant.



Le type License expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [__init__](/cells/python-net/fr/aspose.cells/license/__init__/#) | Initialise une nouvelle instance de cette classe.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [set_license](/cells/python-net/fr/aspose.cells/license/set_license/#str) | Licence pour le composant.|
| [set_license](/cells/python-net/fr/aspose.cells/license/set_license/#io.RawIOBase) | Licence pour le composant.|



###  Exemple

Dans cet exemple, une tentative sera faite pour trouver un fichier de licence nommé MyLicense.lic.
 dans le dossier qui contient


le composant, dans le dossier qui contient l'assembly appelant,
dans le dossier de l’assembly d’entrée puis dans les ressources embarquées de l’assembly appelant.

```python
from aspose.cells import License

license = License()
license.set_license("MyLicense.lic")

```

###  Voir également
* module [`aspose.cells`](..)
