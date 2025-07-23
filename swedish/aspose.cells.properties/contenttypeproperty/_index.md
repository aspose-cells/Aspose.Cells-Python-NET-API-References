---
title: ContentTypeProperty klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 20
url: /sv/aspose.cells.properties/contenttypeproperty/
is_root: false
---
##  ContentTypeProperty klass
Representerar identifierarinformation.



Typen ContentTypeProperty avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [name](/cells/python-net/sv/aspose.cells.properties/contenttypeproperty/name) | Returnerar eller anger namnet på objektet.|
| [value](/cells/python-net/sv/aspose.cells.properties/contenttypeproperty/value) | Returnerar eller anger värdet för innehållstypsegenskapen.|
| [type](/cells/python-net/sv/aspose.cells.properties/contenttypeproperty/type) | Hämtar och anger egenskapstypen.|
| [is_nillable](/cells/python-net/sv/aspose.cells.properties/contenttypeproperty/is_nillable) | Anger om värdet kan vara tomt.|



###  Exempel

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Add a new property.
workbook.content_type_properties.add("Admin", "Aspose", "text")
# Save the Excel file
workbook.save("book1.xlsm")

```

###  Se även
* modul [`aspose.cells.properties`](..)
