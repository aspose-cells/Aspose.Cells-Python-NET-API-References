---
title: ExternalLinkCollection classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 580
url: /fr/aspose.cells/externallinkcollection/
is_root: false
---
##  ExternalLinkCollection classe
Représente une collection de liens externes dans un classeur.



Le type ExternalLinkCollection expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [count](/cells/python-net/fr/aspose.cells/externallinkcollection/count) | Obtient le nombre d'éléments réellement contenus dans la collection.|



Obtient l'élément [`ExternalLink`](/cells/python-net/fr/aspose.cells/externallink) à l'index spécifié.
###  Indexeur
| Nom| Description|
| :- | :- |
| [index] | L'indice de base zéro de l'élément.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`add(self, file_name, sheet_names)`](/cells/python-net/fr/aspose.cells/externallinkcollection/add/#str-list) | Ajoute un lien externe.|
| [`add(self, directory_type, file_name, sheet_names)`](/cells/python-net/fr/aspose.cells/externallinkcollection/add/#aspose.cells.directorytype-str-list) | Ajouter un lien externe.|
| [`clear(self)`](/cells/python-net/fr/aspose.cells/externallinkcollection/clear/#) | Supprime tous les liens externes.|
| [`clear(self, update_references_as_local)`](/cells/python-net/fr/aspose.cells/externallinkcollection/clear/#bool) | Supprime tous les liens externes.|
| [`remove_at(self, index)`](/cells/python-net/fr/aspose.cells/externallinkcollection/remove_at/#int) | Supprime le lien externe spécifié du classeur.|
| [`remove_at(self, index, update_references_as_local)`](/cells/python-net/fr/aspose.cells/externallinkcollection/remove_at/#int-bool) | Supprime le lien externe spécifié du classeur.|



###  Exemple

```python
from aspose.cells import Workbook

# Open a file with external links
workbook = Workbook("book1.xls")
# Change external link data source
workbook.worksheets.external_links[0].data_source = "d:\\link.xls"

```

###  Voir également
* module [`aspose.cells`](..)
* classe [`ExternalLink`](/cells/python-net/fr/aspose.cells/externallink)
