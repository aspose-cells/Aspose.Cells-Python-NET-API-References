---
title: ContentTypeProperty Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 20
url: /de/aspose.cells.properties/contenttypeproperty/
is_root: false
---
##  ContentTypeProperty Klasse
Stellt Identifikationsinformationen dar.



Der Typ ContentTypeProperty macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [name](/cells/python-net/de/aspose.cells.properties/contenttypeproperty/name) | Gibt den Namen des Objekts zurück oder legt ihn fest.|
| [value](/cells/python-net/de/aspose.cells.properties/contenttypeproperty/value) | Gibt den Wert der Inhaltstyp-Eigenschaft zurück oder legt ihn fest.|
| [type](/cells/python-net/de/aspose.cells.properties/contenttypeproperty/type) | Ruft den Typ der Eigenschaft ab und legt ihn fest.|
| [is_nillable](/cells/python-net/de/aspose.cells.properties/contenttypeproperty/is_nillable) | Gibt an, ob der Wert leer sein könnte.|



###  Beispiel

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Add a new property.
workbook.content_type_properties.add("Admin", "Aspose", "text")
# Save the Excel file
workbook.save("book1.xlsm")

```

###  Siehe auch
* Modul [`aspose.cells.properties`](..)
