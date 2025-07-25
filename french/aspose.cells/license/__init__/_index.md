---
title: License constructeur
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 10
url: /fr/aspose.cells/license/__init__/
is_root: false
---
##  \_\_init\_\_(self){#}
Initialise une nouvelle instance de cette classe.



```python

def __init__(self):
    ...
```



###  Exemple

Dans cet exemple, une tentative sera faite pour trouver un fichier de licence nommé MyLicense.lic
 dans le dossier qui contient


le composant, dans le dossier qui contient l'assembly appelant,
dans le dossier de l'assembly d'entrée puis dans les ressources intégrées de l'assembly appelant.

```python
from aspose.cells import License

license = License()
license.set_license("MyLicense.lic")

```



###  Voir également
* module [`aspose.cells`](../../)
* classe [`License`](/cells/python-net/fr/aspose.cells/license)
