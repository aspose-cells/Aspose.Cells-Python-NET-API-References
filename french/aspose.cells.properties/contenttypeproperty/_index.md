---
title: ContentTypeProperty classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 20
url: /fr/aspose.cells.properties/contenttypeproperty/
is_root: false
---
##  ContentTypeProperty classe
Représente les informations d'identification.



Le type ContentTypeProperty expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [name](/cells/python-net/fr/aspose.cells.properties/contenttypeproperty/name) | Renvoie ou définit le nom de l'objet.|
| [value](/cells/python-net/fr/aspose.cells.properties/contenttypeproperty/value) | Renvoie ou définit la valeur de la propriété de type de contenu.|
| [type](/cells/python-net/fr/aspose.cells.properties/contenttypeproperty/type) | Obtient et définit le type de la propriété.|
| [is_nillable](/cells/python-net/fr/aspose.cells.properties/contenttypeproperty/is_nillable) | Indique si la valeur peut être vide.|



###  Exemple

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Add a new property.
workbook.content_type_properties.add("Admin", "Aspose", "text")
# Save the Excel file
workbook.save("book1.xlsm")

```

###  Voir également
* module [aspose.cells.properties](..)
