---
title: VbaProject classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 30
url: /fr/aspose.cells.vba/vbaproject/
is_root: false
---
##  VbaProject classe
Représente le projet VBA.



Le type VbaProject expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [is_valid_signed](/cells/python-net/fr/aspose.cells.vba/vbaproject/is_valid_signed) | Indique si la signature du projet VBA est valide ou non.|
| [cert_raw_data](/cells/python-net/fr/aspose.cells.vba/vbaproject/cert_raw_data) | Obtient les données brutes du certificat si ce projet VBA est signé.|
| [encoding](/cells/python-net/fr/aspose.cells.vba/vbaproject/encoding) |Obtient et définit l'encodage du projet VBA.|
| [name](/cells/python-net/fr/aspose.cells.vba/vbaproject/name) | Obtient et définit le nom du projet VBA.|
| [is_signed](/cells/python-net/fr/aspose.cells.vba/vbaproject/is_signed) | Indique si le code VBA est signé ou non.|
| [is_protected](/cells/python-net/fr/aspose.cells.vba/vbaproject/is_protected) | Indique si ce projet VBA est protégé.|
| [islocked_for_viewing](/cells/python-net/fr/aspose.cells.vba/vbaproject/islocked_for_viewing) | Indique si ce projet VBA est verrouillé pour la visualisation.|
| [modules](/cells/python-net/fr/aspose.cells.vba/vbaproject/modules) | Obtient tous les [`VbaModule`](/cells/python-net/fr/aspose.cells.vba/vbamodule) objets.|
| [references](/cells/python-net/fr/aspose.cells.vba/vbaproject/references) | Obtient toutes les références du projet VBA.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`sign(self, digital_signature)`](/cells/python-net/fr/aspose.cells.vba/vbaproject/sign/#aspose.cells.digitalsignatures.digitalsignature) | Signez ce projet VBA avec une signature numérique|
| [`protect(self, islocked_for_viewing, password)`](/cells/python-net/fr/aspose.cells.vba/vbaproject/protect/#bool-str) | Protège ou déprotège ce projet VBA.|
| [`copy(self, source)`](/cells/python-net/fr/aspose.cells.vba/vbaproject/copy/#aspose.cells.vba.vbaproject) | Copier le projet VBA à partir d'un autre fichier.|
| [`validate_password(self, password)`](/cells/python-net/fr/aspose.cells.vba/vbaproject/validate_password/#str) | Valide le mot de passe de protection.|



###  Exemple

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Init VBA project.
vbaProject = workbook.vba_project
# Saving the Excel file
workbook.save("book1.xlsm")

```

###  Voir également
* module [`aspose.cells.vba`](..)
* classe [`VbaModule`](/cells/python-net/fr/aspose.cells.vba/vbamodule)
