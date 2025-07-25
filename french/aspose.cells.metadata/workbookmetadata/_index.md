---
title: WorkbookMetadata classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 20
url: /fr/aspose.cells.metadata/workbookmetadata/
is_root: false
---
##  WorkbookMetadata classe
Représente les métadonnées.



Le type WorkbookMetadata expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [`__init__(self, file_name, options)`](/cells/python-net/fr/aspose.cells.metadata/workbookmetadata/__init__/#str-aspose.cells.metadata.metadataoptions) | Créez l'objet de métadonnées.|
| [`__init__(self, stream, options)`](/cells/python-net/fr/aspose.cells.metadata/workbookmetadata/__init__/#io.rawiobase-aspose.cells.metadata.metadataoptions) | Créez l'objet de métadonnées.|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [options](/cells/python-net/fr/aspose.cells.metadata/workbookmetadata/options) | Obtient les options des métadonnées.|
| [built_in_document_properties](/cells/python-net/fr/aspose.cells.metadata/workbookmetadata/built_in_document_properties) | Renvoie une collection [`DocumentProperty`](/cells/python-net/fr/aspose.cells.properties/documentproperty) qui représente toutes les propriétés de document intégrées de la feuille de calcul.|
| [custom_document_properties](/cells/python-net/fr/aspose.cells.metadata/workbookmetadata/custom_document_properties) | Renvoie une collection [`DocumentProperty`](/cells/python-net/fr/aspose.cells.properties/documentproperty) qui représente toutes les propriétés de document personnalisées de la feuille de calcul.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`save(self, file_name)`](/cells/python-net/fr/aspose.cells.metadata/workbookmetadata/save/#str) | Enregistrez les métadonnées modifiées dans le fichier.|
| [`save(self, stream)`](/cells/python-net/fr/aspose.cells.metadata/workbookmetadata/save/#io.rawiobase) | Enregistrez les métadonnées modifiées dans le flux.|



###  Exemple

L'exemple suivant crée un WorkbookMetadata.

```python
from aspose.cells.metadata import MetadataOptions, MetadataType, WorkbookMetadata

options = MetadataOptions(MetadataType.DOCUMENT_PROPERTIES)
meta = WorkbookMetadata("book1.xlsx", options)
meta.custom_document_properties.add("test", "test")
meta.save("book2.xlsx")

```

###  Voir également
* module [`aspose.cells.metadata`](..)
* classe [`DocumentProperty`](/cells/python-net/fr/aspose.cells.properties/documentproperty)
