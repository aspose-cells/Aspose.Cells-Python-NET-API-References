---
title: ExternalLinkCollection classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 600
url: /fr/aspose.cells/externallinkcollection/
is_root: false
---
##  ExternalLinkCollection classe
Représente la collection de liens externes dans un classeur.



Le type ExternalLinkCollection expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [count](/cells/python-net/fr/aspose.cells/externallinkcollection/count) | Obtient le nombre d'éléments réellement contenus dans la collection.|



Obtient l'élément [`ExternalLink`](/cells/python-net/fr/aspose.cells/externallink) à l'index spécifié.
###  Indexeur
| Nom| Description|
| :- | :- |
| [index] | L'index de base zéro de l'élément.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [add](/cells/python-net/fr/aspose.cells/externallinkcollection/add/#str-list) | Ajoute un lien externe.|
| [add](/cells/python-net/fr/aspose.cells/externallinkcollection/add/#aspose.cells.DirectoryType-str-list) | Ajoutez un lien externe .|
| [clear](/cells/python-net/fr/aspose.cells/externallinkcollection/clear/#) | Supprime tous les liens externes.|
| [clear](/cells/python-net/fr/aspose.cells/externallinkcollection/clear/#bool) | Supprime tous les liens externes.|
| [remove_at](/cells/python-net/fr/aspose.cells/externallinkcollection/remove_at/#int) | Supprime le lien externe spécifié du classeur.|
| [remove_at](/cells/python-net/fr/aspose.cells/externallinkcollection/remove_at/#int-bool) | Supprime le lien externe spécifié du classeur.|



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
