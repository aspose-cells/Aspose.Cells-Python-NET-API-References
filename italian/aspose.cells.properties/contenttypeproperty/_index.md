---
title: classe ContentTypeProperty
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 20
url: /it/aspose.cells.properties/contenttypeproperty/
is_root: false
---
##  classe ContentTypeProperty
Rappresenta le informazioni sull'identificatore.



Il tipo ContentTypeProperty espone i membri seguenti:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [name](/cells/python-net/it/aspose.cells.properties/contenttypeproperty/name) | Restituisce o imposta il nome dell'oggetto.|
| [value](/cells/python-net/it/aspose.cells.properties/contenttypeproperty/value) | Restituisce o imposta il valore della proprietà del tipo di contenuto.|
| [type](/cells/python-net/it/aspose.cells.properties/contenttypeproperty/type) | Ottiene e imposta il tipo della proprietà.|
| [is_nillable](/cells/python-net/it/aspose.cells.properties/contenttypeproperty/is_nillable) | Indica se il valore può essere vuoto.|



###  Esempio

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Add a new property.
workbook.content_type_properties.add("Admin", "Aspose", "text")
# Save the Excel file
workbook.save("book1.xlsm")

```

###  Guarda anche
* modulo [aspose.cells.properties](..)
